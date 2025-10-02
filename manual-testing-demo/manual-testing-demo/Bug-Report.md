# Bug Report – Template

**ID:** BUG-001  
**Title:** Login allows submission with empty password (no validation)  
**Env:** Web (Chrome 140, Windows 10) – demo build 2025-10-02  
**Preconditions:** App deployed; /login reachable

**Steps to Reproduce:**
1) Open /login
2) Enter valid email; leave password empty
3) Click **Login**

**Actual Result:** Request is sent; generic error appears after page reload  
**Expected Result:** Client-side validation message “Password is required”; no request sent  
**Severity:** Major  
**Priority:** High  
**Attachments:** (screenshots, console logs)  
**Notes:** Happens only in Chrome; Firefox blocks it correctly.
