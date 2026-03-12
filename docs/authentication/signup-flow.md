# Signup Flow

## Overview
The signup process allows a new user to create an AinFinance Books account.

## Entry Points

Users can reach the signup page through:

- Landing page "Get Started"
- Marketing popup "Generate Free Invoices Now"
- Subscription plan page
- Login page signup link

Signup URL:

https://qabooks.ainfinance.com/register

---

## Signup Form Fields

| Field | Required | Validation |
|------|------|------|
First Name | Yes | None
Last Name | Yes | None
Company Name | Yes | Editable until KYC completion
Email Address | Yes | Must be unique
Password | Yes | Minimum 8 characters, must contain letter, number and special character
Confirm Password | Yes | Must match password
Phone Number | Yes | Duplicate allowed
Terms & Conditions | Yes | Must be accepted
reCAPTCHA | Yes | Required

---

## Email Verification

After signup:

1. User account is created in Books database
2. Verification email is sent
3. Link expires after **24 hours**

Verification route:

/verify

---

## Login

After verification user logs in via:

/login

Fields:

- Email
- Password
- reCAPTCHA
- Remember Me

---

## Subscription

User selects a plan:

- Free (0 AED)
- Business (1500 AED/month)
- Enterprise (2500 AED/month)

---

## Onboarding Flow

Signup → Verify Email → Login → Subscription → KYC → Dashboard

---

## Organization Lifecycle

Signup → Organization created  
KYC → Company name editable  
Post-KYC → Company name locked

---

## Screenshots

(To be added later)
