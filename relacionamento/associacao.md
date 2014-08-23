# Associação

Objetos se associam para realizar seu trabalho, elas conversam uns com os outros através de mensagens, compartilhando informações e delegando responsabilidades.

Associação é a forma mais simples de relacionamento entre objetos, a associação é caracterizada quando um objeto utiliza os serviços de outro objeto, porém não existe a noção de objeto proprietário(Owner).

![Diagrama UML](http://yuml.me/diagram/scruffy/class/[Carro]->[Local], [Carro]-[note: Carro usa Local{bg:cornsilk}])

```java
class Local {
    //propriedades e métodos
}

class Carro {
    public void dirigirAte(Local local){
        //usar local aqui
    }
}

Local local = new Local();
Carro carro = new Carro();
carro.dirigirAte(local);
```

>Note que o objeto carro não possui uma propriedade do tipo Local, portando o relacionamento entre eles é temporário. Este relacionamento existe apenas durante a execução do método **dirigirAte()**.

O carro utiliza o objeto local, mas o objeto local é criado separadamente. Podemos destruir o objeto carro e mesmo assim o objeto local continuará existindo.

>Como os objetos são criados separadamente, portanto seus ciclos de vida são independentes. Se eu destruir o carro, o objeto local continua existindo.

###Sumário

Nesse tópico aprendemos que:

* Associações são temporárias
* Os objetos possuem ciclo de vida independentes
* O relacionamento é de usa-um, dizemos que um objeto usa outro.
