# Rubber Ducky #



## Links diversos ##


[DigistumpArduino](https://github.com/digistump/DigistumpArduino/releases)

## Configurando seu [ATTINY85](http://www.ebay.com/itm/221889695650?_trksid=p2057872.m2749.l2649&ssPageName=STRK%3AMEBIDX%3AIT) ##

[Instruções](http://digistump.com/wiki/digispark/tutorials/connecting)

[Instruções (Youtube)](https://www.youtube.com/watch?v=fGmGBa-4cYQ)

1. Baixar e instalar a [Arduino IDE](https://www.arduino.cc/en/main/software) 
1. Baixar e instalar o [Driver do Digistump](https://github.com/digistump/DigistumpArduino/releases/download/1.6.7/Digistump.Drivers.zip)
1. Abrir Arduino IDE. Em preferências, definir *URLs Adicionais para Gerenciadores de Placas* para: http://digistump.com/package_digistump_index.json
1. Em Ferramentas -> Placa (...) -> Gerenciador de Placas: Selecione a opção contribuido e instale Digistump AVR Boards
1. Selecione a placa específica em Ferramentas -> Placa (...) -> Digispark (Default - 16.5mhz)
1. Abra um sketch para teste em Arquivo -> Exemplos -> Digispark Keyboard -> Keyboard
1. Clique em carregar e espere a mensagem para inserir o dispositivo.
1. (re)Insira o ATTINY85 na USB, agora ele deve ser reconhecido, e o sketch será instalado nele. Se tudo der certo, ele deve começar a digitar Hello Digispark! a cada 5 segundos.
1. ???
1. Profit