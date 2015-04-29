# mi:muz

`mi:muz`はArduinoとATtinyを使ってMIDIで遊ぶプロジェクトです。
ATtinyでMIDIを扱うためのライブラリと、実験用ボードを開発しています。
全てオープンソースです。

## Software

- [VUSB-MIDI-ATtiny](https://github.com/tadfmac/mi-muz/tree/master/arduino/libraries/VUSBMidiATtiny) ATtiny45/85/44/84/841をUSB-MIDIデバイスにするためのArduinoライブラリ。

- [mi:muz設定ファイル (for Arduino IDE 1.6.3)](https://github.com/tadfmac/mi-muz/tree/master/arduino/hardware) Arduino IDEからmi:muz実験用ボードへスケッチを書き込む際に使う設定ファイル。

- Hybrid MIDI for ATtiny (Comming Soon)

## boards

- [mi:muz:prot#1]() (ATtiny45/85用V-USB-MIDI実験用ボード)
- [mi:muz:prot#2]() (ATtiny44/84/841用V-USB-MIDI実験用ボード)
- [mi:muz:prot#3]() (ATtiny45/85用V-USB-MIDI実験用ボード。I2Cマスタ用回路入り)
- [mi:muz:expr#2]() (ATtiny841用Hybrid-MIDI実験用ボード) [Comming Soon]
