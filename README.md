  # Arduino Assignment 2 — Beeping Countdown
This is my submission for Assignment 2 in the Programming C++ for Engineers Using Arduino course at [Ghana Communication Technology University].

What my project does
I built a simple countdown system using a 7‑segment display and a passive buzzer. The display counts down from 9 to 0, and at each step the buzzer gives a short beep. When the countdown reaches 0, the buzzer plays a longer tone to signal that the countdown is complete.

  # Hardware I used
1.Arduino Uno

2.Passive buzzer (piezo)

3.Single‑digit 7‑segment display (common cathode)

4.220 Ω resistor (on the COM pin)

5.Breadboard and jumper wires

# Concepts I demonstrated
1.Using tone() and noTone() functions

2.Difference between passive and active buzzers

3.Wiring a common cathode 7‑segment display

4.Creating a 2D array as a lookup table for digit patterns

5;Writing functions with parameters

6.Applying while and for loops

7.Printing output to the Serial Monitor

# How to run my project
Connect the buzzer to pin 8.

Wire the 7‑segment display segments (a–g) to pins 2, 3, 4, 5, 6, 7, and 9.

Connect the COM pin of the display to GND through a 220 Ω resistor.

Open the .ino file in the Arduino IDE.

Go to Tools > Board and select Arduino Uno, then choose the correct Port.

Click Upload to run the program.

Author
[Opoku Emmanuel] — [2526402738]
