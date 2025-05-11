# Requirement Analysis in Software Development
Air bnb clone project requirement analysis for ALX PRO DEV program

## What is Requirement Analysis?

Requirement Analysis, or Requirements Engineering, is the vital SDLC phase focused on understanding, documenting, and validating stakeholder needs for a software system. It defines what the system should do through active collaboration.

### Key Activities:
* **Elicitation (Gathering):** Discovering requirements through interviews, surveys, workshops, use cases, etc.
* **Analysis & Modeling:** Organizing and representing requirements using techniques like use case diagrams and user stories.
* **Specification** (Documentation): Formally documenting requirements in a Software Requirements Specification (SRS).
* **Validation:** Ensuring requirements accurately reflect stakeholder needs through reviews and prototyping.
* **Management:** Controlling changes to requirements throughout the SDLC.

## Why is Requirement Analysis Important?
* Provides a clear foundation for the project.
* Reduces development costs by identifying issues early.
* Improves software quality by ensuring the system meets user needs.
* Minimizes scope creep through a well-defined scope.
* Enhances communication among stakeholders.
* Enables better planning and estimation.
* Facilitates effective testing.
* Increases user satisfaction.

In essence, thorough Requirement Analysis is essential for building successful software that meets stakeholder needs and delivers value, preventing costly errors and ensuring a focused development process.


## Key Activities in Requirement Analysis

The Requirement Analysis phase involves several key activities that are crucial for defining the software system effectively. These include:

* **Requirement Gathering:** This involves identifying and collecting all possible requirements for the system from various stakeholders and sources. Techniques used can include interviews, surveys, workshops, and analyzing existing documents. The goal is to obtain a broad understanding of the needs and expectations.

* **Requirement Elicitation:** This activity focuses on refining and elaborating on the initial gathered requirements. It involves actively interacting with stakeholders to clarify ambiguities, uncover hidden needs, and ensure a deep understanding of what is required. Techniques like brainstorming, prototyping, and use case analysis are often employed.

* **Requirement Documentation:** Once the requirements are elicited and understood, they need to be formally documented in a clear, concise, and structured manner. The primary output of this activity is the Software Requirements Specification (SRS) document, which serves as a blueprint for the development process.

* **Requirement Analysis and Modeling:** This involves organizing, structuring, and analyzing the documented requirements. Modeling techniques, such as use case diagrams, activity diagrams, and data flow diagrams, are used to visualize the system and its interactions. This step helps to identify inconsistencies, incompleteness, and potential conflicts among requirements.

* **Requirement Validation:** This critical activity ensures that the documented requirements accurately reflect the stakeholders' needs and are of high quality. Techniques like reviews, inspections, and prototype validation are used to verify the completeness, consistency, clarity, and correctness of the requirements before development begins.



## Types of Requirements

This section differentiates between functional and non-functional requirements and provides examples within the context of a booking management project.

### Functional Requirements

Functional requirements define *what* the system should do. They describe the specific actions or functions that the software must perform. In essence, they are the features of the system.

**Definition:**

Functional requirements describe the interactions between the system and its environment. They specify how the system should behave when certain conditions are met or when specific inputs are provided. They detail the processes, data manipulation, and computations that the system must carry out.

**Examples for a Booking Management Project:**

* **User Management:**
    * The system shall allow users to create and manage their accounts (registration, login, profile editing).
    * The system shall allow administrators to manage user roles and permissions.
* **Booking Management:**
    * The system shall allow users to search for available properties/services based on criteria like date, location, and price.
    * The system shall allow users to book a property/service.
    * The system shall allow users to view, modify, or cancel their bookings.
    * The system shall calculate the total booking cost, including taxes and fees.
    * The system shall generate booking confirmations.
* **Payment Processing**
    * The system shall integrate with a payment gateway to process transactions.
    * The system shall record payment history.
* **Reporting:**
    * The system shall generate reports on booking revenue.
    * The system shall generate reports on property/service availability.
  

### Non-functional Requirements

Non-functional requirements specify *how* the system should perform. They describe the qualities or attributes that the system must possess. They are often related to system-wide constraints and characteristics, rather than specific features.

