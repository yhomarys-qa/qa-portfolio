# TC-046 – Verify Address field rejects spaces-only input

## 🧪 Test Steps

1. Open Add New Address form  
2. Enter valid data in all required fields except Address  
3. Locate the "Address" field  
4. Enter spaces only in the Address field  
   (e.g., "     ")  
5. Click on "Submit"  

---

## ✅ Expected Result
- Spaces-only input is not accepted  
- Validation error message is displayed  
- Address field is highlighted in red (if validation styling is applied)  
- Form is not submitted  
