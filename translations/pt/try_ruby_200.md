---
lang:   PT
title:  Um livrinho em branco
answer: ^(splendid|quite_good|mediocre|quite_not_good|abyssmal)$
load:   books = {}
ok:     Sim é uma nova revisão
error:  Use splendid, quite_good, mediocre, quite_not_good, abyssmal. Não esqueça a vírgula
---

Você fez uma __hash__ vazia. Uma hash é como uma array, com a diferença de que cada elemento dela tem um nome.

Vamos guardar algumas revisões de livros em miniatura em nossa nova hash. Aqui está nosso sistema de qualificações:

- :splendid &rarr; uma obra prima
- :quite\_good &rarr; gostei, certeza que gostei
- :mediocre &rarr; bom e ruim ao mesmo tempo
- :quite\_not\_good &rarr; bem ruim
- :abyssmal &rarr; desgraça total

Para classificar um livro, ponha o título entre colchetes e ponha a classificação após o igual. Por exemplo:

    books["Gravitys Rainbow"] = :splendid

> Acho por bem informar que todas as lições em TryRuby são separadas umas das outras.
> Então se você enlouquecer digitando revisões de livros aqui, você só pode usá-las nessa lição.
> Se você quiser usar suas revisões em uma lição seguinte você deveria copiá-la e colá-la.
> Não se preocupe muito com isso agora, cada lição tem um bocado de coisas predefinidas para você brincar.
