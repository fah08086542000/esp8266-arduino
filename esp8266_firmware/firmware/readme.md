1.Ai-Thinker_ESP8266_DOUT_8Mbit_AiCloud_0.0.0.6_20170517.bin---baud rate:115200(AT 指令可以更改baud rate)

2.ai-thinker-0.9.5.2-9600.bin---baud rate:9600(AT 指令不可以更改baud rate、提供的AT指令比較少)

3.ai-thinker-v1.1.1.bin---baud rate:115200(AT 指令可以更改baud rate)

1和3內部指令差別在哪我沒多做比較

但我發現2和1差別是2--AT+CIPSEND後AT+CIPCLOSE沒辦法直接繼續連線做資料傳送，但1是可以得