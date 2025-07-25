Em Java, String e considerada uma **classe,** usamos quando queremos armazenar **sequências de caracteres**.

```java
String nome = "Paulo Cesar";
```

Além disso temos alguns pontos importantes a ser considerados sobre a classe String.

- **Imutáveis** : Ou seja elas não podem ser alteradas depois de criadas.
- Considerada uma array de **char**
- Possui alguns **métodos poderosos** que nos ajudam na manipulação de textos.

## Métodos da classe String

|`length()`|Retorna o tamanho da string|
|---|---|
|`charAt(int)`|Retorna o caractere na posição|
|`contains("txt")`|Verifica se contem algo dentro do meu texto|
|`startsWith()`|Saber se começa com uma letra especifica|
|`endsWith()`|Verifica se termina com…|
|`equals()`|Comparar textos ou seja Strings|
|`trim()`|Remove espaços nas bordas|
|`split(" ")`|Divide a string em partes|
|`toUpperCase()`|Converte para maiúsculas|
|`toLowerCase()`|Converte para minúsculas|

### **Lembrando :**

- Sempre que quisermos comparar uma String, devemos utilizar o método **equals()**