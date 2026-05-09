# TC-060 – Verify State field behavior with numeric input

## 🧪 Test Steps

1. Open Add New Address form  
2. Fill all required fields with valid data except State  
3. Locate the "State" field  
4. Enter numeric input only  
   (e.g., "123456")  
5. Click on "Submit"  

---

## ✅ Expected Result

- Numeric-only input should not be accepted  
- Validation error message should be displayed  
- Form submission should not proceed with invalid input  
