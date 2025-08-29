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



