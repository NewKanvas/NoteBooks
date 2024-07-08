# ***Table of Contents*** <!-- omit in toc -->
- [Exponenciação](#exponenciação)
  - [Números com Expoentes altos](#números-com-expoentes-altos)
  - [Quadrado de 5](#quadrado-de-5)
- [Raiz Quadrada](#raiz-quadrada)


# Exponenciação

## Números com Expoentes altos

1. **Dividir o numero na maior quantidade de pares possíveis:**

$2^{10} → 2 \times 2 \times 2 \times 2 \times 2 \times 2 \times 2 \times 2 \times 2 \times 2$

$2^{10} → 4 \times 4 \times 4 \times 4 \times 4$

$2^{10} → 16 \times 16 \times 4$

2. **Decomposição:**

    Você pode decompor a potência em etapas menores mais fáceis de calcular. Por exemplo, em vez de calcular $1.01^{12}$ diretamente, você pode calcular $1.01^6$ e depois elevar o resultado ao quadrado.

$1.01^{12}$

$1.01^{12 \div 2}$

$1.01^6 → 1.01 \times 1.01 \times 1.01 \times 1.01 \times 1.01 \times 1.01 \times$

$1.01^6 → 1,0201 \times 1,0201 \times 1,0201$

$1.01^6 → 1,04060401 \times 1,0201$

$1.01^6 = 1,061520150601$

$1,061520150601^2 = 1,12682503013197$

---

1. Multiplicação de Potências de Mesma Base:
   
Para calcular a potência de uma potência, você pode multiplicar os expoentes.

    Exemplo: (a^m)^n = a^(m*n).

3. Potência de Um Produto:
   
Para calcular uma potência de um produto, você pode distribuir a potência para cada termo.

    Exemplo: (ab)^n = a^n * b^n.

4. Potência de um Quociente: 

Para calcular uma potência de um quociente, você pode distribuir a potência para o numerador e o denominador.

    Exemplo: (a/b)^n = (a^n) / (b^n).

## Quadrado de 5

Para calcular o quadrado de um número que termina em 5, multiplique o algarismo que vem antes do 5 pelo algarismo seguinte, 1 * 2. Em seguida, adicione 25 no final.

### Ex:

$15^2$

    1*2 = 2
    15^2 = 225

$65^2$

    6*7 = 42
    65^2 = 4225

$445^2$

    44*45 = 1980
    445^2 = 198025


# Raiz Quadrada

`Esta fórmula não é aplicável a números que terminam em 2, 3 ou 7.`

[*How To Calculate Square Roots*](https://www.youtube.com/watch?v=I7TFYa1v9xI&ab_channel=MindYourDecisions)
- Este vídeo aborda técnicas adicionais para calcular raízes quadradas, incluindo exemplos como $\sqrt{16384}$, discutidos por volta do minuto 6:47.

    Nele, é explicado que, para números grandes, o primeiro grupo de dígitos pode conter três dígitos em vez de dois.

- Além disso, o vídeo também explora a raiz cúbica, discutida por volta do minuto 7:34.

Para Números grandes tenha em mente que:

![resultado dos quarados](../images/image.png) 

### **Fórmula**

1. **Divida o numero em duas partes:**
   
    Separe o número em duas partes, por exemplo, 
    16384 seria dividido em 163 e 84.
    5554 seria dividido em 55 e 54

2. **Determine o último dígito da resposta:**

    Use a segunda parte (84) para identificar o último dígito da resposta.

    Se termina em 0, o último dígito da resposta será 0.
    Se termina em 1, 4, 5, 6, ou 9, utilize a tabela fornecida para determinar o último dígito possível.

| Último dígito da 2º parte do número | Último dígito do quadrado |
|---|---|
| 0 | 0 |
| 1 | 1 ou 9 |
| 4 | 2 ou 8 |
| 5 | 5 |
| 6 | 4 ou 6 |
| 9 | 3 ou 7 |

3. **Identifique o primeiro dígito da resposta:**  
   
   Utilize a primeira parte (163) para encontrar o maior quadrado perfeito que seja igual ou menor que esse número.

4. **Caso haja ambiguidade no último dígito da resposta:**
   
   Se houver mais de uma opção para o último dígito, utilize os primeiros dígitos da sua resposta com o final 5.
   31/39 -> 35
   122/128 -> 125
   
   E verifique o o quadrado desses números (35^2 ou 125^2) resultado.
   Se o resultado for maior do que o número original, escolha o menor dos dois dígitos finais possíveis; caso contrário, escolha o maior.

### *Exemplo 1*:

Calcular $\sqrt{1600}$

Para encontrar a raiz quadrada de 1600, dividimos o número em duas partes de dois dígitos: 16 e 00.

- A última parte, 00, termina em 0, então o último dígito da resposta será 0.

- Para a primeira parte, 16, procuramos o maior número cujo quadrado seja igual ou menor que 16.
Isso nos dá 4, porque $4^2 = 16$.

Portanto, $\sqrt{1600} = 40$.

---

### *Exemplo 2*:

Calcular $\sqrt{3969}$

Ao encontrar a raiz quadrada de 3969, observamos que o primeiro dígito será 6, pois o **maior quadrado menor ou igual a 39 é 6**.

- Para determinar o último dígito, consideramos que 69 pode levar a uma ambiguidade: os quadrados de **3** e **7** terminam em **9**. 
- Sendo assim a resposta poderia ser **63** ou **67**.Nesse caso, verificamos o resultado de $65^2$.

6*7 = 42
$65^2 = 4225$

Como 4225 é menor que 3969, sabemos que o último dígito da resposta deve ser o maior dos dois possíveis, 7.

Portanto, $\sqrt{3969} = 63$.

---

