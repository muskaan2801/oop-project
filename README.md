# Smart Parking Assistant 🚗

The **Smart Parking Assistant** is a C++ console-based project that simulates a smart parking management system using object-oriented programming (OOP) principles. It allows both users and administrators to interact with a parking system through an intuitive text-based menu.

## 💡 Features

- 👤 **User Panel**
  - Book nearest available slot or manually request a specific slot
  - View your current booking and entry time
  - Exit the parking area and generate a bill based on time spent

- 🔐 **Admin Panel**
  - View full parking map with booking status
  - Cancel any booked slot
  - Clear ticket history
  - Search tickets by specific date
  - Book slots manually on user request

- 🧾 **Ticket Generation**
  - Records entry/exit times and calculates fees
  - Logs data to `tickets.txt` for audit/history

## 🛠️ Technologies

- **Language:** C++
- **File Handling:** Logs are stored in `tickets.txt`
- **Time Library:** Uses `ctime` for tracking duration

## 📁 File Structure

- `Smart Parking Assisstant Oop project.cpp` — Main source code for the system
- `tickets.txt` — Log file automatically created/stored with booking data

## 🔧 How to Run

1. Make sure you have a C++ compiler (e.g., g++, MinGW)
2. Compile the code:

   ```bash
   g++ -o parking Smart\ Parking\ Assisstant\ Oop\ project.cpp
