# Requirement Analysis

## What is Requirement Analysis?
Requirement Analysis is the systematic process of identifying, documenting, and analyzing the needs and expectations of stakeholders for a software system. It is one of the most critical phases in the Software Development Life Cycle (SDLC) because it lays the foundation for system design, development, and testing.  

During this phase, requirements are gathered from clients, users, and other stakeholders, then carefully analyzed to ensure they are clear, complete, consistent, and feasible.  

In short, Requirement Analysis bridges the communication gap between stakeholders and developers, ensuring the software meets business needs.

---

## Why is Requirement Analysis Important?
Requirement Analysis is crucial in the SDLC for several reasons:

1. **Clarity and Understanding**  
   - Ensures developers and stakeholders share the same understanding of the project goals.  
   - Reduces the risk of misinterpretation.  

2. **Cost and Time Efficiency**  
   - Detecting and fixing requirement errors early is much cheaper than correcting them later during development or testing.  

3. **Quality Assurance**  
   - Well-defined requirements help build software that meets business goals and user expectations.  
   - Serves as the basis for validation and testing.  

---

## Key Activities in Requirement Analysis
The Requirement Analysis process includes the following key activities:

- **Requirement Gathering**  
  Collecting requirements from stakeholders, customers, users, and existing documentation.  

- **Requirement Elicitation**  
  Engaging stakeholders through interviews, questionnaires, workshops, and brainstorming to uncover needs.  

- **Requirement Documentation**  
  Recording requirements in a structured format (e.g., Software Requirements Specification (SRS)).  

- **Requirement Analysis and Modeling**  
  Studying requirements for feasibility, consistency, and completeness, often with models like data flow diagrams or use case diagrams.  

- **Requirement Validation**  
  Ensuring requirements are accurate, complete, testable, and agreed upon by stakeholders.  

---

## Types of Requirements

### Functional Requirements
Functional requirements describe **what the system should do** — the specific behaviors and functions of the software.  

**Examples for the Booking Management System:**  
- The system must allow users to search for available rooms by date.  
- The system must enable customers to book, modify, or cancel reservations.  
- The system must send confirmation emails after a successful booking.  

### Non-functional Requirements
Non-functional requirements define **how the system performs** and the quality attributes that constrain functionality.  

**Examples for the Booking Management System:**  
- The system should respond to booking requests within 3 seconds.  
- The system must support up to 10,000 concurrent users.  
- The system should be available 99.9% of the time.  
- The interface must be user-friendly and accessible to people with disabilities.  

---

## Use Case Diagrams
Use Case Diagrams are visual representations of the interactions between users (actors) and the system. They help stakeholders quickly understand system functionality and user interactions.  

**Benefits:**  
- Provide a high-level view of system behavior.  
- Help identify actors, system boundaries, and key features.  
- Enhance communication between stakeholders and developers.  

### Booking Management System – Use Case Diagram  
![Use Case Diagram] <img width="660" height="348" alt="alx-booking-uc png" src="https://github.com/user-attachments/assets/c6a5ac6f-571c-4a24-be02-1628ef27c64b" />



*(Actors: Customer, Admin, Payment Gateway; Use Cases: Search Room, Book Room, Cancel Booking, Make Payment, Generate Report)*  

---

## Acceptance Criteria
Acceptance Criteria are predefined conditions that a feature must satisfy to be accepted by stakeholders. They ensure requirements are testable, measurable, and unambiguous.  

**Importance:**  
- Define clear expectations for features.  
- Act as a guide for developers and testers.  
- Reduce scope creep and misunderstandings.  

**Example – Checkout Feature (Booking Management System):**  
- The system must display a summary of booking details before payment.  
- The system must allow users to select a payment method (credit card, PayPal, etc.).  
- The system must validate payment details before processing.  
- The system must show a confirmation message and booking reference number upon successful payment.  
- The system must send an email receipt to the customer after checkout.  

---

