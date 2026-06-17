# 8-Bit Arithmetic Logic Unit (ALU) Simulation

An 8-bit Arithmetic Logic Unit (ALU) designed and simulated in **Proteus**. This project mimics the core functionality of a modern processor's ALU, executing 11 distinct arithmetic and logic operations. It serves as a practical implementation of fundamental digital electronics and computer architecture concepts.

---

## 📸 Hardware Implementation Preview

*(Drop your hardware image right below this line)*
<img width="537" height="637" alt="image" src="https://github.com/user-attachments/assets/7a34c4b6-8858-485f-8600-77bc050cfc08" />


---

## 🚀 Key Features

* **Complete 8-Bit Processing:** Handles 8-bit binary inputs to simulate realistic processor data paths.
* **Interactive Control Inputs:** Dedicated control switches/lines to dynamically select between 11 operations.
* **Visual LED Output:** Real-time binary outputs displayed using an array of digital LEDs.
* **Modular Logic Design:** Built entirely using fundamental digital components, including Full Adders, Multiplexers (MUX), Logic Gates, and Comparators.

---

## 🧠 Supported Operations

The ALU features a versatile instruction set divided into arithmetic, logic, and control operations:

| Category | Operation | Description |
| :--- | :--- | :--- |
| **Arithmetic** | Addition | Adds two 8-bit binary numbers |
| | Subtraction | Subtracts one 8-bit number from another |
| | Increment | Adds 1 to the current input value |
| | Decrement | Subtracts 1 from the current input value |
| **Logic** | Bitwise AND | Standard bitwise conjunction |
| | Bitwise OR | Standard bitwise disjunction |
| | Bitwise XOR | Standard bitwise exclusive OR |
| | 1’s Complement | Inverts all bits of the input |
| | 2’s Complement | Inverts all bits and adds 1 (negation) |
| **Control / Utilities** | Comparator | Outputs true/false for Equal ($A=B$), Greater Than ($A>B$), and Less Than ($A<B$) |
| | Load & Counter | Loads a value or acts as a step counter |

---

## 📁 Repository Structure

* `ALU.pdsprj`: Core Proteus project file (Schematic & Simulation)
* `README.md`: Project documentation

---

## 🛠️ How to Run the Simulation

1. Make sure you have **Proteus Design Suite** installed.
2. Download or clone this repository.
3. Open the `ALU.pdsprj` file directly in Proteus.
4. Click the **Play (Run)** button at the bottom left corner to start the simulation and test the inputs.

---

## 🎓 Learning Outcomes

Developing this project provided a deep hands-on understanding of:
* Propagation delays, carry look-ahead concepts, and signal routing in digital circuits.
* Cascading smaller integrated circuits (like 4-bit adders/multiplexers) to build scalable 8-bit systems.
* Debugging complex logic networks in a simulated CAD environment.
