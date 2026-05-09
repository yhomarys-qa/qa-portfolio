# TC-090 – Verify City field allows input above maximum boundary

## 🧪 Test Steps

1. Open Add New Address form  
2. Fill all required fields with valid data except City  
3. Locate the "City" field  
4. Enter a City value with more than 50 characters  
6. Click on "Submit"  

---

## ✅ Expected Result
- System accepts input above the recommended maximum boundary without validation  
- No maximum length restriction is enforced  
- No validation error message is displayed  
