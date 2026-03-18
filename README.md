# 🧪 Automation Test Store - Selenium Project

## 📌 Overview

This project contains automated test scenarios for the website:  
https://automationteststore.com/

It is built using Selenium WebDriver with Java and TestNG to simulate real user actions such as registration, login, adding products to the cart, and completing the checkout process.

---

## 🛠️ Tech Stack

- Java  
- Selenium WebDriver  
- TestNG  
- Edge WebDriver  
- Maven (optional)  

---

## 🚀 Test Scenarios

### 1. User Signup
- Navigate to the registration page  
- Fill in user details using random data  
- Submit the form  
- Verify successful account creation  

### 2. Signup with Dynamic Data
- Perform signup using generated/random data  
- Ensure unique data for each test run  

### 3. Logout
- Log out from the account  
- Verify logout success message  

### 4. Login
- Log in using the created credentials  
- Validate successful login using assertions  

### 5. Add Random Product to Cart
- Navigate to homepage  
- Select a random product  
- Handle special product cases if needed  
- Add product to cart  

### 6. Checkout Process
- Proceed to checkout  
- Confirm the order  
- Verify order success message  

---

## ✨ Features

- Random test data generation  
- Handling dynamic elements  
- Form automation (signup & login)  
- Assertions using TestNG  
- End-to-end testing scenario (E2E)  
- Reusable test data class  
