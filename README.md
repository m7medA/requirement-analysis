# Requirement Analysis in Software Development

## What is Requirement Analysis?
Requirement Analysis is a critical phase in the Software Development Lifecycle (SDLC) that involves documenting, analyzing, and structuring the needs of a project before development begins. It ensures that the software meets business objectives, user expectations, and technical feasibility.

## Why is Requirement Analysis Important?  
Requirement Analysis plays a foundational role in SDLC by:  

- **Defining Clear Objectives** – Establishing what the software must achieve.  
- **Reducing Ambiguity** – Ensuring all stakeholders have a shared understanding of the project scope.  
- **Preventing Scope Creep** – Avoiding unnecessary changes that could delay development.  
- **Providing a Blueprint for Development** – Helping developers, designers, and testers align their work.  
- **Enhancing Software Quality** – Ensuring the final product meets user needs and business goals. 

## Key Activities in Requirement Analysis.
Requirement Analysis consists of five essential activities:  

1. **Requirement Gathering** – Collecting information from stakeholders.  
2. **Requirement Elicitation** – Refining and clarifying requirements through discussions.  
3. **Requirement Documentation** – Structuring requirements in a clear, organized format.  
4. **Requirement Analysis & Modeling** – Evaluating feasibility and prioritizing features.  
5. **Requirement Validation** – Ensuring accuracy and completeness before development.

## Types of Requirements

### Functional Requirements
Functional requirements define the **specific behaviors and functionalities** that the system must perform. These requirements describe **what the system should do** to meet user needs.

#### Examples for the Booking Management System:
- Users should be able to **search for available bookings** based on date and location.
- The system should allow users to **select a service and confirm their booking**.
- Users should receive a **confirmation email** after completing a booking.
- The system should provide **payment processing** for bookings.

### Non-functional Requirements
Non-functional requirements define the **quality attributes, constraints, and performance expectations** of the system. These requirements describe **how the system should behave** rather than what it should do.

#### Examples for the Booking Management System:
- The system should **respond within 2 seconds** for booking searches.
- The platform should be **accessible on mobile and desktop devices**.
- The system should support **at least 10,000 concurrent users**.
- User data should be **encrypted and stored securely** to ensure privacy.

## Use Case Diagrams

### What is a Use Case Diagram?
A **Use Case Diagram** is a visual representation of how users (actors) interact with a system. It helps in understanding the **functional requirements** by illustrating the relationships between users and system functionalities.

### Benefits of Use Case Diagrams
- **Clarifies system interactions** – Shows how different users interact with the system.
- **Defines system scope** – Helps in identifying key functionalities.
- **Improves communication** – Provides a clear visual for stakeholders.
- **Supports requirement validation** – Ensures all necessary use cases are covered.

### Use Case Diagram for the Booking Management System
Below is a **Use Case Diagram** representing the interactions in the **booking management system**:

![alx-booking-uc.png](https://github.com/m7medA/requirement-analysis/blob/main/alx-booking-uc.png).

### Actors and Use Cases
#### **Actors:**
- **User** – Books services, manages reservations.

#### **Use Cases:**
- **Search for available bookings**
- **Process payment**
- **Receive booking confirmation**

## Acceptance Criteria

### What is Acceptance Criteria?
Acceptance Criteria defines the **conditions that must be met** for a feature to be considered **complete and functional**. It ensures that the software aligns with **business goals, user expectations, and technical feasibility**.

### Importance of Acceptance Criteria
- **Ensures clarity** – Defines what success looks like for a feature.  
- **Reduces ambiguity** – Prevents misunderstandings between developers and stakeholders.  
- **Supports testing** – Helps QA teams validate functionality.  
- **Improves development efficiency** – Guides developers in building features correctly.  

### Example: Acceptance Criteria for Checkout Feature
For the **Checkout** feature in the **booking management system**, the acceptance criteria could be:

#### **Scenario: Successful Booking Checkout**
- Users must be able to **select available dates** for booking.  
- Users must be able to **confirm their booking** and proceed to payment.  
- The system must **process payments securely** and provide a confirmation.  
- Users must receive a **confirmation email** within **2 minutes** of completing the checkout.  
- If payment fails, the system must **display an error message** and allow retrying.  




