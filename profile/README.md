
# 🎨 **Anjezha Services Platform**

Welcome to **Anjezha**, a platform that bridges the gap between skilled crafters and those in need of their expertise. This document will walk you through the platform's idea, features, technical details, and more, presented in a lively, visually engaging way. 

---

## 📋 **Table of Contents**

- [💡 The Idea](#The Idea)
  - [🚨 The Problem](#the-problem)
  - [✨ Our Solution](#our-solution)
- [⚙️ Key Features](#key-features)
- [📜 Requirements](#requirements)
  - [✅ Functional Requirements](#functional-requirements)
  - [🔒 Non-Functional Requirements](#non-functional-requirements)
- [🛠️ Design and Architecture](#design-and-architecture)
  - [📊 Use Case Diagram](#use-case-diagram)
  - [🗂️ Class Diagram](#class-diagram)
- [💻 Technical Details](#technical-details)
- [🚀 How to Get Started](#how-to-get-started)
- [📝 Change Management Process](#change-management-process)
- [📁 Appendix](#appendix)

---

## 💡 The Idea

We live in a world where many talented crafters are hard to find, even though their skills are highly sought after. **Anjezha** was born out of the need to help people connect with these talented individuals. Our platform aims to make it easy for users to find skilled taskers (crafters, workers, freelancers) and for taskers to showcase their expertise.

### 🚨 **The Problem**
Egypt is full of clever, skilled crafters who are known in small, tight-knit communities but largely go unnoticed outside of them. There is no structured way for customers to easily discover and hire these skilled individuals.

### ✨ **Our Solution**
We decided to build **Anjezha**, a platform that connects users with talented taskers, offering a structured solution to bridge this gap. It allows users to post tasks, receive bids from taskers, and hire the best professional for the job.


---

## ⚙️ **Key Features**

The key features that make **Anjezha** stand out:

- **👤 User Registration and Authentication:** Easy sign-up with options for social media logins.
- **📝 Task Creation and Management:** Post a task, manage it, and track its progress from start to finish.
- **🔍 Tasker Search and Bidding:** Search for taskers, view profiles, and negotiate terms.
- **🎯 Task Search and Applications:** Taskers can search for tasks, apply, and get hired.
- **⭐ Ratings and Reviews:** Rate and review taskers after task completion, ensuring quality.
- **📞 Customer Support and Dispute Resolution:** Fast and reliable support to resolve any disputes.


---

## 📜 **Requirements**

We designed **Anjezha** with clear functional and non-functional requirements in mind to ensure the platform performs smoothly and meets user expectations.

### ✅ **Functional Requirements**

- **🔐 User Registration:** A secure form for signing up and authenticating users.
- **🔑 Password Recovery:** Simple password reset options.
- **🛡️ Two-Factor Authentication (2FA):** Optional for added security.
- **📄 Task Posting:** Post tasks with details like title, description, and budget.
- **📈 Task Status:** Track task progress from Pending, Assigned, In Progress, Completed, and Cancelled.
- **🛠️ Tasker Profiles:** Taskers can create detailed profiles, showcase their skills, and set pricing.
- **💬 In-App Messaging:** Real-time communication with secure encryption.
- **🔔 Notifications:** Alerts for new messages, task updates, and more.

### 🔒 **Non-Functional Requirements**

- **🚀 Performance:** The platform supports up to 1000 concurrent users with response times under 2 seconds.
- **🔐 Security:** Data is secured using SSL/TLS for transmission and AES-256 for storage.
- **💼 Reliability:** Guaranteed 99.9% uptime, backed by regular data backups and failover systems.


---

## 🛠️ **Design and Architecture**

### 📊 **Use Case Diagram**

<p align="center">
  <img src="https://github.com/anjazha/.github/blob/main/anjezha_uml_diagram.svg" style="display:block; max-width:100%" title="UML diagram" alt="UML diagram"/>
</p>

### 🗂️ **Class Diagram**

<p align="center">
  <img src="https://github.com/anjazha/.github/blob/main/class-diagrm_depi.drawio.png" style="display:block; max-width:100%" title="Class diagram" alt="Class diagram"/>
</p>

---

## 💻 **Technical Details**

Explore the code and the technical side of **Anjezha**:

- **Frontend Repo**: Visit [Anjezha Frontend](https://github.com/anjezha/anjezha-front) to explore the technologies and frameworks used for the client-side.
- **Backend Repo**: Dive into [Anjezha Backend](https://github.com/anjezha/anjezha) to understand the server-side architecture and database management.

---

## 🚀 **How to Get Started**

To set up the platform locally, follow these steps:

### **For Backend**

1. **Clone the server repository:**
    ```bash
    git clone https://github.com/anjezha/anjezha.git
    ```

2. **Install dependencies:**
    ```bash
    cd anjezha
    npm install
    ```

3. **Set up environment variables:**
    - Create a `.env` file with the necessary configuration.
	  ```.env
		PORT = your prefared port
		MODE = your current mode (development | productions)
		DB_HOST = database host
		DB_PORT = database port 
		DB_USER = database user
		DB_NAME = database name
		DB_CA = database ssl certification
		DB_URL = databse url
		DB_PASSWORD = database password
		JWT_SECRET = jwt secert key
		JWT_EXPIRES_IN = jwt expires in default 1h
		CLOUDINARY_URL = cloudiary url 
	  ```
	  
4. **Run the app:**
    ```bash
    npm start
    ```


### **For Frontend**
1. **Clone the server repository:**
    ```bash
    git clone https://github.com/anjazha/Anjezha-Front.git
    ```

2. **Install dependencies:**
    ```bash
    cd Anjezha-Front
    npm install
    ```
	  
1. **Run the app:**
    ```bash
    npm run dev
    ```
---

## 📝 **Change Management Process**

Changes to the system’s specifications are handled through a formal change management process, ensuring that any changes are reviewed and approved before implementation.

---

## 📁 **Appendix**

For more detailed documentation, diagrams, and models, please refer to the [project’s documentation folder](https://github.com/anjazha/.github).
