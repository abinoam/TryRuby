---
lang:   PT
title:  Elementar
answer: ^(12|35|47)$
load:   ticket = [12, 47, 35]
ok:     Ok
error:  Quase
---

Então guardamos nossos números de loteria dentro de uma variável chamada ticket. Como fazer para tirá-los de lá novamente?

Nós já vimos que nós podemos saber qual é o maior número com __max__. Da mesma forma você pode acessar o primeiro (__first__) ou o último (__last__) elemento da lista.
Mas e se você quisesse acessar um elemento específico?

### [ ]
Ruby usa os colchetes [ ] para acessar um elemento.
Os colchetes são muito comuns em Ruby.
Eles são como miras usadas para focar em um alvo. Exatamente.
Esses colchetes significam, "Eu estou procurando por ____" Pronto, atirar.

Vamos pegar todos os números de loteria:

    puts ticket[0]
    puts ticket[1]
    puts ticket[2]

Por que usamos [0], [1], [2] ?

E não [1], [2] e [3]? Seria algum tipo de coisa Zen do Japão?
Não, nós da computação simplesmente gostamos de contar a partir do zero. Não é uma coisa específica de Ruby, essa _indexação baseada em zero_ é usada na maioria das linguagens de programação.

> Um pequeno lembrete: você pode usar o botão __Copy__ para copiar o código exemplo no editor.

