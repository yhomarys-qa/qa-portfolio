# TC-029 – Verify ZIP Code format changes based on selected country

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name
3. Enter a valid name
4. Enter valid special characters
5. Select Country = Brazil → enter CEP format (e.g., 12345-678)
6. Change Country = USA → enter ZIP format (e.g., 10001)
7. Change Country = UK → enter Postal Code format (e.g., SW1A 1AA)
8. Fill all other required fields  
9. Click on "Submit"

---

## ✅ Expected Result
- System accepts the correct format per country  
- Invalid formats are rejected depending on the selection  
