**1.** O que é o retorno NaN em Javascript? Cite um tipo de condição em que este tipo pode

ser gerado.



NaN (Number) é um valor que representa um resultado inválido em contas de matemática.

**Ex:** Let idade = Number(prompt("Digite sua idade:"));





**2.** É possível adicionar uma configuração CSS de múltiplas formas em um código HTML.

Cite essas formas e dê exemplos de cada uma. Cite também a diferença entre utilizar

cada uma dessas formas.



É possível inserirmos uma configuração CSS dentro de um elemento, mas isso, na prática, não nos ajuda a manter a distribuição entre o conteúdo mostrado e sua formatação. Esse tipo de declaração é denominada declaração INLINE. Outra forma de incluirmos o CSS é adicionarmos a tag <style> no <head> de nossa página e declarar as propriedades para os elementos dentro dessa tag. Esse método é mais eficiente que o anterior. Essa declaração é chamada de “tag style”



inline exemplo: <h1 stylwe="color: red">Money, que é good nós num have...</h1>

tag style exemplo: 

<style>

&#x09;h1{

&#x09;	color: yellow;

&#x09;}

</style>

**3.** Escreva as regras CSS para estilizar uma div com a classe .card-produto com as

seguintes exigências: Largura fixa de 300px e centralizada horizontalmente na página.

Espaçamento interno (padding) de 20px. Bordas arredondadas em 12px e uma borda

