# SAP ABAP Cloud Developer — Complete Learning Syllabus

> **Goal:** Go from SAP beginner to a job-ready junior SAP ABAP / ABAP Cloud developer, build portfolio projects, and prepare for SAP-related opportunities in Japan.

## Phase 1 — SAP Foundations

- [x] **Lesson 1: Introduction to SAP and ERP**
  - [x] ERP meaning and business-process integration
  - [x] SAP company, SAP S/4HANA overview
  - [x] SAP functional areas: FI, CO, MM, SD, PP, HCM
  - [x] ABAP and ABAP Cloud introduction
  - [x] Business scenario: sales vs inventory vs finance
  - [x] MCQ and scenario-based revision
- [x] **Lesson 2: SAP System Architecture**
  - [x] Presentation, application, database layers
  - [x] SAP Fiori, SAP GUI, SAP HANA overview
  - [x] Application server, dispatcher, work processes
  - [x] Dialog vs background processing
  - [x] Eclipse IDE and ABAP Development Tools (ADT)
  - [x] DEV, QAS, PRD system landscape
  - [x] Transport requests and controlled deployment
  - [x] End-to-end supermarket reporting scenario and final test
- [ ] **Lesson 3: ABAP Basics** 🚧
  - [ ] ABAP class-run structure and `if_oo_adt_classrun`
  - [ ] Statements, comments, identifiers, literals
  - [ ] `DATA`, `CONSTANTS`, inline declarations
  - [ ] Elementary types: `i`, `string`, `c`, `d`, `p`, decimals
  - [ ] Assignments, operators, calculations, string templates
  - [ ] Output with `out->write( )`
  - [ ] Practical: supermarket bill calculator
  - [ ] Quiz, coding exercise, corrections and retest

## Phase 2 — Core ABAP Programming

- [ ] **Lesson 4: Conditions and Decisions** — `IF`, `ELSEIF`, `ELSE`, `CASE`, comparison and logical operators; stock validation exercise
- [ ] **Lesson 5: Loops** — `DO`, `WHILE`, `LOOP AT`, `EXIT`, `CONTINUE`; repetitive calculations
- [ ] **Lesson 6: Strings, Dates and Numeric Handling** — formatting, conversions, rounding, business-safe decimal arithmetic
- [ ] **Lesson 7: Internal Tables** — standard/sorted/hashed tables, table expressions, `APPEND`, `INSERT`, `READ TABLE`, `FILTER`, `VALUE`, `FOR`
- [ ] **Lesson 8: Structures and Types** — `TYPES`, work areas, nested structures, typed data models
- [ ] **Lesson 9: Modular Programming** — methods, parameters, returning values, reusable code
- [ ] **Lesson 10: Object-Oriented ABAP** — classes, objects, constructors, visibility, interfaces, inheritance, polymorphism
- [ ] **Lesson 11: Error Handling and Debugging** — exceptions, `TRY...CATCH`, breakpoints, variable inspection, debugging workflow
- [ ] **Phase 2 practical:** Inventory and billing logic with internal tables, methods, validations, and tests
- [ ] **Phase 2 checkpoint:** MCQ + independent coding assessment

## Phase 3 — SAP Development Environment and Data

- [ ] **Lesson 12: SAP BTP and ABAP Environment** — accounts, entitlements/trial availability, landscape concepts, access limitations
- [ ] **Lesson 13: Eclipse + ADT Hands-on** — connect to an authorized ABAP system, packages, classes, activation, execution, debugging
- [ ] **Lesson 14: ABAP Dictionary and Data Modeling** — tables, fields, data elements, domains (conceptual and system-specific usage)
- [ ] **Lesson 15: ABAP SQL** — `SELECT`, `WHERE`, `JOIN`, aggregations, ordering, host variables, performance basics
- [ ] **Lesson 16: Core Data Services (ABAP CDS)** — view entities, associations, annotations, analytical and transactional use cases
- [ ] **Lesson 17: Authorization and Data Access** — roles, authorization checks, least privilege, safe handling of business data
- [ ] **Phase 3 practical:** Product/stock read-only report using available released data sources or a sandbox model
- [ ] **Phase 3 checkpoint:** Build, execute, and explain a data-backed ABAP solution

## Phase 4 — Modern ABAP Cloud Development

- [ ] **Lesson 18: ABAP Cloud Principles** — cloud-ready code, clean core, released APIs, supported ABAP language scope
- [ ] **Lesson 19: Packages and Software Components** — development organization, dependencies, naming, release contracts
- [ ] **Lesson 20: RAP Fundamentals** — RESTful Application Programming Model, business objects, service architecture
- [ ] **Lesson 21: RAP Data Modeling** — CDS entities, behavior definitions, managed vs unmanaged scenarios
- [ ] **Lesson 22: RAP Business Logic** — validations, determinations, actions, save lifecycle, authorization
- [ ] **Lesson 23: OData Services** — service definitions, service bindings, API exposure, testing
- [ ] **Lesson 24: SAP Fiori Elements** — metadata-driven UI, list reports, object pages, annotations
- [ ] **Lesson 25: Extensibility** — key-user vs developer extensibility, side-by-side vs on-stack choices
- [ ] **Phase 4 practical:** CRUD business application using RAP + Fiori elements where system access permits
- [ ] **Phase 4 checkpoint:** Demonstrate a working business object with validation and UI/API

## Phase 5 — Engineering Practices and Integration

- [ ] **Lesson 26: Testing ABAP** — ABAP Unit, test doubles, testable design, regression checks
- [ ] **Lesson 27: Performance** — efficient SQL, table choices, avoiding unnecessary database calls, profiling basics
- [ ] **Lesson 28: APIs and Integration** — HTTP, REST, OData, JSON, released SAP APIs, authentication concepts
- [ ] **Lesson 29: Security and Quality** — authorization, secure coding, code checks, ATC, clean code
- [ ] **Lesson 30: Transports and Deployment** — transport concepts, cloud-specific tooling, change approval and release flow
- [ ] **Lesson 31: Git and Documentation** — GitHub README, branches, commits, issue tracking, screenshots, architecture notes
- [ ] **Phase 5 practical:** Tests, documentation, and quality checks for an earlier project

## Phase 6 — Portfolio Projects

- [ ] **Project 1: Supermarket Inventory Tracker** — products, quantities, stock threshold checks, low-stock reporting
- [ ] **Project 2: Purchase Order / Procurement Workflow** — suppliers, purchase requests, order status, validations
- [ ] **Project 3: Employee Leave Management** — leave requests, approvals, balances, role-based access
- [ ] **Capstone: RAP Business Application** — CDS data model, behavior, OData service, Fiori elements UI, unit tests, documentation
- [ ] Add screenshots or demo recordings (no confidential company data)
- [ ] Add architecture diagrams and explanation of design choices
- [ ] Add setup steps, known limitations, and tests to each project README
- [ ] Review and refactor projects based on feedback
