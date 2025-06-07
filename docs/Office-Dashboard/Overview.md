# Office Dashboard - Help Documentation

## Overview
**Purpose**:  
The Office Dashboard allows staff to **schedule, track, and manage appointments** in real-time using a Kanban-style interface. Appointments are categorized by status (e.g., "Scheduled," "Checked In"), and users can manually update statuses as patients progress through their visit.

**User Roles**:  
- Front Desk  
- Providers  
- Physician Assistants (PA)  
- Medical Assistants (MA)  
- System Admins  

---

## UI Elements & Functionality

### 1. Filters Section
- **Locations Dropdown**: Filter appointments by clinic location.  
- **Providers Dropdown**: Filter by provider (e.g., Dr. Smith).  
- **Date Range Picker**: Select a date range (e.g., "Today" or custom range).  
- **Quick Buttons**:  
  - **Search/Refresh**: Apply filters or reset.  
  - **Display Settings**: Toggle columns on/off.  

### 2. Results Section (Kanban Board)
- **Columns**:  
  - `Scheduled` → `Unresponsive` → `Confirmed` → `Checked In` → `Registered` → `In Progress` → `Checked Out` → `Completed` → `Cancelled` → `Reschedule Requested` → `Cancellation Requested`.  
- **Appointment Cards**:  
  - **Patient Name**, **Time**, **Provider**, **Visit Type** (e.g., "Follow-up").  
  - **Color Coding**: Priority levels (e.g., red for overdue).  
  - **Drag & Drop**: Move cards between columns to update status.  

---

## Step-by-Step Workflows

### Create an Appointment
1. Click **"+ New Appointment"** (top-right corner).  
2. Fill in:  
   - Patient (search by name/MR#).  
   - Provider, Location, Date/Time.  
   - Visit Type (e.g., "Annual Physical").  
3. Click **"Save"**. The appointment appears in the `Scheduled` column.  

### Update Appointment Status
1. **Drag & Drop** the appointment card to the next relevant column (e.g., `Scheduled` → `Checked In` when the patient arrives).  
2. **Optional**: Right-click a card to:  
   - Add notes (e.g., "Patient late by 15 mins").  
   - Request rescheduling.  

### Customize View
1. Click **"Display Settings"**.  
2. Toggle columns (e.g., hide `Unresponsive` if unused).  

---

## FAQs & Troubleshooting
**Q: Why can’t I see certain appointments?**  
- Verify **filters** (e.g., correct date range/provider selected).  

**Q: How to handle a no-show?**  
- Drag the appointment to `Cancelled` and add a note ("No-show").  

**Q: Can I bulk-update statuses?**  
- Yes! Select multiple cards (Shift+Click) and drag to the new column.  

---

## Visual Guide
![Office Dashboard Screenshot](../asset/Overview.png)  
*Annotations*:  
1. **A**: Filters section.  
2. **B**: Kanban columns with appointment cards.  
3. **C**: Drag-and-drop demo.  

---

## Permissions
- **Front Desk/MA**: Can create/move appointments but not delete.  
- **Providers/Admins**: Full access (edit/delete).  