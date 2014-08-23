# Composição

A composição é um tipo de relacionamento onde os objetos são dependentes uns dos outros.

Um carro possui um motor e se for destruído o motor também será. Seus ciclos de vida estão interligados e são dependentes.

```java
//Classe abstrata
abstract class Motor {
    //propriedades e métodos
}

//Especialização da classe Motor
class V8 extends Motor {
    //propriedades e metodos
}

class Carro {
    //O motor compôe o carro
    private Motor motor;
    public Carro(){
        this.motor = new V8();
    }
}

Carro carro = new Carro();
```

>Repare que a classe Carro possui uma propriedade privada do tipo Motor, e o Motor é criado pela classe Carro. O ciclo de vida do objeto motor inicia-se na construção do objeto carro.
