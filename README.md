# # Autenticação via RFID

### Atividade da matéria de Comunicação de Dados - Faculdade UNISATC (SC) <p>

### Este código realiza funções de cadastro e validação de TAGs ou Cartões por meio de um servidor hospedado localmente utilizando um módulo RFID.

#

<p align="center">
  <img src="./images/RFID-WEB.png" alt="print do Navegador"/><br>
  Print do Navegador
</p>

## # Hardware Necessário

- Módulo Rfid Rc522
- Cartão
- Tag Mifare 13.56mhz
- Buzzer Ativo 5V
- Protoboard
- ESP8266 D1 R1
- LED Vermelho, Verde e Azul (ou LED RGB)
- 3 resistores de 330R
- Cabos para conexão

## # Ligações no ESP8266 D1 R1 (respectivamente)

- LEDs (ou LED RGB) conectados em D2 e D4 (Verde e Vermelho)
- Módulo Rfid Rc522 conectado em D8, D5, D7, D6, D3, 3.3V e GND (SDA, SCK, MOSI, MISO, RST, VCC e GND)
- Buzzer Ativo 5V conectado em A9 e GND (A0, GND)

## # Inclusão das seguintes bibliotecas

- ESP8266WiFi
- ESPAsyncTCP
- ESPAsyncWebServer
- FS
- SPI
- MFRC522
- vector

## # Preparação do Ambiente

### Para executar esse código, foi utilizado a IDE do Arduino com algumas personalizações, nas quais são:

<br>




## # Finalizando

### Após todos esses passos basta rodar o código na IDE, quando ele terminar de compilar abra o Console e desative a Auto-rolagem, em alguns segundos irá aparecer o IP alocado para uso embaixo de [CONNECTED] (caso você já ter ajustado no código o campo char ssid[] e char pass[] com os dados de sua rede, do contrário irá ficar conectando infinitamente).
