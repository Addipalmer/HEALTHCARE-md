## SYSTEM DIAGRAM
```mermaid
graph TD

Practical Lab: Healthcare Portal Modernization


1. Domain Context Mapping

The legacy healthcare portal can be divided into three bounded contexts:

Bounded Context

Primary Entities

Main Responsibility

Patient Care Context

Patient, Appointment, Doctor, Medical Record

Manages patient information, appointments, and patient care

Billing & Insurance Context

Bill, Payment, Insurance Claim, Insurance Provider

Manages patient bills, payments, and insurance claims

Diagnostics Context

Lab Test, Lab Result, Test Request, Laboratory

Manages laboratory tests and patient test results


A. Patient Management

Bounded Context: Patient Care Context

Primary entities:

* Patient
* Doctor
* Appointment
* Medical Record

Purpose: To manage patient information, appointments, and healthcare services.

B. Billing & Insurance Claims

Bounded Context: Billing & Insurance Context

Primary entities:

* Bill
* Payment
* Insurance Claim
* Insurance Provider

Purpose: To manage billing, payments, and insurance claims.

C. Lab Test Diagnostics

Bounded Context: Diagnostics Context

Primary entities:

* Lab Test
* Test Request
* Lab Result
* Laboratory

Purpose: To manage laboratory tests and provide patients and doctors with test results.

```
