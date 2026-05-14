# TC-020 - Verify that the Security Question field is mandatory in the "Forgot Password" form

## Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid email address
3. Leave the Security Question field empty
4. Attempt to continue the password recovery process

---

## ✅ Expected Result
- A validation message "Please answer your security question," should be displayed
- The user should not be allowed to proceed with the password recovery process
