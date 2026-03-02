# OOPS Banner App

## 📖 Overview
The **OOPS Banner App** is a Java learning project that demonstrates progressive refinement of programming concepts.  
It begins with a simple console print of `"OOPS"` and evolves into rendering `"OOPS"` in a banner format using ASCII art.  
Each use case (UC1–UC8) introduces new techniques, improving modularity, readability, and maintainability while applying core Object-Oriented Programming (OOP) principles.

---

## 🚀 Git Setup Process

### Step 1: Create a GitHub Account
1. Navigate to [GitHub](https://github.com).
2. Sign up and complete registration.
3. Verify your email address.
4. Set up your profile with username and profile picture.

### Step 2: Create Repository
1. Log in to GitHub.
2. Click the **+** icon → **New repository**.
3. Repository name: `OOPSBannerApp`.
4. Description: *"OOPS Banner App - Object-Oriented Programming Learning Project"*.
5. Choose visibility: Public or Private.
6. Optionally initialize with `README.md`.
7. Click **Create repository**.

### Step 3: Local Git Configuration
```bash
git clone https://github.com/<your-username>/OOPSBannerApp.git
cd OOPSBannerApp
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"




🧩 Use Cases
UC1: Print OOPS to Console
Goal: Display "OOPS" directly in the console.

Concepts: Basic System.out.println() usage.

UC2: Render OOPS as Banner using Print Statements
Goal: Display "OOPS" in a large banner using * and spaces.

Concepts: ASCII Art, String Manipulation, Operator Overloading.

Requirements: 7-line format, 9-character width, multiple println() calls.

UC3: Modular Approach with Functions
Goal: Refactor UC2 by creating reusable functions for each character.

Drawback: Still requires multiple print statements.

UC4: Render OOPS using String Array and Loop
Goal: Store banner lines in a String[] array and print with a loop.

Benefits:

Reduced repetition.

Improved maintainability.

Enhanced scalability.

Better readability.



UC5: Render OOPS using Inline Array Initialization
Goal: Combine array declaration and initialization with String.join() calls.

Benefits: Concise code, improved readability, eliminates intermediate variables.

UC6: Render OOPS using Helper Methods
Goal: Define static helper methods (getOPattern(), getPPattern(), getSPattern()).

Benefits: Reusability, modularity, DRY principle, cleaner main logic.


UC7: Store Character Pattern in a Class
Goal: Create a CharacterPattern class to encapsulate character data and its banner pattern.

Concepts:

Inner Static Class for logical grouping.

Instance variables & constructor for initialization.

Getters for encapsulation.

Arrays of objects for managing multiple characters.

StringBuilder for efficient concatenation.

JavaDoc for documentation.

OOPS Principles: Encapsulation, Modularity, Reusability, Abstraction, Single Responsibility, Separation of Concerns.

Benefits: Centralized pattern management, extensibility for new characters, cleaner display logic.

UC8: Use Map for Character Patterns and Render via Function
Goal: Use a HashMap<Character, String[]> to store and retrieve character patterns efficiently.

Concepts:

HashMap for key-value storage.

Static methods for pattern creation and retrieval.

Nested loops for rendering.

StringBuilder for efficient concatenation.
