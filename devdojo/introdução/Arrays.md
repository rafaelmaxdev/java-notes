> É um **objeto na memória heap**, e a variável que o representa é uma **referência a esse objeto**
- As posições (índices) começam em **0**
- Se nenhum valor for atribuído, o **valor padrão** será usado (ex: `0` para `int`, `\u0000` para char, `null` para objetos, [[String]], reference, `false` para `boolean`)
- Se tentar acessar uma posição fora do limite, será lançado um erro **`ArrayIndexOutOfBoundsException`**
### Sintaxe
Essa variável é do tipo **reference** e faz referência a um objeto em memória
```java
int [] ages // declaração da variável (ainda sem alocação)
```

new instancia um novo objeto, nesse caso do tipo int e com três espaços na memória
```java
new int [3]
```

tipo [] nome = new tipo \["espaço em memória alocado"\]
```java
int [] ages = new int [3]
```

#### Na prática
```java
    int [] ages = new int [3];  
	ages[0] = 21;  
	ages[1] = 15;  
	ages[2] = 11;  
	System.out.println(ages[0]); // 21
	System.out.println(ages[1]); // 15
	System.out.println(ages[2]); // 11 
	System.out.println(ages[3]); // 0 (valor padrão)
```