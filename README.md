📚 Quiz Application
A full-featured Quiz Application built using Java, Spring Boot, RESTful APIs, and MySQL. This app enables users to register, login, and participate in categorized quizzes such as Tech Quizzes and UPSC Quizzes. It also supports leaderboards, result tracking, and links to YouTube lectures and notes for learning reinforcement.

✨ Features
✅ User Authentication-Secure Login & Signup functionality
🧠 Quiz Categories-Technical Quizzes (Programming, CS topics, etc.), UPSC Quizzes (General Studies, Current Affairs, etc.)
📊 Performance Tracking-View marks, detailed results, and leaderboard standings
📺 Learning Resources-Click on quiz solutions or lecture links to be redirected to YouTube, Read comprehensive notes for each question/topic
🔁 RESTful APIs-Modular and scalable backend with REST endpoints

🛠️ Tech Stack
1. Backend-	Java, Spring Boot
2. Database-	MySQL
3. API Protocol-	RESTful API
4. Frontend - React

🧰 Dependencies
1. Ensure the following are installed on your system:
2. Java 17 or higher
3. Maven
4. MySQL Server
5. Postman or any API client (for testing APIs)
Required Spring Boot Dependencies
These dependencies should be included in your pom.xml:
<dependencies>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>
    <dependency>
        <groupId>mysql</groupId>
        <artifactId>mysql-connector-java</artifactId>
        <scope>runtime</scope>
    </dependency>
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-security</artifactId>
    </dependency>
</dependencies>
⚙️ Configuration
Update your application.properties file in src/main/resources with your database credentials:
spring.datasource.url=jdbc:mysql://localhost:3306/quizapp
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.security.user.name=admin
spring.security.user.password=admin

📂 Project Structure (Backend)
bash
Copy
Edit
src/
├── controller/       # REST Controllers
├── service/          # Business Logic
├── model/            # Entity Definitions
├── repository/       # JPA Repositories
└── config/           # Security & App Configuration

📌 Future Enhancements
Admin panel for quiz management
More quiz categories
User profile analytics
Mobile app support

