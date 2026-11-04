# SRE-GITHUB-LAB
Requirements documentation for a Student Task Tracker

# Pharmacy Management System

## 1. Project Overview

The Pharmacy Management System is a software project designed to manage the daily operations of a pharmacy efficiently.

In traditional pharmacy management, maintaining medicine records, checking available stock, and recording medicine sales manually can be time-consuming and may lead to errors.

The purpose of this system is to help pharmacy administrators and staff manage medicine inventory, monitor stock availability, and maintain sales records in an organized way.

The system aims to reduce manual work, improve record accuracy, and make pharmacy operations more efficient.

**Target Users:**
- Pharmacy Administrators
- Pharmacists
- Pharmacy Sales Staff

## 2. Project Scope

### In Scope

- **Medicine Inventory Management:** The system shall allow authorized staff to add and manage medicine records, including medicine name, price, and available quantity.
- **Medicine Search:** The system shall allow staff to search for medicines by their names.
- **Sales Management:** The system shall allow staff to record medicine sales and update the available stock accordingly.
- **Stock Monitoring:** The system shall allow staff to check the available quantity of medicines.

### Out of Scope

- Online medicine ordering and home delivery.
- Online payment processing through banks or digital wallets.
- Automatic diagnosis or medical recommendations.

## 3. Stakeholders

- **Pharmacy Administrator:** Responsible for managing pharmacy operations, monitoring inventory, and maintaining pharmacy records.
- **Pharmacist:** Interested in checking medicine availability, accessing medicine information, and ensuring accurate medicine records.
- **Sales Staff:** Responsible for recording medicine sales and updating stock quantities.
- **Project Maintainer/Developer:** Responsible for maintaining project documentation, reviewing requirements, and managing project changes.
- **Customers:** Interested in receiving accurate information about medicine availability and prices.

## 4. Functional Requirements

- **FR-01: Medicine Registration**

  The system shall allow an authorized pharmacy staff member to add a new medicine record by entering its name, price, and available quantity.

- **FR-02: Medicine Search**

  The system shall allow pharmacy staff to search for a medicine by entering its name and display the matching medicine information.

- **FR-03: Medicine Sales and Stock Update**

  The system shall allow pharmacy staff to record a medicine sale and automatically decrease the available stock quantity according to the quantity sold.

## 5. Non-Functional Requirements

- **NFR-01: Performance**

  The system shall display medicine search results within 2 seconds in at least 95 out of 100 trials when the database contains up to 1,000 medicine records on the agreed test device.

- **NFR-02: Usability**

  A pharmacy staff member who has received basic system training shall be able to complete the medicine registration and medicine search workflows within 2 minutes each in at least 9 out of 10 usability trials.

- **NFR-03: Data Accuracy**

  The system shall maintain accurate medicine stock quantities, and every successfully recorded sale shall update the corresponding stock quantity correctly.

## 6. Acceptance Criteria

- **FR-01: Medicine Registration**

  Given that an authorized staff member enters the medicine name, price, and quantity, when the staff member saves the record, then the new medicine shall appear in the medicine inventory with the entered information.

- **FR-02: Medicine Search**

  Given that a medicine exists in the inventory, when staff enter its name in the search field, then the system shall display the matching medicine information.

- **FR-03: Medicine Sales and Stock Update**

  Given that a medicine has 50 units available, when staff record a sale of 5 units, then the available stock shall decrease to 45 units.

## 7. Assumptions and Open Questions

### Assumptions

- **A-01:** The pharmacy staff will have access to the system through an authorized device.
- **A-02:** Medicine information, including names, prices, and quantities, will be entered by authorized pharmacy staff.
- **A-03:** The pharmacy will maintain medicine inventory records using the system.

### Open Questions

- **Q-01:** Should the system support different user roles with separate access permissions?
- **Q-02:** Should the system generate automatic alerts when medicine stock becomes low?
- **Q-03:** Should the system maintain medicine expiry dates and notify staff about expired medicines?
- **Q-04:** Which database and operating environment will be used for the final implementation?

## 8. Project Status and Usage

**Current Status:** Documentation Only.

This project currently focuses on software requirements and project documentation. Application implementation has not started.

### How to Obtain the Project Files

1. Open the project's GitHub repository.
2. Select the Code option.
3. Copy the repository HTTPS URL.
4. Run the following command in Git Bash:

   `git clone YOUR-REPOSITORY-URL`

5. Open the downloaded project folder.

### How to View the README

- Open README.md using Visual Studio Code or another Markdown-compatible editor.
- Alternatively, visit the GitHub repository and open the rendered README.md file.

No application installation or execution is currently required.

## 9. Author

- **Student Name:** [Your Full Name]
- **Course:** Software Requirement Engineering (SEF25)
- **Department:** Software Engineering
- **Institution:** University of the Punjab, Lahore, Pakistan

## 10. Contributing

Contributions and documentation improvements should follow the Git workflow:

1. Create or switch to a separate documentation branch.
2. Make the required changes to README.md.
3. Review the changes before staging.
4. Stage the updated documentation using `git add`.
5. Commit changes with a meaningful commit message.
6. Push the branch to the GitHub remote repository.
7. Open a pull request to propose merging the changes into the main branch.
8. Review the proposed changes before merging.

All documentation changes should be reviewed to maintain clarity, consistency, and accuracy of project requirements.
