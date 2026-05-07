# TC-036 – Verify ZIP Code rejects input above maximum boundary (9+ characters)

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a ZIP Code with more than 8 characters (e.g., 1234567890010100)     
6. Fill all other required fields  
7. Click on "Submit"

---

## ✅ Expected Result
- Validation error message is displayed  
- Field is highlighted in red 
