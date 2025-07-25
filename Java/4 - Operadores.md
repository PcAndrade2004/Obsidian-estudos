## Classificação dos operadores

- **Atribuição**
    
    Em Java, representamos o operador de atribuição pelo símbolo de igualdade =
    
    Utilizamos o operador de atribuição para definirmos o valor inicial ou sobrescrever o valor de uma variável.
    
    ```java
    String nome = "Paulo";
    int idadde = 20;
    float peso = 70.5F;
    char primeiraLetra = 'P';
    boolean doaDorDeOrgao = true;
    Date dataNascimento = new Date();
    ```
    
- **Aritméticos**
    
    O operador aritmético é utilizado para realizar operações matemáticas entre valores numéricos, pode se tornar ou não expressões mais complexas.
    
    - - (adição)
    - - (subtração)
    - - (multiplicação)
    - / (divisão)
    - % (modulo) → Usamos quando queremos saber o resto da divisão.

Os operadores aritméticos utilizamos para fazer operações matemáticas, cada um com sua função específica.

## Observação :

### Errado:

Os operadores de **Divisão** e **Multiplicação** tem prioridade quando temos que fazer algum cálculo.

```java
double somaNotas = n1 + n2 + n3 / 3;
```

- Neste caso esperamos que seja feito a soma dos três números e depois seja feito a divisão. Mas neste caso como falamos que a divisão tem prioridade, o cálculo a ser realizado primeiro sera da nossa variável **n3 / 3.**
    
    ### Correto :
    
    Quando tivermos que fazer um cálculo e dentro dele precisarmos ter alguma conta de Divisão ou Multiplicação, podemos usar o **( )** e dentro dele colocamos a conta de Adição e Subtração e após isso devemos adicionar as demais contas.
    

```java
double somaNota = (n1 + n2 + n3) / 3;
```

## Operadores Unários

Em Java, os operadores unários são utilizados juntos com os operadores aritméticos. Eles realizam tarefas básicas como **incrementar, decrementar, inverter valores numéricos e booleanos**.

- ( + ) **Operadores unário de valor positivo -** números são positivos mesmo não utilizando esses operadores.
- ( - ) **Operador unário de valor negativo** - usamos quando queremos negar um número ou expressão.
- ( ++ ) **Operador unário de incremento de valor** - aumenta o valor em 1 unidade.
- ( - - ) **Operador unário de decremento de valor - diminui** o valor em 1 unidade.
- ( ! ) **Operador unário lógico de negação -** podemos negar o valor de uma expressão booleana**.**