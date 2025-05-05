# Pachinko Quiz Ball Game

An Arduino-based interactive quiz game that combines a Pachinko ball drop mechanism with multiple-choice questions. Players release a ball and answer questions using buttons. Correct answers light a green LED, while incorrect answers light a red LED.

## Components Used

- **Arduino Board** (e.g., Uno)
- **Servo Motor** (for ball drop mechanism)
- **4x Buttons** (A, B, C, D for answering questions)
- **2x LEDs** (Green and Red for answer feedback)
- **Push Button** (for triggering the ball drop)
- **Miscellaneous Components** (Wires, Breadboard, etc.)

## Features

- **Pachinko Ball Drop**: Press the play button to drop the ball and select a question slot.
- **Multiple Question Difficulty Levels**: Easy, Average, and Difficult questions.
- **LED Feedback**: Green LED for correct answers, Red LED for wrong answers.
- **Question Display**: Questions and options are displayed via Serial Monitor.

## How It Works

1. Press the **Play Button** to drop the ball.
2. Enter a **Slot Number** (1-15) to select a question.
3. Answer the question by pressing one of the buttons (A, B, C, D).
4. Correct answers light the **Green LED**, while wrong answers light the **Red LED**.
5. The game continues by dropping the ball and answering more questions.

## Wiring Diagram

- **Servo Motor** connected to pin 9.
- **Buttons** connected to pins 4, 5, 6, and 7.
- **LEDs** connected to pins 2 and 3.

## How to Use

1. Clone or download the repository.
2. Connect your components to the Arduino as per the wiring diagram.
3. Upload the code to your Arduino.
4. Open the Serial Monitor to interact with the game and display questions.
5. Start the game by pressing the **Play Button**.

## License

This project is open-source and free to use. Feel free to modify and build upon it!
