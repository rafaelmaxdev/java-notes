while, do while, for

### while
Faz algo enquanto a condição é verdadeira
```java
public static void main(String[] args) {  
    int count = 0;  
    while (count < 10) {  
        System.out.println(count);  
        count++;  
    }}
```
A contagem começa em 0, mas vai adicionando um e imprimindo até o 9, até que chega em 10 e não imprime mais

### do while
```java
public static void main(String[] args) {  
    int count = 0;  
    while (count < 10) {  
        System.out.println(count);  
        count++;  
    }    do {  
        System.out.println("inside do-while");  
    }    while (count < 10);  
}
```
No while já que a condição é falsa não vai nem executar, enquanto no do while vai executar pelo menos uma vez

### for
```java

```



### while ou for
O **`while`** é ideal quando não se sabe exatamente quantas vezes o loop vai rodar, mas se tem uma condição que precisa ser verificada a cada iteração. Ele é útil em situações como leitura de dados até que uma condição seja atendida (por exemplo, ler até o usuário digitar "sair").

Já o **`for`** é mais adequado quando o número de repetições é conhecido ou facilmente determinado, como em loops que dependem de um contador (por exemplo, percorrer os elementos de um array). Ele é mais eficiente e claro quando o controle do loop envolve inicialização, condição e incremento/decremento dentro de uma estrutura compacta.