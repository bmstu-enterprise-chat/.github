# BMSTU Distributed Messaging System

Welcome to the official GitHub organization for the BMSTU coursework project **"Distributed Messaging System"** — a real-time chat between Earth and Mars simulating three layers of the OSI model.

---

## About the Project

This project is a multi-layered communication system that emulates data transmission over the **application, transport, and channel layers**. It was developed as part of a senior coursework at **Bauman Moscow State Technical University (BMSTU)**, focusing on network architecture, fault tolerance, and real-time communication.

---

## Project Structure

The project consists of three main services, each representing a network layer:

- **Application Layer:** React + Redux Toolkit + WebSocket chat interface  
- **Transport Layer:** Kafka-based segment queue and message reassembly in Go  
- **Channel Layer:** Simulation of noisy channels with error injection and correction algorithms

---

## Project Variant

**Variant 33**

The system sends text messages protected by a cyclic [7,4]-code.  
Segment length (X): 140 bytes  
Segment assembly period (N): 1 second  
Error probability (P): 10%  
Frame loss probability (R): 2%

---

## Documentation

Our project documentation is organized by network layers and common project files:

- **Application Layer**  
  Includes Figma design mockups (PDF), Swagger API documentation, and sequence diagrams.  
  [View Application Layer docs](https://github.com/bmstu-enterprise-chat/docs/tree/main/application%20layer)

- **Transport Layer**  
  Contains sequence diagrams and Swagger API specifications.  
  [View Transport Layer docs](https://github.com/bmstu-enterprise-chat/docs/tree/main/transport%20layer)

- **Channel Layer**  
  Also includes sequence diagrams and Swagger API files.  
  [View Channel Layer docs](https://github.com/bmstu-enterprise-chat/docs/tree/main/channel%20layer)

- **Common Project Documents**  
  - [Technical Specification (ТЗ)](https://github.com/bmstu-enterprise-chat/docs/blob/main/common/%D0%A1%D0%A2_%D0%A2%D0%97_%D0%9A33_%D0%9B%D0%B0%D1%80%D0%BA%D0%B8%D0%BD_%D0%A6%D1%8B%D0%BF%D1%8B%D1%88%D0%B5%D0%B2_%D0%A1%D0%B5%D1%80%D0%BE%D0%B2.docx)  
  - [Project Work Report (РПЗ)](https://github.com/bmstu-enterprise-chat/docs/blob/main/common/%D0%A1%D0%A2_%D0%A0%D0%9F%D0%97_%D0%9A33_%D0%9B%D0%B0%D1%80%D0%BA%D0%B8%D0%BD_%D0%A6%D1%8B%D0%BF%D1%8B%D1%88%D0%B5%D0%B2_%D0%A1%D0%B5%D1%80%D0%BE%D0%B2.docx)  
  - [Deployment Diagram](https://github.com/bmstu-enterprise-chat/docs/blob/main/common/%D0%A0%D0%B0%D0%B7%D0%B2%D0%B5%D1%80%D1%82%D1%8B%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5.png)  
  - [Postman API Collection](https://github.com/bmstu-enterprise-chat/docs/blob/main/common/enterprise-chat.postman_collection.json)

---

## Team

For any questions or support related to the project, please contact the organizer: [@ttsypyshev](https://github.com/ttsypyshev).

The team also included other members who contributed to the project, but they are not publicly available.


---

## How to Use

1. Clone the repositories of each service from this organization.  
2. Follow the deployment instructions in the admin guide.  
3. Run the services locally or in a virtual network (e.g., ZeroTier).  
4. Use the React frontend to connect and test real-time messaging.

---

## Contact

- **Project Organizer:** [@ttsypyshev](https://github.com/ttsypyshev)  
- **Scientific Supervisor:** Anton Igorevich Kanev (tg: [@neughost](https://t.me/neughost))  
- **Course Assignment Repository:** [https://github.com/iu5git/Networking](https://github.com/iu5git/Networking)

---

*This project is a coursework developed by BMSTU students as part of their academic program.*
