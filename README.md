# Hackathon-SmartBank-2025

# 🧩 Project Title
SmartBank - Modular Banking Backend System


## 📘 Overview
To build a secure,scalable backend system that supports core banking operations such as account management,transactions, loan processing, and fraud detection.



## Use Cases
## 1. User Registration & KYC

Initially i will Implement API Endpoints for User Registration were i will take Firstname, Lastname, Age, Date of Birth,and Location and for the KYC Document i will ask user to upload Pdf format file of an 
Pan Card or any Government ID Proof and Bank Admin Will validate the documents and Store the User details in the Database

## 🧠 Tech Stack
- **Backend:** FastAPI  
- **Database:** MySQL    


## 2. Loan Application and EMI Calculation
This section of the SmartBank API handles loan applications, EMI calculation, and admin approval/rejection of loans.
The calculate_emi function calculates the Equated Monthly Installment (EMI) for a loan using the standard formula:
emi = (principal * r * (1 + r)**n) / ((1 + r)**n - 1)

Endpoint: POST /apply_loan, GET /calculate_emi/{loan_id}, PUT /admin/approve_loan/{loan_id},PUT /admin/reject_loan/{loan_id},GET /loans

## 🧠 Tech Stack
- **Backend:** FastAPI  
- **Database:** MySQL
