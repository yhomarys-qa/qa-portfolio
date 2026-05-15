# TC-037 - Verify that the Repeat New Password field is mandatory in the "Forgot Password" form

## 🧪 Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid email address
3. Enter a valid answer in the "Security Question" field
4. Enter a valid password in the New Password field
5. Leave the Repeat New Password field empty
7. Observe the validation behavior

---

## ✅ Expected Result
- The system should reject the form submission
- The validation message "Please repeat your password." should be displayed
