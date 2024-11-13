# Programming Logic
## Fonte:Livro: INTRODUÇÃO A PROGRAMAÇÃO: 500 Algoritmos resolvidos. Anita Lopes & Guto Garcia. 


### Lógica de Programação

💡 Algoritmo para Trocar Lâmpadas

1️⃣ Se (lâmpada estiver fora de alcance), pegue a escada 🪜
2️⃣ Pegue a lâmpada 💡
3️⃣ Se (lâmpada estiver quente), pegue um pano 🔥
4️⃣ Retire a lâmpada queimada 🗑️
5️⃣ Coloque uma lâmpada nova 🌟
🌞 Algoritmo para o Fim de Semana

1️⃣ Veja a previsão do tempo 🌦️
2️⃣ Se (fizer sol), vá à praia 🏖️; senão, vá estudar 📚
3️⃣ Almoce 🍲
4️⃣ Assista televisão 📺
5️⃣ Durma 🛌
🍰 Algoritmo para Fazer um Bolo Simples

1️⃣ Pegue os ingredientes 🥛🥚🍫
2️⃣ Se (roupa branca), coloque um avental 🧑‍🍳
3️⃣ Se (tiver batedeira), bata os ingredientes na batedeira; senão, bata à mão 🥄
4️⃣ Coloque a massa na forma 🧁
5️⃣ Coloque a forma no forno 🔥
6️⃣ Aguarde o tempo necessário ⏳
7️⃣ Retire o bolo 🍰
🥔 Algoritmo para Descascar Batatas

1️⃣ Pegue faca, bacia e batatas 🥔
2️⃣ Coloque água na bacia 🚰
3️⃣ Enquanto (houver batatas), descasque as batatas 🔪
📝 Algoritmo para Fazer uma Prova

1️⃣ Leia a prova 📜
2️⃣ Pegue a caneta ✒️
3️⃣ Enquanto ((houver questão em branco) e (tempo não terminou)), faça:

    Se (souber a questão), resolva-a ✅; senão, pule para outra ➡️
    4️⃣ Entregue a prova 📨

❌ Algoritmo para Jogar o Jogo da Velha

Enquanto ((existir um quadrado livre) e (ninguém ganhou o jogo)), faça:

    Espere a jogada do adversário e, em seguida:
        Se (existir um quadrado livre), jogue no centro ➕, ou:
            Se (adversário tem 2 quadrados em linha com o terceiro desocupado), jogue nesse quadrado.
            Se (há algum canto livre), jogue no canto 🔲

🦁🐐🌱 Algoritmo para Transportar Leão, Cabra e Grama

1️⃣ Leve a grama e o leão 🌱🦁
2️⃣ Volte com o leão 🦁
3️⃣ Deixe o leão 🦁
4️⃣ Leve a cabra 🐐
5️⃣ Deixe a cabra 🐐
6️⃣ Volte com a grama 🌱
7️⃣ Leve o leão e a grama 🌱🦁
⛵ Algoritmo para Levar Missionários e Canibais

Para atravessar três missionários e três canibais sem que os missionários fiquem em menor número:

1️⃣ Envie 2 canibais para o outro lado

    Lado A: 3 missionários, 1 canibal
    Lado B: 0 missionários, 2 canibais

2️⃣ Retorne 1 canibal para o lado inicial

    Lado A: 3 missionários, 2 canibais
    Lado B: 0 missionários, 1 canibal

3️⃣ Envie 2 canibais para o outro lado novamente

    Lado A: 3 missionários, 0 canibais
    Lado B: 0 missionários, 3 canibais

4️⃣ Retorne 1 canibal para o lado inicial

    Lado A: 3 missionários, 1 canibal
    Lado B: 0 missionários, 2 canibais

5️⃣ Envie 2 missionários para o outro lado

    Lado A: 1 missionário, 1 canibal
    Lado B: 2 missionários, 2 canibais

6️⃣ Retorne 1 missionário e 1 canibal para o lado inicial

    Lado A: 2 missionários, 2 canibais
    Lado B: 1 missionário, 1 canibal

7️⃣ Envie 2 missionários para o outro lado

    Lado A: 0 missionários, 2 canibais
    Lado B: 3 missionários, 1 canibal

