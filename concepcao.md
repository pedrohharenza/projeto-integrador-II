
# Concepção

Neste projeto, será utilizado o conceito da domótica com objetivo de modernizar e automatizar funções básicas dentro de uma casa a partir das necessidades do usuário, mantendo o menor custo possível. Será utilizada uma maquete como referência.

Os principais objetivos de automação são:

- Controle de iluminação dos cômodos atravez do sensor de movimentação
- Sensoriamento de gás de cozinha
- Controlar um portão com acionamento eletrônico
- Efetuar o sensoriamento de temperatura e umidade com o controle das janelas
- Controle do nível de água
- Sistema de seguraça nas entradas e janelas com ativação automática

Serão utilizados os seguintes componentes para realizar esse projeto:

- *Placa MEGA 2560 R3 + Fonte + Cabo USB para Arduino:*
Será utilizado para fazer a "conversão" entre sensores e dispositivos que realizam uma ação.
- *Sensor de Umidade e Temperatura DHT11:*
Será utilizado para determinar se as persianas estarão abertas ou não.
- *Sensor de presença e movimento PIR:*
Realizará o controle das luzes quando detectado o movimento no local, sem a necessidade de ir ao interruptor para controlar as luzes.
- *Sensor de gás MQ-2 inflamável e fumaça:*
Será colocado na cozinha. Quando ativado realizará o comando para o buzzer para sinalizar o proprietário, ativará a matriz de LED e desativará o controle das luzes com o interruptor impedindo qualquer tipo de acidente.
- *Micro Servo SG92R 9g TowerPro:*
Trabalhará em conjunto com o sensor de umidade, realizando o controle das persianas.
- *Módulo Sensor de Umidade/Nível Água Chuva:*
Será utilizado para controlar o nível de água da piscina e a disponibilidade de água para regar o jardim
- *Sensor ultrasônico HC-SR04:*
Será responsável por detectar presença nas entradas como portas e janelas
- *Display LCD 16×2 I2C Backlight Azul:*
Realizará a comunicação com o usuário para o controle do sistema de seguraça


