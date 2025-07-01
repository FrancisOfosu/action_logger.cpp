# Action Logger 🔐

A simple C++ console application that simulates an audit logging system.  
It prompts the user for their full name, an action they performed, and the time the action occurred — then outputs a clean, structured log entry.

---

## 📌 Features

- Interactive user input using `std::getline`
- Clean and clear output log in the format:
[AUDIT LOG] 10:30 AM - Francis Ofosu performed 'updated firewall rules'

- Structured and commented C++ code (beginner-friendly)
- Demonstrates foundational skills from Chapter 1.1 and 1.2 of LearnCpp.com

---

## 🛠️ Built With

- **Language:** C++
- **Compiler:** Tested with g++ (MinGW64) and Visual Studio Code
- **Standard:** C++11 and above

---

## 🚀 How to Run

1. Clone or download the repository
2. Navigate into the folder and open the file `action_logger.cpp`
3. Compile using your preferred method. Example using g++:
 ```bash
 g++ -o action_logger action_logger.cpp
 ./action_logger

Enter your full name: Francis Ofosu  
Enter action performed: changed firewall rules  
Enter the time the action occurred (e.g. 10:30 AM): 10:30 AM  

[AUDIT LOG] 10:30 AM - Francis Ofosu performed 'changed firewall rules'

🧠 Concepts Practiced
- C++ Input/Output (std::cout, std::cin, std::getline)
- Program structure (main() function)
- Commenting and documentation
- Clean formatting and beginner-friendly syntax

📚 Learning Goals
This mini project was created as part of a learning roadmap to master C++ for cybersecurity and system programming.
It reflects the application of early concepts (statements, variables, comments) in a real-world-style use case.

## 💡 Future Upgrades

- Allow multiple entries in one session (looping)
- Save logs to a text file
- Add timestamp automatically using system time

---

## 📌 Author

**Francis Ofosu**  
📍 GitHub: [FrancisOfosu](https://github.com/FrancisOfosu)

---