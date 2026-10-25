# Day 01 — SAP & ERP Fundamentals

## Learning Objectives
- Understand ERP and why businesses use it.
- Distinguish SAP, ERP, and SAP S/4HANA.
- Identify common SAP functional areas.
- Understand the roles of ABAP and ABAP Cloud.
- Explain how sales, inventory, and finance processes connect.

## 1. What is ERP?
**Enterprise Resource Planning (ERP)** software integrates business processes such as sales, purchasing, inventory, finance, and HR, allowing departments to work with consistent information.

**Example:** A supermarket sells eight biscuit packets. The sales transaction captures the items and amount, inventory reflects eight fewer packets, and finance records the cash received.

## 2. What is SAP?
SAP is a German enterprise software company. **SAP S/4HANA** is an ERP product family from SAP, designed for the SAP HANA database.

| Term | Meaning |
| --- | --- |
| ERP | Category of integrated business management software |
| SAP | Enterprise software company |
| SAP S/4HANA | SAP ERP product family |

## 3. Common SAP Functional Areas
| Area | Focus |
| --- | --- |
| FI | Financial Accounting |
| CO | Controlling and costs |
| MM | Materials Management and purchasing |
| SD | Sales and Distribution |
| PP | Production Planning |
| HCM / HR | Human resources processes |

These are commonly used names; product capabilities and naming vary by SAP solution.

## 4. ABAP vs. ABAP Cloud
- **ABAP**: SAP's programming language for business applications.
- **ABAP Cloud**: Modern development model using supported language features and released APIs for upgrade-stable applications and extensions.
- **Eclipse + ABAP Development Tools (ADT)**: Common environment for modern ABAP development.

### Example ABAP class (not yet executed)
```abap
CLASS zcl_hello_world DEFINITION
  PUBLIC
  FINAL
  CREATE PUBLIC.

  PUBLIC SECTION.
    INTERFACES if_oo_adt_classrun.
ENDCLASS.

CLASS zcl_hello_world IMPLEMENTATION.
  METHOD if_oo_adt_classrun~main.
    out->write( 'Hello, SAP World!' ).
  ENDMETHOD.
ENDCLASS.
```

> This is a learning example. Execution requires a suitable ABAP development system.

## 5. Key Takeaways
1. ERP integrates business processes and information.
2. Sales records the transaction, inventory tracks stock, and finance accounts for payment.
3. ABAP developers build or extend SAP business functionality.
4. Business-process understanding is as important as code.

## Assessment Progress
- Fundamentals quiz: **10/10**
- Initial practical assignment: **13/20**
- Correction exercise: **5/5**
- **Lesson 1 completed** after successfully correcting the initial gaps.

## Next Lesson
**Day 02 — SAP System Architecture:** presentation, application, and database layers.