**Definition:**

Non-functional requirements specify the criteria that can be used to judge the operation of a system, rather than specific behaviors. They relate to system properties such as performance, security, usability, reliability, scalability, and maintainability.

**Examples for a Booking Management Project:**

* **Performance:**
    * The system shall respond to user requests within 2 seconds.
    * The system shall be able to handle 1000 concurrent users.
* **Security:**
    * The system shall protect user data and payment information using encryption.
    * The system shall implement access control to restrict unauthorized access.
    * The system shall comply with relevant data privacy regulations (e.g., GDPR).
* **Usability:**
    * The system shall have a user-friendly interface that is easy to navigate.
    * The system shall provide clear and helpful error messages.
* **Reliability:**
    * The system shall be available 99.9% of the time.
    * The system shall recover from failures without data loss.
* **Scalability:**
    * The system shall be able to handle a growing number of users and bookings.
    * The system's database should be able to scale to accommodate increased data volume.
* **Maintainability:**
    * The system's code shall be well-structured and easy to understand.
    * The system shall be designed to facilitate future modifications and enhancements.
* **Portability:**
    * The system shall be compatible with multiple web browsers (Chrome, Firefox, Safari).


## Use Case Diagrams

Use Case Diagrams are a visual way to represent the interactions between users (actors) and a system to achieve specific goals. They illustrate the different ways a user can interact with the system's functionalities.

**Benefits of Use Case Diagrams:**

* **Improved Communication:** They provide a common language for stakeholders and developers to understand system requirements.
* **Clearer Scope Definition:** They help define the boundaries of the system and what it should and shouldn't do.
* **Requirement Validation:** They allow stakeholders to easily verify that the system will meet their needs.
* **Test Case Generation:** They provide a basis for creating test cases to ensure all functionalities are working correctly.
* **User-Centric Design:** They focus on the user's perspective, leading to more user-friendly systems.


## Acceptance Criteria

Acceptance Criteria are a set of predefined statements that specify the conditions a software feature must meet to be considered complete and acceptable by the stakeholders. They provide a clear and measurable definition of "done" for each requirement.

**Importance of Acceptance Criteria in Requirement Analysis:**

* **Clear Understanding:** They ensure that everyone involved (developers, testers, stakeholders) has the same understanding of what constitutes a successful implementation of a feature.
* **Testability:** They provide a solid basis for writing test cases, ensuring that the implemented feature can be effectively verified.
* **Reduced Ambiguity:** They minimize misunderstandings and ambiguities in the requirements, leading to less rework and fewer defects.
* **Stakeholder Alignment:** They allow stakeholders to clearly articulate and agree on what they expect from a particular feature.
* **Progress Tracking:** They provide measurable milestones for tracking development progress and determining when a feature is complete.
* **Improved Communication:** They facilitate clearer communication between the development team and stakeholders throughout the development process.

**Example of Acceptance Criteria for the "Checkout" Feature in the Booking Management System:**

**Feature:** Checkout

**Description:** Allows a logged-in user to review their selected booking(s), enter payment information, and finalize the booking.

**Acceptance Criteria:**

* **AC01:** Given a user has added one or more items to their booking, when the user navigates to the checkout page, then the selected items, quantities, and individual prices should be displayed.
* **AC02:** Given a user is on the checkout page, then the system should display a clear breakdown of the total cost, including any applicable taxes and fees.
* **AC03:** Given a user is on the checkout page, then the system should provide options for entering payment information (e.g., credit card details, integration with other payment methods).
* **AC04:** Given a user has entered valid payment information and clicks the "Confirm Booking" button, when the payment is successfully processed, then the system should display a booking confirmation message with a unique booking ID and booking details.
* **AC05:** Given a user has entered invalid payment information, when the user clicks the "Confirm Booking" button, then the system should display a clear and informative error message indicating the issue with the payment details.
* **AC06:** Given a user is on the checkout page, then the system should provide a clear way to navigate back to the booking details page to make changes.
* **AC07:** Given a user initiates the checkout process, then the system should ensure that all communication of sensitive payment information is secured using HTTPS.
