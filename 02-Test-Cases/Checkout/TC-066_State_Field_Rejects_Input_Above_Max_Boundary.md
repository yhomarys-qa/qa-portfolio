# TC-066 – Verify State field rejects input above maximum boundary

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Enter a valid address
7. Enter a valid City   
8. Enter a State value with more than 50 characters
9. Click on "Submit"

---

## ✅ Expected Result

- System should not accept input above 50 characters  
- Validation error message should be displayed, or
- Additional characters should be blocked  
- Form submission should not proceed with invalid input  
