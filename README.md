# Solar-Manager-ESP32
Connection:
ESP32   - 1602 LCD + I2C Converter
GND		-	 GND
VIN  	-	 VCC
D21  	-	 SDA
D22  	-	 SCL


ESP32   - HW-040 Encoder
GND		-	 GND(1pin)
VIN  	-	 5V(2pin)
D15  	-	 SW(3pin)
D5	 	-	 DT(4pin)
D4  	-	 CLK(5pin)
You can change these two pin D4 и D5 и тогда поменяется направление увеличения цифр


ESP32   - 1ch 30A Relay
GND		-	 DC-(1pin)
VIN  	-	 DC+(2pin)
D13  	-	 IN(3pin)
