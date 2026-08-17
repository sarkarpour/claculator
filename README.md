# 🧮 Claculator

> A multi-purpose desktop calculator built with **C# and Windows Forms**.

**Claculator** is a feature-rich calculator application designed to go beyond basic arithmetic.
It combines standard calculations with programmer utilities, unit conversion, currency conversion, calculation history, and a customizable interface — all inside a simple desktop application.

## ✨ Features

### 🧮 Standard Calculator

* Addition, subtraction, multiplication, and division
* Percentage and remainder operations
* Power and factorial calculations
* Negative numbers
* Calculation history
* Backspace and reset controls

### 💻 Programmer Mode

Convert numbers between:

* Decimal
* Binary
* Octal
* Hexadecimal

Bitwise **AND** operations are also supported.

### ⚖️ Unit Converter

Convert between common units of:

* Weight — kg, g, mg, ton
* Length — km, m, cm, mm

### 💱 Currency Converter

Supports conversion between:

* USD
* EUR
* IRR

### 🎨 User Interface

* Windows desktop interface
* Dark / Light appearance
* Multiple calculator modes
* Keyboard input support for numeric calculations

## 🛠️ Built With

* **C#**
* **.NET**
* **Windows Forms**
* **Newtonsoft.Json**

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/sarkarpour/claculator.git
cd claculator
```

Open the solution file in **Visual Studio**:

```text
claculator.sln
```

Build and run the project.

The application starts with the standard calculator and provides access to the additional modes through the interface.

## 📂 Project Structure

```text
claculator/
├── Form1.cs          # Standard calculator
├── Form2.cs          # Programmer calculator
├── Form3.cs          # Weight converter
├── Form4.cs          # Length converter
├── Form5.cs          # Currency converter
├── Program.cs        # Application entry point
└── Resources/        # Application resources
```

## 📌 Project Status

Claculator is a learning-focused desktop project built to explore **C#, Windows Forms, event-driven programming, calculations, and UI design**.

The project can be extended with additional mathematical functions, more unit types, improved currency data, and a more modular architecture.

---

⭐ **Built with C# — one calculation at a time.**
