# TC-047 – Verify Address field handles consecutive spaces

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Enter an address containing consecutive spaces in the "Address" field   
   (e.g., "Street    ABC    123")   
7. Fill all other required fields  
8. Click on "Submit"

---

## ✅ Expected Result
- System handles consecutive spaces appropriately  
- Address input is either:
  - normalized automatically, or
  - accepted without causing formatting or validation issues  
