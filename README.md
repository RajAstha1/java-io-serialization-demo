# Java I/O, Serialization, and File Handling Demo

Comprehensive Java project demonstrating three essential concepts: **Autoboxing/Unboxing**, **Serialization/Deserialization**, and **File Handling**.

## 📚 Project Modules

This multi-module Maven project contains three practical demonstrations:

### Part A: Sum of Integers Using Autoboxing/Unboxing
- **Directory**: `part-a-autoboxing/`
- **Objective**: Build a Java program that utilizes autoboxing and unboxing to calculate the sum of a list of integers
- **Key Features**:
  - Autoboxing and unboxing demonstrations
  - Integer.parseInt() string parsing
  - Collection-based integer operations
- **Package**: `com.demo.autoboxing`

### Part B: Serialization and Deserialization of Student Object
- **Directory**: `part-b-serialization/`
- **Objective**: Implement Java serialization to save and retrieve a Student object from a file
- **Key Features**:
  - Student object serialization
  - File I/O operations
  - Deserialization and object recovery
  - Version control with serialVersionUID
- **Package**: `com.demo.serialization`

### Part C: Menu-Based Employee Management System Using File Handling
- **Directory**: `part-c-file-employee-management/`
- **Objective**: Develop a menu-driven Java application for adding and displaying employee records using file handling
- **Key Features**:
  - Menu-driven console interface
  - Employee record management
  - File persistence for records
  - Add/Display/Delete employee operations
- **Package**: `com.demo.employee`

## 🏗️ Project Structure

```
java-io-serialization-demo/
├── pom.xml                          (Parent POM)
├── .gitignore
├── README.md
├── part-a-autoboxing/
│   ├── pom.xml
│   ├── README.md
│   └── src/
│       ├── main/java/com/demo/autoboxing/
│       └── test/java/
├── part-b-serialization/
│   ├── pom.xml
│   ├── README.md
│   └── src/
│       ├── main/java/com/demo/serialization/
│       └── test/java/
└── part-c-file-employee-management/
    ├── pom.xml
    ├── README.md
    └── src/
        ├── main/java/com/demo/employee/
        └── test/java/
```

## 🛠️ Technologies Used

- **Java**: JDK 11 or above
- **Build Tool**: Apache Maven 3.6+
- **IDE**: IntelliJ IDEA / Eclipse / VS Code
- **Version Control**: Git & GitHub

## 📋 Prerequisites

- Java Development Kit (JDK) 11 or higher
- Apache Maven 3.6 or higher
- Git installed on your system

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/RajAstha1/java-io-serialization-demo.git
cd java-io-serialization-demo
```

### Build the Project

```bash
# Build all modules
mvn clean install

# Build a specific module
cd part-a-autoboxing
mvn clean install
```

### Run Individual Modules

```bash
# Part A: Autoboxing Demo
cd part-a-autoboxing
mvn exec:java -Dexec.mainClass="com.demo.autoboxing.SumCalculator"

# Part B: Serialization Demo
cd part-b-serialization
mvn exec:java -Dexec.mainClass="com.demo.serialization.StudentDemo"

# Part C: Employee Management System
cd part-c-file-employee-management
mvn exec:java -Dexec.mainClass="com.demo.employee.EmployeeManagementSystem"
```

## 📝 Module Details

Each module contains:
- Complete source code implementation
- Comprehensive README with setup instructions
- Maven POM configuration
- Sample input/output examples

Refer to individual module README files for detailed information.

## 📦 Dependencies

- No external dependencies required (uses Java standard library)
- JUnit 4+ for testing (optional)

## 👨‍💻 Author

RajAstha1

## 📄 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Feel free to fork, modify, and submit pull requests to improve the project.