8️⃣ Retorne 1 canibal para o lado inicial

    Lado A: 0 missionários, 3 canibais
    Lado B: 3 missionários, 0 canibais

9️⃣ Envie os 2 canibais finais para o outro lado

    Lado A: 0 missionários, 1 canibal
    Lado B: 3 missionários, 3 canibais

Conceitos Fundamentais de Programação
Variáveis

    Variável é um local na memória onde armazenamos dados temporários para o programa. Cada variável possui um tipo como int, real, string, ou boolean.

Tipos de Variáveis

    Numérica: Inteira (int) ou Real (float).
    String: Sequência de caracteres, como "Maria".
    Boolean: Valores lógicos, verdadeiro ou falso.

Operadores Aritméticos

    Soma: +
    Subtração: -
    Multiplicação: *
    Divisão: /
    Módulo (resto da divisão): %

Operadores Relacionais

    Igual: ==
    Diferente: !=
    Maior que: >
    Menor que: <

Operadores Lógicos

    E: &&
    OU: ||
    NÃO: !

Atribuição

    O comando de atribuição (=) permite armazenar valores em variáveis.

Comando de Saída

    Saída: Exibe informações para o usuário, como print para mostrar mensagens na tela.



    🧠 Memória Principal (MP)

A Memória Principal (MP) é o espaço de armazenamento onde os dados e variáveis de um programa são guardados temporariamente enquanto o programa está sendo executado. Ela é essencial para o funcionamento do computador, pois permite que ele acesse e manipule dados rapidamente.
📋 Características da Memória Principal

    Armazenamento Temporário 🕒
        A MP armazena dados temporariamente, como variáveis e resultados de cálculos. Esses dados ficam disponíveis apenas enquanto o programa está em execução. Quando o programa termina, esses valores são apagados, pois a memória principal é volátil.

    Organização em Endereços 📍
        A MP é dividida em pequenos blocos ou "endereços", e cada variável ou dado ocupa um desses espaços. Isso permite que o computador saiba exatamente onde encontrar cada informação.

    Execução de Instruções ⚙️
        Durante a execução do programa, o processador acessa a MP para ler e modificar os dados. Isso permite que operações e cálculos sejam feitos de forma muito rápida, pois a MP é muito mais acessível para o processador do que o armazenamento permanente (como o disco rígido).

    Função de Variável Auxiliar (AUX) 🔄
        Em alguns algoritmos, como o exemplo da troca de valores entre variáveis, uma variável auxiliar (AUX) é usada para armazenar temporariamente o valor de uma variável enquanto outro valor é atribuído. Isso impede a perda de dados importantes durante o processo.

    Importância na Computação 💻
        A MP permite que o computador realize operações diretamente em dados sem depender do armazenamento externo. Isso é fundamental para a eficiência e velocidade do processamento.

        Em resumo, a Memória Principal é onde o computador guarda e manipula os dados que estão sendo usados em tempo real. Ela é essencial para que o computador possa realizar operações com agilidade durante a execução de um programa.

   EXERCÍCIOS - LISTA 1

LEIA, IMPRIMA, ATRIBUIÇÃO E FUNÇÕES

Algoritmo 28

Objetivo: Imprimir a mensagem "É PRECISO FAZER TODOS OS ALGORITMOS PARA APRENDER".
prog leal
imprima "\nÉ PRECISO FAZER TODOS OS ALGORITMOS PARA APRENDER";
imprima "\n";
fimprog

Algoritmo 29

Objetivo: Imprimir seu nome.
prog lea2
imprima "\n<seu nome>";
imprima "\n";
fimprog

Algoritmo 30

Objetivo: Criar um algoritmo que imprima o produto entre 28 e 43.
prog lea3
int produto;
produto <- 28 * 43;
imprima "\nO produto entre os dois é: ", produto;
imprima "\n";
fimprog

Algoritmo 31

Objetivo: Criar um algoritmo que imprima a média aritmética entre os números 8, 9 e 7
prog lea4
real ma;
ma <- (8 + 9 + 7) / 3;
imprima "\nA média aritmética é: ", ma;
imprima "\n";
fimprog

Algoritmo 32

Objetivo: Ler um número inteiro e imprimi-lo.
prog lea5
int num;
imprima "\nEntre com um número: ";
leia num;
imprima "\nNúmero: ", num;
imprima "\n";
fimprog

