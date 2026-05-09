# TC-050 – Verify City field behavior with numeric input

## 🧪 Test Steps
1. Open Add New Address form  
2. Fill all required fields with valid data except City  
3. Locate the "City" field  
4. Enter numeric input only (e.g., 123456)  
5. Click on "Submit"  

---

## ✅ Expected Result
- System behavior follows validation rules:
  - numeric input is rejected, or
  - validation error message is displayed  
- Form submission should not proceed with invalid numeric-only input  
