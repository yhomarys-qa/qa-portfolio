# TC-027 - Verify that the system rejects passwords containing only numeric characters

## 🧪 Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid email address
3. Enter a valid answer in the "Security Question" field
4. Enter a password containing only numeric characters in the New Password field (e.g., 12345678) 
5. Observe the validation behavior

---

## Expected Result
- A validation message should be displayed indicating that uppercase letters, lowercase letters, and special characters are required
- The system should reject the password

