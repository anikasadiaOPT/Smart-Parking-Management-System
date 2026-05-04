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

**MOBARAK GROUP AND INDUSTRY**

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

