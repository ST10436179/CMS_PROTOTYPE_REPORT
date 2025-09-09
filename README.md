# Contract Monthly Claim System (CMCS) - Part 1

## Student Information
- **Name:** Luthando Didiza
- **Student Number:** ST10436179
- **Module:** PROGRAMMING 2B (PROG6212)
- **Date:** 9 September 2025

## Project Overview
This repository contains Part 1 of the Contract Monthly Claim System (CMCS) - Project Planning and Prototype Development. This phase focuses on creating a non-functional prototype including design documentation, UML diagrams, and a WPF interface prototype.

## 📋 Deliverables
- Design documentation report (400-500 words)
- UML class diagram for database structure
- Project plan with timeline and dependencies
- WPF GUI prototype (non-functional)
- Version control history with 5+ commits

## 🗃️ Database Structure
The system uses a relational database model with three main entities:

### Classes and Attributes:
- **User** (UserId PK, Name, Email, PasswordHash, Role)
- **Claim** (ClaimId PK, UserId FK, HoursWorked, HourlyRate, TotalAmount, Status, SubmissionDate, ApprovalDate)
- **Document** (DocumentId PK, ClaimId FK, FileName, FilePath, UploadDate)

### Relationships:
- One User (Lecturer) → Many Claims
- One Claim → Many Documents

## 🖥️ GUI Prototype Features
- **Lecturer Submit Tab:** Claim submission form with hours worked, hourly rate, notes, and file upload
- **Approver View Tab:** ListView showing claims with Approve/Reject buttons
- **Track Status Tab:** DataGrid displaying claim history with status labels


## 📅 Project Timeline

| Task ID | Description | Dependencies | Effort | Timeline |
|---------|-------------|--------------|--------|----------|
| 1 | Research Requirements | None | 2 hours | Day 1 |
| 2 | Design UML Diagram | Task 1 | 3 hours | Day 1-2 |
| 3 | Develop Project Plan | Task 1 | 1 hour | Day 2 |
| 4 | Build WPF Prototype | Task 2 | 6 hours | Day 3-4 |
| 5 | Final Documentation | Tasks 2-4 | 3 hours | Day 5 |
