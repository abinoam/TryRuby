---
lang:   PT
title:  Puts!
answer: ^[0-9\.,-]{1,}$
ok:     Putzgrilla!!!
error:  
---

Você percebeu que se você tiver digitado mais de uma fórmula você verá apenas o resultado da última.
O que está acontecendo?

Para fazer esse website mais fácil de se usar eu disse ao Ruby para copiar o resultado do seu programa para a janela de saída na parte superior. É porisso que quando você digita uma fórmula você consegue ver o resultado.
__Mas apenas o último resultado.__ E somente se a saída ainda estiver vazia.

Dessa forma quando você entrou 2 ou mais fórmulas, Ruby mostrou apenas o resultado da última fórmula.

É claro que você tem o poder de controlar a tela! Simplesmente digite __puts__ antes de cada fórmula (com um espaço entre elas). Puts significa *'ponha algo na tela'*.

Experimente isso:

    puts 4 * 10
    puts 5 - 12
    puts 30 / 4

Agora remova o puts da última fórmula e veja o que acontece.
