# My Cake Factory - EPIC Backlog

## EPIC 2 — Authentication & Authorization

**Status:** Planned

### Purpose

Implement secure authentication and role-based access control (RBAC) for all three application roles: USER, OPERATOR, and ADMIN.

### Initial scope

- Design authentication approach (JWT, sessions, etc.)
- Implement user model and registration
- Implement authentication system
- Implement RBAC with three roles: USER / OPERATOR / ADMIN
- Configure Spring Security backend
- Implement backend authorization rules
- Protect frontend routes based on roles
- Add initial RBAC tests

### Critical principle

**Backend authorization is the source of truth.** Frontend routing and UI controls are convenience features only. All security decisions must be enforced server-side.

### Follow-up

Detailed tasks and role-specific features will be expanded in the next phase.

---

## Other Epics Created

1. EPIC 1 — Project Foundation & Architecture (#5)
2. EPIC 3 — Database & Domain Model (#18)
3. EPIC 4 — Customer Management (#17)
4. EPIC 5 — Cake Configuration & Catalog (#16)
5. EPIC 6 — Orders (#15)
6. EPIC 7 — Recipes & Ingredients (#14)
7. EPIC 8 — Price Calculator (#13)
8. EPIC 9 — Gallery (#12)
9. EPIC 10 — Feedback (#11)
10. EPIC 11 — About & Contacts (#9)
11. EPIC 12 — Admin & Settings (#10)
12. EPIC 13 — Operator Back Office (#8)
13. EPIC 14 — Customer Frontend (#7)
14. EPIC 15 — API & Backend Quality (#6)
15. EPIC 16 — Testing & QA (#4)
16. EPIC 17 — CI/CD & DevOps (#3)
17. EPIC 18 — Security (#2)
18. EPIC 19 — Documentation (#1)
