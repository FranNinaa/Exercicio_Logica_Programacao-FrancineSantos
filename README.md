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

## ELista do exercicios 1

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

## Lista do exercicios 2

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


    ## Lista do exercicios 3

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
