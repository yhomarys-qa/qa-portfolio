# TC-036 - Verify that the Repeat New Password field must match the New Password field

#### Test Steps
1. Navigate to the "Forgot Password" form
2. Enter a valid password in the New Password field
3. Enter a different password in the Repeat New Password field
4. Observe the validation behavior

#### Expected Result
- The system should reject the password confirmation
- An appropriate validation message should be displayed indicating that both passwords must match
