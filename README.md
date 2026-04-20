# CS-320 Software Test, Automation QA

## Module 8

## Github Repository

### Submitted By:

**Hamna Khalid**
hamna.khalid@snhu.edu

### Submitted To:

**Professor Sherif Antoun**
s.antoun@snhu.edu

Southern New Hampshire University
Monday, April 20, 2026


This repository contains coursework from CS-320 at Southern New Hampshire University.

## Contents
- Contact Service
- Task Service
- Appointment Service
- Unit Testing with JUnit

## Technologies Used
- Java
- JUnit 5
- HashMap
- Defensive Validation

# Repository Overview

This repository contains selected artifacts from **CS 320: Software Test, Automation, and Quality Assurance**. The included files demonstrate my ability to implement backend validation logic, design unit tests using JUnit, analyze software testing approaches based on requirements, and reflect on testing strategies and quality assurance practices.

Included Artifacts:

* Contact.java
* ContactService.java
* ContactTest.java
* ContactServiceTest.java
* Project Two: Summary and Reflections Report

Together, these artifacts showcase both technical implementation and analytical reflection on testing methodologies.


# Reflection

## How can I ensure that my code, program, or software is functional and secure?

I ensure functionality and security through structured unit testing, strict validation logic, and defensive programming principles. In Project One, all data models enforced constraints at the constructor level to prevent invalid states. For example, contact IDs were restricted in length and made immutable, while phone numbers were validated to ensure correct formatting.

Functionality was verified using JUnit tests that covered both valid inputs and invalid edge cases. I used `assertThrows()` to confirm that exceptions were properly triggered when requirements were violated. This ensured that incorrect data could not silently enter the system.

Security in foundational systems begins with preventing invalid inputs and enforcing predictable behavior. By combining input validation with automated testing, I reduced the risk of unexpected runtime failures and improved overall system reliability.



## How do I interpret user needs and incorporate them into a program?

Interpreting user needs begins with careful requirement analysis and direct translation of those requirements into enforceable code constraints. In Project One, the specifications clearly defined field lengths, immutability rules, and validation requirements. Instead of treating those as suggestions, I encoded them directly into constructors and service-layer methods.

For example:

* Contact IDs were limited to 10 characters and made non-updatable.
* Phone numbers were restricted to exactly 10 digits.
* Null values were explicitly rejected.

By mapping each requirement to a corresponding validation rule and test case, I ensured traceability between user expectations and program behavior. This approach minimizes ambiguity and strengthens reliability.



## How do I approach designing software?

My approach to designing software follows a structured process:

1. Analyze and clarify requirements.
2. Design clear data models with enforced constraints.
3. Separate concerns between data classes and service classes.
4. Implement validation at the lowest possible level.
5. Develop unit tests to verify both functional and edge-case behavior.
6. Refactor only after tests confirm stability.

Throughout this course, I adopted a test-aware mindset. Rather than writing code first and testing afterward, I considered how each method would be validated during implementation. This approach promotes clarity, maintainability, and disciplined development.

I also prioritized efficiency and readability. Using a HashMap for service-level storage provided constant-time access while keeping logic straightforward and easy to test.

---

# What This Repository Demonstrates

* Object-oriented design principles.
* Requirement-driven validation.
* Automated unit testing using JUnit.
* Exception-based error handling.
* Reflection on testing strategies and automation concepts.
* Awareness of software quality assurance practices.

This repository represents foundational competency in backend service validation, automated testing, and disciplined engineering practices.

---

# AI Acknowledgment

Generative AI tools were used to assist in refining written reflections for clarity, organization, and formatting. All technical implementations, design decisions, and testing strategies reflect my independent work completed throughout the course.
