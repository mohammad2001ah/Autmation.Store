Automation Test Store - Selenium Project
📌 Overview

This project contains automated test scenarios for the website:
🔗 https://automationteststore.com/

The automation is built using Selenium WebDriver with Java and TestNG, simulating real user actions such as registration, login, adding items to cart, and completing checkout.

🛠️ Tools & Technologies

Java

Selenium WebDriver

TestNG

Edge WebDriver

Maven (optional)

🚀 Test Scenarios
1. 📝 Signup

Navigate to registration page

Fill user details with random data

Submit the form

Validate successful account creation

2. 🗄️ Signup (Data-Driven Simulation)

Same signup process using dynamic/generated data

Ensures reusability and randomness

3. 🔓 Logout

Logout from the account

Verify logout success message

4. 🔐 Login

Login using created credentials

Validate successful login using assertions

5. 🛒 Add Random Item to Cart

Open homepage

Select a random product

Handle special product cases (if needed)

Add item to cart

6. 💳 Checkout Process

Proceed to checkout

Confirm the order

Validate order success message

✨ Features Implemented

✅ Random test data generation

✅ Handling dynamic elements

✅ Form automation (signup/login)

✅ Assertions for validation

✅ End-to-end test scenario (E2E)

✅ Reusable test data class
