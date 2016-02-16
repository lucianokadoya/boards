# Meccano Boards
Meccano is a development kit based on ESP8266, integates GPIO, PWM, IIC, 1-Wire and ADC all in one board.
Different from other ESP8266 projects, Meccano board has been heavily tested in retail stores and adjusted to be safe against RF (radio frequency) interferences. The physical store is an inhospitable environment since there are several hundreds of electronic products, such as TVs, computers, sound and home theaters as well as electronic home appliances.

## Features
 - Arduino Like Hardware
 - NodeMCU
 - Low cost WiFi
 - Heavily tested
 - Open Source



 ## Meccano Hardware Platform

 ### What is the history behind Meccano Board?

 Meccano Board project started early 2014 for Magazine Luiza, leaded by Rogerio Biondi, Luciano Kadoya and Diego Osse for a Large Retailer of São Paulo/Brazil. The initial goal was collecting information about the number of the visitors in each physical store in order to calculate several productivity ratios such as the number of sales by visitors and total amount of sales by visitors. The development started using commodity hardware available on the market and the Arduino Platform was the first board choosen for development. After some rounds of development, due to the nature of the application, the Ethernet connection was discarded due to several facility issues. After that several Wi-Fi solutions were tried by the development team and none of them considered satisfatory or reliable.


 <img src="./Development%20History/Meccano%20Board%20Development%203.jpg" width=500>

 <img src="./Development%20History/Meccano%20Board%20Development%201.jpg" width=300>


 During that time the ESP8266 was presented to the market as a really cheap solution and group started a spin-off project based on that microprocessor, the ESP-01 board. But dev team quickly realized that despite the low cost and good number of features, ESP8266 was not an out-of-the-box solution without a reliable development board. It has been tried but failed due to the high intensive RF (Radio Frequency) issues in the physical store, where there are several TVs, computers, mobile phones, sound systems and other appliances sharing the same power line/system. The team has pivoted from Arduino to ESP8266 and a quick prototype has been created (Take a look at Development History), a little larger than a R$ 1,00 coin. When tested in the field, it rocked and a new board called Meccano Mini has born.

 <img src="./Development%20History/Meccano%20Mini%20Prototype%204.jpg" width=300>

 <img src="./Development%20History/Meccano%20Mini%20Prototype%201.jpg" width=500>

 <img src="./Development%20History/Meccano%20Mini%20Prototype%203.jpg" width=500>

 <img src="./Development%20History/Meccano%20Mini%20PCB.jpg" width=500>



 ### Why should I use Meccano Mini Board?

 This is just a question of preference. Meccano Board is optimized for running retail IoT applications and has already been built for low cost and high scale production. Due to cost reduction, it has a simple design, uses a 5V switched font, just one tension regulator and needs a simple FTDI board for programming. Since this doesn't have many SMD components, it may also be assembled at home.


 ### How do I assemble and test my Meccano Board?

 Just download the meccano-iot/boards content and produce your own PCB (printed circuit board). One of the recommended services is OSH Park, where you may produce your PCB with high quality and low cost. Take a look at http://www.oshpark.com for more details, submit the eagle/PCB file there and produce your board. After that, you must buy the components. They are specified in detail in the components.txt file. After you have assembled it, download the client for that board (meccano-iot/arduino-esp-library), install the software (Arduino IDE, Arduino-ESP board libraries and meccano library) and deploy the sample script for testing.

 <img src="./Development%20History/Meccano%20Mini%20Final%20-%20v%201.0.jpg" width=500>
 

## Versions
[Meccano Micro](/meccano_micro.MD)
