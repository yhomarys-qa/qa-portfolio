# TC-033 – Verify ZIP Code rejects mixed invalid input

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter mixed invalid input containing letters, numbers, and special characters (e.g., A1@B2#C3 or AB$12CD)   
6. Fill all other required fields  
7. Click on "Submit"

---

## ✅ Expected Result
- System rejects mixed invalid input  
- Validation error message is displayed  
- Field is highlighted in red 
