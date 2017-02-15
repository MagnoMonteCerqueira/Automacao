## Automacao Residencial com Raspberry pi x Shield de Automacao

### Gambiarra das coisas

![asciicast](https://github.com/MagnoMonteCerqueira/Automacao/blob/master/imgs/GAMBIARRA-DAS-COISAS.jpg)


## Introdução

A ideia deste projeto e automatizar uma residência com a shield de automação utilizando raspberry pi.

### Materiais Necessários

* Raspberry PI 3;
* Shield de Automação;
* Fonte de alimentação 12V 2A ( ou superior);

### Dependências

Para utilizarmos os reles para o acionamento em conjunto com a shield e necessario instalarmos a biblioteca para comunicação do CI MCP23017.

#### -1 Vamos seguir o passo a passo abaixo para instalação das dependencias. 
```sh
* apt-get update 
* apt-get install build-essential python-pip python-dev python-smbus git
* git clone https://github.com/adafruit/Adafruit_Python_GPIO.git
* cd Adafruit_Python_GPIO
* python setup.py install
```
