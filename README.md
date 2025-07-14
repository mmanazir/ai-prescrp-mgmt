AI Prescription Management System
Internship Project at Netsol Technologies


Project Overview
The AI Prescription Management System is a modern, web-based application developed during my internship at Netsol Technologies. It aims to revolutionize traditional prescription handling by digitizing and automating the process of managing medical prescriptions for both patients and doctors. The system provides a secure and efficient platform for uploading, extracting, and storing prescription data, enhancing accessibility and streamlining healthcare record management.
Key Features
•	Secure User Authentication & Role-Based Access:
•	Supports distinct user roles for Doctors and Patients, each with secure login and registration functionalities.
•	Ensures role-based access control, directing users to their respective dashboards.
•	Intuitive Prescription Upload:
•	Patients can easily upload their prescription documents, supporting various formats including image files (PNG, JPG) and PDFs.
AI-Powered Optical Character Recognition (OCR):
Leverages the Groq API (Llama-4-Scout) to intelligently extract critical information from uploaded prescription images.
Automatically identifies and separates medicine names and any general notes/instructions, converting unstructured image data into structured text.
Centralized & Secure Data Storage:
Extracted prescription data, along with the original file paths, is securely stored in a centralized database.
Prescriptions are directly linked to the respective patient IDs, ensuring accurate record-keeping and easy retrieval.
Prescription sends to the doctor to verify it.



Modular Microservices Architecture:
Designed with a decoupled microservices approach, utilizing FastAPI for robust backend APIs (Authentication Service and Prescription Service).
Employs a shared database with carefully managed SQLModel relationships, ensuring data integrity without tight code-level dependencies between services.
Interactive Frontend:
Built with Streamlit, providing a user-friendly and responsive interface for seamless interaction.
Benefits
Enhanced Efficiency: Automates the tedious process of manual data entry from prescriptions, saving time for healthcare providers and patients.
Improved Accuracy: AI-driven OCR minimizes human error in transcribing prescription details.
Digital Accessibility: Provides easy access to digital prescription records anytime, anywhere, reducing reliance on physical paper.
Streamlined Management: Centralized storage and role-based dashboards simplify the management and retrieval of patient prescriptions.
Scalability & Maintainability: The microservices architecture ensures the system is scalable for future features and easier to maintain.
Technologies Used
Backend Framework: FastAPI
Database ORM: SQLModel (built on SQLAlchemy and Pydantic)
Database: PostgreSQL (or SQLite for development)
Asynchronous Server: Uvicorn
Frontend Framework: Streamlit
AI/OCR: Groq API (Llama-4-Scout-17b-16e-instruct)
Password Hashing: Passlib (Bcrypt)
JWT Handling: PyJWT (or Jose)
Python Libraries: Requests, Pydantic, etc.

Conclusion
The AI Prescription Management System represents a significant step towards modernizing healthcare data management. By integrating advanced AI capabilities with a robust microservices architecture, it offers a practical solution for efficient, accurate, and secure handling of medical prescriptions, ultimately contributing to better patient care and operational efficiency.

