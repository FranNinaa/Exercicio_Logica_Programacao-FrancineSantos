# Lógica de Programação - Lista de Exercícios 

## Objetivos
- Compreender na prática os conceitos de variáveis, sequência lógica, fluxo do processamento (Entrada - Processamento - Saída).
- Criar algoritmos simples capturando elementos da tela (Entrada de dados), efetuar cálculos aritméticos (Processamento) e imprimir os resultados na tela (Saída).
- Compreender os operadores aritméticos e a tipagem de dados.
- Desenvolver o raciocínio lógico e a habilidade analítica.

## Palavras-Chave
- Proposições, sequência lógica, fluxo do processamento, variáveis, operadores aritméticos

---

## Instruções Adicionais
- Resolva os exercícios propostos usando HTML e JavaScript.
- Crie um repositório no GitHub chamado "Exercicios_Logica_Programacao-[Seu Nome]".
- Crie uma pasta para cada lista de exercícios.

---

# ELista do exercicios 1

1. Faça um programa que leia o nome de uma pessoa e mostre uma mensagem de boas-vindas para ela:

```
Ex:
Qual é o seu nome? João da Silva
Olá João da Silva, é um prazer te conhecer!
```

2. Crie um programa que leia o nome e o salário de um funcionário, mostrando no final uma mensagem.

```
Ex:
Entrada:
Nome do Funcionário: Maria do Carmo
Salário: 1850,45
Saída:
O funcionário Maria do Carmo tem um salário de R$1850,45 em Junho.
```

3. Desenvolva um algoritmo que leia dois números inteiros e mostre o somatório entre eles.

```
Ex:
Entrada:
Digite um valor: 8
Digite outro valor: 5
Saída:
A soma entre 8 e 5 é igual a 13.
```

4. Faça um programa que leia as duas notas de um aluno em uma matéria e mostre na tela a sua média na disciplina.

```
Ex:
Entrada:
Nota 1: 4.5
Nota 2: 8.5
Saída:
A média entre 4.5 e 8.5 é igual a 6.5
```


5. Faça um programa que leia um número inteiro e mostre o seu antecessor e seu sucessor.

```
Ex:
Entrada:
Digite um número: 9
Saída:
O antecessor de 9 é 8
O sucessor de 9 é 10
```


6. Crie um algoritmo que leia um número real e mostre na tela o seu dobro e a sua terça parte.

```
Ex:
Entrada:
Digite um número: 3.5
Saída:
O dobro de 3.5 é 7.0
A terça parte de 3.5 é 1.16666
```

7. Desenvolva um programa que leia uma distância em metros e mostre os valores relativos em outras medidas.

```
Digite uma distância em metros: 185.72
Saída:
A distância de 185.72m corresponde a:
0.18572Km
1.8572Hm
18.572Dam
1857.2dm
18572.0cm
185720.0mm
```

8. Faça um algoritmo que leia quanto dinheiro uma pessoa tem na carteira (em R$) e mostre quantos dólares ela pode comprar. Considere US$1,00 = R$3,45.

9. Faça um algoritmo que leia a largura e altura de uma parede, calcule e mostre a área a ser pintada e a quantidade de tinta necessária para o serviço, sabendo que cada litro de tinta pinta uma área de 2 metros quadrados.

10. Crie um programa que leia o preço de um produto, calcule e mostre o seu PREÇO PROMOCIONAL, com 5% de desconto.
 ```
 Desconto: preco * 0.05
 Preço Promocional: preco - desconto
 ```

--- 

# Lista do exercicios 2

### Objetivos
- Reforçar a compreensão dos conceitos de variáveis, sequencia lógica, fluxo do processamento (Entrada - Processamento - Saída). 
- Criar algoritmos simples capturando elementos da tela (Entrada de dados), efetuar cálculos aritméticos (Processamento) e imprimir os resultados na tela (Saída). 
- Reforçar a compreensão dos operadores aritméticos, e tipagem de dados.   
- Compreender o funcionamento e aplicabilidade das **estruturas de seleção**.  
- Desenvolver o racíocinio lógico e a habilidade analítica. 
#### Palavras Chave  
- Proposições, sequência lógica, fluxo do processamento, veriáveis, operadores aritméticos, tipagem de dados, estruturas de seleção. 

---
### Instruções Adicionais 
- Resolva os exercícios propostos usando HTML e JavaScript

