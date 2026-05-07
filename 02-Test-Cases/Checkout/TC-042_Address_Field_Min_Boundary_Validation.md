# TC-042 – Verify Address field minimum length validation

## 🧪 Test Steps

1. Open Add New Address form  
2. Enter valid data in all required fields except Address  
3. Locate the "Address" field  
4. Enter a very short Address value (e.g., A)  
5. Click on "Submit"  

---

## ✅ Expected Result

- System behavior depends on business rules:
  - If minimum length is enforced → validation error is displayed  
  - If no minimum length exists → input is accepted  
- No unexpected behavior occurs  
