# Acoplamento

O maior problema do acoplamento é que alterações em uma parte podem se alastrar por todo o software por causa do alto índica de acoplamento entre as classes.

Acoplamento diminui a reutilização, porque toda vez que precisar criar um objeto x outros objetos deverão ser criados.

**Tipos básicos de acoplamento**

* A tem um atributo do tipo B
* A usa serviços do tipo B
* A tem um método que referencia o tipo B
* A é direta ou indireta subclasse de B
* A é uma interface e B implementa essa interface
