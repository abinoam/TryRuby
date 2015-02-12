---
lang:   PT
title:  To (be) or not to (be)
answer: 
load:   poem = "Minha torradeira voou da minha mão\nE minha torradeira se foi para a lua\nSei que lá, sei que lá\n"
ok:     
error:  
---

Mais uma coisinha sobre a qual ainda não conversamos abertamente: argumentos dos métodos.
Você lembra quando nós mudamos o poema um pouco? Nós usamos:

__poem.gsub("toast", "honeydew")__
    
O método _gsub_ requer 2 argumentos, que nós passamos para gsub incluindo duas strings entre parênteses. _Argumentos dizem ao método exatamente o que fazer._

### Parênteses
Realmente, a maior parte do tempo Ruby não se importa se você omitir os parênteses. Teria funcionado dessa forma também:

__poem.gsub "toast", "honeydew"__

Nós já usamos outro método com um parâmetro. Muitas vezes na verdade, apesar disso não ser muito óbvio:

    puts "Hello"
    puts("Hello")
    
Sim __puts__ é também um método. Usando puts com ou sem parênteses é a mesma coisa em Ruby, mas a versão sem parênteses é um pouco mais fácil de ler. E lhe economiza precioso tempo de digitação.

> Então eu imagino que a conclusão seja que você pode fazer o que
> quiser com os parênteses, desde que seu código fique legível.

### To (be) or not to (be)
Então se _to_ é um método e _be_ é um argumento, agora sabemos a resposta para essa antiga questão.
Realmente é apenas uma questão de preferência se você quer _to be_ ou _to(be)_.

Ainda está no ritmo para um pouco mais de Shakespeare? Continue lendo.
