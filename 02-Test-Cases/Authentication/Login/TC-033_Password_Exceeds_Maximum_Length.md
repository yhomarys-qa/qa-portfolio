# TC-033 - Verify that the system rejects passwords exceeding the maximum length

## 🧪 Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid email address
3. Enter a valid answer in the "Security Question" field
4. Enter a password containing more than 40 characters in the New Password field (e.g., Testing#2026-03-19%Software2020#025$368200) 
5. Observe the validation behavior

---

## ✅ Expected Result
- The system should reject the password or prevent additional character input
- A validation message should be displayed indicating the maximum allowed new password length
