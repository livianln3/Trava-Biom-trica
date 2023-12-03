# Trava-Biom-trica
Projeto de IOT feito com arduino UNO. O Projeto "Trava Biométrica" foi idealizado para trazer segurança 
e acessibilidade para o usuário através do destrancamento de uma trava utiizando somente impressões digitais.

Materiais utilizados:
Sensor biométrico com quatro conexões, fios macho-macho, macho-fêmea e fêmea-fêmea, um resistor de 5.6KOs, 3.3KOs, 
uma trava solenoide, um botão, um relê, fonte de 12 Volts e Placa Arduino UNO.

![WhatsApp Image 2023-12-03 at 15 24 57](https://github.com/livianln3/Trava-Biom-trica/assets/142273050/7f940cf8-52c5-4007-a8b1-a361aeb5540c)

Quando o sensor é identificado no arduino, a mensagem "Sensor Biométrico encontrado!" É exibida no Monitor Serial. 
![WhatsApp Image 2023-12-03 at 15 24 57 (1)](https://github.com/livianln3/Trava-Biom-trica/assets/142273050/cbcb2d04-8307-4490-aba6-aa4a9eb307f5)

Ao apertar o botão, o circuito inicia o modo adminstrador, que permite que novas impressores digitais sejam adicionadas. Quando uma impressão gravada anteriormente é identificada pela placa, a mensagem "As impressões batem" é exibida no monitor e mostra também o nível de segurança. Em seguida, o relê é acionada e a trava abre.
![WhatsApp Image 2023-12-03 at 15 24 57 (2)](https://github.com/livianln3/Trava-Biom-trica/assets/142273050/b9e97cb8-cf3e-4341-a2bd-36b2e34c00d1)
