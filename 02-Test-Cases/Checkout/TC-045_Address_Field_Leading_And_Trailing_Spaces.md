# TC-045 – Verify Address field handles leading and trailing spaces

## 🧪 Test Steps

1. Open Add New Address form  
2. Enter valid data in all required fields except Address  
3. Locate the "Address" field  
4. Enter an Address value with leading and trailing spaces  
   (e.g., "   Street ABC 123   ")  
5. Click on "Submit"  

---

## ✅ Expected Result

- System handles leading and trailing spaces appropriately  
- Address value is either:
  - trimmed automatically, or
  - accepted without causing validation or formatting issues  
- No unexpected behavior occurs during form submission  
