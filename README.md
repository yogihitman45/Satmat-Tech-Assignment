# Mobile Recharge & Wallet Dashboard Application

A web application that allows users to register/log in, select prepaid mobile operators, trigger mobile recharge API calls, and add money to their wallet using Razorpay integration.

---

## 📌 Features

1. **User Authentication & Database Integration**
   - User login page with `username` and `password` fields.
   - Database table `user` to manage user accounts with the following schema:
     - `name`     
     - `email`
     - `password`
     - `datetime`
     - `wallet_balance`

2. **Prepaid Recharge Interface**
   - Operator selection (Airtel, BSNL, BSNL STV, Idea, Jio, Vodafone).
   - Input fields for prepaid mobile number and recharge amount.
   - Option to select/view recharge plans.

3. **Recharge API Integration**
   - "Proceed To Recharge" button integrates with the Recharge API endpoint.
   - API response is dynamically displayed inside a pop-up modal.

4. **Payment Gateway Integration**
   - "ADD Money" feature integrated with **Razorpay Payment Gateway** to top up funds.

---

## 🛠️ API Reference

### Mobile Recharge API
- **Endpoint:** 
  `https://supay.in/recharge_api/recharge`
- **Parameters:**
  - `member_id`: `9876543210`
  - `api_password`: `1234`
  - `api_pin`: `1234`
  - `number`: `998988200`

---