Algoritmo 33

Objetivo: Ler dois números inteiros e imprimi-los.
prog lea6
int num1, num2;
imprima "\nEntre com um número: ";
leia num1;
imprima "\nEntre com outro número: ";
leia num2;
imprima "\nNúmero 1: ", num1;
imprima "\nNúmero 2: ", num2;
imprima "\n";
fimprog

Algoritmo 34

Objetivo: Ler um número inteiro e imprimir seu sucessor e antecessor.
prog lea7
int numero, suc, ant;
imprima "\nEntre com um número: ";
leia numero;
ant <- numero - 1;
suc <- numero + 1;
imprima "\nO sucessor é: ", suc, " e o antecessor é: ", ant;
imprima "\n";
fimprog

Algoritmo 35

Objetivo: Ler nome, endereço e telefone e imprimi-los.
prog lea8
string nome, endereco, telefone;
imprima "\nEntre com o nome: ";
leia nome;
imprima "\nEntre com o endereço: ";
leia endereco;
imprima "\nEntre com o telefone: ";
leia telefone;
imprima "\n\n";
imprima "\nNome: ", nome;
imprima "\nEndereço: ", endereco;
imprima "\nTelefone: ", telefone;
imprima "\n";
fimprog

Algoritmo 36

Objetivo: Ler dois números inteiros e imprimir a soma. Antes do resultado, deverá aparecer a mensagem: "Soma".
prog lea9
int num1, num2, soma;
imprima "\nEntre com um número: ";
leia num1;
imprima "\nEntre com outro número: ";
leia num2;
soma <- num1 + num2;
imprima "\nSoma: ", soma;
imprima "\n";
fimprog

Algoritmo 37

Objetivo: Ler dois números inteiros e imprimir o produto.
prog lea10
int num1, num2, prod;
imprima "\nEntre com um número: ";
leia num1;
imprima "\nEntre com outro número: ";
leia num2;
prod <- num1 * num2;
imprima "\nProduto: ", prod;
imprima "\n";
fimprog


Observações Importantes:

    Todas as palavras reservadas devem ser escritas em letras minúsculas.
    O operador de atribuição é <-.
    Os identificadores (nomes de variáveis e do algoritmo) devem começar com uma letra.
    Comandos como imprima, leia, atribuições e declarações de variáveis terminam com ;.
    Os comandos prog e fimprog não têm ;.
    Para evitar que o prompt fique na mesma linha da última impressão, utilize imprima "\n"; para inserir uma nova linha.

    Algoritmo 38

Objetivo: Ler um número real e imprimir a terça parte deste número.
prog leal1
real num;
imprima "\nEntre com um número com ponto: ";
leia num;
imprima "\nA terça parte é: ", num / 3;
imprima "\n";
fimprog


Algoritmo 39

Objetivo: Entrar com dois números reais e imprimir a média aritmética com a mensagem "média" antes do resultado.
prog leal2
real nota1, nota2, media;
imprima "\nDigite a 1ª nota: ";
leia nota1;
imprima "\nDigite a 2ª nota: ";
leia nota2;
media <- (nota1 + nota2) / 2;
imprima "\nMédia: ", media;
imprima "\n";
fimprog

Algoritmo 40

Objetivo: Entrar com dois números inteiros e imprimir a seguinte saída:

    dividendo
    divisor
    quociente
    resto

    prog leal3
int quoc, rest, val1, val2;
imprima "\nEntre com o dividendo: ";
leia val1;
imprima "\nEntre com o divisor: ";
leia val2;
quoc <- val1 div val2;
rest <- val1 % val2;
imprima "\n\n\n";
imprima "\nDividendo: ", val1;
imprima "\nDivisor: ", val2;
imprima "\nQuociente: ", quoc;
imprima "\nResto: ", rest;
imprima "\n";
fimprog

Algoritmo 41

Objetivo: Entrar com quatro números e imprimir a média ponderada, sabendo-se que os pesos são respectivamente: 1, 2, 3 e 4
prog lea14
real a, b, c, d, mp;
imprima "\nEntre com o 1º número: ";
leia a;
imprima "\nEntre com o 2º número: ";
leia b;
imprima "\nEntre com o 3º número: ";
leia c;
imprima "\nEntre com o 4º número: ";
leia d;
mp <- (a*1 + b*2 + c*3 + d*4) / 10;
imprima "\nMédia Ponderada: ", mp;
imprima "\n";
fimprog

