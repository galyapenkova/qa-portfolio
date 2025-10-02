# Test Plan – Demo Web App (Manual Testing)

## 1. Overview
This plan covers manual testing of a small public demo web app (login + basic navigation).
Goal: validate core user flows, basic error handling, and UI consistency.

## 2. Scope
**In scope:** login form, navigation menu, basic CRUD page.  
**Out of scope:** performance, security pentesting, i18n.

## 3. Test Types
- Smoke & sanity
- Functional positive/negative
- UI/UX basic checks
- API spot checks via UI behavior

## 4. Environment
- Web: Chrome (latest), Firefox (latest), Windows 10/11
- Test data: demo accounts listed in this repo

## 5. Entry/Exit Criteria
**Entry:** app deployed and reachable; demo user available.  
**Exit:** all high/critical defects fixed or deferred with acceptance; smoke pass = 100%.

## 6. Risks & Mitigations
- Unstable demo endpoints → test retry + narrow scope
- Ambiguous UI → align expected results in test cases

## 7. Deliverables
- Test Cases (Markdown)
- Bug Reports (Markdown)
- Test Summary (if needed)

## 8. Tools
Browser devtools, screenshots, GitHub issues (or MD files).

## 9. Schedule & Roles
Solo tester; short iteration (1–2 days) for documentation baseline.
