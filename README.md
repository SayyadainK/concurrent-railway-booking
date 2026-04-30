# Multi-threaded Railway Reservation System

## 📌 Project Overview
This Java-based console application simulates a **real-world railway ticket booking system**. The system is capable of handling **multiple user requests simultaneously** using Java's multithreading and synchronization mechanisms.

---

## 🎯 Core Functionalities
- ✅ **Seat Selection**: Users can book available seats.
- ❌ **Cancellation**: Cancel previously booked tickets.
- 💳 **Payment Validation**: Ensures payment before booking.
- 🧵 **Thread Safety**: Prevents overbooking with synchronized blocks.

---

## 🔧 Technologies Used
| Technology | Purpose |
|-----------|---------|
| Java      | Core programming, threading, synchronization |
| File I/O  | Storing booking records |
| DAO Pattern | Decoupled logic for booking management |
| Multithreading | Simulating multiple users |
| Git/GitHub | Version control |

---

## 🛠️ System Workflow
1. User interacts with the CLI menu.
2. Requests to book or cancel seats are managed by threads.
3. Synchronization ensures no two users book the same seat.
4. Payment is validated before confirming a seat.
5. Bookings are saved to a file `bookings.txt`.

---

## 🗃️ Project Structure
```
RailwayReservationSystem.java      # Main source code file
bookings.txt                       # Booking records (auto-created)
README.md                          # Project overview and instructions
```

---

## 🚀 How to Run
1. **Compile** the project:
   ```bash
   javac RailwayReservationSystem.java
   ```

2. **Run** the application:
   ```bash
   java RailwayReservationSystem
   ```

---

## 📌 Contributors
- Om
- Runjhun
- Kanishk

---

## 🔗 GitHub
Project Repository: [https://github.com/4ditxya/concurrent-railway-booking](https://github.com/4ditxya/concurrent-railway-booking)