Algoritmo 42

Objetivo: Entrar com um ângulo em graus e imprimir: seno, co-seno, tangente, secante, co-secante e co-tangente deste ângulo.
prog lea15
real angulo, rang;
imprima "\nDigite um ângulo em graus: ";
leia angulo;
rang <- angulo * pi / 180;
imprima "\nSeno: ", sen(rang);
imprima "\nCo-seno: ", cos(rang);
imprima "\nTangente: ", tan(rang);
imprima "\nCo-secante: ", 1 / sen(rang);
imprima "\nSecante: ", 1 / cos(rang);
imprima "\nCo-tangente: ", 1 / tan(rang);
imprima "\n";
fimprog


Observação: Em algumas situações, certos ângulos podem resultar em valores indefinidos para funções como secante, co-secante e co-tangente. Esse problema pode ser tratado utilizando estruturas de controle (como if) para verificar a validade dos valores antes de realizar os cálculos.
==================================================================================
Algoritmo: Cálculo de Custo de Energia

Objetivo: Fazer um algoritmo que receba o valor do salário mínimo e a quantidade de quilowatts gasta por uma residência e calcule:

    O valor em reais de cada quilowatt.
    O valor em reais a ser pago.
    O novo valor a ser pago com um desconto de 10%.

    prog lea21
real sm, qtdade, preco, vp, vd;
imprima "\nEntre com o salário mínimo: ";
leia sm;
imprima "\nEntre com a quantidade em quilowatts: ";
leia qtdade;

# Calcula o preço de 1 quilowatt (100 quilowatts = 1/7 do salário mínimo)
preco <- sm / 700;

# Calcula o valor a ser pago sem desconto
vp <- preco * qtdade;

# Calcula o valor com 10% de desconto
vd <- vp * 0.9;

# Exibe os resultados
imprima "\nPreço do quilowatt: ", preco;
imprima "\nValor a ser pago: ", vp;
imprima "\nValor com desconto: ", vd;
imprima "\n";
fimprog

Esse algoritmo calcula o custo por quilowatt, o valor total de energia a ser pago e o valor com desconto de 10%, com uma formatação adequada para facilitar a compreensão.

Algoritmo 49

Objetivo: Entrar com um nome e imprimir várias informações específicas sobre ele.

prog lea22
string nome;
int n;
imprima "\nEntre com o nome: ";
leia nome;

imprima "\nTodo nome: ", nome;
imprima "\nPrimeiro caractere: ", nome[0];
imprima "\nÚltimo caractere: ", nome[strtam(nome) - 1];
imprima "\nPrimeiro ao terceiro caractere: ", strsub(nome, 0, 3);
imprima "\nQuarto caractere: ", nome[3];
imprima "\nTodos menos o primeiro: ", strsub(nome, 1, strtam(nome));
n <- strtam(nome) - 2;
imprima "\nOs dois últimos: ", strsub(nome, n, strtam(nome));
imprima "\n";
fimprog


Algoritmo 50

Objetivo: Entrar com a base e a altura de um retângulo e imprimir o perímetro, área e diagonal.

prog lea23
real perimetro, area, diagonal, base, altura;
imprima "\nDigite a base: ";
leia base;
imprima "\nDigite a altura: ";
leia altura;

perimetro <- 2 * (base + altura);
area <- base * altura;
diagonal <- raiz(base**2 + altura**2);

imprima "\nPerímetro: ", perimetro;
imprima "\nÁrea: ", area;
imprima "\nDiagonal: ", diagonal;
imprima "\n";
fimprog

Algoritmo 51

Objetivo: Entrar com o raio de um círculo e imprimir o perímetro e a área.
prog lea24
real raio, perimetro, area;
imprima "\nDigite o raio: ";
leia raio;

perimetro <- 2 * pi * raio;
area <- pi * raio ** 2;

imprima "\nPerímetro: ", perimetro;
imprima "\nÁrea: ", area;
imprima "\n";
fimprog

=============================================