1. Elabore um algoritmo que permita a entrada de dois números diferentes e verifique qual deles é o maior. 

entradas 
   num1 e num2

processamnto 
   Descobrir qual o maior numero entre num1 e num2 
   SE num1 > num2 ENTAO 
      maior = num1 
   SENAO
      maior = num2
   FIM-SE

saidas 
  o maior numero 

2. Elabore um algoritmo que permita a entrada de três números e imprima o maior deles.

3. Elabore um algoritmo para Entrar com um número e imprimir uma das mensagens: 
 	maior do que 20, igual a 20 ou menor do que 20.

4. Entrar com um número e verificar se o mesmo está no intervalo entre 30 e 90, inclusive. 

5. Elabore um algoritmo para entrar com três números e imprimi-los em ordem decrescente (suponha números diferentes). 

6. Construa uma calculadora. O programa deverá receber 2 números e o caractere equivalente a um dos operadores aritméticos. Efetuar a operação aritmética correspondente e apresentar o resultado. 

Entrada 
   num1 
   num2 
   operacao =  + - * /

processamento
   descobrir qual é a operação 
   if(operacao == "+")
   efetuar a operaçao correspondente

saida 
  resultado da operacao aritmetica


7. Entrar com o salário de uma pessoa e imprimir o Salário Líquido, segundo a tabela a seguir:
   
|  Salário Bruto                                   |   INSS   |
|:-------------------------------------------------|:--------:|
| Menor ou igual a R$600,00                        |  Isento  |
| Maior que R$600,00 e menor ou igual a R$1200,00  |    25%   |
| Maior que R$1200,00 e menor ou igual a R$2000,00 |    30%   |
| Maior que R$2000,00                              |    35%   |	

- O salário líquido é igual ao Salário Bruto menos o desconto de INSS. 

8.	Um comerciante comprou um produto e quer vende-lo com um lucro de 50% se o valor da compra for menor que R$ 20,00. Caso contrário, o lucro será de 35%. Entrar com o valor do produto e imprimir o valor de venda.



9. Crie um programa para calcular a área das formas geométricas básicas:  
a.	Círculo (pedir o raio);  
b.	Retângulo (pedir a base e altura);  
c.	Triangulo retângulo (pedir a base e altura);  
d.	Triangulo Equilátero: pedir o lado.
- O usuário deve poder escolher a forma geométrica que deseja calcular a partir de um menu.   

10. Crie um programa para autenticação de usuários.

- Salve 3 usuários em variáveis pré-inicializadas 

|  userId   |    senha    |
|-----------|:-----------:|
| Aluno1    |  Trocar123  |
| Aluno2    |  Senha@123  |
| Aluno3    |  123Trocar  |

- Regras
-   Se o usuário informar o userId e senha corretamente o sistema deverá exibir a mensagem: 

    **"Acesso Permitido"**

-   Se o userId não estiver correto, exibir: 

    **"Usuário não cadastrado"**

-   Se o usuário estiver correto, mas a senha estiver errada, exibir:

    **"Senha incorreta"**
<br><br>

    # Lista do exercicios 3

    ### Objetivos
- Reforçar a compreensão dos conceitos de variáveis, sequencia lógica, fluxo do processamento (Entrada - Processamento - Saída). 
- Criar algoritmos simples capturando elementos da tela (Entrada de dados), efetuar cálculos aritméticos (Processamento) e imprimir os resultados na tela (Saída). 
- Reforçar a compreensão dos operadores aritméticos, e tipagem de dados.   
- Compreender o funcionamento e aplicabilidade das **estruturas de seleção**.  
- Promover a construção de um ferramental lógico e algorítmico para posterior aplicação em soluções de maior complexidade.
- Desenvolver o racíocinio lógico e a habilidade analítica. 
#### Palavras Chave  
- Proposições, sequência lógica, fluxo do processamento, veriáveis, operadores aritméticos, tipagem de dados, estruturas de seleção. 

---
### Instruções Adicionais 
- Resolva os exercícios propostos usando HTML e JavaScript

--- 

1. Escreva um programa que pergunte a velocidade de um carro. Caso ultrapasse 80Km/h, exiba uma mensagem dizendo que o usuário foi multado. Nesse caso, exiba o valor da multa, cobrando R$5 por cada Km/h acima da velocidade permitida.

2. Faça um programa que leia o ano de nascimento de uma pessoa, calcule a idade dela e depois mostre se ela pode ou não votar.

