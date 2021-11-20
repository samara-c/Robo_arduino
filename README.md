# Robo_arduino

O projeto apresentado é uma garra robótica desenvolvida com a plataforma de prototipagem Arduíno Uno. A garra é controlada por dois joysticks direcionais, ligados diretamente à 4 servo motores. Ao movimentar os joysticks, os servo motores correspondentes se movem de acordo, e o corpo do robô muda de posição. Para abrir e fechar a garra, é necessário apertar o botão do joystick (eixo Z).

O funcionamento do robô acontece de acordo com o fluxo a seguir:

![alt text](https://github.com/samara-c/Robo_arduino/blob/main/fluxo.png)

Ao ser acionado, o robô responde aos comandos do computador (através do protocolo MQTT) ou dos sensores analógicos. Apesar de ser capaz de pegar pequenos objetos, a arquitetura do robô desenvolvida em sala ainda não permite que ele segure por muito tempo, sendo necessárias melhorias na estrutura física da garra. A seguir, temos uma foto da entrega final do robô:

![alt text](https://github.com/samara-c/Robo_arduino/blob/main/Imagem_2.jpeg)
