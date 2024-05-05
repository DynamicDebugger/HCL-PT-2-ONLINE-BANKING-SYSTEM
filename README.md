# HCL-PT-2-ONLINE-BANKING-SYSTEM

This project is an online banking system consisting of two main components: the backend (bankdb) and the frontend (bankdbui).

## Prerequisites

Before running the application, ensure you have the following prerequisites installed:

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Node.js and npm](https://nodejs.org/)
- [IntelliJ IDEA](https://www.jetbrains.com/idea/) or any Java IDE
- [Visual Studio Code](https://code.visualstudio.com/) or any text editor

## Installation and Setup

### 1. Clone or Download

Clone or download the project from the GitHub repository:
```bash
git clone <[repository-url](https://github.com/DynamicDebugger/HCL-PT-2-ONLINE-BANKING-SYSTEM/)>
```

2. Set Up Backend (bankdb)

   - Open the bankdb directory in IntelliJ IDEA or your preferred Java IDE.
   - Install any dependencies required by the project.
   - Start the Spring Boot application.

3. Set Up Frontend (bankdbui)

   - Navigate to the bankdbui directory.
   - Install dependencies by running:

     ```bash
     npm install
     ```

   - Create a proxy server file by running:

     ```bash
     node proxy-server.js
     ```

4. Run the Application

   - Start the backend server by running the Spring Boot application.
   - Open index.html from the bankdbui directory with a live server in your browser.

## Usage

Once the backend and frontend servers are running, you can access the online banking system by visiting the URL provided by the frontend server.

## Additional Notes

- Make sure to configure any necessary environment variables or database connections according to your setup.
- Ensure that ports used by the backend and frontend servers are not in use by other applications.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
