# TC-028 - Verify that the system rejects passwords containing only special characters

## Test Steps
1. Navigate to the "Forgot Password" form.
2. Enter a password containing only special characters (e.g., @#$%&*!?) in the New Password field.
3. Observe the validation behavior.

---

## Expected Result
- The system should reject the password.
- A validation message should be displayed indicating that uppercase letters, lowercase letters, and numeric characters are required.
