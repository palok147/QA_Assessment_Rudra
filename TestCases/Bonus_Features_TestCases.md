# Bonus Feature Test Cases

## Forgot Password - Positive
**Test Case:** Request password reset with valid registered email
**Expected Result:** Password reset email sent to user

## Forgot Password - Negative
**Test Case:** Request password reset with unregistered email
**Expected Result:** Error message: "Email not found"

## Email Verification - Positive
**Test Case:** Click valid email verification link
**Expected Result:** Email gets verified successfully

## Email Verification - Negative
**Test Case:** Click expired email verification link
**Expected Result:** Error message: "Verification link expired"

## Email Verification - Invalid Token
**Test Case:** Click a tampered or invalid verification link
**Expected Result:** Error message: "Invalid verification token"
