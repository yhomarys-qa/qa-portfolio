# TC-030 – Verify ZIP Code accepts alphanumeric input (letters + numbers)

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter alphanumeric characters in the field (e.g., A1B2C3 or 123ABC)   
6. Fill all other required fields  
7. Click on "Submit"

---

## ✅ Expected Result
- System should validate ZIP Code format according to selected country  
- If alphanumeric is not allowed for the selected country:
  - Input should be rejected  
  - Validation error should be displayed  
