# **Amusement Park Digital Payment and Ticketing System**

## **Overview**

This project replaces the traditional physical ticketing and payment system of an amusement park with a **web-based digital ticketing solution**. The system allows park visitors to purchase **entry and ride tickets online**, receive **QR-coded virtual tickets**, and enables smooth validation by park employees.

## **Key Features**

### **1. Entry Ticketing System**

- Visitors can **purchase entry tickets online** via the amusement park’s website.
- **On-site Ticket Purchase:** Visitors can scan a **QR code at the park gate** to access the entry ticket purchase page.
- A visitor can **purchase tickets for multiple people** in one transaction.
- Upon successful purchase, visitors receive a **virtual ticket (PDF via email)** containing:
  - QR code for verification
  - Booking details (name, number of people, date, time slot)
- Park employees scan the QR code at the entrance for validation.

#### **Entry Ticket Pricing & Cancellation Policy**

- Tickets can be **canceled up to 1 hour before the booked time slot** with a **20% cancellation fee**.
- If a **time slot reaches capacity (500 people per shift), further ticket purchases will be disabled**.

### **2. Ride Ticketing System**

- Visitors can buy ride tickets **through the website** or **by scanning a QR code at each ride location**.
- A visitor can **purchase ride tickets for multiple people** in one transaction.
- Upon successful purchase, visitors receive a **virtual ticket** that includes:
  - QR code for ride validation
  - Number of people, ride name, time slot
- Ride tickets can be **canceled at any time without a deduction**, but only within the entry ticket’s booked time slot.
- Each ride operates **independently of the park’s capacity limit**, allowing multiple purchases for different rides.

### **3. Park Capacity Management**

- The amusement park operates in **two shifts per day**:
  - **Morning Shift:** 10 AM – 2 PM
  - **Evening Shift:** 4 PM – 8 PM
- Maximum **500 visitors per shift**.
- If a shift reaches full capacity:
  - The system will display a **“Capacity Reached”** message on the website.
  - Entry ticket purchases will be disabled.
  - Ride ticket purchases will remain active.

### **4. Admin & Owner Dashboard**

- A **dashboard for park owners and admins** provides **real-time analytics** on:
  - **Daily, weekly, and monthly ticket sales** (entry and ride tickets).
  - **Peak booking times and visitor trends**.
  - **Revenue generation from tickets**.
  - **Cancellation statistics**.

### **5. Promotional & Advertising Campaigns**

- Visitors who register on the website become **members** after OTP verification.
- **Only registered members** receive **promotional and advertising materials** via email and SMS.
- The system includes a **Campaign Management Panel** where park owners/admins can:
  - Create and send promotional campaigns.
  - Offer discounts and exclusive deals to members.
  - Track engagement and response rates.

## **User Roles & Access Control**

| **User Type** | **Permissions**                                                                                                             |
| ------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **Guest**     | Browse ticket options, purchase tickets (entry & rides), must register via OTP to become a **member and purchase tickets**. |
| **Member**    | All guest privileges + receives promotional offers and discounts.                                                           |
| **Admin**     | Manages ticket sales, monitors bookings, views analytics, and handles ride/entry ticket settings.                           |
| **Owner**     | All admin privileges + access to financial reports and campaign management.                                                 |

##

### 🚀 Developed by **Ehsaas Chaudhary**
