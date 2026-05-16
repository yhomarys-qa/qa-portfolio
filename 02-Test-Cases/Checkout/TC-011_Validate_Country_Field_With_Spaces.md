# TC-011 – Validate Country Field With Spaces

## 🧪 Test Steps
1. Open Add New Address form 
2. Enter the name of a country, including spaces, in the country field (e.g., "New Zealand")
4. Fill other fields with valid data
5. Submit the form.

---

## ✅ Expected Result
The system should handle spaces correctly by:
- Trimming leading and trailing spaces, and/or
- Validating the input according to defined business rules

The system should not reject the input solely because of extra spaces unless explicitly required by validation rules.

