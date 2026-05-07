# TC-029 – Verify system behavior when changing language with address form open

## 🧪 Test Steps
1. Open Add New Address form
2. Enter a valid country name (e.g., Brazil)  
3. Enter a valid name (e.g., John Doe)  
4. Enter a valid mobile phone number (e.g., 4187745635)
5. Enter a valid ZIP Code (e.g., 12345-678) 
6. Change language using the language selector (top navigation)
7. Observe the form behavior
8. Verify if all previously entered data is preserved  
9. Verify if labels and validation messages are translated correctly 
10. Fill all other required fields  
11. Click on "Submit"

---

## ✅ Expected Result
- System accepts the correct format per country  
- Invalid formats are rejected depending on the selection  
