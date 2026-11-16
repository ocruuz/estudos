16/11/2026
o que é JavaScript e como ele conversa com HTML e CSS?
HTML é uma linguagem de marcação, CSS uma linguagem de folha de estilos e o JavaScript é uma linguagem de programação, JavaScript faz com que a página web seja interativa, deixa seu HTML com funcionalidades.
quais são os tipos de dados?
Number, String, Boolean, Undefined e null, object, symbol e bigint: Number trabalha com números inteiros e decimais. String são os textos, sendo necessario colocar aspas sempre ("Gustavo"). Boolean é true and false, esta ativo ou nao esta ativo? e determinada ação conforme a verificação feita. Undefined é quando uma variável foi declarada e ainda não recebeu um valor e null é quando propositalmente a variável não recebe valor. Object é uma coleção de pares-chave-valor {
name: "Gustavo",
age: 19
}; são uma boa alternativa para agrupar informações relacionadas. symbol é um valor único que não pode ser mudado. bigint é usado quando o número é muito grande e acaba passando da capacidade do tipo de dado NUMBER, ex:131314141616516141515165, passando disso o number acaba tendo uma precisão menor, nisso entra o tipo de dado, bigint, dando a capacidade de receber um número gigante para seu programa.
o que é uma variável  e como nomear?
variáveis são espaços na memória utilizados para armazenar informações que podem ser acessadas e utilizadas durante a execução de um programa, para nomer pode se começar por letra, $, _ e não pode começar com números e não pode se utilizar palavras reservadas. CamelCase é uma convenção utilizada em JavaScript, a primeira palavra com letra minúscula e a segunda com letra maiúscula. let userName, let userAge. let Age=19 let age=25, são duas variáveis diferentes pois o JavaScript diferencia letras minúsculas de maiúsculas.
a diferença entre let e const:
let  permite trocar o valor depois, já const o valor não pode ser mudado. ex: pontuação de jogo: let, nome da empresa que nunca muda: const.
ONDE TRAVEI? ao criar meu próprio codigo com variáveis coloquei:
let userName=Gustavo; ao invés de let userName="Gustavo"; onde deu erro pois o JavaScript não reconhece como texto automaticamente, preciso colocar " quando trata se de uma spring=texto.
