# NADRA Registration System

## Overview
The **NADRA Registration System** is a console-based application designed to facilitate the registration and validation of NIC (National Identity Card) information. This system ensures that users can efficiently manage their identity records through a structured and secure process.

## Features & Functionalities

### 🔑 User Authentication
- The program starts with a **welcome screen**.
- Users must enter a valid **username (nadra)** and **password (12345)**.
- If incorrect credentials are entered **three times**, the program terminates.
- Upon successful login, users proceed to the **main menu**.

### 📋 Main Menu Options
The menu provides **five key options**:

1️⃣ **Register a New NIC**
   - Users enter personal details.
   - NIC file is created for users **aged 18 or above**.
   - If the user is **below 18**, the program **terminates** with an error message.

2️⃣ **Check NIC Validity**
   - Users enter their NIC number.
   - If found, the system verifies whether the NIC is expired or still valid.
   - If the NIC is expired, a **NIC expired** message is displayed.
   - If an incorrect NIC number is entered, an error message **Record Not Found** appears.

3️⃣ **Update NIC Information**
   - Users enter their existing NIC number.
   - A new NIC file is created with updated details.

4️⃣ **Retrieve NIC Information**
   - Users enter their NIC number.
   - If the NIC exists, the stored record is displayed.
   - If an incorrect NIC number is entered, an error message **Record Not Found** appears.

5️⃣ **Exit the Program**
   - The program terminates with a **Thank You for Visiting** message.

## Technologies Used
- **Programming Language**: C++
- **Concepts Applied**: Loops, Conditions, Switch Cases, Labels, Structures, Pointers, File Handling
- **IDE**: Dev C++
