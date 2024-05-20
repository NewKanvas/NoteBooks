# **Porcentagem**

Na garrafa de mostarda esta escrito que em uma porção de 12g tem 4% de Sódio.

### **Fórmula**:

Quanto uma ***Porcentagem*** representa = $\frac{Porcentagem \times Total}{100}$

### *Exemplo*:

    Sódio(mg) = (4*12) /100
    48/100

    -> 0,48 mg 
---

Exitem 20 garotos e 16 meninas em uma sala. Sendo assim 36 pessoas na sala.

### **Fórmula**:

Quanto uma ***Parte*** representa: $\frac{Parte}{Total} \times 100$

### *Exemplo*:

    % Garotos = (20/36)*100
    ~ 0,55 * 100

    -> 55,5% 

    % Meninas = % Garotos - 100

    -> 44,5% 

    * Prova Real

    % Meninas = (16/36)*100
    ~0,44 * 100

    -> 44,5% 
---

# **Valorização**

Eu coloquei R$55 em uma criptomoeda, depois de 2 meses eu tinha R$123.

### **Fórmula**:

$\frac{Valor Final - Valor Inicial}{Valor Inicial} \times 100$

### *Exemplo*:

    Valorização = ((123 - 55)/55) *100
    (68/55) * 100
    1,236*100

    -> 123,6% 
---

# **Juros Compostos**

Suponha que você tenha investido **um capital inicial de R$1000** em uma conta de investimento com **juros compostos de 5%** ao **ano**. **Após 3 anos**, qual será o valor do seu investimento?

### **Fórmula**

$Juros Apurados = Capital \times (1 + \frac{Taxa Juros}{100}) ^n$

Onde:

$n$ é o número de períodos de capitalização

### *Exemplo*:

    Rendimento = 1000*(1+0,05)^3
    1000*(1,05)^3
    1000*1,157625
    -> R$ 1157,625 

    Valor Atual = 1000 + 1157,625
    -> R$ 2157,625 
---

## ***Juros Simples***

Suponha que você emprestou R$2000 para um amigo a uma taxa de juros de 8% ao mês. Após 5 meses, quanto seu amigo terá que pagar de volta?

### **Fórmula**

$Juros Apurados = Capital \times (1 + \frac{Taxa Juros}{100}\times n)$

Onde:

- $n$ é o número de períodos de capitalização

### *Exemplo*:

    Juros = 2000*(1+0,08*5)
    2000*(1,08*5)
    2000*(5,40)
    -> R$ 10,800 

    Valor Atual = 2000 + 10,800
    -> R$ 2010,800 
---

# **Probabilidade**

Probabilidade de cair um numero par em um Dado de 6 lados.

### **Fórmula**

$Probabilidade = \frac{Favoráveis}{Possíveis}$

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

$P(A∣B)=\frac{P(A∩B)}{P(B)}$

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

# **Sistemas de amortização**

Métodos utilizados para calcular o valor das parcelas de um empréstimo ou financiamento ao longo do tempo, levando em consideração o pagamento do principal (valor emprestado) e dos juros.

*"Juros são sempre calculados sobre o saldo devedor!"*

Os principais sistemas de amortização são:

1. [**Sistema de Pagamento único**](#sistema-de-pagamento-único)
2. [**Sistema de Pagamentos variáveis**](#sistema-de-pagamentos-variáveis)
3. [**Sistema Americano**](#sistema-americano)
4. [**Sistema de Amortização Constante (SAC)**](#sistema-de-amortização-constante-sac)
5. [**Sistema Price ou Francês (PRICE)**](#sistema-price-ou-francês-price)
6. [**Sistema de Amortização Misto (SAM)**](#sistema-de-amortização-misto-sam)
7. [**Sistema Alemão**](#sistema-alemão)

Em todos os sistemas de amortização, cada pagamento é a soma do valor amortizado com os juros do saldo devedor, isto é:

$Pagamento = Amortizacão + Juros$

## ***Sistema de Pagamento único***
Um único pagamento no final.

Suponha que você pegou emprestado R$ 10.000 a uma taxa de juros de 5% ao ano para ser pago em um único pagamento ao final de 5 anos.

### **Fórmula**

$Montante = C (1+i)^n$

Onde:

- $C$ é o Capital (valor emprestado)
- $i$ é a taxa de juros por período (Em decimal)
- $n$ é o número de períodos.

### *Exemplo*:


---
## ***Sistema de Pagamentos variáveis***
Vários pagamentos diferenciados.

### **Fórmula**

### *Exemplo*:

---
## ***Sistema Americano***
Pagamento no final com juros calculados período a período.

### **Fórmula**

### *Exemplo*:

---
## ***Sistema de Amortização Constante (SAC)***
A amortização da dívida é constante e igual em cada período.

### **Fórmula**

### *Exemplo*:

---
## ***Sistema Price ou Francês (PRICE)***
Os pagamentos são iguais.

### **Fórmula**

### *Exemplo*:

---
## ***Sistema de Amortização Misto (SAM)***
Os pagamentos são as médias aritméticas dos sistemas SAC e Price.

### **Fórmula**

### *Exemplo*:

---
## ***Sistema Alemão***
Os juros são pagos antecipadamente com prestações iguais, exceto o primeiro pagamento que corresponde aos juros cobrados no momento da operação.

### **Fórmula**

### *Exemplo*:

---

# **Equivalência de capitais**

## **Fluxos regulares**

## **Fluxos irregulares**
