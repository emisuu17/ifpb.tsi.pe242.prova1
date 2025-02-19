# TSI-Programação-Estruturada242-Prova01

## Questão 1:
   
Dado um número inteiro x, retorne verdadeiro se x for um palíndromo, e falso caso contrário.

Exemplo 1:

Entrada: x = 121
Saída: True
Explicação: 121 é lido como 121 da esquerda para a direita e da direita para a esquerda.

Exemplo 2:

Entrada: x = -121
Saída: False
Explicação: Da esquerda para a direita, lê-se -121. Da direita para a esquerda, torna-se 121-. Portanto, não é um palíndromo.

Exemplo 3:

Entrada: x = 10
Saída: False
Explicação: Lê-se 01 da direita para a esquerda. Portanto, não é um palíndromo.

## Questão 2:

Os numerais romanos são representados por sete símbolos diferentes: I, V, X, L, C, D e M.

| Símbolo | Valor |
|---------|-------|
| I       | 1     |
| V       | 5     |
| X       | 10    |
| L       | 50    |
| C       | 100   |
| D       | 500   |
| M       | 1000  |

Por exemplo, 2 é escrito como II no sistema romano, ou seja, dois uns adicionados juntos. 12 é escrito como XII, que é simplesmente X + II. O número 27 é escrito como XXVII, que é XX + V + II.

Os numerais romanos são geralmente escritos do maior para o menor da esquerda para a direita. No entanto, o numeral para quatro não é IIII. Em vez disso, o número quatro é escrito como IV. Como o I vem antes do V, subtrai-se o I, resultando em quatro. O mesmo princípio se aplica ao número nove, que é escrito como IX. Existem seis casos em que a subtração é usada:

- I pode ser colocado antes de V (5) e X (10) para fazer 4 e 9.
- X pode ser colocado antes de L (50) e C (100) para fazer 40 e 90.
- C pode ser colocado antes de D (500) e M (1000) para fazer 400 e 900.

Dado um numeral romano, converta-o para um número inteiro.

### Exemplo 1:

Entrada: s = "III"  
Saída: 3  
Explicação: III = 3.

### Exemplo 2:

Entrada: s = "LVIII"  
Saída: 58  
Explicação: L = 50, V = 5, III = 3.

### Exemplo 3:

Entrada: s = "MCMXCIV"  
Saída: 1994  
Explicação: M = 1000, CM = 900, XC = 90 e IV = 4.

### Restrições:

- 1 <= s.length <= 15
- s contém apenas os caracteres ('I', 'V', 'X', 'L', 'C', 'D', 'M').
- É garantido que s é um numeral romano válido no intervalo [1, 3999].