sólida de 1px na cor cinza claro (#ddd).Cor de fundo branca.

ARQUIVO CSS:

.card-produto{ largura máxima: 300px; altura: automático; preenchimento: 20px; borda:1px sólido #ddd; raio da borda: 12px; cor de fundo: branco; }
Mas essa classe (cartão-produto) tem que estar dentro de um container não conterá as seguintes configurações para ser centralizada.

#container-card{ isplay-flex: flex; justify-content: center; }


Wid



**4.** Diferencie as listas ordenadas (<ol>) das listas não ordenadas (<ul>). Crie um exemplo

de cada.



Lista ordenada: é aquela que segue uma ordem numeral , é muito utilizada para fazer uma cronologia, como por exemplo uma lista de tarefas a ser cumprida.



**Ex:**

<h1>Lista de tarefa</h1>



&#x20;   <ol>

&#x20;       <li>Acordar</li>

&#x20;       <li>Escovar os dentes</li>

&#x20;       <li>Colocar a roupa</li>

&#x20;       <li>Arrumar a mochila</li>

&#x20;       <li>Terminar de se arrumar</li>

&#x20;       <li>Pegar a mochila</li>

&#x20;       <li>Ir para escola</li>

&#x20;   </ol>



Lista não ordenada: não segue uma ordem,é ultizada para resumos, tópicos, lista de compra.



**Ex:**

<h1>Lista de algumas comidas</h1>

&#x20;   <ul>

&#x20;       <li>Arroz</li>

&#x20;       <li>Feijão</li>

&#x20;       <li>Macarrão</li>

&#x20;       <li>Frutas</li>

&#x20;       <li>Verduras</li>

&#x20;       <li>Carnes</li>

&#x20;       <li>Oleo</li>

&#x20;   </ul>







**5.** O que significa a propriedade display no CSS? Compare o comportamento de block,

inline e inline-block.

R: A propriedade display no CSS altera a forma como determinado elemento se comporta na página. O display: bloco; faz com que o elemento se comporte com um bloco forçando a quebra de linha e não respeitando a altura e largura do elemento adjacente, o display:inline; faz com que o elemento aceite a altura e a largura do elemento sem quebrar a linha, já o display:inline-block; é uma mistura de ambos forçando a quebra de linha e respeitando a altura e largura dos elementos adjacentes.

6-Explique o que é o Box Model no CSS e descreva suas partes de dentro para fora.

O box Model é um modelo reconhecido pelo CSS, é uma forma em que o navegador representa cada elemento em várias caixas. representação do box model de um elemento:

4 retângulos, um dentro do outro. O Maior é a margem de propriedade seguida de borda e preenchimento, e o mais interno, a altura e largura do elemento.

7 - Qual é a função das tags semânticas no HTML5, como

,
, e
Dê exemplos de uso.
As tags semânticas são utilizadas para deixar o código limpo, dando um valor real para aquele trecho facilitando assim a acessibilidade e o reconhecimento.

CABEÇALHO: Ela engloba as informações possíveis para uma navegação mais fluida na página.

SEÇÃO: Ela define uma seção no site delimitando e organizando cada seção em assuntos específicos.

ARTIGO: Ela demarca um trecho de conteúdo com um sentido independente do site.

rodapé: Ele demarca as informações finais do site como direitos e créditos além de resumir os depósitos do site.


**8.** Explique o que é e para que serve o atributo target="\_blank" em um link. Quais cuidados

de segurança devem ser tomados ao utilizá-lo?


const desconto = Number(prompt("Digite quantos % de desconto o produto desejado tem "));
let valor = 0
valor = valorPrimario * [1-(desconto/100)];
 alert("O valor do produto é " + valor);

 var e let: o comando var cria uma variavel que pode ser alterada livremente e que pode ser acessada em qualquer escopo do codigo, idempendente do local que ela foi criada, o comando let tambem cria uma variavel que pode ser alterada livremente porém ela só pode ser acessada pelo seu escopo e os escopos filhos, isso faz com que as variaveis tipo var sejam menos seguras que as let pois seram acessadas a qualquer momento independente do escopo  exemplo;

 var fruta = "banana";
 let molho = "rosé";
 console.log("A fruta" + fruta + "não combina com o molho" + molho + "não combine frutas com molho") // Nesse caso o valor de ambas as variaveis poderá ser acessado pois a var pode ser acessada de qualquer lugar e a let está no escopo

 console.log ("A carne" + carne + "combina com o molho" + molho + "?"); //Nesse caso a variavel let carne não podera ser acessada pois está em um escopo pai 

 {
    let carne = "picanha"
    console.log("Por favor compre" + fruta + " " + carne + " " + molho); // nesse caso todos os valores poderam ser exibidos 
 }

17 - Qual a diferença entre JavaScript e Java?

R: A diferença entre java e java script é que a primeira é uma linguagem de progamação focada em back-end sendo de compilação e usada em aplicativos e sistemas bancarios por exemplo, ja javascript é outra linguagem de progamação focada em front-end, não faz compilação, roda nso navegadores e é focada em progamar a interatividade e comportamento dos sites.

18 - Qual a diferença entre == e === no JavaScript? Dê exemplos práticos
O sinal de == serve para comparar se duas variaveis possuem o mesmo valor, enquanto o === conpara se duas variaveis possuem o mesmo tipo e valor Ex:
let a = "1"; // tipo=string
let b = Number(1); //tipo=Number

if(a==b){
    alert("a + "é igual a" + b);
} else {
    alert("Não é igual");
}
//nesse caso a condição do if é verdadeira pois o == confere que ambas as variaveis tem valor 1
if(a===b){
    alert("a + "é igual a" + b);
} else {
    alert("Não é igual");
}
//nesse caso a condição é falsa pois o === confere que o valor é igual mas o tipo diferende sendo a string e b number

19 - O que são operadores lógicos (&&, ||, !) e como eles podem ser usados em condicionais?
Exemplifique.

Os operadores logicos são operadores que adicionam uma condição para uma condicional, o && siguinifica e, o || ou e o ! diferente

exemplo: 
let a = 1;
let b = 1;

if( a && b == 1){
console.log(" certo ");
}else{
console.log(" errado ");
}
//nesse caso a condição e verdadeira pois A(1) e B(1) são iguais a 1, assim então as duas variáveis cumprindo a condição proposta.

let a = 1;
let b = 0;

if( a || b == 1){
console.log(" certo ");
}else{
console.log(" errado ");
}
//nesse caso a condição e verdadeira pois apenas uma das afirmações devem ser verdadeiras para cumprir a condição proposta, e no caso o A(1) e igual a 1, cumprindo assim a condição proposta.

let a = 1;
let b = 1;

if( a != b ){
console.log(" certo ");
}else{
console.log(" errado ");
}
//nesse caso a condição é falsa pois para que fosse verdadeira era necessário que a e b fossem diferentes, mas ambos possuem o valor 1.

Questão 20 - É possível adicionar novas propriedades a um objeto depois de criado? Como?

Sim é possível, basta criar uma propriedade e atribuir um valor a ela, Ex:

const jogo = {
nome: Pac man,
Preco: "R$20",
}

jogo.ano = "2099"

Ou também...

jogo["tamanho"] = "199 GB"

Questão 21 - Qual a diferença entre null e undefined no JavaScript?

Ambos são tipos de dados primitivos. O Null indica um valor Nulo por conta que a linguagem e Case-Sensitive ent "a" != "A". O Undefined indica que você tentou utilizar uma variável que não foi definida no seu código.

Questao 22 - O que é um objeto em JavaScript e como ele é declarado? Dê um exemplo básico.

Um objeto e uma entidade independente que possui propriedade e valor, elas são declaradas com o uso de chaves após definit o tipo e o nome do objeto, exemplo:

const objetovazio = {}

const objetocheio = {
nome: "objeto",
Tamanho: "modificável",
função: "fazer o computador entender que existe uma conexão entre propriedade x e valor y",
melhorvariavel: "const + dentro de um vetor pois e melhor manipulavel"
}

**9.** O que é a propriedade flex no CSS e como ela é usada?

10\. Faça a leitura de um vetor de tamanho 5 de notas. Escreva um código que utilize um

laço de repetição (for ou for...of) para percorrer o array, calcular e exibir no console a

soma total e a média aritmética das notas.

11\. Crie um objeto com informações de um produto (nome, preco, emEstoque). Se

emEstoque for true, exiba "Produto disponível"; caso contrário, "Produto indisponível".

12\. Crie um objeto pessoa com os atributos nome, peso, altura e temperatura. Faça uma

saída que verifica se essa pessoa está ou não com febre.

13\. Crie 2 objetos do tipo livro e peça ao usuário para preenche-los. Depois, imprima na tela

o livro com autoria mais antiga, o livro com mais páginas e o livro com autor brasileiro (caso haja).



