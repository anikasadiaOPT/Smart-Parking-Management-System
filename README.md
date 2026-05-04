# Smart Parking Management System

A mobile application concept for discovering, reserving, and paying for parking spaces—designed to reduce time spent searching for parking, ease traffic congestion, and improve parking space utilization.

## Goals & Objectives

- Help drivers find available parking spaces easily.
- Offer a pre-booked parking slot facility.
- Ease traffic jams caused by unplanned parking.
- Minimize illegal parking iin urban areas.
- Ensure efficient use of parking spaces.
- Save time and reduce driver frustration.

## Client

**SOFTWARE GROUP AND INDUSTRY**

## Product Overview

- **Product type:** Mobile Application
- **Access layers / roles:** User (Driver), Admin, Parking Lot Owner
- **Design required:** Yes

## Core Features

### 1) Authentication

**Signup (All Users)**
- Create account with name, email, password, and role.
- Email must be unique.
- Password must meet security rules and match confirmation.

**Signin (All Users)**
- Login with email + password.
- Optional “Remember me”.
- Links to Signup and Forgot Password.

**Signup (Parking Lot Owner)**
- Register with full name, email, phone number, password, and NID/Trade License.
- Validations: unique email, password ≥ 8 chars, password match, document required.
- On success: owner redirected to dashboard and confirmation email sent.

**Forgot Password (Admin, User)**
- Request a code by email.
- Verify code and set a new password.

### 2) Dashboards & Menus

**Driver / Customer menu**
- Dashboard
- View/Edit Profile
- Change Profile Photo
- Change Password
- Driving License Info
- Find Parking
- My Bookings
- Payment Methods
- Transaction History
- Notifications
- Logout

**Admin dashboard**
- Summary cards: Total Users, Total Parking Spots, Total Bookings, Total Revenue.
- Management sections: Customer/Driver, Parking Lot Owner, Parking Management, Booking Management, Payment, Reports, Settings.


**Parking Lot Owner dashboard**
- Summary cards: Total Earnings, Active Slots, Pending Bookings, Confirmed Bookings.
- Menu: My Slots, Add New Slot, Booking Requests, Earnings, Profile, Change Password, Logout.

### 3) Navigation (Top & Bottom Bars)

**Top bar**
- Platform logo/name (links to dashboard)
- Global search
- Notification bell
- Profile dropdown (View Profile, Settings, Logout)

**Bottom bar**
- About Us | Contact | Privacy Policy | Terms of Service
- Copyright + year

### 4) Driver Profile & Verification

- View Profile (personal + vehicle information)
- Edit Profile (update basic info, gender, DOB, vehicle type)
- Change Profile Photo (png/jpg)
- Change Password (email + verification code flow)
- Driving License Info (license number, expiry date, image upload)

### 5) Parking Search, Booking & Reservation

**Search parking spots (Driver)**
- Address/keyword search
- Filters: vehicle type, price range, distance
- Map view + list view results

**Real-time availability (Driver)**
- Auto refresh every 30 seconds
- Status indicators: Green (available), Red (taken), Amber (expiring)
- “Last updated” timestamp

**Slot booking flow (Driver)**
- Select date/time/duration
- Choose vehicle
- Slot held for 10 minutes during payment
- Booking summary before confirmation

**Booking confirmation (Driver)**
- Confirmation screen includes QR code
- Confirmation via SMS/push
- Booking ID + details
- Option to add to calendar


**Manage bookings (Driver)**
- Tabs: upcoming, active, past
- Cancel up to 2 hours before start
- Extend booking if the spot is free

**Booking cancellation (Driver)**
- Cancel reason required
- Refund policy shown before confirm
- Full refund if cancelled ≥ 2 hours early; 50% forfeited within 2 hours

### 6) Payments

- 50% advance payment to hold slot
- Remaining balance payment (at arrival / as configured)
- Payment methods: card, mobile banking
- Transaction history with filters and payment status

### 7) Notifications

- Real-time alerts for bookings, payments, and system messages
- Stored notification history

### 8) Parking Lot Owner Features

- View/Edit profile
- Manage slots (list, add, edit, delete)
- Add parking space/listing (pending admin approval)
- Earnings dashboard and transaction list

### 9) Admin Panel

- Manage customers/drivers (search, filter, block/unblock)
- Manage parking owners (approve/reject, status filters)
- Manage bookings (approve/cancel, status filters)
- Manage payments (confirm/refund, status filters)

