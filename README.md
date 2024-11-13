# Programming-Logic
Lógica de Programação


Algoritmo para trocar lâmpadas
1- se (lâmpada estiver fora de alcanc e)
pegar a escada;
2 - pegar a lâmpada;
3- se (lâmpada estiver quente)
pegar pano;
4 - Tirar lâmpada queimada;
5- Colocar lâmpada boa
=====================================
Algoritmo para o fim de semana
1 - vejo a previsão do tempo;
2 - se (fizer sol)
vou à praia;
senão
vou estudar;
3 - almoçar
4- ver televisão
5 - dormir
==================================

Algoritmo para fazer um bolo simples
1 -pegar os ingredientes;
2 - se (roupa branca)
colocar avental;
3 - se (tiver batedeira)
bater os ingredientes na batedeira;
senão
bater os ingredientes à mão;
4 - colocar a massa na forma;
5 - colocar a forma no forno;
6 - aguardar o tempo necessário;
7 - retirar o bolo;

==================================
Algoritmo para descascar batatas
1 - pegar faca, bacia e batatas;
2 - colocar água na bacia;
3 - enquanto (houver batatas)
descascar batatas;

=================================

Algoritmo para fazer uma prova
1 - ler a prova;
2 - pegar a caneta;
3- enquanto ((houver questão em branco) e (tempo não terminou))faça
se (souber a questão)
resolvê-la;
senão
pular para outra;
4 - entregar a prova
==================================
Algoritmo para jogar o jogo da velha:
enquanto ((ex i stir um quadrado livre ) e (ninguém perdeu(ganhou) o jogo))
espere a jogada do adversário, continue depo is
se (existir um quadrado livre)
se (centro livre)
jogue no centro
senão
se (adversário tem 2 quadrados em linha com o terc~iro
desocupado)
jogue neste quadrado desocupado
senão
se (há algum canto livre)
jogue neste canto
=======================================
Algoritmo para levar um leão, uma cabra e um pedaço de grama de um lado para
outro de um rio, atravessando com um bote. Sabe-se que nunca o leão pode ficar
sozinho com a cabra e nem a cabra sozinha com a grama.
1 - Levar a grama e o leão
 2- Voltar com o leão
 3 - Deixar o leão
4 - Levar a cabra
5 - Deixar a cabra
6- Voltar com a grama
7 - Levar o leão e a grama
======================================
1) Fazer um algoritmo para levar 3 missionários e 3 canibais de um
lado para outro de um rio, atravessando com um bote. Sabe-se que
nunca pode ter mais missionários do que canibais porque senão os
missionários catequizam os canibais. O que fazer para levar os 6 de
uma margem para outra?
Passos do Algoritmo

    Enviar 2 canibais para o outro lado
        Lado A: 3 missionários, 1 canibal
        Lado B: 0 missionários, 2 canibais

    Retornar 1 canibal para o lado inicial
        Lado A: 3 missionários, 2 canibais
        Lado B: 0 missionários, 1 canibal

    Enviar 2 canibais para o outro lado novamente
        Lado A: 3 missionários, 0 canibais
        Lado B: 0 missionários, 3 canibais

    Retornar 1 canibal para o lado inicial
        Lado A: 3 missionários, 1 canibal
        Lado B: 0 missionários, 2 canibais

    Enviar 2 missionários para o outro lado
        Lado A: 1 missionário, 1 canibal
        Lado B: 2 missionários, 2 canibais

    Retornar 1 missionário e 1 canibal para o lado inicial
        Lado A: 2 missionários, 2 canibais
        Lado B: 1 missionário, 1 canibal

    Enviar 2 missionários para o outro lado
        Lado A: 0 missionários, 2 canibais
        Lado B: 3 missionários, 1 canibal

    Retornar 1 canibal para o lado inicial
        Lado A: 0 missionários, 3 canibais
        Lado B: 3 missionários, 0 canibais

    Enviar os 2 canibais finais para o outro lado
        Lado A: 0 missionários, 1 canibal
        Lado B: 3 missionários, 3 canibais
   ========================================================

   Capítulo 2
