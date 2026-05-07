# TC-037 – Verify validation message when Address field is empty

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a valid mobile phone number
5. Enter a valid ZIP code
6. Leave the "Address" field empty       
7. Fill all other required fields  
8. Click on "Submit"

---

## ✅ Expected Result
- Validation message is displayed:
  "Por favor, seleccione una dirección"  
- Address field is highlighted in red (if validation styling is applied)  
- Form is not submitted  
