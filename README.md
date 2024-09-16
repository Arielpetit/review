# Mobile Banking Application for ESASCCO

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Technologies Used](#technologies-used)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact Information](#contact-information)
- [Acknowledgements](#acknowledgements)

## Project Overview and Goals

The Mobile Banking Application for ESASCCO is an open-source solution designed for Cooperative Financial Institutions (CFIs). This application facilitates secure and efficient banking operations, enabling users to manage accounts, transfer funds, and apply for loans seamlessly. By integrating with various core banking systems, such as Ledgers CBS, it enhances financial accessibility and inclusivity. 

### The goals of this project include:
1. Enhance financial accessibility and inclusivity for CFIs.
2. Provide a secure, flexible, and scalable mobile banking platform.
3. Facilitate seamless integration with existing core banking systems.

## Features
- **Account Management**: Users can check balances, view transactions, and manage their accounts.
- **Fund Transfers**: Initiate payments and transfer funds easily.
- **Loan Applications**: Apply for loans directly through the app.
- **Progressive Web Application (PWA)**: Accessible via web browsers, no app store required.
- **Offline Functionality**: Essential features available even without internet access.

## Prerequisites
Before you begin, ensure you have met the following requirements:

- **Node.js**: Version 14.x or higher
- **npm**: Version 6.x or higher (comes with Node.js)
- **Java JDK**: Version 11 or higher
- **Maven**: Version 3.6 or higher
- **Database**: ** (ensure it's installed and running)
- **Git**: Version 2.x or higher (for cloning the repository)

## Technologies Used
- **Backend**: Java Spring Boot
- **Frontend**: ReactJS
- **Database**: **
- **APIs**: ISO20022 compatible APIs for core banking integration

## Installation Instructions
### Frontend
1. **Clone the Frontend repository**:
   **For the UserApp :**
   ```bash
   git clone https://github.com/ADORSYS-GIS/webank-UserApp.git
   ```
   **For the TellerApp :**
   ```bash
   git clone https://github.com/ADORSYS-GIS/webank-TellerApp.git
   ```
   **For the AdminApp :**
   ```bash
   git clone https://github.com/ADORSYS-GIS/webank-AdminApp.git
   ```
   **For the OwnerApp :**
   ```bash
   git clone https://github.com/ADORSYS-GIS/webank-AppManager.git
   ```
   **For the ManagerApp :**
   ```bash
   git clone https://github.com/ADORSYS-GIS/webank-UserApp.git
   ```
2. **Navigate into the project directory**:
   Example for the UserApp : 
   ```bash
   cd webank-UserApp
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **Run the application**:
   ```bash
   npm start
   ```

### Backend
1. **Clone the Frontend repository**:
   ```bash
   git clone https://github.com/ADORSYS-GIS/webank-OnlineBanking.git
   ```
2. **Navigate into the project directory**:
   ```bash
   cd webank-OnlineBanking
   ```
3. **Install dependencies**:
   ```bash
   mvn install
   ```
4. **Set up the database**: Configure your database settings in the application properties file.
5. **Run the application**:
   ```bash
   mvn spring-boot:run
   ```

## Usage
Once the application is running, users can:
- Access the app via a web browser using the provided URL.
- Follow the onboarding process guided by the banking tellers.
- Utilize the app to manage their banking needs as outlined in the features.

## Contributing
Contributions are welcome! Please see the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to the project.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact Information
For questions or support, please reach out to:
- **Email**: Ariel.Tchikaya@adorsys.com
- **GitHub Issues**: [Submit an issue](https://github.com/yourusername/your-repo/issues)

## Acknowledgements
- Thanks to the adorsys development team for their contributions.
- Special thanks to the contributors and libraries that supported this project.
