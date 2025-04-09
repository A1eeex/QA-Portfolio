# Test Case: Login functionality

**Pre-condition:**
- User must be registered.

**Test Steps:**
1. Go to the login page.
2. Enter valid username and password.
3. Click the login button.

**Expected Result:**
User is redirected to the dashboard.

**Actual Result:**
User is logged in successfully.
# 📋 Login Test Cases  

## ✅ Positive Test Cases  
| ID  | Test Scenario | Steps | Expected Result |
|-----|-------------|-------|----------------|
| TC01 | Valid login | 1. Open login page <br> 2. Enter valid username and password <br> 3. Click "Login" | User successfully logs in |

## ❌ Negative Test Cases  
| ID  | Test Scenario | Steps | Expected Result |
|-----|-------------|-------|----------------|
| TC02 | Incorrect password | 1. Open login page <br> 2. Enter valid username and incorrect password <br> 3. Click "Login" | Error message appears |
| TC03 | Empty fields | 1. Open login page <br> 2. Leave username and password empty <br> 3. Click "Login" | Error message appears |
