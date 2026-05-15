# TC-037 - Verify that the Repeat New Password field is mandatory in the "Forgot Password" form

#### Test Steps
1. Navigate to the "Forgot Password" form
2. Enter valid data in all required fields except the Repeat New Password field
3. Leave the Repeat New Password field empty
4. Observe the validation behavior

#### Expected Result
- The system should reject the form submission
- The validation message "Please repeat your password." should be displayed
