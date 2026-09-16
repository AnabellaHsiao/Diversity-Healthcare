# Diversity Healthcare App (Final Project Pitch Package)

Diversity Healthcare is an HCI-driven, unified digital healthcare platform designed to reduce system fragmentation across patient and provider environments. The platform integrates appointment scheduling, medical records management, e-prescribing, and localized clinic discovery into a single mobile application for patients and an administrative dashboard for clinicians.

---

## Team & Roles

* **Project Leader:** Anabelle Hsiao
* **Team Communicator:** Muhammad Bilal

### Contributors
* **Christian Rogers**
* **Ho Ching Ashley Wong**
* **Zeynep Sude Haksal**
* **Vignesh Veerakumar Sathya**

---

## Interactive Figma Prototypes

* **Doctor View Interactive Prototype:** [View Doctor Figma Prototype](https://www.figma.com/proto/iZTQXMzdTFQXQ0KwxznBBp/Team-Diversity-Phase-3?node-id=1-15141&t=SLxFX9OPkkxF7DsD-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1)
* **Patient View Interactive Prototype:** [View Patient Figma Prototype](https://www.figma.com/proto/iZTQXMzdTFQXQ0KwxznBBp/Team-Diversity-Phase-3?node-id=1-14638&t=vw1RliHkHYMZPN7v-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1)

---

## Problem Statement & HCI Objectives

* **Core Problem:** Digital health data is currently scattered across isolated portals, legacy EHRs, and disjointed communications, leading to care delays, administrative burnout, and inequitable access.
* **Research Question:** How can we design a single, accessible digital health application that addresses fragmentation and supports both patients and clinicians in managing appointments, health records, and prescriptions more effectively?
* **Key Focus Areas:** 
  1. *System Integration:* Combining scheduling, diagnostic results, visit notes, and pharmacy orders into a single coherent workflow.
  2. *Inclusive Accessibility:* Designing interfaces optimized for high-contrast modes, adjustable font sizing, screen readers, and simple touch interactions.
  3. *Role-Differentiated Design:* Delivering streamlined comprehension for patients while offering robust administrative controls for doctors.

---

## Requirements Gathering Summary

Requirements were collected using a mixed-methods user-centered design approach:

* **Patient Survey (n=29):**
  * *Current Booking Habits:* 44.8% book via phone call, 34.5% via portals, and 20.7% via walk-in.
  * *Top Booking Struggles:* Finding available time slots (62.1%), long wait times (55.2%), and managing multiple login portals (48.3%).
  * *Record Retrieval:* 65.5% receive records via email attachments and 34.5% via paper copies, while only 27.6% access them via clinic portals.
  * *Preferences:* 69% prefer biometric login (Face ID/Touch ID). High demand was recorded for adjustable text size (55.2%), high contrast/dark mode (51.7%), and screen reader support (48.3%).
* **Clinician Interviews (n=11):**
  * *Key Pain Points:* 10/11 cited fragmented patient data as a major hurdle; 9/11 noted excessive time wasted on documentation; 8/11 flagged poor existing app usability.
  * *Workarounds:* Trainees reported using informal workarounds (e.g., screenshots or shared spreadsheets) to communicate patient status due to disconnected platforms.

---

## Core Task Workflows & Step-by-Step Instructions

### Task 1: Locate Nearby Clinics (Patient)
* **Description:** Patients scan a distance-sorted list of clinics, filter by availability ("Open Now") or services, view detailed clinic profiles, and launch booking directly.
* **Step-by-Step Flow:**
  1. Homepage $\rightarrow$ Select "Check Clinics Nearby"
  2. Clinics Nearby $\rightarrow$ Scroll distance-sorted list or enter terms into Search Bar
  3. Clinic Card $\rightarrow$ Select "Details" (e.g., Clinic Y) to open profile
  4. Clinic Details Page $\rightarrow$ Review embedded map, opening hours, specialties, languages, and physician availability
  5. Action $\rightarrow$ Select "Book Appointment" to initiate reservation

### Task 2: View, Book, and Cancel Appointments (Patient)
* **Description:** Patients search available providers, reserve time slots, review existing bookings, update appointment times, or cancel as needed.
* **Step-by-Step Flow:**
  1. Homepage $\rightarrow$ Select "Add Appointment" or navigate from Clinic Details
  2. Booking Flow $\rightarrow$ Select Visit Type, Reason for Visit, and Physician (e.g., Dr. Eggward Cullen)
  3. Confirmation $\rightarrow$ Review date/time and select "Accept"
  4. View Appointments $\rightarrow$ Locate booked card and select "Edit" to change date/time or "Cancel" to remove
  5. Edit Page $\rightarrow$ Select "Update" to finalize modifications

### Task 3: Health Records & E-Prescription Management

#### Patient Health Records & Prescriptions Flow
* **Description:** Patients browse historical lab results and visit summaries, search specific tests, review drug information, and locate nearby pickup pharmacies with integrated QR fulfillment codes.
* **Step-by-Step Flow:**
  1. Homepage $\rightarrow$ Select "Health Records" or "Prescriptions"
  2. Records View $\rightarrow$ Select specific test (e.g., "Cholesterol Test") to see concise summaries and complete criteria scales
  3. Prescriptions View $\rightarrow$ Select drug card (e.g., "Atorvastatin") to view details, OHIP coverage, and nearby pharmacy hours/locations
  4. Pharmacy Details $\rightarrow$ Open pharmacy card to display address, navigation links, and pharmacist QR code

#### Doctor Health Records & Prescriptions Flow
* **Description:** Clinicians view consolidated patient charts, upload diagnostic DICOM sets/sheets, edit text fields, issue timestamped e-prescriptions, and add visit notes.
* **Step-by-Step Flow:**
  1. MD Homepage $\rightarrow$ Select patient (e.g., "John Doe")
  2. Patient Profile $\rightarrow$ View 3-column overview: Health Records (left), Prescriptions (middle), Clinical Notes (right)
  3. Manage Records $\rightarrow$ Select "Add Record" or click existing entry (e.g., "Brain MRI") to update text/files and click "Update Changes"
  4. Manage Prescriptions $\rightarrow$ Select "Add Order", auto-fill medication via name search, adjust dosage/duration, and click "Order"

---

## Usability Study & Quantitative Evaluation

An empirical usability study was conducted with 15 participants (ages 20–50; 80% patients, 26.7% clinical staff) using remote interactive Figma testing and structured Google Forms surveys.

| Task / Evaluation Category | Metric / Satisfaction Rating | Observed Strengths & Feedback |
| :--- | :--- | :--- |
| **Booking Appointments** | **78.6%** (3.93 / 5) | Intuitive step-by-step flow and provider context retention. |
| **Modifying / Cancelling** | **80.0%** (4.00 / 5) | Straightforward appointment management cards. |
| **Clinic List Browsing** | **78.6%** (3.93 / 5) | Clear layout, useful distance sorting, and informative chips. |
| **Locating Health Records** | **81.6%** (4.08 / 5) | Searchable layout; fast navigation to diagnostic history. |
| **Understanding Test Results** | **77.2%** (3.86 / 5) | Two-level detail view balances quick scans with deep detail. |
| **Doctor: Adding New Record** | **72.8%** (3.64 / 5) | Clean separation of medical record categories. |
| **Doctor: Updating Prescriptions** | **74.6%** (3.73 / 5) | Direct side-by-side management of treatment history. |
| **Doctor: Editing Records** | **76.4%** (3.82 / 5) | Logical layout, though needed stronger save feedback. |

### Summary of Results
* **Overall Usability:** Core workflows scored consistently between **73% and 82%**, validating the overall UI structure.
* **Visual Appeal:** 40% of participants explicitly highlighted the clean, minimalistic design as their favorite feature.
* **Key Areas for Refinement:** Misfiring touch targets (attributable to prototype frame constraints), lack of instant save confirmation dialogs, and minor filter logic bugs.

---

## Project Limitations

1. **Participant Scope:** Small evaluation sample (n=15) focused primarily on tech-literate users aged 20–50; lacked dedicated testing with elderly or severely impaired user groups.
2. **Prototype Constraints:** Interactive mid-fidelity Figma constraints led to occasional unclickability or frame jumps.
3. **Session Duration:** Short task-based sessions evaluated single interactions rather than multi-month record tracking.
4. **Accessibility Audits:** Formal screen-reader, high-contrast, and haptic testing with disabled participants was not conducted.
5. **Real-World Testing:** System was not tested on large tablets or within noisy, fast-paced clinical waiting rooms.

---


## Future Roadmap




0–3 Months (Short-Term)       3–6 Months (Medium-Term)      6–12 Months (Long-Term)      12+ Months (Vision)
[Phase 1]                      [Phase 2]                    [Phase 3]                    [Phase 4]
Interaction Fixes          Accessibility & Templates     Multi-Device & OS      AI & Enterprise Integration



* **Phase 1: Immediate Interaction Fixes (0–3 Months)**
  * Standardize touch hitboxes, expand button padding, and fix broken Figma links.
  * Implement explicit save confirmation popups and quick error notifications.
  * Refine filter logic and simplify medical terminology across all pages.

* **Phase 2: Accessibility & Clinical Efficiency (3–6 Months)**
  * Add full screen-reader compliance, dark high-contrast mode, and dynamic text scaling.
  * Introduce clinician autosave, quick-note templates, and edit history summaries.

* **Phase 3: Multi-Platform Scaling (6–12 Months)**
  * Optimize layouts for tablet viewports and native iOS/Android/Windows runtimes.
  * Conduct multi-month longitudinal field studies to measure ongoing patient retention.

* **Phase 4: Advanced AI & Integration (12+ Months)**
  * Implement multi-language translations tailored for low-literacy populations.
  * Integrate AI-driven features: smart appointment suggestions, auto-generated lab summaries, and medication adherence alerts.
  * Perform pilot evaluations inside active hospital wards and primary care clinics.

