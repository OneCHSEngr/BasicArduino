# BasicArduino

## Hello World

Goal was to make an LED blink on and off.

### Wiring diagram

<img src="Images\HelloArduino.png" width = "300">

### My Code

[Link to Create](https://create.arduino.cc/editor/OneCHSEngr/278b79a8-ddf5-4306-bdc7-293704e709f9/preview)

```C++
/*
  Hello Arduino

  Mr. Dierolf - 11/13/2020

  This is my first Arduino sketch.
  It writes to the serial monitor and
  makes an LED blink.
*/

void setup() {
  Serial.begin(9600);
  pinMode(7, OUTPUT);
}

void loop() {
  Serial.println("Blink");
  digitalWrite(7, HIGH);
  Serial.println("On");
  delay(500);
  digitalWrite(7, LOW);
  Serial.println("Off");
  delay(500);
}

```

### Reflection

Pretty straightforward but very cool.  I learned about the Arduino Create Web Editor and writing to the serial monitor.  My program makes an LED blink.  If you lower the number in the delay funtion it blinks faster.