3. Crie um algoritmo que leia o nome e as duas notas de um aluno, calcule a sua média e mostre na tela. No final, analise a média e mostre se o aluno teve ou não um bom aproveitamento (se ficou acima da média 7.0).

4. Desenvolva um programa que leia um número inteiro e mostre se ele é PAR ou ÍMPAR.

5. Faça um algoritmo que leia um determinado ano e mostre se ele é ou não BISSEXTO. 

6. Escreva um programa que leia o ano de nascimento de um rapaz e mostre a sua situação em relação ao alistamento militar.
- Se estiver antes dos 18 anos, mostre em quantos anos faltam para o alistamento.
- Se já tiver depois dos 18 anos, mostre quantos anos já se passaram do alistamento.

7. Numa promoção exclusiva para o Dia da Mulher, uma loja quer dar descontos para todos, mas especialmente para mulheres. Faça um programa que leia nome, sexo e o valor das compras do cliente e calcule o preço com desconto. Sabendo que:

- Homens ganham 5% de desconto
- Mulheres ganham 13% de desconto

8. Faça um algoritmo que pergunte a distância que um passageiro deseja percorrer em Km. Calcule o preço da passagem, cobrando R$0.50 por Km para viagens até 200Km e R$0.45 para viagens mais longas.

9. Crie um programa que leia o tamanho de três segmentos de reta.
Analise seus comprimentos e diga se é possível formar um triângulo com essas retas. Matematicamente, para três segmentos formarem um triângulo, o comprimento de cada lado deve ser menor que a soma dos outros dois.

10. O Índice de Massa Corpórea (IMC) é um valor calculado baseado na altura e no peso de uma pessoa. De acordo com o valor do IMC, podemos classificar o indivíduo dentro de certas faixas.
    - abaixo de 18.5: Abaixo do peso
    - entre 18.5 e 25: Peso ideal
    - entre 25 e 30: Sobrepeso
    - entre 30 e 40: Obesidade
    - acima de 40: Obesidade mórbida

    Obs: O IMC é calculado pela expressão peso/altura² (peso dividido pelo quadrado da altura)

    Crie um programa que receba o peso e a altura de uma pessoa e informe na tela em que faixa de IMC ela se encontra. 

## Realização dos Exercícios
Os exercícios foram desenvolvidos e implementados em HTML e JavaScript conforme as instruções fornecidas.
<br><br>

# Lista de Exercícios 4
### Objetivos
- Compreender na prática o funcionamento das estruturas de repetição.  
- Criar algoritmos simples usando estruturas de repetição. 
- Reforçar a fixação dos conteúdos anteriores. 
- Promover a construção de um ferramental lógico e algorítmico para posterior aplicação em soluções de maior complexidade.
- Desenvolver o racíocinio lógico e a habilidade analítica. 
#### Palavras Chave  
- Estruturas de repetição, estruturas de seleção, operadores relacionais, operadores lógicos, proposições
---
### Instruções Adicionais 
- Exercícios 1 à 4:
Crie o programa utilizando um estrutura de repetição PARA, depois crie uma versão 2 utilizando a estrutura de repetição ENQUANTO. 

- Todos os exercícios devem ser resolvidos usando estruturas de repetição. 
---
### Exercícios 
1. Escreva um programa que mostre na tela a seguinte contagem:
"Inicio 5 6 7 8 9 10 11 12 Acabou!". 

2. Faça um algoritmo que mostre na tela a seguinte contagem:
"Inicio 15 14 13 12 11 10 9 8 7 6 5 4 3 Acabou!" 

3. Crie um aplicativo que mostre na tela a seguinte contagem:
"Inicio 0 4 8 12 16 20 Acabou!" 

4. Desenvolva um programa que mostre na tela a seguinte contagem: "Inicio 100 95 90 85 80 ... 0 Acabou!"

5. Faça um algoritmo que pergunte ao usuário um número inteiro e positivo qualquer e mostre uma contagem até esse valor:  
Ex: Digite um valor: 77  
Contagem: "Inicio 1 2 3 4 5 6 7 ... 75 76 77 Acabou!" 

6. Desenvolva um algoritmo que mostre uma contagem regressiva de 30 até 1, marcando os números que forem divisíveis por 4, exatamente como mostrado abaixo:  
30 29 [28] 27 26 25 [24] 23 22 21 [20] 19 18 17 [16]...

