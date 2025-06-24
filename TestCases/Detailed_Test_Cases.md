## Test Case 1
**ID:** TC_LOGIN_01
**Title:** Successful login with valid credentials
**Pre-condition:** User must be registered
**Steps:**
1. Navigate to login page
2. Enter valid email and password
3. Click Login
**Expected Result:** User is redirected to the dashboard
**Priority:** High
**Test Data:** email: test@assignemnt.com, password: India@123

## Test Case 2
**ID:** TC_LOGIN_02
**Title:** Error on login with wrong password
**Pre-condition:** User exists in system
**Steps:**
1. Go to login page
2. Enter valid email and invalid password
3. Click Login
**Expected Result:** Error message displayed: "Incorrect password"
**Priority:** High
**Test Data:** email: test@assignment.com, password: WrongPass

## Test Case 3
**ID:** TC_EMAIL_01
**Title:** Successful email verification
**Pre-condition:** User has just registered
**Steps:**
1. Open verification email
2. Click on verification link
**Expected Result:** Message displayed: "Email verified successfully"
**Priority:** Medium
**Test Data:** Auto-generated verification token
