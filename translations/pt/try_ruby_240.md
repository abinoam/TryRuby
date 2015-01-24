---
lang:   PT
title:  Você é rigoroso?
answer: "mediocre"
load:   books = {"Gravitys Rainbow" => :splendid, "The deep end" => :abyssmal, "Living colors" => :mediocre, "Bumblebees" => :mediocre}
ok:     Ótimo, caramba! Você fez um quadro de resultados das suas avaliações
error:  
---

Então você está dando revisões severas e injustas? Vamos controlar as notas com uma nova Hash __ratings__:

Isso, ok, agora deixe-me contabilizar suas revisões. Apenas me acompanhe. Digite:

    ratings = Hash.new {0}
    
    books.values.each { |rate|
      ratings[rate] += 1
    }
    
    puts ratings

O character linha vertical chama-se "pipe", na maioria dos teclados está localizado logo acima do da tecla Enter no seu teclado.

Não se preocupe se você não conseguir entender tudo o que está acontecendo aqui. Será explicitado mais a frente.