7. Crie um programa que calcule e mostre na tela o resultado da soma entre 6 + 8 + 10 + 12 + 14 + ... + 98 + 100.


8. Crie um algoritmo que leia o valor inicial da contagem, o valor final e o incremento, mostrando em seguida todos os valores no intervalo:  
Exemplo: 
Digite o primeiro Valor: 3 
Digite o último Valor: 10  
Digite o incremento: 2  
Contagem: 3 5 7 9 Acabou!

9. O programa acima vai ter um problema quando digitarmos o primeiro valor maior que o último. Resolva esse problema com um código que funcione em qualquer situação.

10. Crie um programa que leia os valores inicial e final de um intervalo e imprima todos os valores impares ou pares contidos no intervalo. 
- O usuário deve poder escolher entre impares e pares.  
<br><br>

# Lista de Exercícios 5
### Objetivos
- Compreender na prática o funcionamento das estruturas de repetição.  
- Criar algoritmos simples usando estruturas de repetição. 
- Reforçar a fixação dos conteúdos anteriores. 
- Promover a construção de um ferramental lógico e algorítmico para posterior aplicação em soluções de maior complexidade.
- Desenvolver o racíocinio lógico e a habilidade analítica. 
#### Palavras Chave  
- Estruturas de repetição, estruturas de seleção, operadores relacionais, operadores lógicos, proposições
---

### Instruções Adicionais 


---
### Exercícios  
1. Crie um algoritmo que mostre na tela todos os números entre 1 e 100 que sejam múltiplos de 3 ou 5.

2. Crie um programa que leia os valores inicial e final de um intervalo e imprima todos os números primos contidos no intervalo. 

3. Desenvolva um programa que faça o sorteio de 20 números entre 0 e 10 e mostre na tela:
a) Quais foram os números sorteados  
b) Quantos números estão acima de 5  
c) Quantos números são divisíveis por 3  

4. Faça um programa que mostre os 10 primeiros elementos da Sequência de Fibonacci:  
0 1 1 2 3 5 8 13 21...

5. Crie um aplicativo que leia o preço de 'n' produtos. No final, mostre na tela qual foi o maior e qual foi o menor preço digitados.

6. Crie um algoritmo que leia a idade de 'n' pessoas, mostrando no final:  
a) Qual é a média de idade do grupo  
b) Quantas pessoas tem mais de 18 anos  
c) Quantas pessoas tem menos de 5 anos  
d) Qual foi a maior idade lida  

7. Em um jogo de adivinhação, o jogador deve descobrir um número entre 1 e 10 usando até três tentativas. A cada tentativa o jogador é informado se o número foi descoberto, ou se ele é maior ou menor do que a tentativa. Se após três tentativas o jogador não descobrir o número, então ele perde o jogo. Crie um algoritmo que implemente esse jogo.

8. Ler uma temperatura em graus Celsius e apresentá-la convertida em graus Fahrenheit. A fórmula de conversão é: F=(9*C+160)/5, sendo F a temperatura em Fahrenheit e C a temperatura em Celsius. 

9. Crie um novo programa a partir do exercício anterior e permita que o usuário escolha em que unidade de medida ele deseja informar a temperatura (C, F ou K). O programa deverá converter deverá converter a temperatura para as outras unidades de medida. 

    Sendo C= Celsius, F= Fahrenheit e K = Kelvin 

    Formulas fornecidas: 

    K=C+273

    K-273 = C

    F=(9*C+160)/5 

    ((F * 5)-160)/9 = C

    ((F * 5)-160)/9 + 273 = K

    F  = (((K - 273) * 9) + 160)/5

    Referências: https://www.infoescola.com/fisica/conversao-de-escalas-termometricas/

10. Elaborar um programa para a casa de câmbio que receba as cotações do dia e efetue a conversão de uma moeda para outra. O programa deverá permitir conversões entre Real, Dólar Americano, Euro, Libra Esterlina e Dólar Canadense. 
- O usuário pode selecionar o tipo de moeda de entrada e selecionar o tipo para o qual ele deseja converter.

--------> entra -- Dolar -- Destino 
<br><br>
# Lista de Exercícios 6 
### Objetivos
- Compreender na prática a aplicabilidade e funcionamento das estruturas de dados. 
- Reforçar a fixação dos conteúdos anteriores. 
- Promover a construção de um ferramental lógico e algorítmico para posterior aplicação em soluções de maior complexidade.
- Desenvolver o racíocinio lógico e a habilidade analítica.

