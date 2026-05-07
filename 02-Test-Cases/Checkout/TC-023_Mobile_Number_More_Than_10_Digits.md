# TC-023 – Verify Mobile Number rejects values with more than 10 digits

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter a mobile number with more than 10 digits (e.g., 12345678901)  
5. Fill all other required fields  
6. Click on "Submit"  

---

## ❌ Expected Result
- System rejects the input  
- Validation message is displayed:
  "O número de celular deve corresponder ao formato 1000000-9999999999"  
- Field is highlighted in red  
- Form is not submitted  
