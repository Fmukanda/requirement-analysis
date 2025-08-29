# Requirement Analysis in Software Development
****
The main purpose of this repository is to document the concept of Requirement Analysis, including its importance in the software development lifecycle (SDLC).
## What is Requirement Analysis?
Requirement Analysis is the process of gathering, understanding, and defining the requirements of the software product that meet the needs and expectations of users and stakeholders. This process ensures that the software product being developed is aligned with the goals and requirements all stakeholders during the SDLC.
## Why is Requirement Analysis Important?
Requirement Analysis is  a crucial process in setting out the direction of Software development project. The following are significances of Requirement Analysis in SDLC
 - **Clear Understanding of Objectives:** Requirement analysis prevents misunderstandings and ensures everyone has a shared vision.
 - **Scope Definition:** It helps define the scope of the project, specifying what features are included and prevents scope creep.
 - **Efficient Resource Allocation:** By understanding the requirements upfront, the team can plan the project effectively and allocate resources efficiently.
 - **Reduces Risk:** Properly gathering and documenting requirements helps identify potential risks early on before the development of software product.
 - **Improved Quality:** Clear requirements guide the development, testing, and deployment phases of software product by ensuring it meets the desired quality.
## Key Activities in Requirement Analysis
  - **Requirement Gathering:** Collect detailed information through interviews, surveys, workshops, or document analysis to understand user needs, system functionality, and constraints.
  - **Requirement Elicitation:** Engage with stakeholders to clarify ambiguous or incomplete requirements. This often involves discussions to dig deeper into the desired features, performance, and security needs.
  - **Requirement Documentation:** Write down both functional requirements (what the system should do) and non-functional requirements (performance, security, usability, etc.) in a clear, structured format.
  - **Requirement Analysis and Modeling:** Create models to visualize requirements. Analyze and prioritize requirements based on business value, feasibility, and urgency to ensure the most critical needs are addressed first.
  - **Requirement Validation:** Ensure that the documented requirements align with stakeholder expectations and are achievable. This may involve reviewing the requirements with stakeholders for validation.
## Types of Requirements
There two type of requirements in system application - Functional and Non-Functional requirements
Below is an example of requirements in a booking management system like Booking.com 
   1. **Functional Requirements**
      This requirements specifies the functions and tasks of the applications.It define **WHAT** the application should do.   
       - _**User Registration & Login:** Users must be able to sign up, log in, and manage their profiles._
       - _**Property Listing:** Hosts should be able to list properties with details like title, description, price, photos, and availability._
       - _**Search & Filter:** Users can search for properties based on location, check-in/check-out dates, price range, amenities, etc._
       - _**Booking Management:** Users can book properties, cancel bookings, and view past/future reservations._
       - _**Payment Integration:** Users can pay for bookings via credit/debit card, PayPal, UPI, etc._
       - _**Review & Rating System:** Users can leave reviews and ratings for properties after their stay._
       - _**Notification System:** Email or in-app notifications for booking confirmations, cancellations, and payment receipts._
       - _**Admin Dashboard:** Admins can manage users, listings, bookings, payments, and handle reports/disputes._
       - _**Multi-language Support:** The app supports multiple languages for users in different regions._
         
   3. **Non-Functional Requirements**
      This requirements specifies quality attributes, constraints, and performance metrics. It define **HOW** the system application should behavior.
       - _**Performance:** The system should respond to user actions (e.g., search, booking) within 2 seconds._
       - _**Scalability:** The application must handle high traffic, especially during peak travel seasons._
       - _**Availability/Uptime:** The system should be available 99.9% of the time (24/7 availability)._
       - _**Security:** User data and payments must be protected with encryption (e.g., HTTPS, PCI-DSS compliance)._
       - _**Usability:** The UI/UX must be intuitive and user-friendly, accessible on web and mobile platforms._
       - _**Maintainability:** Code should be modular and documented to support easy updates and bug fixes._
       - _**Localization:** The system should support local currencies, languages, and date formats._
       - _**Reliability:** The system must recover gracefully from crashes or unexpected failures._
       - _**Data Backup & Recovery:** TThe system must perform daily backups and support data recovery within 1 hour._
     
   ## Use Case Diagrams
   A Use Case Diagram is a visual representation in UML (Unified Modeling Language) that shows the interactions between users (actors) and a system. Use Case Diagram focus on **WHAT** the system does and not on **HOW** it does it. It show how different actors interact with the system to achieve specific goals (use cases).

   The following is an illustration of User Case Diagram for a booking management system.

   ![image alt](https://github.com/Fmukanda/requirement-analysis/blob/31b2695b3e5049e9b0b78b1d93623383ec80235a/alx-booking-uc.png)

## Acceptance Criteria
Acceptance Criteria are a set of predefined conditions or standards that a software feature must meet for it to be considered acceptable to the stakeholders. Acceptance criteria are importantant in the following ways:
 - They provide clear, specific guidelines on what the feature should do,
 - They ensure that both the development team and stakeholders are aligned on expectations.
 - They help to define the scope of the feature by outlining what is in scope and what is out of scope, preventing ambiguity and scope creep

The following is an example of an acceptance criteria for a Checkout feature in the booking management system
  - _**User Authentication:**_
      - _The guest must be logged in to proceed with checkout. If the guest is not logged in, they should be prompted to log in or create an account._
  - _**Valid Payment Methods:**_ 
      - _The checkout screen should display supported payment methods (e.g., credit card, PayPal, Apple Pay)._
      - _The user should be able to select one of the listed payment methods and enter the necessary information._
  - _**Payment Confirmation:**_
      - _Upon successful payment, the guest should receive an on-screen confirmation message, "Your booking has been successfully confirmed!"._
      - _A confirmation email should be sent to the guest’s registered email with booking details and payment confirmation._
  - _**Invalid Payment Handling:**_ 
      - _If the payment is declined (e.g., insufficient funds or network issue), the user should see a clear error message, such as "Payment could not be processed. Please check your details or try another method."_
      - _The guest should be able to retry payment with different methods._
  - _**Booking Summary:**_
      - _The checkout page should display a summary of the booking (property details, dates, total cost, taxes, etc.) for the guest to review before proceeding._
  - _**Security:**_
      - _The payment process must use encrypted communication (SSL/TLS) to secure sensitive information like credit card details._
      - _The system should comply with PCI-DSS standards for payment card security._
  - _**Error Handling:**_
      - _If there is a technical error during the payment processing (e.g., network failure), the user should see a message like "An error occurred. Please try again later."_
      - _The user should be able to resume the payment attempt once the error is resolved._
  - _**Booking Status Update:**_
      - _After successful payment, the status of the booking should change from "Pending" to "Confirmed" in the guest’s profile and booking history._
  - _**Time-out Handling:**_
      - _If the guest does not complete the payment within a certain time (e.g., 15 minutes), the system should automatically cancel the booking and release the property for others to book._