Variável, expressões,
funções, atribuição,
entrada e saída
VARIÁVEL
Conceitos iniciais
Uma variável é um local na memória principal, isto é, um endereço que ar -
mazena um conteúdo. Em linguagens de alto nível, nos é permitido dar
nome a esse endereço para facilitar a programação,
O conteúdo de uma variável pode ser de vários tipos: inteiro, real, ca-
ractere, lógico, entre outros. Normalmente, quando se ensina algoritmo,
trabalha-se com os quatro tipos citados

OBSERVAÇÃO
int a;
real b;
string nome;
logico r;

Um dos objetivos de se declarar uma variável no início do algoritmo é para
que seja alocada (reservada) uma área na memória (endereço de memória)
para a variável. Outro objetivo da declaração de variáveis é que, após a
declaração, o algoritmo sabe os tipos de operações que cada variável pode
realizar; explicando: algumas operações só podem ser realizadas com
variáveis do tipo inteiro, outras só podem ser realizadas com variáveis dos
tipos inteiro ou real, outras só com variáveis de caractere etc
========================================================================
Tipos de variáveis
Numérica
Variáveis numéricas são aquelas que armazenam dados numéricos, po -
dendo ser divididas em duas classes:
int
Os números inteiros são aqueles que não possuem componentes decimais
ou fracionários, podendo ser positivos ou negativo

Como exemplo de números inteiros temos:
12 número inteiro positivo
-12 número inteiro negativo

=============================================
real
Os números reais são aqueles que podem possuir componentes decimais
ou fracionários, podendo também ser positivos ou negativos.
As variáveis compostas com estes números pertencentes aos conjuntos
dos números reais são chamadas de VARIÁVEIS REAIS.
Como exemplos de números reais temos:
24.01
144.
-13.3
0.0
número real positivo com duas casas decimais
número real positivo com zero casa decimal
número real negativo com uma casa decimal
número real com uma casa decimal

========================================
string
Também conhecida como caractere, alfanumérica ou literal. Esse tipo de
variável armazena dados que contêm letras, dígitos e/ou símbolos especiais.
Como exemplos de constantes string temos:
"Maria"
"123"
"O"
"A"
string de comprimento 5
string de comprimento 3
string de comprimento 1
string de comprimento 
===============================================
logico
Também conhecido como booleano. É representado no algoritmo pelo
dois únicos valores lógicos po ssíveis: verdadeiro ou falso. Porém, é co-
mum encontrar em outras referências outros tipos de pares de valores ló-
gicos como : sim/nao, 1/0, true/false, verdadeiro/falso.
Como exemplos de constantes lógicas temos:
verdadeiro
falso
Valor lógico verdadeiro
Valor lógico falso

========================================================
Aritméticas
Expressões aritméticas são aquelas cujo resultado da avaliação é do tipo
numérico, seja ele inteiro ou real. Somente o uso de operadores aritméti-
cos e variáveis numéricas é permitido em expressões deste tipo.
Como exemplo de operadores e expressões aritméticas temos:
Soma Na matemática, representada pelo sinal + e, em expressões em
termos computacionais, pelo mesmo sinal.
A + B Expressão que simboliza a soma do valor de duas variáveis.
2 + 3 Nessa expressão, o valor retornado é a soma dos valores
dados, isto é, 5.
Subtração Na matemática, representada pelo sinal- e, em expressões
em termos computacionais, pelo mesmo sinal.
A - B Expressão que simboliza a subtração do valor de duas variáveis.
3 - 2 Nessa expressão, o valor retornado é o resto, isto é, 1.
Multiplicação Na matemática, representada pelos sinais x ou. e, em
expressões em termos computacionais, pelo sinal *.
B ::- D Expressão que simboliza a multiplicação do valor de duas
variáveis.
3*2 Nessa expressão, o valor retornado é o produto dos valores
dados, isto é, 6.
Divisão Na matemática, representada pelo sinal -;- e, em expressões
computacionais, pelo sinal/.
A / B
6 I 2
5 / 2
Expressão que simboliza a divisão do valor de duas variáveis.
Nessa expressão, o valor retornado é a divisão dos valores
dados, que, no caso, será equivalente a 3.
Nessa expressão, o valor retornado é a divisão dos valores
dados, que, no caso, será equivalente a 2.5

