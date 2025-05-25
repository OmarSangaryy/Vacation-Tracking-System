# Vacation Time System (VTS)

## 📌 Overview

The **Vacation Time System (VTS)** is a comprehensive solution aimed at automating and streamlining employee leave management within the Human Resources (HR) domain. It improves efficiency and transparency in handling vacation requests, sick leaves, and personal time off for both employees and managers.

---

## 🎯 Vision

To deliver a **user-friendly**, **efficient**, and **transparent** platform for vacation management, ultimately boosting organizational productivity.

---

## ✅ Functional Requirements

- **Vacation Management:**  
  Employees can submit and manage requests for vacation time, sick leave, and personal time off.

- **Historical Data Access:**  
  Ability to view and retrieve vacation requests from the previous calendar year.

- **Flexible Rules-Based System:**  
  Validates leave requests based on configurable organizational policies.

- **Manager Approval Workflow:**  
  Supports a manager review and approval process when required.

- **Status Change Notifications:**

  - Sends email to managers for approval requests.
  - Notifies employees of status updates on their leave requests.

- **Employee Vacation Summary API:**  
  Secure internal API that allows retrieval of employee vacation request summaries.

---

## ⚙️ Non-Functional Requirements

- **Ease of Use:**  
  User-friendly and intuitive interface.

- **Time Efficiency:**  
  Speeds up the process of submitting and approving vacation requests.

- **Cost Efficiency:**  
  Reduces manual effort for HR, managers, and employees — saving time and cost.

- **Integration with Internal Portal:**  
  Supports authentication through the organization's existing Single Sign-On (SSO) mechanism.

---

## 🚧 Constraints

- **SSO Integration:**  
  Must integrate with the organization’s SSO for authentication.

- **Historical Data Access:**  
  Must support access to leave requests from the previous calendar year.

- **Logging and Notifications:**
  - **Activity Logging:** Maintains detailed logs for all transactions.
  - **Email Notifications:** Informs managers and employees of relevant actions.

---

## 🧩 System Sequence Diagram

![System Sequence Diagram](vts%20sequence%20diagram.png)

<!-- If the filename contains spaces, using %20 works for GitHub -->

---

## 📂 Folder Structure

Make sure both `README.md` and `vts sequence diagram.png` are in the **same directory** to ensure the image renders correctly.

---
