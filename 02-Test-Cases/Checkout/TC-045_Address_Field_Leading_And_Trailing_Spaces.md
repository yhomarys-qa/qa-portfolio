# TC-045 – Verify Address field handles leading and trailing spaces

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Enter an address containing spaces at the beginning and end in the "Address" field  
   (e.g., "   Street ABC 123   ")        
7. Fill all other required fields  
8. Click on "Submit"

---

## ✅ Expected Result
- System handles leading and trailing spaces appropriately  
- Address value is either:
  - trimmed automatically, or
  - accepted without causing validation or formatting issues  
