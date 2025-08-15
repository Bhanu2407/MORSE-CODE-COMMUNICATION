# Morse Code Communication using Arduino Nano

## 📜 Overview
This project demonstrates the working of **Morse Code** – a historic communication method using combinations of dots (`.`) and dashes (`-`) to represent letters, numbers, and symbols.  
We implemented a **low-cost, reliable, and scalable Morse Code decoder** using **Arduino Nano** along with hardware components like a buzzer, LEDs, and push buttons.  
The system can encode and decode Morse Code in real time, displaying results via the Serial Monitor.

---

## 🎯 Objectives
- Implement a cost-effective Morse Code decoder.
- Understand the basics of Morse communication.
- Provide a scalable system for learning and experimentation.

---

## 🛠 Hardware Components
- **Arduino Nano** (ATmega328P)
- **Buzzer**
- **LED**
- **Push Buttons**
- **330Ω Resistors**
- **Breadboard & Jumper Wires**
- **Serial Monitor (via Arduino IDE)**

---

## 💻 Software Requirements
- **Arduino IDE** (for writing and uploading code)
- **Serial Monitor** (for displaying decoded text)

---

## 🔌 Circuit Diagram
The project connects an **LED** and **Buzzer** to indicate Morse input (dots/dashes), with push buttons to input signals.

[Button 1] → Dot (.)
[Button 2] → Dash (-)
[LED] → Visual feedback
[Buzzer] → Audio feedback

yaml
Copy
Edit

---

## ⚙️ Working Principle
1. **User Input**  
   - Press **Dot button** for `.`
   - Press **Dash button** for `-`
   - Use `2` for a space between letters.
   - Use `3` for a space between words.
   - Press `1` to decode.

2. **Processing**  
   - The Arduino Nano reads button presses and builds Morse code strings.
   - The entered code is processed and converted into corresponding characters using the **International Morse Code Table**.

3. **Output**  
   - The decoded text is displayed on the **Serial Monitor**.

---

## 📊 Advantages
- **Low cost** and easy to build.
- Wireless communication possible (light/sound).
- Can be used for emergency communication.
- Useful for learning the history and basics of communication systems.

---

## ⚠️ Limitations
- Learning Morse Code requires practice.
- Slower than modern communication methods.
- Easy to intercept.

---

## 📈 Future Scope
- Implement **automatic Morse Code detection** from audio/light signals.
- Add **LCD Display** for portable decoding.
- Integrate with **IoT** for remote communication.

---

## ▶️ Getting Started
### 1️⃣ Install Arduino IDE
Download and install from: [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/morse-code-arduino.git
cd morse-code-arduino
3️⃣ Upload the Code
Connect your Arduino Nano.

Open .ino file in Arduino IDE.

Select correct Board and Port.

Click Upload.

4️⃣ Run the Project
Open Serial Monitor (9600 baud rate).

Enter Morse sequences using the defined inputs.

See the decoded message instantly.

📷 Demo
(Add circuit image & working GIF here)

👨‍💻 Author
Jatoth Bhanu Naik
B.Tech Electronics and Communication Engineering
SR University

📚 References
Arduino Project Hub

International Morse Code Chart

Applications of Buzzers

yaml
Copy
Edit

---

I can also **add your circuit diagram and working photos/GIF** into this README so it looks more professional on GitHub.  
Do you want me to **include the actual Arduino code inside the README** or keep it in a separate `.ino` file?
