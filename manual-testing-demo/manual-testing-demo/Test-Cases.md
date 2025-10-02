# Test Cases – Demo Web App

| ID | Title | Preconditions | Steps | Test Data | Expected Result |
|---|---|---|---|---|---|
| TC-001 | Successful login with valid credentials | App is reachable; demo user exists | 1) Open /login 2) Enter valid email/pass 3) Click **Login** | user: demo@site.test / Passw0rd! | User lands on dashboard; username visible |
| TC-002 | Login with invalid password | Same as above | 1) Open /login 2) Enter valid email + wrong pass 3) Click **Login** | wrong pass | Error message shown (no login) |
| TC-003 | Login input validation (empty fields) | — | 1) Open /login 2) Leave fields empty 3) Click **Login** | — | Validation messages per field |
| TC-004 | Logout from dashboard | User is logged in | 1) Click avatar/menu 2) Click **Logout** | — | User is returned to /login; session cleared |
| TC-005 | Navigation: open “Items” page | User is logged in | 1) Click **Items** in navbar | — | Items list is displayed; no console errors |
| TC-006 | Create item – happy path | User is on Items page | 1) Click **Add** 2) Fill name 3) Save | Name: “Item A” | New item appears in list |
| TC-007 | Create item – validation | On Add form | 1) Leave name empty 2) Save | — | Inline validation: “Name is required” |
