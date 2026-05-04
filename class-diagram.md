 #Smart Parking Management System
 # Class Diagram – Smart Parking Management System
 ## Classes and Relationships
 
### 1. User (Base Class)
- userId
- name
- email
- password
- role
 
---
 
### 2. Customer (extends User)
- phoneNumber
- bookingHistory
 
---
 
### 3. ParkingOwner (extends User)
- ownerId
- parkingSlots
 
---
 
### 4. Admin (extends User)
- adminId
- manageUsers()
- manageBookings()
- managePayments()
 
---
 
### 5. ParkingSlot
- slotId
- location
- slotType (Car/Bike/Both)
- pricePerHour
- availabilityStatus
 
---
 
### 6. Booking
- bookingId
- customerId
- slotId
- bookingTime
- status
 
---
 
### 7. Payment
- paymentId
- bookingId
- amount
- paymentMethod
- paymentStatus
 
---
 
## Relationships
 
- User → Customer, ParkingOwner, Admin (Inheritance)
 
- Customer → Booking (1 to many)
- ParkingOwner → ParkingSlot (1 to many)
- Booking → ParkingSlot (many to 1)
- Booking → Payment (1 to 1)
 
---
 
## Simple UML Representation
 
User
│
├── Customer
├── ParkingOwner
└── Admin
 
Customer ────< Booking >──── ParkingSlot
                      │
                   Payment