#### Palavras Chave  
- Estruturas de dados, Vetores, estruturas de repetição, estruturas de seleção
---
### Instruções Adicionais 
- Resolva os exercícios propostos usando HTML e JavaScript.

---
### Exercícios 

1. Crie um programa que preencha automaticamente (usando lógica, não apenas atribuindo diretamente) um vetor numérico com 10 posições conforme abaixo:  

|  5 | 10 | 15 | 20 | 25 | 30 | 35 | 40 | 45 | 50 |
|----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|  0 |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |

2. Crie um programa que preencha automaticamente (usando lógica, não apenas atribuindo diretamente) um vetor numérico com 10 posições, conforme abaixo:

|  9 |  8 |  7 |  6 |  5 |  4 |  3 |  2 |  1 |  0 |
|----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|  0 |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |

3. Crie um programa que preencha automaticamente (usando lógica, não apenas atribuindo diretamente) um vetor numérico com 10 posições, conforme abaixo:

|  5 |  3 |  5 |  3 |  5 |  3 |  5 |  3 |  5 |  3 |
|----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|  0 |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |

4. Crie um programa que preencha automaticamente (usando lógica, não apenas atribuindo diretamente) um vetor numérico com 15 posições com os primeiros elementos da sequência de Fibonacci:

|  1 |  1 |  2 |  3 |  5 |  8 | 13 | 21 | 34 | 55 | 89 | 144| 233| 377| 610| 987| 
|----|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|  0 |  1 |  2 |  3 |  4 |  5 |  6 |  7 |  8 |  9 |  10|  11|  12|  13|  14|  15|


5. Crie um programa que preencha automaticamente um vetor numérico com 20
números gerados aleatoriamente pelo computador e depois mostre os valores
gerados na tela (console.log).

6. Faça um programa que leia "n" nomes de pessoas e guarde-os em um vetor. No
final, mostre uma listagem com todos os nomes informados, na ordem inversa
daquela em que eles foram informados.

7. Escreva um programa que leia "n" números e guarde-os em um vetor. No final,
mostre o vetor inteiro na tela e em seguida mostre em que posições foram
digitados valores que são múltiplos de 10.

8. Faça um algoritmo que preencha um vetor de 30 posições com números entre 1 e 15 sorteados pelo computador. Depois disso, peça para o usuário digitar um número (chave) e seu programa deve mostrar em que posições essa chave foi
encontrada. Mostre também quantas vezes a chave foi sorteada.
<br><br>

# Lista de Exercícios 7 
### Objetivos
- Compreender na prática a aplicabilidade e funcionamento das estruturas de dados. 
- Reforçar a fixação dos conteúdos anteriores. 
- Promover a construção de um ferramental lógico e algorítmico para posterior aplicação em soluções de maior complexidade.
- Desenvolver o racíocinio lógico e a habilidade analítica.
#### Palavras Chave  
- Estruturas de dados, arrays, estruturas de repetição, estruturas de seleção
---
### Instruções Adicionais 
- Resolva os exercícios propostos usando HTML e JavaScript.

---
### Exercícios 
1. Faça um algoritmo que leia a nota de "n" alunos de uma turma e guarde-as em um vetor. No final, mostre:  
a) Qual e a media da turma   
b) Quantos alunos estão acima da média da turma  
c) Qual foi a maior nota digitada  
d) Em que posições a maior nota aparece  

2. Crie um programa que leia o nome e a idade de 9 pessoas e guarde esses valores em dois vetores, em posições relacionadas. No final, mostre uma listagem contendo apenas os dados das pessoas menores de idade.

3. Faça um algoritmo que leia o nome, o sexo e o salário de 5 funcionários e guarde esses dados em três vetores. No final, mostre uma listagem contendo apenas os dados das funcionárias mulheres que ganham mais de R$5 mil.

4. Crie um programa para armazenar informações meteorológicas. 
    - Crie um vetor para armazenar 30 temperaturas. (pre-inicializado)
    - Calcular a média das temperaturas. 
    - O usuário pode informar um dia qualquer e o programa deve dizer se a temperatura desse dia estava acima ou abaixo da média. (dia = indice) 

