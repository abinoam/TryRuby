---
lang:   PT
title:  Mais pequenas revisões de livros
answer: [3-9]
load:   books = {"Gravitys Rainbow" => :splendid}
ok:     Veja, o método 'length' funciona com strings, arrays e hashes.
error:
---

Continue, preencha as revisões. E, se você quiser ver a lista inteira, digite: __puts books__

Repetindo, as avaliações são: :splendid, :quite\_good, :mediocre, :quite\_not\_good e :abyssmal.

Essas avaliações não são strings. Quando você coloca um sinal de dois pontos antes de uma palavra simples, você tem um __símbolo__ (Symbol).

Símbolos são versões mais baratas das strings (em termos de memória do computador). Se você usa uma palavra mais de uma vez no seu programa, use um símbolo. Ao invés de ter milhares de cópias dessa palavra na memória, o computador armazenará o símbolo apenas __uma vez__. 

E mais importante, um símbolo alerta que não se trata apenas de uma velha palavra mas sim uma que tem algum significado no contexto do seu programa.

Adicione mais 2 revisões de livros, use use __books.length__ para ver quantas revisões existem em uma hash:

    books["The deep end"]  = :abyssmal
    books["Living colors"] = :mediocre
    
    puts books
    
    puts books.length
