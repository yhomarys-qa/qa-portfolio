# TC-063 – Verify State field rejects spaces-only input

## 🧪 Test Steps

1. Open Add New Address form  
2. Fill all required fields with valid data except State  
3. Locate the "State" field  
4. Enter spaces only (e.g., "     ")  
5. Click on "Submit"  

---

## ✅ Expected Result
- Spaces-only input is not accepted  
- Validation error message is displayed  
- Form submission is blocked  
