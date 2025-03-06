# Amusement Park Digital Payment & Ticketing System - User Stories

## Guest User Stories

### 1. Purchase Entry Tickets
**User Story:**
"As a guest, I want to browse and purchase entry tickets online so that I can plan my visit to the amusement park easily."

**Acceptance Criteria:**
- Guests can view available time slots and ticket prices.
- Guests can purchase tickets for multiple people in a single transaction.
- A QR-coded virtual ticket is generated and sent via email after successful payment.
- If the selected time slot reaches 500 people, ticket purchases are disabled.

### 2. Purchase Ride Tickets
**User Story:**
"As a guest, I want to purchase ride tickets online or at the ride location so that I can access my preferred rides conveniently."

**Acceptance Criteria:**
- Guests can select and purchase ride tickets individually.
- Ride tickets are issued as QR codes and sent via email.
- Tickets can be canceled anytime within the booked entry ticket slot.
- Ride purchases are not affected by park capacity limits.

### 3. Cancel Entry Ticket
**User Story:**
"As a guest, I want to cancel my entry ticket so that I can get a refund if my plans change."

**Acceptance Criteria:**
- Guests can cancel entry tickets online up to 1 hour before the booked time slot.
- A 20% cancellation fee is applied.
- Guests receive a confirmation email upon successful cancellation.

### 4. Cancel Ride Ticket
**User Story:**
"As a guest, I want to cancel my ride ticket so that I don’t lose money if I change my mind."

**Acceptance Criteria:**
- Guests can cancel ride tickets anytime within their booked entry ticket slot.
- Ride ticket cancellations are fully refunded.
- Guests receive a confirmation email upon successful cancellation.

---
## Member User Stories

### 5. Receive Promotional Offers
**User Story:**
"As a registered member, I want to receive promotional offers so that I can get discounts and special deals on park tickets."

**Acceptance Criteria:**
- Members receive promotional offers via email and SMS.
- Promotional offers are personalized based on past purchases.
- Users can opt-in or opt-out of promotional campaigns.

### 6. View Purchase History
**User Story:**
"As a registered member, I want to view my past ticket purchases so that I can keep track of my visits."

**Acceptance Criteria:**
- Members can access a list of all past entry and ride ticket purchases.
- Members can download past ticket receipts.

### 7. Redeem Promotional Discounts
**User Story:**
"As a registered member, I want to apply promotional discount codes so that I can get cheaper tickets."

**Acceptance Criteria:**
- Members can apply discount codes at checkout.
- Discount history is tracked per member.
- Discounted amounts are reflected in the total payment before checkout.

---
## Admin User Stories

### 8. Manage Ticket Sales & Analytics
**User Story:**
"As an admin, I want to monitor and manage ticket sales so that I can ensure smooth park operations."

**Acceptance Criteria:**
- Admins can view daily, weekly, and monthly ticket sales reports.
- Admins can enable or disable ticket sales based on park capacity.
- System displays visitor trends and peak booking times.
- Cancellation statistics are available for analysis.

### 9. Monitor Park Capacity
**User Story:**
"As an admin, I want to track visitor capacity so that I can control entry ticket sales accordingly."

**Acceptance Criteria:**
- The system tracks and displays real-time visitor count per shift.
- Entry ticket sales are automatically disabled when capacity reaches 500.
- Ride ticket sales remain active regardless of park capacity.

### 10. Enable or Disable Ticket Sales
**User Story:**
"As an admin, I want to manually control ticket availability so that I can manage visitor flow."

**Acceptance Criteria:**
- Admins can enable or disable entry and ride ticket sales at any time.
- Visitors receive notifications when ticket sales are disabled.
- Disabled tickets cannot be purchased until re-enabled by an admin.

### 11. View Cancellation Reports
**User Story:**
"As an admin, I want to track ticket cancellations so that I can analyze refund trends."

**Acceptance Criteria:**
- Admins can view entry and ride ticket cancellation statistics.
- Refund percentages and reasons for cancellations are recorded.
- Admins can generate reports on cancellation trends.

---
## Owner User Stories

### 12. Manage Marketing Campaigns
**User Story:**
"As the park owner, I want to create and manage promotional campaigns so that I can increase park revenue and visitor engagement."

**Acceptance Criteria:**
- Owners can create and schedule email/SMS marketing campaigns.
- Promotional campaigns can be targeted based on user activity.
- Campaign performance is tracked, showing engagement rates.

### 13. Track Marketing Campaign Performance
**User Story:**
"As the park owner, I want to track promotional campaign effectiveness so that I can optimize future campaigns."

**Acceptance Criteria:**
- Engagement metrics such as open rates and conversions are displayed.
- Revenue impact of marketing campaigns is analyzed.
- Performance trends are visualized using graphs.

### 14. View Financial Reports
**User Story:**
"As the park owner, I want to analyze financial reports so that I can make informed business decisions."

**Acceptance Criteria:**
- Owners can access detailed financial summaries.
- Ticket sales revenue and marketing expenses are displayed.
- Reports can be exported for offline analysis.

### 15. Manage Admin Users
**User Story:**
"As the park owner, I want to manage admin accounts so that I can control who has access to park operations."

**Acceptance Criteria:**
- Owners can create, edit, or remove admin accounts.
- Admin roles and permissions can be modified.
- An audit log tracks all admin activities.

---
### 📌 **End of User Stories**
