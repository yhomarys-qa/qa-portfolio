# TC-058 – Verify that the status field cannot be empty

## 🧪 Test Steps

1. Open Add New Address form  
2. Fill all required fields with valid data except State  
3. Leave the "State" field empty  
4. Click on "Submit"  

---

## ✅ Expected Result

- Validation message is displayed:
  "Please provide a state"  
- State field border is highlighted in red  
- Form submission is blocked  
