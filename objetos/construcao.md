# Construção

Uma das fases do ciclo de vida de um objeto é a de construção do objeto, esse é o momento ideal para atribuirmos valores iniciais para nossos objetos funcionarem corretamente.

```java
class Car {
    //this is a construction method
    public void Car(){
        //construction code here
    }
}

Car car = new Car(); //moment to call construction method
```

A construção também é ideal para associarmos ao objeto à suas dependências caso necessário. No caso um carro não pode ser criado sem ser especificado o tipo de motor que ele irá utilizar.

```java
class Engine {
    //class code here
}

class Car {
    private Engine engine;
    //this is a construction method
    public void Car(Engine engine){
        this.engine = engine;
    }
}

Engine v8 = new Engine();
Car car = new Car(v8); //moment to call construction method
```
