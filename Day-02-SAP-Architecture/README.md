# Day 02 — SAP System Architecture

## Learning objectives
- Understand SAP's three-tier architecture.
- Explain the ABAP application server, dispatcher and work processes.
- Identify Eclipse IDE, ABAP Development Tools (ADT) and the connected SAP ABAP system.
- Distinguish system architecture from system landscape.
- Understand the typical DEV → QAS → PRD workflow and transport requests.

## 1. Three-tier architecture

| Layer | Purpose | Examples |
|---|---|---|
| Presentation | User interaction | SAP Fiori, SAP GUI |
| Application | Business logic and processing | ABAP application server |
| Database | Data persistence and retrieval | SAP HANA in SAP S/4HANA |

**Example:** A cashier sells 5 kg of rice. The presentation layer captures the sale; application logic validates and processes it; the database persists relevant transactions and stock updates.

## 2. ABAP application server
- **Dispatcher:** Distributes requests to available work processes.
- **Dialog work process:** Processes interactive user requests.
- **Background work process:** Executes non-interactive scheduled jobs.
- A system may have multiple application server instances.

## 3. ABAP development environment
- **Eclipse IDE:** Desktop development interface.
- **ADT (ABAP Development Tools):** Eclipse-based tools to create, edit, activate and debug ABAP objects.
- **Connected SAP ABAP system:** Where ABAP code is activated and executed.
- **ABAP Cloud:** A modern ABAP development model using supported language features and released APIs; not a fourth architecture tier.

## 4. SAP system landscape

| System | Role |
|---|---|
| DEV | Develop and initially test changes |
| QAS | Test and validate changes |
| PRD | Run approved changes for business users |

Typical flow: **DEV → QAS → PRD**. Actual landscapes and deployment tooling vary by SAP product and organization.

### Transport requests
In traditional SAP landscapes, transport requests organize development or configuration changes for release and import between systems. They are not the same as GitHub commits.

## 5. Practical scenario — low-stock report
**Requirement:** Show products with stock strictly below 10 units.

1. Create ABAP report logic in DEV using appropriate authorized data access.
2. Test values in QAS: 5 and 9 should appear; 10 and 25 should not.
3. Deploy approved changes to PRD using the organization's process.
4. Optionally schedule report generation as a background job if supported by the environment.

## 6. Key distinction
- **Architecture:** Components and responsibilities *inside* an SAP system.
- **Landscape:** Separate systems/environments used to develop, test and run changes.

## Assessment
- Part 1 quiz: **5/5**
- Part 2 quiz: **5/5**
- Final assessment: **9/10 — Passed**

## Next lesson
**Day 03 — ABAP Basics:** Syntax, comments, variables, data types, output and simple calculations.
