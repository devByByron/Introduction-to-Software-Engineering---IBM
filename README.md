# Introduction-to-Software-Engineering - IBM

Course Structure Overview
The course is organized into five modules:

The Software Development Lifecycle

Introduction to Software Development

Basics of Programming

Software Architecture, Design, and Patterns

Job Opportunities and Skillsets in Software Engineering


What is Software Engineering?

Definition: Applying scientific principles to design, build, and test software systematically.

Purpose: Collect and analyze business requirements → create reliable software solutions.

History & Evolution

1950s–1960s: Software development was ad hoc, with no formal process.

1960s–1980s: “Software Crisis” — projects ran over budget, behind schedule, and produced buggy, unscalable code.

Solution: Introduce engineering discipline → structured methods, CASE (Computer-Aided Software Engineering) tools.

CASE Tools Categories:

Business analysis & modeling

Development tools (e.g., debugging)

Verification & validation

Configuration management

Metrics & measurement

Project management

Software Engineer vs. Software Developer

Software Engineer:

Broader scope, system-level focus

Designs, builds, maintains whole systems

Responsibilities: writing/testing code, consulting with clients, vendors, security specialists, and team members

Works mainly on large-scale projects

Software Developer:

Narrower focus, implements specific functionality

Often more creative problem-solving on smaller parts of the system

Key Difference: Engineers = big-picture/system-wide approach; Developers = code/functionality focus.

Modern Practices

Guided by Software Development Lifecycle (SDLC) to ensure quality and scalability.

SDLC = structured phases to build high-quality software.

**Phases of the Software Development Life Cycle (SDLC)**

<img width="241" height="283" alt="image" src="https://github.com/user-attachments/assets/dcde7e75-52b1-4b2d-829a-21aa5923d114" />


Planning Phase

Requirements are gathered, analyzed, documented, and prioritized.
Factors such as user needs, project purpose, compliance, and resource allocation are considered.
Design Phase

The software architecture is developed based on the requirements from the Software Requirements Specification (SRS).
Prototypes may be created for demonstration and feedback, and a design document is produced for developers.
Development Phase

Coding begins once the design document is completed, with tasks assigned to developers.
Various programming tools and languages are utilized, adhering to organizational standards.
Testing Phase

Code is thoroughly tested to ensure stability, security, and compliance with the SRS.
Different testing levels, such as unit and integration testing, are conducted to identify and fix bugs.
Deployment Phase

The application is released into the production environment, often in stages.
User acceptance testing (UAT) is performed before final release to ensure functionality.
Maintenance Phase

Post-deployment, the software is monitored for bugs and user interface issues.
Feedback is collected for future enhancements, and the cycle may restart as needed.

**Building Quality Software – Key Points**
1. Requirements Gathering

Collect and document everything the software must do.

Stored in an SRS (Software Requirements Specification).

Categories of requirements:

Functional (what it does)

UI / external requirements

System features

Non-functional (performance, security, etc.)

2. Design

Turns requirements into a blueprint developers can code.

Defines system architecture: components, their roles, and how they interact.

Includes: business rules, APIs, UI design, database design, performance, and security.

3. Coding for Quality

Write clean, consistent, maintainable, and secure code.

Practices:

Follow coding standards & patterns

Use linters (tools that detect style or code issues)

Add meaningful comments

Goal: Code that meets requirements, is easy to read, test, and maintain.

4. Testing

Verifies software matches requirements and is bug-free.

Ensures reliability, performance, and security.

Levels of testing:

Unit (smallest pieces, by developers)

Integration (how components work together)

System (whole product)

User Acceptance / Beta testing (by end users)

Types of testing: Functional, Non-functional, Regression.

5. Releases

Versions of software given to users:

Alpha → early version for internal stakeholders, incomplete and buggy.

Beta → for external stakeholders, functional but still tested in real conditions.

GA (General Availability) → final, stable release for all users.

6. Documentation

Explains how to use and maintain the software.

System documentation (for technical users): architecture, design, code comments, guides.

User documentation (for non-technical users): manuals, help files, videos, tutorials.


**Welcome to Requirements**

By the end of this lesson, you’ll be able to:

Understand the steps of the requirements gathering process.

Explain what a User Requirement Specification (URS) is.

Explain what a Software Requirement Specification (SRS) is.

Explain what a System Requirement Specification (SysRS) is.

The Requirements Gathering Process

Requirements gathering is all about figuring out the problem to solve and then clearly documenting how to solve it. It usually follows six steps:

