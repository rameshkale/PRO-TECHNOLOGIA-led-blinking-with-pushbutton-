# PRO-TECHNOLOGIA-led-blinking-with-pushbutton-
beginner freindly arduino project (microcontroller)

# Project Overview

This is a beginner Arduino project where an LED blinks only when a push button is pressed.
When the button is released, the LED turns OFF.

This project helps beginners understand input (button) and output (LED) using simple Arduino code.

 Online Simulation (No Hardware Needed)

This project can be tried safely using Tinkercad.

🔗 Tinkercad Simulation:
https://www.tinkercad.com/things/eY68NaMjFsu-push-button

Beginners and children can test the project online before using real components.

# 🎯 What You Will Learn

How a push button works as an input

How to control an LED as an output

Using pinMode(), digitalRead(), and digitalWrite()

Basic if–else logic

Simple interaction between hardware and software


# 🧰 Components Used

Arduino Uno

LED

220Ω resistor

Push button



# 🪜 Step-by-Step Explanation (Simple)
Step 1: Set Pin Modes

LED pin is set as OUTPUT

Button pin is set as INPUT

Step 2: Read Button State

Arduino checks if the button is pressed using digitalRead()

{Step 3: Control the LED

If button is pressed → LED blinks

If button is not pressed → LED stays OFF}

# 💻 Arduino Code

int s=6;
int x;
int led=7;

void setup() 
{

  Serial.begin(9600);
  pinMode(6,INPUT);
  pinMode(7,OUTPUT);

}

void loop() {
  x=digitalRead(s);
  Serial.println(x);
  
if(x==0)
{
  digitalWrite(7,LOW);
}

else
{ 
  digitalWrite(7,HIGH);
}

}

# 👨‍👩‍👧‍👦 Parent-Friendly Note
For beginners and children, it is recommended to start by practicing Arduino projects using online simulations before buying or using physical components.

Online simulators like Tinkercad allow children to:

Learn coding concepts safely

Understand how circuits work without any risk

Make mistakes and fix them without damaging components

Build confidence before working with real hardware

Once the child is comfortable with the code and understands how the circuit behaves, parents can then consider purchasing basic Arduino components for hands-on practice.


## 🙌 Feedback
# Suggestions and feedback to improve this beginner project are welcome 🙂
# If there is interest, I can create a complete beginner guide covering the basics of microcontrollers and simple coding, especially designed for younger kids.
