# Ainjazha Management System

## Software Requirements Specification

**Version**: 1.0  
**Date**: 2024  
---
You can find project PDF documentation [here](../ainjezha%20managment%20system.pdf)

## Table of Contents

- [Introduction](#introduction)
- [Scope](#scope)
- [General Description](#general-description)
- [Specific Requirements](#specific-requirements)
  - [External Interface Requirements](#external-interface-requirements)
  - [Functional Requirements](#functional-requirements)
- [Use Cases](#use-cases)
- [Non-Functional Requirements](#non-functional-requirements)
- [Database Requirements](#database-requirements)
- [Change Management Process](#change-management-process)

---

## Introduction

The Ainjazha management system is a platform designed to connect customers and taskers to facilitate task outsourcing within a local community.

---

## Scope

Key features include:
- User registration and authentication.
- Task creation and management.
- Tasker search and bidding.
- Secure payment processing.
- Ratings and reviews.
- Customer support and dispute resolution.

---

## General Description

### Product Perspective

Ainjazha Management System is a web and mobile-based platform for outsourcing tasks and services, connecting customers with taskers offering assistance.

### User Roles

- **Customers**: Individuals or businesses posting tasks.
- **Taskers**: Individuals offering services to complete tasks.
- **Admin**: Responsible for managing the platform.
- **Support Seekers**: Users requiring platform assistance.

---

## Specific Requirements

### External Interface Requirements

#### User Interfaces

- **Web Interface**: Accessible via desktop browsers.
- **Mobile Interface**: Available for iOS and Android devices.

#### Software Interfaces

- **Payment Processing**: Integration with payment gateways like PayPal, Stripe.
- **Mapping & Location**: Google Maps or Mapbox for location services.
- **Authentication**: OAuth and identity verification systems.
- **CDN**: Content delivery via Amazon CloudFront or Akamai.

### Functional Requirements

#### User Registration and Authentication

- **Form Validation**: Secure form for user registration.
- **Login**: Email/password login with optional social media integration.
- **Password Recovery**: Mechanism for password reset.
- **Two-Factor Authentication (2FA)**: Optional for enhanced security.

#### Task Posting

- **Task Form**: Details like title, description, location, and budget.
- **Task Statuses**: Pending, Assigned, In Progress, Completed, Cancelled.
  
#### Tasker Profile and Skills

- **Profile Creation**: Taskers can showcase skills, location, and portfolio.
- **Pricing**: Taskers can set their own prices.

#### In-App Messaging

- **Encrypted Communication**: Real-time messaging between users.
- **Notifications**: Alerts for task updates and new messages.

---

## Use Cases

### 1. User Registration
- **Actors**: Client, Tasker
- **Description**: Allows taskers and customers to register and authenticate.

### 2. Task Posting
- **Actors**: Customers
- **Description**: Customers can post tasks specifying all required details.

### 3. Tasker Ratings and Reviews
- **Actors**: Customers
- **Description**: Customers can rate and review taskers upon task completion.

---

## Non-Functional Requirements

### Performance
- Support for up to 1000 concurrent users with less than 2 seconds response time.

### Security
- SSL/TLS for data encryption.
- AES-256 for data storage encryption.

### Reliability
- 99.9% uptime guarantee through failover systems and data backups.

---

## Database Requirements 
    you can see design database from [here](https://drawsql.app/teams/admin-43/diagrams/anjazha)

- Support for both SQL and NoSQL databases with minimal changes.
- Data migration tools for smooth transition between databases.

---

## Change Management Process

Any changes to the system's specifications will follow a formal change management process that includes submission, review, and approval procedures.

---

## Appendix

For more detailed diagrams, models, and technical documentation, please refer to the project's documentation folder.