Identify stakeholders – the people who care about or are affected by the product (decision-makers, end-users, admins, sales, support, etc.).

Define goals – the big-picture outcomes you want to achieve (e.g., happier customers, increased sales).

Set objectives – more specific, measurable steps that support those goals.

Elicit requirements – gather input from stakeholders using surveys, interviews, or workshops.

Document requirements – write them down in a clear, easy-to-understand way.

Confirm and prioritize – check for clarity, consistency, and completeness, then label requirements as must-have, highly desired, or nice-to-have.

The Three Main Documents

From this process, three key documents may be created:

1. Software Requirement Specification (SRS) – the most common

Describes what the software should do and how it should perform.

Includes:

Purpose & scope – what the product is for, who will use it, and its overall goals.

Constraints, assumptions, dependencies – technical limits, required platforms, or other software it depends on.

Requirements, grouped into:

Functional – core features and functions.

External interface – how it interacts with users, hardware, or other systems.

System features – must-have functions to make it work.

Non-functional – performance, security, quality, safety, etc.

2. User Requirement Specification (URS)

Focuses on the needs and expectations of the end-user.

Usually written as user stories or use cases, answering:

Who is the user?

What do they want to do?

Why do they want it?

Validated through user acceptance testing.

Sometimes merged into the SRS for simplicity.

3. System Requirement Specification (SysRS)

Broader than the SRS – covers the entire system, not just the software.

Includes:

System capabilities and interfaces.

Hardware requirements.

Policy, regulatory, and security requirements.

Performance expectations.

Personnel and operational needs.

System acceptance criteria.


**Software Development Methodologies Overview**

There are many ways to approach software development. Three commonly used Software Development Life Cycle (SDLC) methods are:

1. Waterfall Model

Sequential approach: each phase must finish before the next starts.

Customer sees the product only during testing.

Long release cycles (months/years).

✅ Pros: Simple, easy to follow, clear roles, upfront planning helps with budgeting.

❌ Cons: Inflexible, hard to adapt to changing requirements, late customer feedback.

2. V-Shape Model

Sequential like waterfall, but shaped like a V.

Left side = verification (planning → system design → architecture design → module design).

Bottom = coding.

Right side = validation (unit testing → integration testing → system testing → acceptance testing).

✅ Pros: Simple, emphasizes testing (test plans are made early).

❌ Cons: Rigid, difficult to accommodate changes, expensive to fix issues late.

3. Agile Model

Iterative and cyclical approach with short sprints (1–4 weeks).

Working code delivered frequently in sprint demos for stakeholder feedback.

Produces a Minimum Viable Product (MVP) quickly.

Guided by the Agile Manifesto values:

Individuals & interactions > processes & tools

Working software > documentation

Customer collaboration > contract negotiation

Responding to change > following a plan

✅ Pros: Flexible, adapts to changes, frequent feedback, faster delivery of usable features.

❌ Cons: Hard to plan long-term scope, budget, and schedule; requires strong collaboration.

🔑 Key Differences

Waterfall & V-Shape = Sequential, customer feedback comes late.

Agile = Iterative, customer feedback is continuous.

Waterfall & V-Shape = stable planning but rigid.

Agile = flexible but harder to predict costs/scope.

**Software Testing**

Purpose of Software Testing

Ensures the software matches expected requirements.

Helps deliver error-free software.

Uses test cases (steps, inputs, data, expected outputs).

Types of Testing

Functional Testing

Black-box testing → focuses on inputs and outputs, not source code.

Verifies functional requirements.

Ensures usability, accessibility, and proper handling of edge cases/errors.

Non-Functional Testing

Tests system attributes: performance, scalability, security, availability.

Example questions:

How does the app perform under stress?

Is it secure?

Does it behave consistently across platforms?

How is disaster recovery handled?

Regression Testing (Maintenance Testing)

Ensures new changes (bug fixes, requirement updates) don’t break existing features.

Prioritizes test cases based on frequent defects, recent changes, critical functionality, and complexity.

Testing Levels

Unit Testing

Verifies small sections of code (functions, methods).

Done by developers early in the SDLC.

Eliminates construction errors before integration.

Integration Testing

Tests how independent modules interact.

Exposes bugs from poor communication between modules/databases/external systems.

System Testing

Performed on the complete, integrated system.

Both functional and non-functional.

Conducted in a staging environment similar to production.

Acceptance Testing

Formal testing by customers/stakeholders.

Ensures software meets business requirements and user needs.

Typically done during the maintenance stage.

