# TC-043 – Verify Address field prevents input above maximum length

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Enter characters continuously until reaching 160 characters        
7. Fill all other required fields  
8. Click on "Submit"

---

## ✅ Expected Result
- Address field accepts up to 160 characters only  
- Additional characters beyond 160 are not accepted  
