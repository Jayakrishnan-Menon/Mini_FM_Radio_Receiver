<h1># Mini_FM_Radio_Receiver</h1>
A project, where we created an FM Receiver using an Arduino UNO, an LCD and a TEA5767 Module

<h2>Hardware Components Required:</h2>
<p>1. Arduino Uno or similar microcontroller board</p>
<p>2. TEA5767N FM Radio Module</p>
<p>3. Four push buttons</p>
<p>4. 16x2 LCD display with I2C capability</p>
<p>5. Breadboard and jumper wires</p>

<h2>Software Required:</h2>
<p>Arduino IDE</p>
<p>Header files: TEA5767N.h, LiquidCrystal_I2C.h</p>

<h2>Connections</h2>
<p>Connect the 5v, GND and I2C pins (SDA and SCL) of the Arduino to the VCC, GND and I2C pins of the LCD and the TEA5767 respectively</p>
<p>Connect 4 push buttons to digital pins 10, 11, 12, 13; the other pins of the push buttions must be connected with ground</p>
<p>Button connected to pin 10 is the mode button</p>
<p>Button connected to pin 11 controls the Backlight of the LCD</p>
<p>Button connected to pin 12 is the button to incrment the frequency</p>
<p>Button connected to pin 13 is the button to incrment the frequency</p>

