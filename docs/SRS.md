Here is the complete solution for **Task 6: SRS Review Activity**.
You can directly copy this into your `docs/SRS.md`.

---

# Task 6: SRS Review Activity

## Review Checklist Criteria

Each requirement must be:

* Clear
* Complete
* Testable
* Unambiguous
* Atomic (only one requirement per statement)
* Measurable
* Feasible

---

# Requirement 1

### ❌ Original:

> The system should be user-friendly.

### 🔎 Problems:

* ❌ Not Clear (What does "user-friendly" mean?)
* ❌ Not Measurable
* ❌ Not Testable
* ❌ Ambiguous
* ❌ Not Complete

### ✅ Improved Requirement:

The system shall allow new users to complete account registration within 3 minutes without external assistance.

✔ Specific
✔ Measurable (3 minutes)
✔ Testable
✔ Atomic

---

# Requirement 2

### ❌ Original:

> The system shall store student records safely.

### 🔎 Problems:

* ❌ Not Clear ("safely" is vague)
* ❌ Not Measurable
* ❌ Not Testable
* ❌ Ambiguous
* ❌ Not Complete

### ✅ Improved Requirement:

The system shall store student records in a database encrypted using AES-256 encryption and restrict access to authenticated users only.

✔ Specific
✔ Measurable (encryption standard defined)
✔ Testable
✔ Atomic

---

# Requirement 3

### ❌ Original:

> The system should load quickly.

### 🔎 Problems:

* ❌ Not Clear
* ❌ Not Measurable
* ❌ Not Testable
* ❌ Ambiguous

### ✅ Improved Requirement:

The system shall load the main dashboard page within 2 seconds for 95% of users under normal operating conditions.

✔ Specific
✔ Measurable (2 seconds, 95%)
✔ Testable
✔ Atomic

---

# Requirement 4

### ❌ Original:

> The system shall allow users to register, login, and manage their profile.

### 🔎 Problems:

* ❌ Not Atomic (contains multiple requirements)
* ❌ Not Fully Specific
* ❌ Partially Not Testable (manage profile not defined)

---

### ✅ Improved Requirements (Split into Atomic Statements)

1. The system shall allow users to create an account using a valid email address and password.
2. The system shall allow registered users to log in using valid credentials.
3. The system shall allow authenticated users to update their name, phone number, and password.

✔ Atomic
✔ Specific
✔ Testable
✔ Clear

---

# Requirement 5

### ❌ Original:

> The system shall send notifications.

### 🔎 Problems:

* ❌ Not Clear (what type of notification?)
* ❌ Not Complete
* ❌ Not Measurable
* ❌ Not Testable
* ❌ Ambiguous

### ✅ Improved Requirement:

The system shall send an email notification to users within 1 minute after successful account registration.

✔ Specific
✔ Measurable (1 minute)
✔ Testable
✔ Atomic

---

# ✅ Final Result

All rewritten requirements are now:

* Clear
* Complete
* Specific
* Measurable
* Testable
* Unambiguous
* Atomic

---

If you want, I can also format this in a **more professional university submission style** to get full marks.
