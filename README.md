# CPU Scheduling Algorithms in C++

This project demonstrates two CPU Scheduling techniques used in Operating Systems:

1️⃣ **Round Robin Scheduling** (Preemptive)  
2️⃣ **FCFS – First Come First Serve Scheduling** (Non-Preemptive)

---

## 🧠 CPU Scheduling Overview
CPU Scheduling is a fundamental concept in operating systems that determines the order in which processes are executed.  
This project calculates:
✔ Completion Time  
✔ Waiting Time  
✔ Turnaround Time  
✔ Average Waiting & Turnaround Time  

---

## 🛠️ Technologies Used
- C++ Programming Language
- Concepts of Operating System Scheduling
- Standard Template Library (queue)

---

## 📌 Features
| Feature | FCFS | Round Robin |
|--------|:----:|:-----------:|
| Preemptive | ❌ | ✔ |
| Uses Queue | ✔ | ✔ |
| Fair for all processes | ❌ | ✔ |
| Minimal context switching | ✔ | ❌ |

---

## 📂 Project Files
| File | Description |
|------|-------------|
| `fcfs.cpp` | Implementation of First Come First Serve algorithm |
| `round_robin.cpp` | Implementation of Round Robin scheduling algorithm |

---

## ▶️ How to Run the Program

### Compile
```sh
g++ fcfs.cpp -o fcfs
g++ round_robin.cpp -o rr

### Execute
./fcfs
./rr

GitHub: your username here
