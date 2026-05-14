# TC-026 - Verify if the New Password field only accepts uppercase letters

## Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid email address
3. Enter a valid answer in the "Security Question" field
4. Enter a password containing uppercase letters in the New Password field (e.g., TesTing) 
5. Observe the validation behavior

---

## Expected Result
- A validation message should be displayed indicating that the password does not meet the required complexity rules
- The system should reject the new password
