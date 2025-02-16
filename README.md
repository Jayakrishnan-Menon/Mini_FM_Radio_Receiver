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
<p>Connect the 5v, GND and I2C pins (SDA and SCL, same as A4 and A5 pins) of the Arduino to the VCC, GND and I2C pins of the LCD and the TEA5767 respectively</p>
<p>Connect 4 push buttons to digital pins 10, 11, 12, 13; the other pins of the push buttions must be connected with ground</p>
<p>Button connected to pin 10 is the mode button</p>
<p>Button connected to pin 11 controls the Backlight of the LCD</p>
<p>Button connected to pin 12 is the button to incrment the frequency</p>
<p>Button connected to pin 13 is the button to incrment the frequency</p>
<table>
  <tr>
    <td><img width='600' src=https://github.com/user-attachments/assets/19c4215e-8380-4fb0-be09-20e7260ea08d></td>
    <td><img width='380' src=https://github.com/user-attachments/assets/86cbb11c-ca35-4cf0-bb4c-1637fe3a2f4c></td>
    <td><img width='660' src=https://github.com/user-attachments/assets/3d7713b7-4a8f-4a0f-822d-7c5659946ef6></td>
  </tr>
</table>

<h2>Working Flowchart</h2>
<img width='380' src=https://github.com/user-attachments/assets/0d24d33e-86a5-4b55-b371-1350201b94f1>

