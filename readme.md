# Event Manager FastAPI Project

This project is a secure RESTful API for managing users in an event management system. It features JWT-based OAuth2 authentication, role-based access control, email verification, and administrative tools.

1. **[#1: Fix SMTP Disconnection in EmailService](https://github.com/carlos-fuentes15/event_manager/issues/1)**  

2. **[#2: Add 'last_name' to UserResponse Schema](https://github.com/carlos-fuentes15/event_manager/issues/2)**  

3. **[#3: Fix Enum Usage for UserRole](https://github.com/carlos-fuentes15/event_manager/issues/3)**  
 
4. **[#4: Import Missing 'Enum' for UserRole](https://github.com/carlos-fuentes15/event_manager/issues/4)**  
  
5. **[#5: Adjust LoginRequest Schema](https://github.com/carlos-fuentes15/event_manager/issues/5)**  
  
1. **Fork the Project Repository**: Forked the [project repository](https://github.com/carlos-fuentes15/event_manager)
   
Docker Image: [https://hub.docker.com/r/csf1515/event_manager](https://hub.docker.com/r/csf1515/event_manager)

![QR Code to GitHub](images/qr_code.png)

## Reflection 

This assignment greatly improved my ability to use FastAPI for real-world backend programming. I gained a deeper grasp of asynchronous programming, token-based auth processes, and Dockerized API deployment through tasks like troubleshooting complex SMTP issues, fixing schema incompatibilities, and putting role-based authentication into practice.

I learned how to use GitHub Issues and branches to manage tasks collaboratively using the issue-based workflow. Clean code and agile techniques were reinforced through the creation of tests, the tying of changes to issues, and the use of GitHub Actions to ensure CI/CD. Additionally, I discovered how crucial clear commit messages and documentation are to long-term maintenance and team visibility.

## Running the Project

```bash
docker-compose up --build
