# Analogia Biológica

* Cada “célula” interagiria com outras células através do envio de mensagens para realizar um objetivo comum.
* Adicionalmente, cada célula se comportaria como uma unidade autônoma.
* De uma forma mais geral, Kay pensou em como construir um sistema de software a partir de agentes autônomos que interagissem entre si.

### Fundamentos Orientação a Objetos

* Qualquer coisa é um objeto.
* Cada objeto pertence a uma determinada classe (uma classe agrupa objetos similares).
* A classe é um repositório para comportamento associado ao objeto.
* Classes são organizadas em hierarquias.
* Objetos realizam tarefas através da requisição de serviços a outros objetos.

Em um sistema orientado à objetos os objetos devem pertencer a classes, as classes podem ou não ser organizadas em hierarquias como conhecemos na biologia.

As classes são compostas por informações tanto das características quanto do comportamento que terão os objetos daquela classe.

Características representam os atributos da classe que modelamos, por exemplo uma classe cachorro pode possuir atributos raça, cor, tipo de pêlo, etc.

Já o comportamento se refere ao o que a classe faz, um cachorro por exemplo late, anda, corre, rosna, esses são comportamentos de um cachorro.

Em software as características de uma classe são representados por atributos ou propriedades e o comportamento representado por métodos.

Como no mundo real o comportamento de uma classe pode possuir níveis de visibilidade, por exemplo um cachorro como animal possui comportamento de digerir alimentos que por sua vez é um comportamento não visível externamente e possui comportamentos visíveis como latir e correr.

Em software funciona da mesma maneira cada método possui um indicador de visibilidade que dita quais métodos são visíveis externamente e quais internamente.

Os conjunto de métodos visíveis externamente são chamados métodos públicos de uma classe e compõe sua interface pública que é visível à outras classes de objetos.

Ou seja esses métodos podem ser invocados por outras classes. Porém as classes invocadoras devem possuir conhecimento prévio dos métodos para saber quais informações eles recebem e quais informações eles retornam.

São os métodos da classe que manipulam suas propriedades, um carro por exemplo possui propriedade velocidade máxima e velocidade atual, um método com comportamento de acelerar manipula essas propriedades incrementando a velocidade atual até o limite que é a velocidade máxima.




