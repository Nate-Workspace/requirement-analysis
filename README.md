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

**Use Case Diagram for the Booking Management System:**

Here's a description of how you would design a use case diagram for your booking system. You will need to use a diagramming tool like Draw.io to create the actual diagram.

**1. Actors:**

* **User:** A customer who wants to book a property or service.
* **Administrator:** Manages the system, properties, users, etc.
* **Payment Gateway:** (External System) Handles payment processing.

**2. Use Cases:**

* **User:**
    * Register Account
    * Login
    * Search for Properties/Services
    * View Property/Service Details
    * Book Property/Service
    * Manage Bookings (View, Modify, Cancel)
    * Make Payment
    * View Booking History
    * Manage Profile
* **Administrator:**
    * Manage Users
    * Manage Properties/Services
    * Manage Bookings
    * Generate Reports
    * Manage Payment Gateway Settings
* **Payment Gateway:**
    * Process Payment
    * Return Payment Status

**3. Relationships:**

* Use lines and arrows to show the relationships between actors and use cases.
* Use `<<include>>` or `<<extend>>` relationships where appropriate (e.g., "Make Payment" might `<<include>>` "Process Payment").

**Example using Draw.io:**

1.  Go to [Draw.io](https://app.diagrams.net/).
2.  Create a new diagram.
3.  Use the UML shapes (specifically, the Use Case shapes) to represent actors and use cases.
4.  Connect them with lines to show the interactions.
5.  Label the actors and use cases clearly.

**Including the Diagram in your README:**

1.  **Export from Draw.io:** Once you've created your diagram in Draw.io, export it as a PNG file named `alx-booking-uc.png`.
2.  **Place in your Repository:** Make sure the `alx-booking-uc.png` file is in the same directory as your `README.md` file (or in a subdirectory if you prefer).
3.  **Link in Markdown:** Use the following Markdown syntax to embed the image in your README:

    ```markdown
    ![Use Case Diagram for Booking System](alx-booking-uc.png)
    ```

    If the image is in a subdirectory (e.g., `images`), the path would be:

    ```markdown
    ![Use Case Diagram for Booking System](images/alx-booking-uc.png)
    ```

This will display the image in your README, illustrating the use cases for your booking system. Remember to replace `images/alx-booking-uc.png` with the correct path if you place the image in a different directory.
