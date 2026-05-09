# TC-057 – Verify City field allows input above maximum boundary

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Enter a valid address
7. Enter a City value with more than 50 characters   
8. Fill all other required fields  
9. Click on "Submit"

---

## ✅ Expected Result
- System accepts input above the recommended maximum boundary without validation  
- No maximum length restriction is enforced  
- No validation error message is displayed  
