# TC-015 - Verify that the user can proceed with an empty email field in the "Forgot my password" form

if the system allows the user to proceed with an empty email field in the "Forgot my password" form

## Test Steps
1. Navigate to the Forgot Password form.
2. Leave the Email field empty.
3. Observe the remaining form fields.

---

## Expected Result
- The remaining form fields should remain blocked or disabled.
- The user should not be able to continue the password recovery process without entering an email address.
- An appropriate validation message should be displayed.
