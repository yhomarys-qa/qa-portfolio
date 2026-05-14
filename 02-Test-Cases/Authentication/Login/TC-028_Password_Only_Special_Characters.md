# TC-028 - Verify that the system rejects passwords containing only special characters

## Test Steps
1. Navigate to the "Forgot Password" form.
2. Enter a valid email address
3. Enter a valid answer in the "Security Question" field
4. Enter a password containing only special characters in the New Password field (e.g., @#$%&*!?) 
5. Observe the validation behavior.

---

## ✅ Expected Result
- The system should reject the password.
- A validation message should be displayed indicating that uppercase letters, lowercase letters, and numeric characters are required.
