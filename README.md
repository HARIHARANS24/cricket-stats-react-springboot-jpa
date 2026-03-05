# 🏏 Cricket Stats Management System

A full-stack Cricket Statistics Management application built using React for the frontend and Spring Boot with MySQL for the backend. This project allows users to manage and view detailed cricket player statistics including matches, runs, wickets, averages, and more.

## 📚 Overview

This system enables users (e.g., admins or analysts) to:
- Add, update, and delete cricket players and their stats
- View all players and filter based on criteria
- Persist data using a MySQL database  
- Interact via a clean, responsive UI 

## 🚀 Features    
 
- 🧑‍💼 **Player Management**: Add, view, update, and delete cricket player profiles 
- 📊 **Stat Tracking**: Store runs, wickets, matches played, batting average, etc.
- 🔍 **Search/Filter**: Filter players by name, country, or stats
- 📂 **Backend APIs**: RESTful CRUD operations for player data
- 🌐 **Database Integration**: Persistent storage with MySQL
- 📱 **Responsive Design**: Works on mobile, tablet, and desktop

## 🛠️ Tech Stack

### Frontend
- **React.js** – UI library
- **React Router** – Page navigation
- **Axios** – API requests
- **Tailwind CSS / Material UI** – UI styling
- **React Context / Redux** – State management

### Backend
- **Spring Boot** – REST API development
- **Spring Data JPA** – ORM for database interaction
- **MySQL** – Relational database
- **Lombok** – Simplifies boilerplate code
- **Spring Security** – Authentication/authorization

## 📁 Project Structure

```
Directory structure:
└── hariharans24-cricket-stats-react-springboot-jpa/
    ├── README.md
    ├── LICENSE.txt
    ├── Backend/
    │   ├── mvnw
    │   ├── mvnw.cmd
    │   ├── pom.xml
    │   └── src/
    │       ├── main/
    │       │   ├── java/
    │       │   │   └── com/
    │       │   │       └── example/
    │       │   │           └── demo/
    │       │   │               ├── Controller/
    │       │   │               │   └── CricController.java
    │       │   │               ├── Demo/
    │       │   │               │   └── CricinfoApplication.java
    │       │   │               ├── Exception/
    │       │   │               │   └── CricinfoNotFoundException.java
    │       │   │               ├── Model/
    │       │   │               │   └── Cricinfo.java
    │       │   │               ├── Repository/
    │       │   │               │   └── CricinfoRepository.java
    │       │   │               └── Service/
    │       │   │                   └── CricService.java
    │       │   └── resources/
    │       │       └── application.properties
    │       └── test/
    │           └── java/
    │               └── com/
    │                   └── example/
    │                       └── demo/
    │                           └── CricinfoApplicationTests.java
    └── Frontend/
        ├── package.json
        ├── public/
        │   └── index.html
        └── src/
            ├── App.css
            ├── App.js
            ├── index.css
            ├── index.js
            ├── serviceWorker.js
            ├── setupTests.js
            ├── components/
            │   ├── CreateCricinfoComponent.jsx
            │   ├── FooterComponent.jsx
            │   ├── HeaderComponent.js
            │   ├── ListCricinfoComponent.jsx
            │   ├── Login.jsx
            │   ├── Register.jsx
            │   ├── UpdateCricinfoComponent.jsx
            │   └── ViewCricinfoComponent.jsx
            └── services/
                └── CricinfoService.js
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Java JDK 11 or higher
- MySQL Server
- Maven

### Frontend Setup
1. Navigate to the Frontend directory:
   ```bash
   cd Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

### Backend Setup
1. Navigate to the Backend directory:
   ```bash
   cd Backend
   ```
2. Configure MySQL database in `application.properties`
3. Run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```

## 🔧 Configuration

### Frontend Configuration
- The frontend runs on `http://localhost:3000` by default
- API endpoints are configured in `CricinfoService.js`

### Backend Configuration
- The backend runs on `http://localhost:8080` by default
- Database configuration is in `application.properties`
- JPA/Hibernate settings are configured in the same file

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## 👥 Authors

- **HARIHARANS24** - *Initial work* - [GitHub Profile](https://github.com/HARIHARANS24)

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the open-source community for the amazing tools and libraries

