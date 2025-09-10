# 📌 Project Management Web - Tasks (Low-fi UI with Tailwind + DaisyUI)

## 1. Authentication
- [ ] **Login Page**
  - Input: Email, Password
  - Button: Login
  - (Optional) Register Page

---

## 2. Project Registration
- [ ] **Create Project Page**
  - Input: Project Name
  - Dropdown: Number of Students (1–2)
  - Button: Next

- [ ] **Project Details Page**
  - Textarea: Project Description
  - Input: Exam Date (date picker)
  - Upload: Proposal File (PDF)
  - Dropdown: Advisor Selection
  - Multi-Select: Committee Members (3 people)
  - Button: Submit Project

- [ ] **Waiting for Approval Page**
  - Status: Pending / Approved / Comment for revision
  - If Approved → Show Exam Date + Committee
  - If Comment → Redirect to Edit Project
  - If Rejected → Allow Re-submit

---

## 3. Progress Tracking
- [ ] **Progress Table Page**
  - Table Columns:
    - Week No.
    - Task Description
    - Status (✓ / ✗)
    - Advisor/Committee Comments
  - Button: Add Weekly Progress
  - Progress % Calculation (10% per week, 10 weeks total)

---

## 4. Final Submission
- [ ] **Final Project Submission Page**
  - Condition: Progress must be 100%
  - Upload Final Report (PDF)
  - Status: Waiting for Approval (3 committee members)
  - If All Approved → Show Success Message
  - If Rejected/Comment → Allow Re-upload

---

## 5. Optional Pages (Recommended)
- [ ] **Student Dashboard**
  - Overview of current project
  - Progress status (%)
  - Next deadline / exam schedule

- [ ] **Advisor/Committee Dashboard**
  - List of projects pending review
  - Action: Approve / Reject / Comment

- [ ] **Student Profile Page**
  - Personal info
  - History of projects

---

## 🔄 Flow Summary
1. Login  
2. Create Project → Enter details → Submit  
3. Wait for approval (Advisor & Committee)  
4. Track weekly progress (10 weeks = 100%)  
5. Submit final report  
6. Approval → Project completed 🎉
