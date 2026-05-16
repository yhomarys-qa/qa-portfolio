# TC-011 – Validate Country Field With Spaces

## 🧪 Test Steps
1. Open the application
2. Navigate to the "Add Address" form
3. Locate the "Country" field
4. Enter the name of a country, including spaces, in the country field (e.g., "New Zealand").
5. Submit the form.

## ✅ Expected Result
The system should handle spaces correctly by:
- Trimming leading and trailing spaces, and/or
- Validating the input according to defined business rules

The system should not reject the input solely because of extra spaces unless explicitly required by validation rules.
