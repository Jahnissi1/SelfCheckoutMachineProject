# SelfCheckoutMachineProject
---

# Java Self-Checkout Machine

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [System Workflow](#system-workflow)
- [Personal Contribution](#personal-contribution)
- [Contributors](#contributors)

## Introduction
This project is a Java implementation of a fully-functional self-checkout machine. Designed and developed by a team of 20, it allows customers to scan items, apply discounts, and complete transactions using various payment methods. The machine simulates a real-world retail checkout system and provides an intuitive interface for users to navigate through the checkout process.

## Features
- Item scanning with simulated barcode input.
- Price calculation with tax and discount application.
- Support for multiple payment methods (cash, card).
- Generation of detailed receipts after each transaction.
- User-friendly graphical interface.
- Error handling for invalid inputs and transaction failures.
- Security features to safeguard against fraud and system misuse.

## Installation
1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    ```

2. **Open the project in your IDE**:
    - Recommended IDEs: IntelliJ IDEA, Eclipse.

3. **Build the project**:
    - Ensure that you have JDK 8 or higher installed.
    - Resolve any project dependencies by building the project in your IDE.

4. **Run the main class**:
    - The entry point of the system is the `Main.java` file. Execute this file to start the self-checkout machine.

## Usage
1. **Launch the application**:
    - After building, run the main program (`Main.java`).
    
2. **Interact with the checkout system**:
    - Use the graphical interface to scan items by entering simulated barcode numbers.
    - View the real-time cart update with itemized details, taxes, and discounts applied.
    - Choose a payment method and complete the transaction.
    - Receive a printed receipt after a successful payment.

## System Workflow
1. **Scan Items**: Customers scan products by entering their barcode into the system.
2. **Price Calculation**: The system calculates the total price, including taxes and any discounts.
3. **Payment Process**: Customers select a payment method and confirm the transaction.
4. **Receipt Generation**: A receipt is generated after the transaction, summarizing the purchase.
5. **Error Handling**: The system handles common errors such as invalid barcodes, insufficient funds, or incorrect inputs.

## Personal Contribution
During the development of the **Self-Checkout Machine** project, I contributed in several key areas, including testing, core feature development, and effective team collaboration. My work ensured that the system was reliable, user-friendly, and aligned with the project’s goals.

### Key Contributions:
1. **Testing and Controllers**:
   - Developed comprehensive test cases, including:
     - **Remove Item Logic Testing** (`RemoveItemTests.java`) for handling item removal, both barcoded and PLU-coded, and testing error handling for non-active sessions.
     - **State Logic Testing** (`StateLogicTests.java`) for ensuring valid state transitions and identifying invalid state change scenarios.
     - **Banknote Dispenser Controller Testing** (`BanknoteDispenserControllerTest.java`) to verify banknote warnings and simulate adding banknotes to different dispenser units.
   - Created controllers to isolate different test cases, making it easier to manage and maintain test scenarios.

2. **Core Features Development**:
   - Contributed to the design and implementation of the **coin dispenser** system.
   - Assisted in building the logic for the **banknote dispenser** and its warning systems.
   - Worked on implementing the **receipt printing** feature, ensuring accurate and detailed receipts were generated for every transaction.
   - Helped design the functionality for adding items to the cart, including handling item prices, taxes, and discounts.
   - Contributed to the **weigh discrepancy** logic, ensuring the system detected inconsistencies between item weight and expected values.

3. **GUI and System Design**:
   - Provided input in the design of the **graphical user interface (GUI)** to ensure it was intuitive and aligned with user needs.
   - Collaborated on the **system workflow design**, offering feedback and suggestions to improve the checkout process from item scanning to payment completion.

4. **Team Collaboration**:
   - Effectively communicated and coordinated with a team of 20 developers.
   - Actively participated in discussions, providing input on architectural decisions and debugging efforts.

My diverse contributions helped ensure the project was successful in delivering a robust and user-friendly self-checkout machine.

## Contributors
- **Developers**:
    - Jahnissi Nwakanma
    - Alan Yong 
    - Andrew Matti
    - Olivia Crosby
    - Rico Manalastas
    - Shanza Raza
    - Danny Ly
    - Maheen Nizmani
    - Christopher Lo
    - Michael Svoboda
    - Sukhnaaz Sidhu
    - Ian Beler
    - Gareth Jenkins
    - Camila Hernandez
    - Zhenhui Ren
    - Ananya Jain
    - Eric George
    - Jenny Dang
    - Tanmay Mishra
    - Adrian Brisebois
    - Atique Muhammad
    - Ryan Korsrud
- **Instructor/Advisor**: [Robert James walker]

---

