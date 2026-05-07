# TC-046 – Verify Address field rejects spaces-only input

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Enter spaces only in the Address field  
   (e.g., "     ")      
7. Fill all other required fields  
8. Click on "Submit"

---

## ✅ Expected Result
- Spaces-only input is not accepted  
- Validation error message is displayed  
- Address field is highlighted in red 
