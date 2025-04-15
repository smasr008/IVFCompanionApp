# IVFCompanionApp

## IVFCompanionApp

A Spring Boot application that helps women manage their IVF treatment timeline with medication tracking and appointment reminders.

![IVF Tracker Screenshot](https://via.placeholder.com/800x400?text=IVF+Tracker+Screenshot)

IVF Companian App provides a reliable way to organize the complex process of fertility treatment. Built with Spring Boot and Java, this application helps users track medications, appointments, and treatment milestones.

## Features

- 📅 Calendar integration for treatment appointments
- 💊 Medication schedule tracking with reminders
- 🏆 IVF milestone visualization
- 🔔 Custom notification system

## Technologies Used

- Java 11
- Spring Boot 2.7
- Spring Data JPA
- Spring Security
- MySQL Database
- Maven

## Getting Started

### Prerequisites

- JDK 11+
- Maven
- MySQL

### Installation

1. Clone the repository
git clone https://github.com/yourusername/ivfcompanionapp.git

2. Configure your database in `application.properties`
spring.datasource.url=jdbc:mysql://localhost:3306/ivf_tracker
spring.datasource.username=root
spring.datasource.password=yourpassword

3. Build and run the application
mvn spring-boot

4. Access the application at `http://localhost:8080`

## API Endpoints

- **User Management**: `/api/users`
- **Treatment Cycles**: `/api/cycles`
- **Appointments**: `/api/appointments`
- **Medications**: `/api/medications`

## Screenshots

![Timeline View](https://via.placeholder.com/400x300?text=Timeline+View)
![Medication Tracker](https://via.placeholder.com/400x300?text=Medication+Tracker)

## Future Development

- Mobile application
- Integration with clinic systems
- Community support features

## License

Copyright (c) 2025 Samira Kazma Masri

All rights reserved. This code is shared for demonstration and educational purposes only.
This code may not be used, modified, or distributed for any commercial or non-commercial purpose
without explicit written permission from the author.

## Acknowledgments

- Inspired by the experiences of women going through IVF treatment
- Thanks to all who provided feedback during development
