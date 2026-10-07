# Product-wide

Rules that apply to more than one feature.

## Requirements

- P1 Todos are stored persistently in a database and survive restarts and sign-outs. Applies to: all.
- P2 Each user sees and changes only their own todos. Applies to: all. *assumed*

## Decisions

- Every user signs in via SSO through Thunder, the platform IDP; the app is not usable signed out. \[org default\]