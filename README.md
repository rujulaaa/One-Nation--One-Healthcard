# One Nation, One Health Card

> A healthcare records platform designed to centralize patient data across providers, built as part of a Software Engineering course (CSE3001) at VIT.

---

## What This Project Is

India's healthcare system is fragmented — patients carry paper records, test results get lost between hospitals, and there's no unified way for providers to access a patient's history. This project is a prototype for a national health card system that gives every citizen a single digital health record accessible across providers.

We designed the full system from requirements through architecture, built a working prototype with Django and PostgreSQL, and documented everything in a formal Software Requirements Specification.

---

## What We Built

**Backend:** Django (Python) with PostgreSQL for patient record storage. REST API endpoints handle data exchange between the frontend, backend, and external notification services.

**Authentication:** Twilio OTP-based verification so patients can securely access their records.

**System Design:** Full UML class diagrams, ER models, sequence diagrams, use case diagrams, and data flow diagrams created in IBM Rational Rose and yEd.

**Documentation:** A complete SRS covering functional requirements, non-functional requirements (scalability, reliability, security), validation criteria, and a test case suite.

**Process:** Agile methodology with iterative review cycles and stakeholder feedback at each stage. All artifacts version-controlled via Git.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend Framework | Django (Python) |
| Database | PostgreSQL |
| APIs | REST APIs for data integration |
| Notifications | Twilio (OTP-based authentication) |
| System Modeling | IBM Rational Rose, yEd (UML, ER diagrams) |
| Version Control | Git / GitHub |

---

## Key Features

- Centralized patient health records accessible across hospitals and clinics
- REST API endpoints for secure data exchange between services
- OTP-based patient authentication via Twilio
- Role-based access so doctors, patients, and admins see different views
- Designed with scalability and data security as core requirements

---

## Documentation

The `CSE3001 J comp_merged.pdf` in this repo contains the full Software Requirements Specification, including:

- System architecture and design rationale
- UML diagrams (class, sequence, use case, activity)
- ER model and database schema
- Non-functional requirements (performance, security, scalability)
- Test case suite and validation criteria
- Process flow diagrams

---

## What I Learned

This was my first time leading a system design effort from requirements gathering through to a working prototype. The biggest takeaway was how much of software engineering happens before you write any code — getting the requirements right, mapping out the data flows, and making sure the architecture can handle what you're asking it to do. The SRS documentation alone was more work than the actual coding, and that's probably how it should be.

---

## Course Context

**Course:** CSE3001 — Software Engineering, Vellore Institute of Technology  
**Duration:** July — November 2023  
**Team Size:** Group project  
**My Role:** Led system design, requirements gathering, SRS documentation, and stakeholder review cycles
