# TC-024 - Verify that the New Password field is mandatory in the "Forgot Password" form

## Test Steps
1. Navigate to the "Forgot Password" form
2. Enter valid data in all required fields except the New Password field
3. Leave the New Password field empty
4. Attempt to continue the password recovery process
---

## Expected Result
- The user should not be allowed to proceed with the password recovery process
- An appropriate validation message should be displayed
