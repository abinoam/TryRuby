---
lang:   PT
title:  Cachinhos de métodos encadeados
answer: ^More still did (.+)
load:   prev
ok:     Que show meu amigo! O método join pegou o array de linhas e os juntou em uma string.
error:  
---

Então, o que você vê? O que aconteceu lá? Você digitou __poem.lines.reverse__ e o que aconteceu?

Duas coisas aconteceram. Você transformou o poema em uma lista usando o método lines.
Lines decide a forma que a string vai ser quebrada e a converte em uma Array.

Então, você inverteu a lista. 

Você tinha cada linha, uma por uma. Você as inverteu. É só isso.

Vamos ver mais um método pra finalizar:

    puts poem.lines.reverse.join("\n")
