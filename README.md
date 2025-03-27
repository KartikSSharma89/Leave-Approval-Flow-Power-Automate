# Leave-Approval-Flow-Power-Automate
This project is a Leave Approval Workflow built using Microsoft Power Automate for Technicolor India. It automates the leave request process, ensuring a smooth and efficient approval system.

**Features**

✅ Automated Leave Requests: Employees submit leave requests via a Microsoft Form.

✅ Conditional Approval Logic: Requests are validated based on the leave start date compared to the current date.

✅ Instant Notifications: First-level approvers receive notifications for pending approvals.

✅ Once the first level approves then request goes to the second level for consents

✅ Seamless Integration: Works with Microsoft Forms, Outlook, and Excel for record-keeping.

**Technologies Used**

1. Microsoft Power Automate – Workflow automation

2. Microsoft Forms – Leave request collection

3. Outlook / Teams – Notifications & approvals

**How It Works**

1. An employee submits a leave request using a Microsoft Form.

2. The flow fetches the response and checks the leave start date.

3. If the leave start date is in the future, the request is processed for approval.

4. If approved, a notification is sent to the employee and HR.

**Setup Instructions**

1. Import the Power Automate Flow into your Microsoft environment.

2. Configure Microsoft Forms to collect leave request details.

3. Update the approval logic as per your company’s policies.

4. Test the flow and deploy it for organization-wide use.

**Future Enhancements**

1. Leave balance tracking

2. Integration with HRMS