5. Crie um programa para:
    - Ler 10 números.
    - Permitir ao usuário que escolha entre:
        -   Ordenar em ordem crescente                
        -   Ordenar em ordem decrescente 


6. Crie um programa para gerenciar as notas dos alunos de uma escola. 
    - Crie um vetor para armazenar o nome dos alunos.
    - Crie um vetor para armazenar o endereço dos alunos. 
    - Crie um vetor para armazenar o nome da mãe dos alunos.
    - Crie um vetor para armazenar o nome do pai dos alunos. 
    - Crie um vetor para armazenar o telefone dos pais dos alunos. 
    - Crie 4 vetores para armazenar 4 notas por aluno.
    - As informações nos vetores se relacionarão através dos indexadores dos vetores.
    - Crie uma tela para cadastrar os alunos (nome, endereço, nome dos pais, telefone).
    - Crie uma tela para cadastrar as notas dos alunos. 
    - Crie uma tela para consultar o cadastro e situação dos alunos.   

 7. Crie um jogo de perguntas e respostas. O programa deverá sortear aleatoriamente um estado brasileiro e o jogador deverá responder informando qual é a respectiva capital. 
    - Cadastrar todos os estados Brasileiros  e suas respectivas capitais.
    - Permitir 4 jogadores. 
    - A cada acerto é somado 1 ponto para o jogador.
    - Ao final do jogo, informar quem ganhou e sua respectiva pontuação (poderá haver empates). 
    - Apresentar os resultados em ordem decrescente (do primeiro ao ultimo colocado).    


    ## Lista de Exercícios 8 
### Objetivos
- Reforçar a compreenção da aplicabilidade e funcionamento das funções
- Reforçar na prática a aplicabilidade e funcionamento das estruturas de dados. 
- Reforçar a fixação dos conteúdos anteriores. 
- Promover a construção de um ferramental lógico e algorítmico para posterior aplicação em soluções de maior complexidade.
- Desenvolver o racíocinio lógico e a habilidade analítica.
- Fixar o conhecimento sobre manipulação de arrays usando métodos da classe Arry
#### Palavras Chave  
- Estruturas de dados, arrays, funções, métodos de Array
---
### Instruções Adicionais 
- Resolva os exercícios propostos usando HTML e JavaScript.
- Utilise Bootstrap para estilizar as telas. 
---
### Exercícios 
1.  Para cada elemento de frutas, criar um option no datalist idFrutas;
    O elemento/fruta deve constar na propriedade innerText e sua respectiva posição deve ser posta no id do Option, conforme exemplo abaixo (veja html). 

~~~javaScript
    var frutas = ["tomate", "morango", "limão", "Abacaxi", "Pêra", "Uva"]
~~~

~~~html
    <!-- Lista de dados (seleção de item) -->
    <label for="idFrutas">Frutas:</label><br>
    <input list="idFrutas">
    <datalist id="idFrutas">
        <option value="0">tomate</option>
        <option value="1">morango</option>
    </datalist>
~~~

2. Refatore o exercício L7E2 usando os métodos filter(), map() e reduce(), no lugar das estruturas de repetição tradicionais, para processar os vetores idades[] e nomes[] a fim de mostrar a listagem contendo apenas os dados das pessoas menores de idade.

3. Refatore o exercício L7E3 usando os métodos filter(), map() e reduce(), no lugar das estruturas de repetição tradicionais, para processar os vetores nomes[], sexos[] e salários[] a fim de mostrar uma listagem contendo apenas os dados das funcionárias mulheres que ganham mais de R$5 mil.

4. Refatore o exercício L7E3, armazenando os dados dos funcionarios em um array de JSObjects, seguindo a estrutura mostrada no exemplo abaixo. 

~~~javaScript
    var funcionarios = [] 
    var funcionario = {
        nome: "Joao", 
        sexo: "M", 
        salario: 3500
    }
    funcionarios.push(funcionario)
~~~

Use os métodos filter(), map() e reduce(), no lugar das estruturas de repetição tradicionais, para processar o vetor funcionarios[] a fim de mostrar uma listagem contendo apenas os dados das funcionárias mulheres que ganham mais de R$5 mil.

5. Refatore o exercício L7E5, corrigindo o método de ordenação dos botões "idOrdemCresSort" e "idOrdemDecresSort" de forma que a sequencia numérica do vetor num[] seja ordenada corretamente em ordem crescente e decrescente respectivamente. 
