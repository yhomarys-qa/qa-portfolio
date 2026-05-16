# TC-010 - Validate Country Field Case Sensitivity

## 🧪 Test Steps
1. Open the application
2. Navigate to the "Add Address" form
3. Locate the "Country" field
4. Enter the same country name in uppercase (e.g., "BRAZIL") and submit
5. Repeat the test using lowercase (e.g., "brazil")
6. Compare the system behavior/results

---

## ✅ Expected Result
The system should handle uppercase and lowercase inputs consistently, either:
- Treating both values as equivalent, or
- Applying a defined normalization rule (e.g., converting to a standard format)
