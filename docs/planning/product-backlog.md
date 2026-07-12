# Product Backlog

## Overview

This document contains proposed features, enhancement ideas, and future improvements for the Internal Audit Platform.

Items in this backlog are ideas under evaluation and are not considered approved until they are included in the Project Roadmap and Architecture Decision Log.

---

# High Priority

## User Authentication

### Remember Me

**Status:** Proposed

- Add a "Remember Me" option to the login page.
- Store the username or a secure session token.
- Never store passwords in plain text.

---

### Logout

**Status:** Planned

- Add a Logout button.
- End the current session.
- Clear session data.
- Redirect to the Login page.

---

# Medium Priority

## User Management

**Status:** Future Release

### Current State

- User information is stored locally using LocalStorage.

### Future State

- Centralized user accounts.
- Secure authentication.
- Role-Based Access Control (RBAC).
- Cloud database support.

---

## User Capacity

**Status:** Under Study

### Discussion

The current version uses LocalStorage and does not maintain centralized user accounts.

When a backend is introduced, the platform should support scalable user registration based on the selected hosting infrastructure.

---

## Guest Mode

**Status:** Planned

Allow visitors to use the platform with limited permissions whenever registration is temporarily unavailable.

---

## Inactive Accounts

**Status:** Proposed

When centralized authentication becomes available:

- Detect inactive accounts.
- Send reminder notifications.
- Suspend inactive accounts after a defined period of inactivity.
- Allow account recovery before permanent deletion.

---

# Future Security

- Two-Factor Authentication (2FA)
- Single Sign-On (SSO)
- Microsoft Authentication
- Google Authentication
- Enterprise Identity Providers

---

# Future Modules

- AI Audit Assistant
- Audit Academy
- Knowledge Center
- Report Builder
- Risk Register
- Compliance Management
- KPI Dashboard
- Notification Center
- Mobile Application
- REST API

---

# Notes

The Product Backlog is a living document.

Features are reviewed, prioritized, approved, and moved into the Project Roadmap before implementation.
