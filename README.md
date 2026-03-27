# Hospital Management System 🏥

## Objective
This project is a Java-based application developed to manage and organize patient and doctor records efficiently. It provides an interactive console-based dashboard for seamless administrative interaction. The primary goal of this project is to demonstrate the practical use of core data structures, sorting algorithms, and object-oriented programming in building a real-world software application.

## Key Features
* **Patient Management:** Add to waiting queue, admit, and discharge patients.
* **Visit History:** Automatically maintains a continuous log of patient admissions and discharges.
* **Doctor Management:** Add, delete, search, and display doctors sorted by their years of experience.
* **Prescription Validation:** Uses stack-based logic to mathematically validate the brackets in medical prescription formulas.
* **Persistent Storage:** Automatically saves and appends all hospital records (patients, doctors, and history logs) to a local text file.

## Data Structures & Algorithms Implemented
* **Doubly Linked List (DLL):** Used to dynamically manage admitted patients and track the hospital's visit history.
* **Queue (Array-based):** Implements a First-In-First-Out (FIFO) system for the patient waiting room.
* **Stack (Array-based):** Implements a Last-In-First-Out (LIFO) system to validate complex prescription formulas.
* **Arrays:** Used to maintain the roster of hospital doctors.
* **Merge Sort:** Efficiently sorts the doctor array based on years of experience.
* **Quick Sort & Binary Search:** Works in tandem to quickly find a specific doctor by their ID in $O(\log n)$ time.
