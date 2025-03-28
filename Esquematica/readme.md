## Funcionamento da esquematica ##

Este é um circuito de fonte de alimentação regulada de 5V. 
Ele converte tensão alternada (AC) da rede elétrica em uma tensão contínua (DC) de 5V, que pode ser utilizada para alimentar circuitos eletrônicos sensíveis. 
O circuito inclui um transformador, uma ponte retificadora, capacitores de filtragem e um regulador de tensão 7805. No final, um LED é alimentado como indicação de funcionamento.
<img src="./Esquematica.jpg">
### Fonte de tensão AC###
Representa a rede elétrica ou uma fonte de tensão alternada que será convertida para corrente contínua.

### Transformador ###
Reduz a tensão da rede elétrica para um nível adequado para o circuito (por exemplo, de 220V para 12V AC).
Também isola eletricamente o circuito da rede, aumentando a segurança.

### Ponte Retificadora ###
Converte a corrente alternada (AC) do transformador em corrente contínua pulsante (DC).
É composta por quatro diodos dispostos em configuração de ponte para garantir que a saída tenha sempre polaridade correta.

### Capacitor de filtragem ###
Suaviza a tensão retificada, reduzindo a ondulação (ripple).
Ajuda a melhorar a estabilidade da tensão DC antes da regulação.

### Regulador de tensão ###
Um regulador linear que ajusta a tensão de entrada (geralmente 12V DC) para uma saída estável de 5V DC.
Tem três terminais: VI (entrada), GND (terra) e VO (saída).
Evita flutuações de tensão e protege os circuitos alimentados.

### Capacitores de desacoplamento ###
Melhoram a estabilidade do regulador de tensão.
Ajudam a eliminar ruídos e interferências de alta frequência.
O capacitor C2 é colocado na entrada do 7805, e C3 na saída.

### Resistor limitador de corrente ###
Controla a corrente que passa pelo LED para evitar que ele queime.
Define a intensidade do brilho do LED.

### LED indicador ###
Indica que a fonte está funcionando corretamente.
Se estiver aceso, significa que há tensão de 5V na saída.


### Funcionamento completo ###

A tensão alternada passa pelo transformador, que reduz sua amplitude.
A ponte retificadora converte a tensão AC em DC pulsante.
O capacitor C1 reduz a ondulação da tensão.
O regulador 7805 estabiliza a tensão em 5V DC.
Os capacitores C2 e C3 melhoram a filtragem da saída.
O resistor R1 limita a corrente para o LED D1, que indica se a fonte está funcionando.
