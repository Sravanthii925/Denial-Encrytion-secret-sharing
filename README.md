# Denial-Encrytion-secret-sharing
A secure cloud storage system implementing deniable encryption using secret sharing,AES Encryption,hashing,and user authentication.
Denial of Encryption from Secret Sharing in Data

About the Project

Denial of Encryption from Secret Sharing in Data is a secure data-sharing project focused on deniable encryption and secret sharing.

The main idea is to provide plausible deniability by allowing different decryption keys to produce different possible plaintexts from the same ciphertext. This helps protect sensitive data when a user is forced to reveal a decryption key.

Objectives

- Securely store and share data.
- Provide authentication and controlled access.
- Implement deniable encryption concepts.
- Use secret sharing for secure key/data management.
- Protect data from unauthorized access.
- Provide plausible/fake plaintext under an incorrect key.

Security Techniques

- Deniable Encryption
- Secret Sharing
- Honey Encryption
- Hashing
- Symmetric Encryption
- Authentication

Project Modules

Authority Server

Handles key requests and key generation.

Owner

- Registration and login
- Upload data
- Store data
- View uploaded data
- Approve data sharing

User

- Registration and login
- Receive authority permission
- Search for available data
- Access shared data

Cloud Service Provider

Stores data along with owner and user information.

Technologies Used

- Java
- JSP
- Servlets
- J2EE
- MySQL 5.5
- Eclipse

Project Architecture

The project consists of the following major entities:

Owner → Cloud Service Provider → User

The Authority Server manages key-related operations and permissions between the entities.

Key Features

- User authentication
- Owner authentication
- Authority-based access
- Key generation
- Secure data storage
- Data sharing and approval
- Data searching
- Encryption and decryption
- Deniable encryption
- Secret-sharing approach



Future Enhancements

- Improve authentication mechanisms.
- Enhance attacker detection.
- Improve key-management mechanisms.
- Support more scalable cloud environments.
- Enhance access-control mechanisms.
- Develop a modern user interface.

Project Information

Project: Denial of Encryption from Secret Sharing in Data

Student: Sravanthi Kachakayalwar

Department: CSE (AI & ML)



Academic Year: 2025–2026

📌 Note

This GitHub repository is maintained as a project documentation and presentation repository. It does not contain the application's source code.
