# TC-036 – Verify ZIP Code rejects input above maximum boundary (9+ characters)

## 🧪 Test Steps
1. Open Add New Address form  
2. Locate the "ZIP Code" field  
3. Enter a ZIP Code with more than 8 characters (e.g., 123456789)  
4. Fill all other required fields with valid data  
5. Click on "Submit"  

---

## ✅ Expected Result
- Input is rejected  
- Validation error message is displayed  
- Field is highlighted in red (if UI validation is applied)  
- Form is not submitted  
