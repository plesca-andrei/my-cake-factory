# EPIC 2 — Authentication & Authorization

## Purpose

Implement secure authentication and role-based access control (RBAC) for all three application roles: USER, OPERATOR, and ADMIN.

## Initial scope

- Design authentication approach (JWT, sessions, etc.)
- Implement user model and registration
- Implement authentication system
- Implement RBAC with three roles: USER / OPERATOR / ADMIN
- Configure Spring Security backend
- Implement backend authorization rules
- Protect frontend routes based on roles
- Add initial RBAC tests

## Critical principle

**Backend authorization is the source of truth.** Frontend routing and UI controls are convenience features only. All security decisions must be enforced server-side.

## Follow-up

Detailed tasks and role-specific features will be expanded in the next phase.
