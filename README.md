# Diversity Healthcare App (Phase 2)

Diversity Healthcare is a unified mobile healthcare application designed to reduce system fragmentation for patients and healthcare providers. The platform streamlines scheduling, centralizes medical records, and simplifies clinical record management into a single, user-centered interface.

---

## Team & Roles

* **Project Leader:** Anabelle Hsiao
* **Team Communicator:** Muhammad Bilal

### Contributors
* **Zeynep Sude Haksal**
* **Christian Rogers**
* **Vignesh Veerakumar Sathya**
* **Ho Ching Ashley Wong**

---

## Personas & Scenarios

### Patient Persona: Sarah (32)
* **Demographics & Role:** Marketing Manager from Toronto; Patient on Clinic App.
* **Characteristics & Interests:** Hard-working, passionate, efficient; enjoys marketing strategy videos, yoga, and audiobooks.
* **Frustrations:** Struggles to balance work, family, and healthcare; tired of repeating medical information and waiting for results.
* **Needs & Motivations:** Wants a single portal to book appointments, view test results, and manage prescriptions.
* **Scenario Summary:** Resolves a cross-city, cross-timezone calendar conflict while traveling from Toronto to Edmonton by rebooking a local appointment near her destination hotel in a single tap.

### Doctor Persona: Dr. Mike (45)
* **Demographics & Role:** Family Physician in Mississauga seeing 20+ patients daily; Doctor on Clinic App.
* **Characteristics & Interests:** Patient, caring, values efficiency; enjoys crime documentaries, dog walks, archery, and singing.
* **Frustrations:** Dislikes dealing with slow, overly complex EMR systems.
* **Needs & Motivations:** Seeks technology that simplifies record management, supports telemedicine, and reduces administrative burden.
* **Scenario Summary:** Completes a telemedicine follow-up, e-prescribes an inhaler with automatic timestamping, reviews his weekly calendar, and updates notification preferences efficiently during a brief admin pause.

---

## Task Hierarchy (HTA Flow Summaries)

1. **View / Book / Cancel Appointments:** Log in via Face ID/PIN $\rightarrow$ Navigate to "Appointments" $\rightarrow$ Filter/Select options (Book, Cancel, or Rebook with location change) $\rightarrow$ Review policy and receive SMS/email confirmation $\rightarrow$ Auto-sync calendar.
2. **Access Patient Records:** Log in with doctor credentials $\rightarrow$ Search patient by name/ID $\rightarrow$ View consolidated history, test results, and visit summaries $\rightarrow$ Update notes (auto-saved and timestamped).
3. **E-Prescription Workflow:** Access patient record $\rightarrow$ Select "Add New Prescription" $\rightarrow$ Input drug details and click "E-Prescribe" $\rightarrow$ Auto-save version-controlled entry and send notification.
4. **Locate Nearby Clinics:** Log in $\rightarrow$ Select "Find Clinics" $\rightarrow$ Provide location/destination $\rightarrow$ Apply filters (specialty, date, rating) $\rightarrow$ Select available time slot and book.
5. **Manage Account Settings:** Log in $\rightarrow$ Navigate to "Settings" $\rightarrow$ Update profile fields (contact details, passwords, identifiers) $\rightarrow$ Verify via SMS/email $\rightarrow$ System logs activity for audit compliance.

---

## Requirements Gathering Methodology

* **Empirical Measurement & User-Centered Approach:** Focuses on cognitive, behavioral, and accessibility needs across patient and clinical workflows.
* **Quantitative Surveys:** Distributed to 29 patients to collect data on booking struggles, record retrieval habits, accessibility options, and authentication preferences.
* **Semi-Structured Interviews:** Conducted with 11 medical students/interns to identify workflow bottlenecks, fragmented EMR pain points, data privacy needs, and feature requirements.

---

## Key Survey & Interview Insights

| Category | Key Findings & Metrics |
| :--- | :--- |
| **Appointment Booking** | • 46.2% book via phone call, 34.6% use online portals, 19.2% walk-in.<br>• Top struggles: finding available times (57.7%), long wait times (53.8%), managing multiple logins (46.2%). |
| **Health Records** | • 65.5% receive records via email attachments, 34.5% paper copies, 27.6% online portals.<br>• Primary actions: 58.6% view on phone, 37.9% share with doctor, 34.5% download to files. |
| **Medical Student Feedback** | • 10/11 cite fragmented patient information as a major challenge.<br>• 9/11 highlight time wasted on paperwork/retrieval.<br>• 8/11 note poor accessibility/usability in current tools. |
| **Accessibility & Security** | • 69% preferred Face ID/Touch ID login over PINs or passwords.<br>• Top requests: adjustable text size (55.2%), high-contrast/dark mode (51.7%), screen reader support (48.3%). |

---

## Design Choices for High-Fidelity Prototype

* **Homepage Restructure:** Prioritize quick action options in order of user intent: **Health Records**, **Appointment Records**, then **Prescriptions**.
* **Appointment Scheduling:** Retain the 3-step booking flow while introducing a time-slot grid with inline filters (Soonest, Virtual-only, Day/Time) and reason-based triage with slot buffers.
* **Health Records Dashboard:** Replace static bottom actions with a single **"Add record"** floating action button sheet (Scan, Request, Import). Relocate record sharing directly to the detailed view.
* **Efficiency Focus:** Guarantee that core primary actions (viewing test results, booking appointments, checking prescriptions) are reachable within 2 to 3 taps.
