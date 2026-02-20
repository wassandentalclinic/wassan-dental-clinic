Wassan Dental & Skin Care Clinic Management System

A lightweight, high-performance practice management solution built for modern dental and skin clinics. This application provides a centralized platform for managing patient records, clinical procedures, financial accounting, and staff administration.

🚀 Core Features

1. Patient Lifecycle Management

Smart Booking: Quick registration for new patients and auto-recognition for returning patients via contact numbers.

MRN Generation: Automatic assignment of Medical Record Numbers (WDC-XXXX).

Electronic Health Records (EHR): Detailed tracking of medical history, allergies, and specific conditions.

2. Clinical Workflow

Visit History: Chronological logging of procedures, clinical notes, and prescriptions.

Sittings & Procedures: Track multiple sittings for complex treatments like RCT or orthodontics.

Digital Prescriptions: Maintain a record of medications advised during each visit.

3. Financial Module

Consolidated Dues List: A dedicated dashboard to track outstanding balances across the entire patient database.

Double-Entry Ledger: Every patient profile features a ledger tracking "Fees Charged" vs. "Payments Received."

Expense Tracker: Log clinic overheads (Rent, Lab Fees, Supplies, and "Other" miscellaneous costs).

Real-time Profit & Loss: Instant calculation of net profit based on actual cash inflow versus total clinic expenditures.

4. Staff Management

Salary Administration: Manage fixed monthly salaries, advances, and deductions.

Attendance & Leave: Log paid leaves, unpaid leaves, and absences with an automated impact on the monthly pending salary.

Finance Ledger: Individual staff ledgers to track historical payments and balances.

🛠 Technical Stack

Frontend: HTML5, CSS3 (Tailwind CSS Framework), JavaScript (ES6+).

Icons: FontAwesome 6.0.

Storage: Browser-based localStorage for persistent data across sessions without requiring a database server.

Design Philosophy: Mobile-first, responsive, and high-density UI for professional environments.

📈 Financial Calculation Logic

Income: Sum of all payment entries within a selected date range.

Expenses: Sum of all expense entries + staff salary disbursements.

Net Profit: Total Income - Total Expenses.

Dues: (Total Treatment Costs) - (Total Payments Received).

📂 Installation & Usage

Download the index.html file.

Open the file in any modern web browser (Chrome, Edge, Safari, or Firefox).

No internet connection is required after the initial load (CDN resources are cached).

Data Backup: It is recommended to periodically export your browser data or clear cache with caution, as data is stored locally on the device.

🛠 Recent Updates

Automated Datestamps: All date inputs now default to the current system date on load.

Expense Bug Fix: Improved "Other" category capturing in the P&L module to ensure 100% accounting accuracy.

Date Range Filters: Enhanced filtering on Dashboard and P&L tabs for precise reporting.

Developed for Wassan Dental & Skin Care Clinic.
