# Grocery Management System

A modern web application for managing grocery inventory and sales built with Spring Boot and Thymeleaf.

## Features

- Add, edit, and delete grocery items
- Record sales transactions
- Track inventory levels
- View total sales
- Search functionality
- Modern and responsive UI
- Real-time updates

## Technologies Used

- Spring Boot
- Thymeleaf
- Bootstrap 5
- Font Awesome
- Maven

## Prerequisites

- Java 17 or higher
- Maven
- Git

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/grocery-management.git
```

2. Navigate to the project directory:
```bash
cd grocery-management
```

3. Build the project:
```bash
mvn clean install
```

4. Run the application:
```bash
mvn spring-boot:run
```

5. Access the application at:
```
http://localhost:8081/grocery
```

## Project Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── grocery/
│   │           ├── controller/
│   │           ├── model/
│   │           ├── service/
│   │           └── GroceryApplication.java
│   └── resources/
│       ├── static/
│       ├── templates/
│       └── application.properties
└── test/
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 