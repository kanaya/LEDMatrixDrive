# LED Matrix Drive コネクタピン配置

## SV1
10ピンMILコネクタ

1-8番をLEDマトリックスのカソード側へ接続．

## SV2
10ピンMILコネクタ

1-8番をLEDマトリックスのアノード側へ接続．

## SV3
10ピンMILコネクタ

1. Vcc
2. GND
3. SPI MOSI
4. SPI SCLCK
5. XLAT（mbedのGPIOを使用）
6. BLANK（mbedのGPIOを使用）
7. GSCLCK （SPI SCLCK で代用）

## SV4
10ピンMILコネクタ．

1-8番をmbedのGPIOへ接続．