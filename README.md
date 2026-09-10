# Garage Manager 🚗🔧

A C# console application designed to manage a vehicle garage. This project was built to demonstrate core **Object-Oriented Programming (OOP)** principles and clean code architecture.

## 🌟 Key Features

* **Vehicle Management:** Add and track different types of vehicles (Cars, Motorcycles, Trucks).
* **Engine Variations:** Support for both Fuel and Electric engines.
* **Garage Operations:** 
  * Update vehicle repair status (In Repair, Fixed, Paid).
  * Display lists of vehicles currently in the garage (with optional filtering).
  * Inflate tires to maximum pressure safely.
  * Refuel gas-powered vehicles and recharge electric ones.

## 🛠️ Technical Highlights

This project heavily utilizes C# and OOP paradigms to ensure the code is scalable, maintainable, and robust:

* **Inheritance:** A base `Vehicle` class extended by specific vehicle types (`Car`, `Motorcycle`, `Truck`).
* **Composition:** Vehicles *contain* an `Engine` (Fuel or Electric) and a collection of `Wheel` objects, separating concerns properly rather than overusing inheritance.
* **Polymorphism:** Overridden `ToString()` methods and abstract engine behaviors allowing the garage system to interact with any vehicle type seamlessly.
* **Encapsulation:** Safe data modifications using properties and strict access modifiers.
* **Exception Handling:** Robust input validation using `out` parameters (e.g., `TryParse`) and custom exceptions for edge cases (e.g., ValueOutOfRangeException).

## 🚀 How to Run

1. Clone this repository to your local machine.
2. Open the solution (`.sln` file) in Visual Studio or JetBrains Rider.
3. Build and Run the Console Application.
4. Follow the on-screen menu prompts to interact with the garage system.