=======================================================
7 Ofo 4 Nessa expressão, o valor retornado é o resto da divisão do
primeiro pelo segundo número, que, no caso, será
equivalente a 3.
div- divisão inteira É usada em expressões em termos computacionais
quando se deseja encont rar o quociente da divisão de dois números inteiros.
A div B Expressão que simboliza a intenção de achar o valor do
divisor na divisão do valor da variável A pelo valor da
variável B.
5 div 2 Nessa expressão, o valor retornado é o coeficiente da divisão
do primeiro pelo segun do número, que, no caso, será
equivalente a 2.
C. Ooperador div necessita que, antes e depois dele, pressionemos a barra de espaço.
Relaciona I
Uma expressão relaciona!, ou simplesmente relação, é uma comparação rea-
lizada entre dois valores de mesmo tipo básico. Estes valores são represen-
tados na relação através de constantes, variáveis ou expressões aritméticas.

Operador Matemática
Igual =
Diferente 7:-
Maior >
Menor que <
=======================================================================
Lógica ou booleana
Denomina-se expressão lógica a expressão cujos operadores são lógicos e
cujos operandos são relações, constantes e/ ou variáveis do tipo lógico

Operador Matemática Usaremos
conjunção e &&
disjunção ou ||
negação !

===================================================
ATRIBUIÇÃO
É a principal forma de se armazenar um dado em uma variável. Esse co-
mando permite que você forneça um valor a uma variável, onde o tipo
desse valor tem de ser compatível com a variável.
===================================================

A "Memória Principal" (MP) representa o espaço de armazenamento onde as variáveis de um programa são guardadas temporariamente enquanto o programa está em execução. Ela é chamada assim porque é a área principal de armazenamento acessível diretamente pela unidade de processamento do computador (CPU).

Aqui estão alguns pontos principais sobre a Memória Principal (MP):

    Armazenamento Temporário: A memória principal armazena valores temporários, como variáveis, durante a execução de um programa. Quando o programa é encerrado, esses valores são perdidos, pois a MP é uma memória volátil.

    Organização em Endereços: A memória principal é dividida em células ou endereços, e cada variável ocupada uma dessas células. No exemplo, temos variáveis como A, B e AUX, cada uma ocupando uma posição específica.

    Execução de Instruções: À medida que o programa é executado, os valores das variáveis podem ser alterados diretamente na memória principal. Isso permite ao processador ler e modificar dados rapidamente.

    Função de AUX: Na imagem, AUX é uma variável auxiliar utilizada para armazenar temporariamente o valor de outra variável. Ela ajuda a evitar a perda de dados durante a troca de valores entre A e B. Sem AUX, o valor original seria sobrescrito.

    Papel na Computação: A MP permite que o computador realize operações em dados sem depender de armazenamento externo (como o disco rígido), tornando o processamento muito mais rápido.

Em resumo, a Memória Principal serve como a área onde o computador armazena e manipula variáveis e dados durante a execução de um programa, sendo essencial para o funcionamento dinâmico dos algoritmos.

====================================================
COMANDO DE SAÍDA
É o comando responsável por enviar um resultado, uma informação ao
usuário. O valor de cada variável é buscado na memória e inserido em um
dispositivo de saída. Através desse comando o computador pode emitir os
resultados e outras mensagens para o usuário através da tela do computa-
dor ou uma impressora
==========================================
Entrar com uma data no formato ddmmaa e imprimir no formato mmddaa.
prog teste
int data,dia,mes,ano,ndata;
imprima "\nDigite data no formato DDMMAA: ";
leia data;
dia<-data div 10000;
mes<-data % 10000 div 100;
ano<-data %100;
ndata<- mes *10000 +dia*100+ano;
imprima "\nDIA: ",dia;
imprima "\nMES: ",mes;
imprima "\nANO: ",ano;
imprima "\n\nDATA NO FORMATO MMDDAA: ",ndata;
imprima "\n";
fimprog


