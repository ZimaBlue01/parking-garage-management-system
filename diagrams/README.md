# System Diagrams

This folder contains the UML diagrams used to design and model the **Parking Garage Management System**.
Each diagram represents a different perspective of the system, focusing on structure, behavior, and interactions.

---

## 📌 Use Case Diagram
**File:** `use-case-diagram.pdf`

The Use Case Diagram illustrates the main functionalities of the system and how different actors interact with it.

**Actors include:**
- Client
- Eduvos Website
- License Plate Reader
- Parking Sensors
- Payment Processor

**Key use cases:**
- Reserve a parking space
- Find available parking spots
- Pay for parking
- Update parking reservations
- Pay for exceeded parking time
- Send parking notifications

This diagram provides a high-level functional overview of the system.

---

## 🔄 Activity Diagram
**File:** `activity-diagram.pdf`

The Activity Diagram models the complete workflow of the parking reservation and usage process.
It uses **swimlanes** to clearly show responsibilities across different system components.

The flow includes:
- User registration and reservation
- Payment processing
- Vehicle entry and license plate capture
- Parking allocation using sensors
- Overtime detection and additional charges
- Vehicle exit and sign-out

This diagram helps visualize the end-to-end system behavior.

---

## 🧩 Class Diagram
**File:** `class-diagram.pdf`

The Class Diagram represents the **static structure** of the system using object-oriented design principles.

It defines:
- Core classes such as `ParkingGarage`, `System`, `Reservation`, `User`, `Vehicle`, and `Payment`
- Relationships including aggregation, composition, association, and inheritance
- Specialized classes like `DailyReservation`, `MonthlyReservation`, and `BorrowedVehicle`

This diagram forms the backbone of the system’s architectural design.

---

## 🔁 State Machine Diagram
**File:** `state-machine-diagram.pdf`

The State Machine Diagram models the lifecycle of an **Account/Reservation** within the system.

Key states include:
- Created
- Unregistered / Registered
- Reservation Pending
- Reservation Confirmed
- Booking Pending
- Booking Confirmed
- Cancelled

State transitions depend on payment success, booking updates, and time constraints (such as the 24-hour update rule).

This diagram ensures correct system behavior across different scenarios.

---

## ✅ Purpose of These Diagrams

Together, these diagrams:
- Provide a complete system design specification
- Support clear communication between stakeholders
- Serve as a foundation for future system implementation
- Demonstrate structured software engineering and UML modeling skills

