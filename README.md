# # Autenticação via RFID

### Atividade da matéria de Comunicação de Dados - Faculdade UNISATC (SC) <p>

### Este código realiza funções de cadastro e validação de TAGs ou Cartões por meio de um servidor hospedado localmente utilizando um módulo RFID.

#

## # Hardware Necessário

- Módulo RFID-RC522
- Cartão Mifare 13.56Mhz
- Tag Mifare 13.56Mhz
- Buzzer Ativo 5V
- Protoboard
- ESP8266 D1 R1
- LED Vermelho e Verde (ou LED RGB)
- 32 resistores de 330R
- Cabos para conexão

#

## # Ligações no ESP8266 D1 R1 (respectivamente)

- LEDs (ou LED RGB) conectados em `D2 e D4` (Verde e Vermelho)
- Módulo RFID-RC522 conectado em `D8, D5, D7, D6, D3, 3.3V e GND` (SDA, SCK, MOSI, MISO, RST, VCC e GND)
- Buzzer Ativo 5V conectado em `D9 e GND`

#

## # Inclusão de Blibiotecas e Auxiliares

- ESP8266WiFi
- ESPAsyncTCP
- ESPAsyncWebServer
- FS
- SPI
- MFRC522
- vector

#

## # Finalizando

### Após todos esses passos basta rodar o código na IDE, quando ele terminar de compilar abra o Console e desative a Auto-rolagem, em alguns segundos irá aparecer o IP alocado para uso embaixo de [CONNECTED] (caso você já ter ajustado no código o campo `char ssid[]` e `char password[]` com os dados de sua rede, do contrário irá ficar conectando infinitamente).
