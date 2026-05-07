# TC-033 – Verify ZIP Code rejects mixed invalid input

## 🧪 Test Steps

1. Open Add New Address form  
2. Locate the "ZIP Code" field  
3. Enter mixed invalid input containing letters, numbers, and special characters (e.g., A1@B2#C3 or AB$12CD)  
4. Fill all other required fields with valid data  
5. Click on "Submit"  

---

## ✅ Expected Result
- System rejects mixed invalid input  
- Validation error message is displayed  
- Field is highlighted in red (if UI validation is applied)  
- Form is not submitted  
