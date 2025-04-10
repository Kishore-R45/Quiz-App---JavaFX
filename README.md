Quiz App using JavaFX and JDBC is a dynamic, GUI-based quiz application built with JavaFX for the frontend and JDBC for backend database connectivity. This project allows users to take a 10-question general knowledge quiz, tracks their performance in real-time, and displays results with a sleek, animated result page.

The application features custom-designed JavaFX UI components — modern buttons, styled labels, and animated progress indicators — giving it a polished and professional feel. It includes user interaction handling, score tracking, and a personalized result message based on performance.

On the backend, the app leverages JDBC (Java Database Connectivity) to manage and store user-related data such as quiz scores, login/logout actions, or even user registration if extended. This makes the project highly scalable and ready for integration with real-world systems like learning platforms or classroom assessments.

A logout button resets the session and returns the user to the login/signup screen, making it ideal for multi-user workflows. The codebase follows clean architecture principles with well-structured controllers and FXML separation.

Whether you’re learning JavaFX UI development or implementing JDBC in a desktop application, this project provides a solid foundation for building interactive, database-driven apps.

# Quiz App - JavaFX

A simple and interactive **Quiz Application built with JavaFX**. This desktop app allows users to test their general knowledge through multiple-choice questions with a clean UI and scoring system.

### 💻 Features
- JavaFX-powered GUI
- Multiple-choice quiz with scoring
- Result screen at the end
- JDBC setup for database connectivity (future expansion)
- Lightweight and beginner-friendly

---

## 🛠️ Tech Stack

- Java 17+
- JavaFX
- JDBC (optional / future)
- Scene Builder (for designing FXML)
- IntelliJ IDEA / VS Code (recommended IDEs)
- Git + GitHub

---

## 🚀 How to Run (For Beginners)

## 1. Clone the Repository
```bash
git clone https://github.com/Kishore-R45/Quiz-App---JavaFX.git
cd Quiz-App---JavaFX
```
## 2. Open Project in IDE
Open the folder in IntelliJ IDEA or VS Code with JavaFX plugins.

## 3. Set Up JavaFX
Download JavaFX SDK from: https://gluonhq.com/products/javafx/

Configure your IDE to include JavaFX lib in the module path.

# Add VM arguments:

css
Copy
Edit
--module-path /path/to/javafx-sdk-17/lib --add-modules javafx.controls,javafx.fxml

## 4. Run the App
Run Main.java. The quiz window will launch with the first question.
