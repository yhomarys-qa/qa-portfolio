# TC-029 - Verify that the system rejects passwords without special characters

## 🧪 Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid email address
3. Enter a valid answer in the "Security Question" field
4. Enter a password without special characters in the New Password field (e.g., Testing123) 
5. Observe the validation behavior

---

## ✅ Expected Result
- A validation message should be displayed indicating that at least one special character is required
- The system should reject the password
