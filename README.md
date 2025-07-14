# 🧵 Threading Room Lock (Parallel Computing Demo)

This project demonstrates a simple use of **Python's threading and locking mechanisms**. It simulates multiple people trying to access a shared room with exclusive access (one at a time) using a `Lock`.

---

## 🚀 Features

- Uses `threading.Thread` for parallelism
- Demonstrates synchronization using `threading.Lock`
- Includes timeout handling
- Clear output of entry and exit from the critical section

---

## 🛠️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/threading-room-lock.git
cd threading-room-lock


##💡 Output Example

I am person 1 entered the room
I am person 1 exited the room
I am person 2 entered the room
I am person 2 exited the room
...
The room is empty!!!
