Os tipos primitivos representam valores básicos. Os tipos primitivos, assim como em várias linguagens, existem para representar os tipos mais simples de dados.

Em Java, nós temos oito tipos primitivos:

- byte
- short
- int
- long
- boolean
- char
- float
- double

Os tipos numéricos podem ser divididos em Integrais e de Ponto Flutuante.

Também temos os tipos boolean que aceita **true** ou **false.**

## Quando devo usar cada tipo primitivo

|O que armazenar|Tipo ideal|Observação|
|---|---|---|

|Idade|`int`|`byte` se for criança|
|---|---|---|

|Peso/altura|`float`|`double` se for cálculos médicos|
|---|---|---|

|Salário/preço|`double`|Usar sempre para valores financeiros|
|---|---|---|

|Quantidade de produtos|`int`|A não ser que seja altíssimo (aí `long`)|
|---|---|---|

|CPF/Número grande|`long`|Número de muitos dígitos|
|---|---|---|

|Sexo (M/F)|`char`|Representa uma letra|
|---|---|---|

|Está ativo?|`boolean`|Lógico: sim ou não|
|---|---|---|