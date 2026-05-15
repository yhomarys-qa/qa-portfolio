# TC-031 - Verify that the system rejects passwords with fewer than 8 characters

## 🧪 Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid email address
3. Enter a valid answer in the "Security Question" field
4. Enter a password containing fewer than 8 characters in the New Password field (e.g., Te#2) 
5. Observe the validation behavior

---

## ✅ Expected Result
- The system should reject the password.
- A validation message should be displayed indicating that the password must contain at least 8 characters.
