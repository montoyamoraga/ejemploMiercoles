# ejemploMiercoles

aksfakjlfjsrf

un párrafo
otro párrafo

parece que otro párrafo

* choclo
* azucar

  línea sin asterisco con dos tabs


SIN TABS

$$universidad_{udd} + mayo = casi se acaba el semestre$$

![imagen bonita de gato](https://images.squarespace-cdn.com/content/607f89e638219e13eee71b1e/1684821560422-SD5V37BAG28BURTLIXUQ/michael-sum-LEpfefQf4rU-unsplash.jpg)

subir gato en serio

![imagen bonita de gato](./imagenes/gato.jpg)

<img src="./imagenes/gato.jpg" alt="imagen bonita de gato" style="width:100px"> 


esto es con drag and drop, pero no lo hagan

![gato](https://github.com/user-attachments/assets/35e86f7b-d039-40a8-b346-53406c9cd293)


```
/*
  Blink

  Turns an LED on for one second, then off for one second, repeatedly.

  Most Arduinos have an on-board LED you can control. On the UNO, MEGA and ZERO
  it is attached to digital pin 13, on MKR1000 on pin 6. LED_BUILTIN is set to
  the correct LED pin independent of which board is used.
  If you want to know what pin the on-board LED is connected to on your Arduino
  model, check the Technical Specs of your board at:
  https://docs.arduino.cc/hardware/

  modified 8 May 2014
  by Scott Fitzgerald
  modified 2 Sep 2016
  by Arturo Guadalupi
  modified 8 Sep 2016
  by Colby Newman

  This example code is in the public domain.

  https://docs.arduino.cc/built-in-examples/basics/Blink/
*/

// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(1000);                      // wait for a second
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
  delay(1000);                      // wait for a second
}
```




