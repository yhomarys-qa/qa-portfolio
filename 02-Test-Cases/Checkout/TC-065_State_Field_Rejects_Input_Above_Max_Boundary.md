# TC-065 – Verify State field rejects input above maximum boundary

## 🧪 Test Steps

1. Open Add New Address form  
2. Fill all required fields with valid data except State  
3. Locate the "State" field  
4. Enter a State value with more than 50 characters  
5. Click on "Submit"  

---

## ✅ Expected Result

- System should not accept input above 50 characters  
- Validation error message should be displayed, or
- Additional characters should be blocked  
- Form submission should not proceed with invalid input  
