# TC-048 – Verify Address field handles consecutive spaces

## 🧪 Test Steps

1. Open Add New Address form  
2. Enter valid data in all required fields except Address  
3. Locate the "Address" field  
4. Enter an Address value containing consecutive spaces  
   (e.g., "Street    ABC    123")  
5. Click on "Submit"  

---

## ✅ Expected Result
- System handles consecutive spaces appropriately  
- Address input is either:
  - normalized automatically, or
  - accepted without causing formatting or validation issues  
- No unexpected behavior occurs during form submission  
