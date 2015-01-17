---
lang:   PT
title:  Pare, você está enlouquecendo!
answer: ^\d{1,}$
ok:     Apenas strings podem ser invertidas
error:  
---

Você não pode inverter o número quarenta. Eu imagino que você até possa segurar seu monitor em frente ao espelho, mas inverter um número simplesmente não faz sentido.

Ruby soltou uma mensagem de erro. Ruby está te dizendo que não existe nenhum método 'reverse' para números.

Talvez se você transformar o número em uma string primeiro:

    40.to_s.reverse
