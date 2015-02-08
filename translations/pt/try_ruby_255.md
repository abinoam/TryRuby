---
lang:   PT
title:  Deu tempo?
answer: ^[0-9]$
ok:     Chegou bem a tempo!
error:  Execute o bloco de 0 a 9 vezes
---

Como vimos em nosso primeiro exemplo com um bloco (quando contabilizamos as avaliações) podemos passar um valor a um bloco. Que valores são __passados__ é determinado pelo método que está rodando o bloco.

Os valores que são __recebidos__ pelo bloco são colocados na variável nomeada no começo do bloco, entre duas barras verticais: Ex: |nome\_da\_variável|

Vamos tentar com esse bloco:

    5.times { |time|
      puts time
    }

Aqui, o método __.times__ envia um valor para a variável __|time|__. Mas note que a variável time é conhecida apenas dentro do bloco. 


> Você notou que você pode quebrar o código em linhas múltiplas? Isso facilita a leitura.
