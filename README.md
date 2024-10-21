# E-Portal for Online Case Management

## Project Overview
This project aims to digitize the paper-based judicial processes in India. The e-portal facilitates the online submission of new cases and allows users to upload judgments or transfer cases to different courts, streamlining case management and improving accessibility for litigants, advocates, and court administrators.

## Problem Statement
India's judicial system is still largely reliant on paper-based processes, causing delays, inefficiencies, and difficulties in securing case-related evidence and paperwork. Currently, over 5.02 crore cases are pending across various courts. This project provides a solution by developing an online portal that:
- Enables the submission of cases online.
- Facilitates uploading and managing case-related evidence and judgments.
- Supports the transfer of cases to higher courts when necessary.
- Allows litigants to search for and contact lawyers based on their profiles.

## Features

### 1. Court Administrator
A court administrator can:
- **Upload Case Documents:** 
  - **Required Data:** File, CNR Number, File Name, File Type.
- **Upload Case Details:** 
  - **Required Data:** CNR, Title, Date, Description.
- Both tasks are managed using a unique CNR number generated for each case.

### 2. Advocate
An advocate can:
- **View Case Documents:**
  - Using a unique code and CNR number sent via email after case filing.
- **File a Case:** 
  - After filing, case files are sent to both the litigant’s advocate and the court administration via email.

### 3. Litigant
A litigant can:
- **Track Cases:** 
  - View case updates provided by the court administration.
- **Access Case Documents:** 
  - Use the unique code and CNR number sent after case filing to view documents.
- **Search for Lawyers:**
  - Search for and contact lawyers for hiring based on their profiles.

## Security Measures
- **Strong Password Requirements:** Enforcing fixed length and complexity.
- **OTP Authentication:** OTP sent to the registered email for verification.

## Target Audience
The e-portal serves:
- **Litigants:** For tracking case details and finding legal representation.
- **Advocates:** For filing and managing cases for their clients.
- **Court Administrators:** For managing case assignments and documents.

## Tech Stack
The project is built using the **MERN stack**, which provides a robust and scalable platform for the e-portal:
- **MongoDB**: For storing case data, documents, and user details.
- **Express.js**: For handling server-side logic and routing.
- **React.js**: For creating the user-friendly interface that makes the portal easy to navigate for all user roles.
- **Node.js**: For back-end development, managing the API and real-time case tracking.
