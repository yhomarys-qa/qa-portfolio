# TC-024 - Verify that the New Password field is mandatory in the "Forgot Password" form

## Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid email address
3. Enter a valid answer in the "Security Question" field
4. Leave the New Password field empty
5. Attempt to continue the password recovery process

---

## Expected Result
- The user should not be allowed to proceed with the password recovery process
- An appropriate validation message should be displayed
