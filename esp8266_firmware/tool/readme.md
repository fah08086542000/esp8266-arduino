1.esp8266_flasher.exe 算是精簡介面，UI裡面Bin選擇要更新的韌體，並輸入你的com port，後0x00000不做更改

2.ESP8266Flasher.exe 算是比較細的更新介面選擇你的com port，config選擇更新韌體(位址不做更改)，但Advanced裡的baudrate、Flash size、Flash speed你要確定(選對)是哪個才有辦法更新，至於SPI Mode選擇QIO

3.nodemcu_flasher32bit.exe 算是1和2的中間版，更新不用顧慮太多Config選擇對基本上就可以直接更新了

但2.3選址上還是有差別這部分就沒再多做研究了