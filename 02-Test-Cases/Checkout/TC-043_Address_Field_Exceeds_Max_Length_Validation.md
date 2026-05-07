# TC-043 – Verify Address field rejects input above maximum length

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Enter an Address value with more than 160 characters        
7. Fill all other required fields  
8. Click on "Submit"

---

## ✅ Expected Result
- System rejects input above 160 characters  
- Validation error message is displayed (if implemented)  
- Address field is highlighted in red (if validation styling is applied)  
- Form is not submitted  
