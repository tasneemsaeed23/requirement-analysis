# requirement-analysis
# Requirement Analysis in Software Development

This repository contains documentation and examples related to the Requirement Analysis phase in the Software Development Life Cycle (SDLC). It focuses on a case study of a booking management system and illustrates how to gather, analyze, and define requirements for building robust software.

## Why is Requirement Analysis Important?

- **Clarity and Alignment:** Helps stakeholders and developers have a shared understanding of what the software will do.
- **Prevents Rework:** Well-defined requirements reduce the chance of costly changes later in development.
- **Scope Management:** Clearly defines what’s in and out of scope, helping avoid scope creep.

## Key Activities in Requirement Analysis

- **Requirement Gathering:** Collecting raw data and inputs from stakeholders via interviews, surveys, etc.
- **Requirement Elicitation:** Clarifying and refining gathered information using techniques like brainstorming and prototyping.
- **Requirement Documentation:** Structuring and recording the requirements in formal documents.
- **Requirement Analysis and Modeling:** Breaking down and modeling requirements using diagrams and use cases.
- **Requirement Validation:** Reviewing the requirements with stakeholders to ensure correctness and feasibility.


## Types of Requirements

### Functional Requirements
These define what the system should do.

**Examples:**
- Users can register and log in.
- Admin can approve or reject booking requests.
- System sends confirmation emails after successful booking.

### Non-functional Requirements
These define how the system should perform.

**Examples:**
- The system should load pages within 2 seconds.
- User data must be encrypted and stored securely.
- The system should support 500 concurrent users.

## Use Case Diagrams

Use Case Diagrams visualize the interactions between users (actors) and the system. They help clarify the functionality from the user’s perspective and define the system boundaries.

![Use Case Diagram](alx-booking-uc.png)

## Acceptance Criteria

Acceptance Criteria define the specific conditions a feature must meet to be accepted by stakeholders. It helps developers understand exactly what is expected and reduces ambiguity.

**Example (Checkout Feature):**

- User must be logged in to proceed to checkout.
- The system should display booking summary including dates and prices.
- Payment must be processed via integrated payment gateway.
- A confirmation email is sent upon successful booking.


