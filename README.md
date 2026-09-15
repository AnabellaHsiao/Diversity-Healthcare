# Diversity Healthcare App (Phase 3)

Diversity Healthcare is a unified mobile healthcare application designed to streamline digital health management for both patients and healthcare providers. The Phase 3 release focuses on high-fidelity interactive Figma prototypes covering core end-to-end workflows including appointment management, clinical record tracking, e-prescribing, and localized clinic discovery.

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

## Interactive Prototypes

* **Doctor View Figma Prototype:** [View Doctor Interactive Flow](https://www.figma.com/proto/iZTQXMzdTFQXQ0KwxznBBp/Team-Diversity-Phase-3?node-id=1-15141&t=SLxFX9OPkkxF7DsD-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1)
* **Patient View Figma Prototype:** [View Patient Interactive Flow](https://www.figma.com/proto/iZTQXMzdTFQXQ0KwxznBBp/Team-Diversity-Phase-3?node-id=1-14638&t=vw1RliHkHYMZPN7v-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1)

---

## Core Task Workflows & Step-by-Step Instructions

### Task 1: View, Book, and Cancel Appointments
* **User Context:** A patient views nearby clinics, books an available time slot with a physician, updates appointment details if needed, or cancels and rebooks.
* **Patient Flow:**
  1. Homepage $\rightarrow$ Select "Check Clinics Nearby"
  2. Clinics Nearby $\rightarrow$ Select "Add Appointment"
  3. Add Appointment $\rightarrow$ Select physician (Dr. Eggward Cullen arrow)
  4. Dr. Eggward Cullen Page $\rightarrow$ Select "Accept"
  5. View Appointments $\rightarrow$ Select "Edit" next to Dr. Eggward Cullen
  6. Edit Page $\rightarrow$ Select "Update" to confirm changes

---

### Task 2: Health Records & Prescription Management

#### Patient Health Records View
* **User Context:** A patient views scrollable test results sorted by recency, applies filters/sorting, searches by test name, and views detailed result summaries and criteria scales.
* **Patient Flow:**
  1. Homepage $\rightarrow$ Select "Health Records"
  2. Health Records $\rightarrow$ Select "Cholesterol Test" (left arrow)
  3. Cholesterol Test Page $\rightarrow$ Review results and select top-left return arrow to return to records
  4. Health Records $\rightarrow$ Select top-left return arrow to return home

#### Doctor Health Records View (Add, View, Update)
* **User Context:** A physician views patient health records sorted by date, inspects uploaded files (CT/MRI DICOM sets or result sheets), updates text fields, and creates new record entries.
* **Doctor Flow:**
  1. MD Homepage $\rightarrow$ Select patient "John Doe" (Details button)
  2. Patient Record $\rightarrow$ Select "Brain MRI" (right arrow)
  3. Record Detail Page $\rightarrow$ View uploaded files and edit text fields $\rightarrow$ Select "Update Changes"
  4. Select top-left return arrow to return to Patient Record
  5. Patient Record $\rightarrow$ Select "Add Record" (mid-left)
  6. Select return arrow to return to Patient Record
  7. Select return arrow again to return to MD Homepage

#### Patient Prescription Orders View
* **User Context:** A patient checks ordered prescriptions, views drug details (pricing, OHIP coverage), reviews nearby pickup pharmacies, inspects pharmacy hours/maps/directions, and presents QR codes for fulfillment.
* **Patient Flow:**
  1. Homepage $\rightarrow$ Select "Prescriptions"
  2. Prescriptions $\rightarrow$ Select "Atorvastatin" (right arrow on drug card) $\rightarrow$ View Drug Details
  3. Drug Details $\rightarrow$ Select "Pharmacy 1 Details" $\rightarrow$ View location details and prescription info
  4. Select Back button $\rightarrow$ Return to Drug Details
  5. Select Back button $\rightarrow$ Return to Prescriptions
  6. Prescriptions $\rightarrow$ Select "Levothyroxine" (right arrow on drug card) $\rightarrow$ View Drug Details
  7. Select Back button $\rightarrow$ Return to Prescriptions
  8. Select Back button $\rightarrow$ Return to Homepage

#### Doctor Prescription Orders View (Add, View, Update)
* **User Context:** A doctor reviews a patient's prescription list, updates medication details, auto-fills new drug details via name search, and submits new orders.
* **Doctor Flow:**
  1. MD Homepage $\rightarrow$ Select patient "John Doe" (Details button)
  2. Patient Page $\rightarrow$ Select "Add Order" (center middle button) $\rightarrow$ Create New Drug Order
  3. Select "Order" or top-left back button $\rightarrow$ Return to John Doe page
  4. Patient Page $\rightarrow$ Select "Atorvastatin" (right arrow) $\rightarrow$ Update Drug Order
  5. Select "Update" or top-left back button $\rightarrow$ Return to John Doe page
  6. Select top-right Return button $\rightarrow$ Return to MD Homepage

---

### Task 3: Locate Nearby Clinics
* **User Context:** A patient scans a distance-sorted list of clinics, uses toggleable filters ("Open Now", "Favourites") or search, and views details (address, hours, languages, specialties) before booking.
* **Patient Flow:**
  1. Homepage $\rightarrow$ Select "Check Clinics Nearby" button at the bottom
  2. Clinics Nearby $\rightarrow$ Scroll default list (sorted by distance)
  3. Search Bar $\rightarrow$ Search for specific clinics (e.g., input "Town")
  4. Clinic Card $\rightarrow$ Select "Details" on Clinic Y to open Clinic Details page
  5. Clinic Details Page $\rightarrow$ View map, address, hours, distance, specialties, languages; scroll horizontally for doctors and availability
  6. Action $\rightarrow$ Select "Book Appointment" at the bottom of the details page to proceed

---

## Phase 4 Prototype Evaluation Plan

The upcoming Phase 4 evaluation will assess interface usability, learnability, and operational efficiency across three primary evaluation methods:

| Method | Target Audience | Primary Focus & Metrics |
| :--- | :--- | :--- |
| **Heuristic Evaluation** | 3 Independent Experts | Inspection using Nielsen’s 10 Heuristics to identify, rate severity, and resolve visibility, consistency, and error prevention flaws prior to user testing. |
| **Cognitive Walkthrough** | Design Team / Usability Experts | Step-by-step task execution to evaluate learnability for first-time patients and doctors, identifying goal-action mismatches or missing system feedback. |
| **Usability Testing** | Real Patients & Healthcare Users | Controlled sessions collecting quantitative metrics (task completion rates, error counts, task times) and qualitative data (think-aloud feedback, post-session satisfaction surveys). |

### Ethical Compliance
All evaluation protocols adhere strictly to the **University of Toronto Research Ethics Board** guidelines. Participation is strictly voluntary with informed consent, full rights of withdrawal without consequence, and zero collection of personal health information.