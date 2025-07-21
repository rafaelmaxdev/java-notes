### if - condição (se)
```java
public static void main(String[] args) {  
    int age = 15;  
    boolean isAuthorizedToPurchaseAlcoholicBeverages = age >= 18;  
    if (isAuthorizedToPurchaseAlcoholicBeverages) {  
        System.out.println("Authorized to purchase alcoholic beverages");  
    }  
    if (!isAuthorizedToPurchaseAlcoholicBeverages) {  
        System.out.println("Not authorized to purchase alcoholic beverages");  
    }
```

### else - se não
#### else if - se não se

```java
public static void main(String[] args) {  
    int age = 15;  
    String category;  
  
    if (age < 15) {  
        category = "Children's category";  
    } else if (age >= 15 && age < 18) {  
        category = "Youth category";  
    }    else {  
        category = "Adult category";  
    }  
    System.out.println(category);  
}
```

### 