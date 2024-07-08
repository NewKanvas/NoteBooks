# ***Table of Contents*** <!-- omit in toc -->
- [**Probabilidade**](#probabilidade)
  - [***Probabilidade Composta***](#probabilidade-composta)
  - [***Probabilidade Condicional***](#probabilidade-condicional)
- [***Análise combinatória***](#análise-combinatória)
  - [**Principio Multiplicativo (Arranjo)**](#principio-multiplicativo-arranjo)
  - [**Permutação**](#permutação)
  - [**Combinação**](#combinação)
- [***Medidas de tendência***](#medidas-de-tendência)
  - [***Média***](#média)
  - [***Mediana***](#mediana)
  - [***Moda***](#moda)
- [**Medidas de dispersão**](#medidas-de-dispersão)
  - [***Variância (σ2)***](#variância-σ2)
  - [***Desvio-padrão (σ)***](#desvio-padrão-σ)
  
---

# **Probabilidade**

Probabilidade de cair um numero par em um Dado de 6 lados.

### **Fórmula**

$$Probabilidade = \frac{Favoráveis}{Possíveis}$$

### *Exemplo*:

    Total Favoráveis = {2, 4, 6}
    Total Possíveis = {1, 2, 3, ..., 6}

    Probabilidade = 3/6
    Probabilidade = 1/2
    1/2 = 0,5 -> 50% 
    Probabilidade de $\frac{3}{6}$ ou $\frac{1}{2}$, 50% de chance de cair um número par.

---

## ***Probabilidade Composta***

> ***A probabilidade dos eventos são independentes***

Probabilidade de obter um número par em ambos os lançamentos de dois dados.

### **Fórmula**

$P(A) \times P(B) \times P(C)...$

Onde:

- $P(A)$ probabilidade de um evento A
- $P(B)$ probabilidade de um evento B
- $P(C)$ probabilidade de um evento C


### *Exemplo*:

    P(Número Par) = 1/2
    P(Número Par Dois Dados) = 1/2 * 1/2
    = 1/4 -> 25%

    P(Número Par Três Dados) = 1/2 * 1/2 * 1/2
    = 1/8 ->  12,5%

    P(Número Par Três Dados Diferentes) = 2/4 * 3/6 * 10/20
---

## ***Probabilidade Condicional***

> ***Quando a probabilidade dos eventos são dependentes***

"Uma moeda comum foi lançada três vezes"
Qual é a probabilidade de se obter exatamente duas caras sabendo que o primeiro resultado foi cara?

### **Fórmula**

$$P(A∣B)=\frac{P(A∩B)}{P(B)}$$


Onde:

- $(B)$ é o condicionante.
- $P(A∣B)$ é a probabilidade condicional de A dado B.
- $P(A∩B)$ é a probabilidade de ambos A e B ocorrerem (a interseção de A e B).
- $P(B)$ é a probabilidade de B ocorrer.

### *Exemplo*:

    P(A) Possui EXATAMENTE duas CARAS
    P(B) Primeiro lançamento foi CARA

    H = Cara
    T = Coroa

    B = {(H, T, T); (H, H T); (H, T H); (H, H, H)}
    n(B) = 4

    A∩B → O resultado possui exatamente duas caras, e o primeiro resultado é cara.

    A∩B = {(H, H T); (H, T H)}
    n(A∩B) = 2

    -> P(A∣B) = 2/4 ->> 1/2
---
# ***Análise combinatória***

## **Principio Multiplicativo (Arranjo)**
"Técnica do tracinho"

De quantos modos posso ir a uma festa se tenho:
- 2 camisas
- 4 calças
- 3 sapatos

### **Fórmula**

Evento A pode ocorrer de m maneiras diferentes;
Evento B pode ocorrer de n maneiras diferentes;
Número total de resultados possíveis é:

$$m \times n$$

### *Exemplo*:

    - 2 camisas
    - 4 calças
    - 3 sapatos
    
    2 * 4 * 3 = 24

### *Exemplo 2*:
"De quantos modos duas pessoas, podem sentar em uma sala com 20 cadeiras"

    1º pessoa - 20 possibilidades
    2º pessoa - 19 possibilidades

    20 * 19 = 380

### *Exemplo 3*:
"Uma sala possui 3 portas, de quantas maneiras a sala pode estar ABERTA"

    1º porta - 2 possibilidades (Aberta & Fechada)
    2º porta - 2 possibilidades
    3º porta - 2 possibilidades

    2 * 2 * 2 = 8

Analisando combinações possíveis:

    8 - Maneiras
    A = Aberta
    F = Fechada

    (A - F - F, 
    F - A - F, 
    F - F - A, 
    ... 
    F - F - F)

    F.F.F a sala esta fechada, dentro das 8 maneiras esta é a única na qual a sla estará fechada

    8 - 1 = 7 Maneiras da Sala Estar ABERTA

---

## **Permutação**
*"A ordem importa"*

### **Permutação Simples:**
*"Não há nenhum elemento repetido."*

Quantos anagramas de (A,B,C,D,E) existem? / De quantos modos distintos 5 pessoas podem sentar em 5 lugares

### **Fórmula**

$$ Pn = n! $$

### *Exemplo*:

        P5 = 5!
        P5 = 5.4.3.2.1
        P5 = 120 Modos

#### **Método do Tracinho**

"Sempre que voce trocar um elemento de lugar e obter resultados diferentes pode usar o método do tracinho"

$$(A,B,C,D,E) ≠ (E,B,C,D,A)$$

Existem 5 posições com 5 possíveis elementos.
E vão diminuindo conforme posições são tomadas.
""O Calculo A seguir não envolve divisão"""

$\frac{5}{1º}\times \frac{4}{2º}\times \frac{3}{3º}\times \frac{2}{4º}\times \frac{1}{5º} = 120$

**120** Modos possíveis

---
### **Permutação com Repetição:**
*"Há elementos repetidos"*

"Qual é a diferença entre o número de anagramas da palavra ANAGRAMA e ARARA?"

### **Fórmula**

$$ Pn^{(a,b)} = \frac{n!}{a!b!} $$

Onde:
- n = Numero total de elementos
- a = Numero de repetições do elemento repetido
- b = Numero de repetições do elemento repetido
...

### *Exemplo*:

ANAGRAMA: Possui 8 letras mas a letra A aparece 4 vezes.

    P8^4 = 8! / 4!

    P8^4 = 8.7.6.5.4! / 4!

    P8^4 = 8.7.6.5

    P8^4 = 1680

ARARA: Possui 5 letras mas A aparece 3 vezes e a letra R aparece 2 vezes.

    P5^(3,2) = 5! / 3! . 2!

    P5^(3,2) = 5.4.3! / 3! . 2!

    P5^(3,2) = 5.4 / 2.1

    P5^(3,2) = 20 / 2

    P5^(3,2) = 10

Sendo assim:

    1680 – 10 = 1670 a diferença 
    entre o número de anagramas 

---
## **Combinação**
*"A ordem não importa"*
$(A,B,C) = (C,B,A)$

Quantos trios posso formar com 5 pessoas (A,B,C,D,E).

### **Fórmula**

$$Cn,p = \frac{n!}{p!(n-p)!} $$

Onde:
- n = Número de Elementos
- p = Número de Posições 

### *Exemplo*:

    C(5,3) = 5! / 3!(5-3)!

    C(5,3) = 5.4.3! / 3!(5-3)1

    C(5,3) = 5.4 / 2!

    C(5,3) = 20 / 2
    C(5,3) = 10

    ou

    C(5,3) = 5.4 / 2  (Divide o 4 para 2)
    C(5,3) = 5.2 = 10

---

Permutação: A ordem importa (Exemplo: Classificação em uma corrida).
Combinação: A ordem não importa (Exemplo: Seleção de um grupo).
Regra do Produto: Contando possibilidades em várias etapas (Exemplo: Várias escolhas consecutivas).

---

# ***Medidas de tendência***

---

## ***Média***

"Soma de todos os valores divida pelo número de valores"

Em um grupo de dança, as idades dos integrantes foram coletadas e representadas na lista a abaixo:

> (18, 20, 20, 21, 21, 21, 22, 22, 25, 30)

### **Fórmula**

$$x = \frac{a_1 + a_2 + a_3...an}{n}$$

### *Exemplo*:

     m = (18 + 20 + 20 + 21 + 21 + 21 + 22 + 22 + 25 + 30)/ 10
     m = 220 / 10
     m = 22

---

## ***Mediana***

Valor do meio quando os dados são ordenados.

### *Exemplo 1*:

> (2, 2, 3, 3, **4**, 5, 6, 7, 9)

O elemento **4** divide a lista em duas partes iguais, logo, ele é o elemento central.

### *Exemplo 2*:

> (18, 20, 20, 21, **21**, **21**, 22, 22, 25, 30)

O número da lista é par, logo, não é possível dividir em duas partes iguais. Assim devemos tomar dois elementos centrais e realizar a média aritmética desses valores (Dividir por 2 no caso).

    m = 21 + 21 /2
    m = 42/2 
    m = 21

---

## ***Moda***
"Valor que mais aparece"

### *Exemplo*:
> (18, 20, 20, **21**, **21**, **21**, 22, 22, 25, 30)

21 aparece um total de **3x**, sendo assim, a moda é igual a ***21***.

---

# **Medidas de dispersão**

"As medidas de dispersão são utilizadas nos casos em que a média já não é suficiente."

Em medidas que há enorme diferença entre valores, vale mais a pena usar as medidas de dispersão que mostram mais dados.

    79.000 km e 1.000 km
    x̅ = 40.000

A média de 40.000 km esconde a enorme diferença entre as distâncias

[*VARIÂNCIA e DESVIO PADRÃO (Sandro Curió)*](https://www.youtube.com/watch?v=JEwd0Vlqapo&ab_channel=DicasdematSandroCuri%C3%B3)

---

## ***Variância (σ2)***

A variância mede a dispersão média dos dados em relação à média, expressa em unidades ao quadrado.

### **Fórmula**
$$σ2 = \frac{(x_1 - \overline{x})^2... + (x_n - \overline{x})^2}{n}$$

$\overline{x}$ = Média Aritmética

O desvio/diferença $(x_n - \overline{x})$ tem que estar positivo em modulo. Para garantir que o desvio seja sempre positivo, podemos utilizar o valor absoluto dos desvios ao quadrado.

### *Exemplo 1*:
    (79K km, 1K km)
    x̅ = 40K

    σ2 = (79 - 40)² + (40 - 1)² / 2
    σ2 = 39² + (39)² / 2
    σ2 = 1521 + 1521 / 2
    σ2 = 3042 / 2
    σ2 = 1521
 
### *Exemplo 2*:
    (4 ,7 ,10)

    x̅ = 21 / 3
    x̅ = 7

    σ2 = (7 - 4)² + (7 - 7)² + (10 - 7)² / 3
    σ2 = 3² + 0² + 3² / 3
    σ2 = 9 + 0 + 9 / 3
    σ2 = 18 / 3
    σ2 = 6

---

## ***Desvio-padrão (σ)***

O desvio-padrão é dado pela raiz da variância, ele nos indica o quanto um elemento está disperso em relação à média. O desvio padrão é denotado por σ.

### **Fórmula**

$σ = \sqrt{σ2}$

### *Exemplo 1*:
    (79K km, 1K km)
    x̅ = 40K
    σ2 = 1521

    σ = √1521
    σ = 39

### *Exemplo 2*:
    (4 ,7 ,10)
    x̅ = 7
    σ2 = 6

    σ = √6
    σ ≅ 2,44
---
