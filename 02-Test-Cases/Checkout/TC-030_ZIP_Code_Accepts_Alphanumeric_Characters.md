# TC-049 – Verify ZIP Code accepts alphanumeric input (letters + numbers)

## 🧪 Test Steps
1. Open Add New Address form  
2. Locate the "ZIP Code" field  
3. Enter a mixed value (e.g., A1B2C3 or 123ABC)  
4. Fill all other required fields  
5. Click on "Submit"  

---

## ❌ Expected Result (best practice)
- System should validate ZIP Code format according to selected country  
- If alphanumeric is not allowed for the selected country:
  - Input should be rejected  
  - Validation error should be displayed  
- If allowed (country-specific):
  - Input should be accepted correctly  
