# Stock Market Simulator

## Overview

The **Stock Market Simulator** is a Java-based application utilizing the **Abstract Window Toolkit (AWT)** to simulate the dynamic environment of a stock market. The application allows users to engage in trading various financial instruments such as Stocks, Shorts, Bonds, and Cash while managing their personal cash balance. The simulation operates day by day, with values for each instrument fluctuating based on predefined algorithms. The user’s final balance is saved to a text file upon exiting the simulation.

---

## Features

### **Core Features**

1. **Buy and Sell Financial Instruments**

   - **Stocks**: Traditional instruments with fluctuating values.
   - **Shorts**: Special stocks that generate immediate cash but require repayment upon expiration.
   - **Bonds**: Secure instruments with steady value appreciation.
   - **Cash**: Acts as the user's primary balance.

2. **Day-by-Day Simulation**

   - The simulation progresses explicitly when the user moves to the next day.
   - New values for each instrument are calculated daily based on individual algorithms.

3. **Final Balance Report**

   - On quitting the simulation, the user’s final balance is written to a text file for record-keeping.

### **Additional Features**

1. **Generate New Instruments**

   - Users can manually create new financial instruments during the simulation.

2. **Automatic Removal of Instruments**

   - Instruments with zero ownership can be removed automatically.

3. **Market Events**

   - Random events of varying significance can impact the inflation rate, influencing the value of all instruments.

4. **Trend Analysis**

   - Moving averages for each instrument are calculated to indicate pricing trends (e.g., increasing, decreasing, stable).

---

## Getting Started

### **Prerequisites**

- Java Development Kit (JDK) version 8 or later.

### **Installation**

#### Option 1: Using Command Line
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/thuvasiva/StockMarket.git
   ```
2. Navigate to the project directory.
   ```bash
   cd stock-market-simulator
   ```
3. Compile the Java files.
   ```bash
   javac *.java
   ```
4. Run the application.
   ```bash
   java GUI
   ```

#### Option 2: Using BlueJ IDE
1. Open the BlueJ IDE.
2. Navigate to **Project > Open Project**, and select the folder containing the project files.
3. Once opened, compile the project by clicking **Compile**.
4. Right-click on the `GUI` class and select **Run Main Method** to start the simulation.

---

## How to Use

### **Starting the Application**

Upon launching the application, the main window will display a menu allowing the user to:

- **View Instruments**: Check current holdings and values.
- **Buy/Sell Instruments**: Perform transactions within the cash balance limits.
- **Move to Next Day**: Progress the simulation and recalculate values.
- **Generate New Instruments**: Add custom instruments to the market.

### **Simulation Flow**

1. Begin trading by purchasing or selling financial instruments.
2. Observe changes in instrument values as you progress day by day.
3. Utilize moving averages and trend indicators to make informed decisions.
4. Exit the simulation to generate a final balance report.

---

## Screenshot

Below is a sample screenshot of the application when first started:

![Screenshot of Stock Market Simulator](https://github.com/user-attachments/assets/d99f9fb3-7bd9-474a-8bab-ee1841694519)

- **Main Features Visible**:
  - Main dashboard currently displaying instructions on how to proceed.
  - List of available financial instruments and their company names.
  - Buttons to Buy, Sell, Generate Instruments, or Move to the Next Day.

---

## Algorithms for Instrument Value Fluctuations

- **Stocks**: Fluctuate based on random market trends and events.
- **Shorts**: Provide immediate cash but require repayment with interest.
- **Bonds**: Increase steadily, offering a safe investment option.
- **Cash**: Tracks the user’s liquidity and limits transactions.

---

## Future Enhancements

- Addition of more complex financial instruments like ETFs or Mutual Funds.
- Improved graphical user interface (GUI) using modern libraries.
- Integration with real-world financial data for more realistic scenarios.



