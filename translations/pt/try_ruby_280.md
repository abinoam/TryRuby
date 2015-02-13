---
lang:   PT
title:  A Megera Domada
answer: ^megera
ok:     Bom bom!
error:  
---

Você já sabe Ruby agora. Quero dizer que você já pegou o essencial.
Você só precisa continuar aprendendo mais métodos e tentar blocos mais complexos.

Mas há um lado de Ruby que não havíamos abordado. Construir seus próprios métodos.
__A-ham!__ Vamos embora com eles.

Da mesma forma que você usou os métodos de fábrica do Ruby (como puts, sort e times) você pode definir seus próprios métodos. Por que isso seria uma boa ideia? Dois motivos:

### Primeiro
Para fazer seu programa mais curto. Se você tem que fazer a mesma coisa em mais de uma parte do seu código, é fácil por esse código em um método. Seu código se reduz a uma razão de 2 vezes ou mais.

### Segundo
Métodos fazem o seu código mais legível. Imagine que seu programa precisa fazer um monte de coisas diferentes. Você __poderia__ juntar todo o código em um longo fragmento. Mas isso iria dificultar a leitura e entendimento posterior do seu código.

Ao invés disso você o corta em diferentes métodos e dá a cada método um nome fácil de ser entendido em linguagem natural. Você irá agradecer a você mesmo no futuro.

Então, como definimos um método? Assim:

    def megera( domada )
    end
