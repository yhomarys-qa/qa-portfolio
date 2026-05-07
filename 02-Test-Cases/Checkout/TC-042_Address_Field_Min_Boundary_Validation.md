# TC-042 – Verify Address field minimum length validation

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Enter a very short Address value (e.g., A)        
7. Fill all other required fields  
8. Click on "Submit"

---

## ✅ Expected Result

- System behavior depends on business rules:
  - If minimum length is enforced → validation error is displayed  
  - If no minimum length exists → input is accepted  
- No unexpected behavior occurs  
