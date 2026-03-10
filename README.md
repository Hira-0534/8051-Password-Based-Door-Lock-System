# 🔐 Password Based Door Lock System (8051)

This project implements a **Password Based Door Lock System** using the **8051 Microcontroller**.  
The system allows access only when the correct password is entered using a keypad. It controls a motor to simulate a door lock and uses an LCD to display system messages.

---

# 📌 Features

- Secure **password authentication**
- **4x4 keypad** used for entering the password
- **16x2 LCD display** to show messages
- **DC motor** used to simulate door locking and unlocking
- **Green LED** indicates successful access
- **Red LED** indicates incorrect password
- **Manual reset using `#` key**
- **Automatic reset after a short delay**
- Password characters are hidden using `*` for security

---

# ⚙️ Components Used

- AT89C51 / 8051 Microcontroller
- 4x4 Matrix Keypad
- 16x2 LCD Display
- DC Motor
- L293D Motor Driver (for motor control)
- Green LED
- Red LED
- 10k Potentiometer (LCD contrast)
- Resistors
- Power Supply
- Proteus Simulation Software

---

# 🧠 Working Principle

1. The system displays **"ENTER PASSWORD"** on the LCD.
2. The user enters a **5-digit password** using the keypad.
3. The LCD displays `*` instead of the actual digits.
4. When `#` is pressed, the system checks the password.
# 🔑 Default Password
**12345**

### If Password is Correct
- Green LED turns ON
- LCD displays **WELCOME**
- Motor rotates to **unlock the door**
- After a delay, the motor rotates again to **lock the door automatically**

### If Password is Incorrect
- Red LED turns ON
- LCD displays **WRONG PASSWORD**
- User can press **# to reset immediately**
- If not pressed, the system **automatically resets after a few seconds**

---

# 💻 Software Used

- **Keil µVision** – for writing and compiling the 8051 code  
- **Proteus** – for circuit simulation

---
# 📂 Project Structure

Password-Door-Lock-8051/
│
├── proteus/
│   ├── doorlocking.pdsprj
│   ├── door_lock.pdsbak
│
├── hex/
│   └── project.hex
└── README.md
---

## ▶️ How to Run the Project

1. Open the **Proteus project file (.pdsprj)**.
2. Double click the **8051 microcontroller**.
3. Load the provided **HEX file**.
4. Run the simulation.
5. Enter the password using the **keypad**.
6. If the password is correct, the door unlocks.

---
## 📷 Project Simulation

<img width="933" height="642" alt="image" src="https://github.com/user-attachments/assets/093dee9d-191c-44d6-8c5c-862057bb98f4" />
<img width="945" height="475" alt="image" src="https://github.com/user-attachments/assets/9b705073-ecbd-4969-b5bb-fa45098c9a71" />
<img width="1324" height="674" alt="image" src="https://github.com/user-attachments/assets/097d4b0b-1d6f-4adc-a75c-04df90fcffac" />
---

# 🎯 Applications

- Home security systems  
- Office door access control  
- Locker security systems  
- Smart security projects

---

# 👨‍💻 Author

**Hira Shahid**

---

⭐ If you like this project, feel free to **star the repository**.

