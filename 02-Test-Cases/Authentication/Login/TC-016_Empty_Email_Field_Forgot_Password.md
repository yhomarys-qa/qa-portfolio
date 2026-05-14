# TC-015 - Verify that the Email field is mandatory in the "Forgot Password" form

## Test Steps
1. Navigate to the Forgot Password form
2. Leave the Email field empty
3. Observe the remaining form fields

---

## Expected Result
- The remaining form fields should remain blocked or disabled
- The user should not be able to continue the password recovery process without entering an email address
- A validation message should be displayed: "Please provide an email address"
