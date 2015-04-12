# Johnny-Five Introduction Workshop

This is a set of exercises for a 2-3 hour workshop I will be running in April 2015.  The workshop is aimed at introducing attendees to Arduino, Johnny-Five, Node.js and Javascript.

The exercises revolve mainly about using different types of sensors (input) to control different types of actuators (output).  The last exercise involves using a public MQTT broker for communication between different Johnny-Five processes.

Note that [solutions to all exercises can be found here](https://github.com/markwest1972/johnny_five_intro/tree/master/solutions).

## Exercises

#### [1. Installation and Setup](https://github.com/markwest1972/johnny_five_intro/blob/master/exercises/01_installation_and_setup.md)

In this first exercise you will install node.js, the Arduino IDE and optionally the Atom text editor.

#### [2. Simple LED Blink](https://github.com/markwest1972/johnny_five_intro/blob/master/exercises/02_simple_led_blink.md)

In this exercise you will install Johnny-Five and use it to make the built in LED (output) on the Arduino Blink on and off at a specified interval.

#### [3. Controlling an LED with a Button](https://github.com/markwest1972/johnny_five_intro/blob/master/exercises/03_led_and_button.md)

In this exercise you will use Johnny-Five to dim and brighten the LED (output) by using a Button (input). In addition you will learn about how you can use the Johnny-Five REPL.

#### [4. Controlling an LED and Servo with a Potentiometer](https://github.com/markwest1972/johnny_five_intro/blob/master/exercises/04_potentiometer_led_and_servo.md)

In this exercise you will expand your experience of  Johnny-Five by using a Potentiometer (input) to control a Servo (output) and LED (output).  You'll also learn more about the different types of Pin provided by the Arduino UNO.

#### [5. Controlling an LED and Servo with a Keyboard](https://github.com/markwest1972/johnny_five_intro/blob/master/exercises/05_keyboard_led_and_servo.md)

In this exercise you will learn how you can utilise other Node.js modules in your Johnny-Five project.  By adding adding the [keypress Node.js module](https://www.npmjs.com/package/keypress) we'll be able to control a Servo and LED using the keyboard.

#### [6. Adding MQTT to the Mix](https://github.com/markwest1972/johnny_five_intro/blob/master/exercises/06_adding_mqtt_to_the_mix.md)

[MQTT](http://mqtt.org) is quickly becoming the de-facto messaging standard for the Internet of Things, due to it's small footprint and simplicity.  In this exercise we'll add an MQTT broker to our solution, making it possible to control our LED and Servo setup from an online MQTT client.
