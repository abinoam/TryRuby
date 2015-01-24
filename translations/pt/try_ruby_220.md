---
lang:   PT
title:  Calma, eu disse que tinha gostado de Gravity's Rainbow?
answer: ^(splendid|quite_good|mediocre|quite_not_good|abyssmal)$
load:   books = {"Gravitys Rainbow" => :splendid, "The deep end" => :abyssmal, "Living colors" => :mediocre}
ok:     Eu adorei
error:  
---

Uma coisa fantástica em Ruby é que os nomes são comumente reutilizados, o que significa menos nomes para lembrar.

Lembra como recuperamos os itens de uma array usando um índice (número):
__puts ticket[1]__.

Para uma hash isso funciona da mesma forma, exceto pelo fato de não utilizar-se um número e sim um nome para recuperar um elemento.

Sendo assim, se você estiver interessado em buscar uma de suas revisões passadas, novamente ponha o título entre colchetes. Mas deixe de fora o sinal de igual.
Bem assim:

    puts books["Gravitys Rainbow"]
