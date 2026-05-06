# TC-007 – Verify search input validation for potentially dangerous characters

## 🧪 Test Steps
1. Open the application  
2. Log in with valid credentials  
3. Locate the search bar  
4. Enter data in SQL format or in script format (e.g., "' OR 1=1 --", "<script>alert(1)</script>")  
5. Press "Enter"  

---

## ✅ Expected Result
- Input is treated as plain text and not executed  
- No matching results are displayed for invalid/malicious input  
- A "No results found" message is shown (or equivalent)  
- No system errors or unexpected behavior occur  
- Application remains stable and secure  
