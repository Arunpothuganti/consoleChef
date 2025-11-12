🍽️ Console Chef – Java Console Application
📘 Overview

Console Chef is a Java-based console application that simulates a food ordering and chef booking system.
Built entirely using Object-Oriented Programming (OOP) principles and Java basics, this project demonstrates strong understanding of classes, objects, encapsulation, inheritance, polymorphism, and abstraction — without using arrays or advanced data structures.

The system allows users to register, log in, explore dishes by cuisine style, select their favorite chef, and confirm bookings with a unique booking ID and payment process.

🎯 Features

👤 User Registration & Login
Securely register and log in using console prompts.

🍛 Dish Selection by Cuisine Style
Choose from styles such as:

North Indian

South Indian

Chinese

👨‍🍳 Chef Selection
Each cuisine style has chefs assigned based on their specialization.

🧾 Booking Confirmation
Displays selected dish, chef, and generates a unique booking ID.

💰 Payment Process
Payment is calculated based on dish quantity.

🧂 Ingredient Updates
Allows chefs to update ingredients for each dish.

🧠 Object-Oriented Concepts Used

Encapsulation:
All data fields are kept private and accessed via getters and setters.

Inheritance:
Chef and Dish classes inherit from base classes to reuse behavior.

Polymorphism:
Chef selection and dish display use method overriding.

Abstraction:
Abstract classes/interfaces define generic behavior for dishes and chefs.

Composition:
A Chef object is linked with Dish objects, showing “has-a” relationships.

🏗️ Technologies Used
Component	Technology
Programming Language	Java
Paradigm	Object-Oriented Programming
Environment	Console (CLI)
Tools	VS Code / Eclipse / IntelliJ IDEA
🗂️ Project Structure
ConsoleChef/
│
├── src/
│   ├── Main.java
│   ├── User.java
│   ├── Dish.java
│   ├── Chef.java
│   ├── Booking.java
│   ├── Payment.java
│   ├── Ingredient.java
│   └── Cuisine.java
│
├── README.md
└── output/
    └── sample_run.txt

▶️ How to Run the Project

Open the project folder in any IDE (VS Code, Eclipse, or IntelliJ).

Compile and run Main.java.

Follow the on-screen instructions to:

Register or Login

Select Cuisine and Dish

Choose a Chef

Confirm Booking and Payment

💡 Sample Flow
Welcome to Console Chef!
1. Register
2. Login
Enter your choice: 1
Enter Username: Arun
Enter Password: *****
Registration successful!

Select Cuisine:
1. North Indian
2. South Indian
3. Chinese
Enter choice: 2

You selected South Indian Dishes:
1. Dosa
2. Idli
3. Biryani
Choose Dish: 3

Available Chefs:
1. Chef Ramesh
2. Chef Anitha
Select Chef: 1

Enter Quantity: 2
Payment Successful!
Booking Confirmed ✅
Booking ID: CC1025

🧩 Future Enhancements

Add database integration for storing users and bookings.

Introduce dish ratings and reviews.

Add order history tracking.

Include cancellation and refund features.

🧑‍💻 Author

Arun Pothuganti
B.E. in Computer Science & Engineering
📍 Hyderabad, India
💬 Passionate about Java, OOP design, and backend systems.
