Batch Payroll Application
📘 Overview

The Batch Payroll Application automates the process of calculating and distributing employee salaries based on their work type, commissions, and applicable deductions.
This system ensures accurate, efficient, and timely payroll processing for different categories of employees — Hourly, Salaried, and Commission-based.

🎯 Purpose

The purpose of this system is to:

Simplify payroll management.

Ensure accurate salary and payment calculations.

Automate repetitive payroll operations.

Provide reporting and integration with external payroll systems.

👥 Actors
Actor	Description
Employee	The main user who submits work-related data (like timecards or sales receipts) and receives payments.
Union	Represents labor unions that can add dues or service charges applicable to unionized employees.
Payroll System	External system used to process payroll, apply deductions, and distribute payments.
🧩 Employee Types
Employee Type	Description
Hourly Employee	Paid based on hours worked. Submits timecards and may receive overtime pay.
Salaried Employee	Receives a fixed salary on a regular schedule.
Commission Employee	Receives base salary plus commission from sales.
⚙️ Main Use Cases
Use Case	Description
Submit Timecard	Hourly employees submit their working hours for payment calculation.
Submit Sales Receipt	Commission employees submit their sales records for commission calculation.
Overtime Calculation	Calculates overtime pay for hourly employees exceeding standard hours.
Commission Calculation	Computes commission-based earnings for sales staff.
Salary Calculation	Calculates base salary for salaried and commission employees.
Calculate Payment	Central use case that integrates salary, overtime, and commission calculations.
Apply Deductions	Deducts union dues, service charges, and other deductions.
Process Payroll	Manages the payroll run by combining all calculations and deductions.
Generate Report	Produces payroll reports for review and audit.
Distribute Payment	Handles final payment distribution via mail or direct deposit.
💵 Payment Distribution Methods

Hold for Pickup — Employee collects payment manually.

Mail Paycheck — Payment is sent via post.

Direct Deposit — Payment is transferred electronically to the employee’s bank account.

🔄 Relationships in the Diagram

Include (→): Indicates mandatory behavior (e.g., Process Payroll → includes Apply Deductions).

Extend (---): Indicates optional or conditional actions (e.g., Generate Report may extend payroll processing).

Generalization: Employee is a general actor for subtypes (Hourly, Salaried, Commission).

🗂️ Workflow Summary

Employees submit work data (timecards or sales receipts).

The system performs salary, overtime, and commission calculations.

Union dues and deductions are applied.

Payroll is processed, reports are generated.

Payments are distributed via selected methods.

Payroll system ensures accuracy and compliance.

📄 Diagram Reference

The included Use Case Diagram visually represents the interaction between:

Actors (Employee, Union, Payroll System)

Use Cases (Payroll processing steps)

Relationships (Includes, Extends, and Associations)
