# TC-037 – Verify validation message when Address field is empty

## 🧪 Test Steps
1. Open Add New Address form  
2. Fill all required fields with valid data except Address  
3. Leave the "Address" field empty  
4. Click on "Submit"  

---

## ✅ Expected Result
- Validation message is displayed:
  "Por favor, seleccione una dirección"  
- Address field is highlighted in red (if validation styling is applied)  
- Form is not submitted  
