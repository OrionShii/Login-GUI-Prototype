## Prototype Login GUI

### Overview
This repository contains a **prototype of a GUI-based login application** developed using **C++/CLI and Windows Forms**. The application demonstrates a **simple login mechanism** with **basic form validation** and **user feedback**. The interface includes fields for entering a username and password, and buttons for login and closing the application.

### Features
- **Username and Password Fields:** Allows users to input their login credentials.
- **Login Button:** Validates the entered credentials and provides feedback.
- **Close Button:** Closes the application.
- **User Feedback:** Displays messages to guide the user through the login process, such as error messages for empty fields or incorrect credentials.
- **Form Customization:** Uses a picture box for displaying images and a table layout for organizing buttons.
  
![Screenshot 2024-06-08 175444](https://github.com/user-attachments/assets/d190f270-cbe7-41ff-85ec-cec2d3c7ec49)
![Screenshot 2024-06-08 175517](https://github.com/user-attachments/assets/f391ca91-f1bb-49e7-8a6b-905f4264072f)
![Screenshot 2024-06-08 175536](https://github.com/user-attachments/assets/bda5e2cb-3af1-4d0f-8b94-dee6c2b8b608)
![Screenshot 2024-06-08 175545](https://github.com/user-attachments/assets/dee57062-70eb-4d56-b4f9-0f3e78d409b3)

### Prerequisites
To build and run this application, ensure that you have:
- **Visual Studio 2019 or later:** For compiling C++/CLI code.
- **.NET Framework 4.7.2 or later:** Required for Windows Forms applications.

### Project Structure
- **MainForm:** The primary form of the application which includes fields for username and password, as well as buttons for login and closing the application.
- **MenuUtama:** A secondary form that is displayed upon successful login.
- **Resources:** Includes images and other assets used by the application.

### How to Use
1. **Clone the Repository:** Download the project files to your local machine.
    ```bash
    git clone https://github.com/yourusername/LoginApplicationGUI.git
    ```
2. **Open the Project:** Launch the project in Visual Studio.
3. **Build the Project:** Compile the project using the build configuration.
4. **Run the Application:** Execute the compiled application to launch the login interface.

### Example Commands
- **Login Validation:**
  - **Username:** `OrionShii`
  - **Password:** `12345`
  - *Note:* These credentials are hardcoded for demonstration purposes. Enter the correct username and password to access the main menu.
  
- **User Feedback:**
  - The application provides real-time feedback for missing fields and incorrect credentials.

### Known Issues
- **Hardcoded Credentials:** The current prototype uses hardcoded credentials (`OrionShii` / `12345`). This should be replaced with a secure user authentication system in a production environment.
- **Form Customization:** The application uses default form controls which may need customization for better aesthetics and user experience.

### Contribution
**Contributions are welcome!** If you have suggestions or improvements, please open an issue or submit a pull request.

Note: `This feature is currently in beta and still under development.`
