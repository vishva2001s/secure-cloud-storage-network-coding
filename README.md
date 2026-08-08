# Secure Cloud Storage for Dynamic Data Using Network Coding Techniques

## Project Overview

This academic project explores a secure cloud storage solution for dynamic data using Secure Network Coding (SNC) techniques.

The project focuses on maintaining the integrity and security of data outsourced to a cloud server while supporting dynamic data operations. The system considers operations such as insertion, deletion, modification, and append-only data management.

Two secure cloud storage protocols are discussed:

- DSCS I – Designed for dynamic data and supports insertion, deletion, and modification operations.
- DSCS II – Designed specifically for append-only data and addresses some limitations of DSCS I.

Prototype implementations of DSCS I and DSCS II were developed to evaluate their practicality and performance.

## Project Objectives

- Provide secure storage for outsourced cloud data.
- Maintain the integrity of stored data.
- Support dynamic data operations.
- Detect unauthorized modifications to stored data.
- Enable data verification through auditing.
- Explore Secure Network Coding techniques for cloud storage.

## System Modules

The project consists of four major modules:

1. Data Owner
2. Third Party Auditor (TPA)
3. Cloud Server
4. Attacker

### Data Owner

The Data Owner can:

- Register and log in.
- Upload files.
- Manage files.
- Search for files.
- Send requests.
- View request status.
- Download files.
- Log out.

### Third Party Auditor (TPA)

The TPA participates in the auditing and verification process to help verify the integrity of outsourced data.

### Cloud Server

The Cloud Server stores the data provided by the Data Owner and participates in the storage and verification process.

### Attacker

The Attacker represents an unauthorized entity that may attempt to modify or compromise stored cloud data.

## Security

The project focuses on secure cloud storage and data integrity using concepts such as:

- Secure Network Coding
- Data Integrity Verification
- Authentication
- Encryption
- Third Party Auditing
- Dynamic Data Management

The project report also discusses the AES algorithm and encrypted data handling.

## Manual Testing

As part of the project, manual testing activities included:

- Preparing test scenarios.
- Designing test cases.
- Functional testing.
- System validation.
- Identifying defects and observations.
- Documenting testing results.

### Testing Areas

- Registration
- Login
- File Upload
- File Management
- File Search
- Request Status
- File Download
- Logout
- Data Modification
- Data Deletion
- Data Integrity Verification

## Testing Documentation

The `Testing` folder contains the manual testing documents prepared for this project:

- Test Plan
- Test Scenarios
- Test Cases
- Defect Reports
- Test Execution Report
- Test Summary

## Project Architecture

The system architecture includes interaction between the Data Owner, Cloud Server, Third Party Auditor, and potential Attacker.

## Project Type

**Academic / College Project**

**Domain:** Cloud Security and Data Security

**Testing Focus:** Manual Software Testing
