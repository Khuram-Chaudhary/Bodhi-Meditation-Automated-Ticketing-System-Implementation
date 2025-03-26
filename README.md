# Ticket Processing System for Bodhi Meditation Toronto

## Project Overview

This project involves the development of an automated **Ticket Processing System** for **Bodhi Meditation Toronto**, a public non-profit organization focused on promoting health and wellness through meditation. The goal of the system is to streamline the process of managing event registrations, ticket distribution, and customer information for free events hosted by the organization.

## Problem Statement

Bodhi Meditation Toronto's current ticketing process is inefficient and manual, relying on word-of-mouth promotion, in-person ticket distribution, and manual data entry. This leads to inconsistencies, delays, and difficulty in tracking ticket availability and customer information. The need for an automated solution is critical to enhance the efficiency of event management and provide a better experience for both customers and administrators.

## Key Features

- **Customer Registration**: Users can view event details, register for events, and receive digital tickets.
- **Ticket Management**: Customers can cancel their tickets and administrators can update or delete event details.
- **Real-Time Notifications**: Automatic notifications about ticket availability, cancellations, and event updates sent to both customers and administrators.
- **Integrated Database**: Centralized system for managing event details, customer information, and attendance data.
- **Event Updates**: Administrators can manage all event details, including adding, updating, or removing events.

## Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express
- **Database**: MySQL 
- **Email Notification**: SMTP, Nodemailer (for sending confirmation and cancellation emails)

## Use Cases

1. **Customers**:
   - View event details.
   - Register for events and receive a digital ticket.
   - Cancel tickets if needed.

2. **Administrators**:
   - Create, manage, and update event details.
   - View ticket availability in real-time.
   - Send email notifications to customers.
   - Delete or remove events from the system.
  
To ensure the success of this project, several techniques were used to understand and document both the current and future state of the ticketing process. These methods helped streamline the process and enabled the creation of a more efficient and effective solution.

### 1. **Business Process Model and Notation (BPMN)**
   - **Reasoning**: The BPMN diagrams were used to visually map the existing process and identify inefficiencies, inconsistencies, and opportunities for automation. The **As-Is BPMN Model** represented the current manual process, while the **To-Be BPMN Model** demonstrated the proposed automated solution, ensuring clarity in understanding the flow of the ticketing system for both customers and administrators.

### 2. **Use Case Diagrams**
   - **Reasoning**: Use case diagrams were created to define the interaction between users (customers and administrators) and the system. These diagrams helped outline functional requirements and ensured that the system design met the needs of its users. They also provided a simple, visual way of communicating how the system would be used by different stakeholders.

### 3. **System Sequence Diagrams (SSD)**
   - **Reasoning**: SSDs were developed to detail the sequence of interactions between the system and external entities (customers and administrators). These diagrams captured the flow of data, such as ticket registration, confirmation emails, and event updates, ensuring that all system interactions were thoroughly mapped and clear to all stakeholders.

### 4. **Class Diagram**
   - **Reasoning**: The class diagram was created to represent the structure of the database and its relationships. This helped identify key data entities like events, customers, and tickets and how they relate to each other, supporting the design of the backend database structure.

### 5. **Entity-Relationship Diagram (ERD)**
   - **Reasoning**: The ERD was used to visualize the database schema, illustrating the relationships between various data entities (e.g., customers, events, and tickets). It helped ensure the integrity of the database and facilitated the design of the relational database system, ensuring efficient querying and data storage.
