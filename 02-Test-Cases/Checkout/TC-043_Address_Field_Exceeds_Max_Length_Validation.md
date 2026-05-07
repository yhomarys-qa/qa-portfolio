# TC-043 – Verify Address field rejects input above maximum length

## 🧪 Test Steps

1. Open Add New Address form  
2. Enter valid data in all required fields except Address  
3. Locate the "Address" field  
4. Enter an Address value with more than 160 characters  
5. Click on "Submit"  

---

## ✅ Expected Result
- System rejects input above 160 characters  
- Validation error message is displayed (if implemented)  
- Address field is highlighted in red (if validation styling is applied)  
- Form is not submitted  
