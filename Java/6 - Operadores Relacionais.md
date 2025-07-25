Em Java, os operadores relacionais eles avaliam a relação entre duas variáveis ou expressões. Podemos dizer que eles definem se o operador á esquerda é **igual**, **diferente**, **menor** ou *igual* , **diferente**, **menor ou igual, / maior ou maior ou igual ao da direita**, é com isso **retorna um valor booleano com resultado**.
Podemos citar alguns operadores relacionais que estão disponíveis para o nosso uso cotidiano.

* `==`  Quando desejamos verificar se uma variável é IGUAL A outra. 
* `! =` Quando desejamos verificar se uma variável é DIFERENTE.
* `>` Quando desejamos verificar se uma variável é MAIOR QUE a outra.
* `>=` Quando desejamos verificar se uma variável é MAIOR OU IGUAL a outra.
* `<` Verificar se uma variável é MENOR OU IGUAL a outra.
* `<=` Verificamos se uma variável é MENOR OU IGUAL a outra.

###  Igualde (== )
Operador de igualde utilizamos quando vamos tratar de Objetos, funciona da seguinte forma ele verifica se as duas variáveis estão apontadas para o mesmo **Objeto** na **memória**.
```Java 
int numeroUm = 10;
int numeroDois = 10;

boolean SimNao = numeroUm == numeroDois;

System.out.println("O número " + numeroUm + " é igual ao " + numeroDois + "? " + simNao);

//SAIDA :
TRUE
```

