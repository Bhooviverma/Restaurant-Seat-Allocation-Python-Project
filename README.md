# 🍽️ Dine & Reserve

A simple restaurant booking desktop app built with **Python (Tkinter)** and **MongoDB**.

---

## 🚀 Features

* Select city & restaurant
* View seat availability
* Choose table (Indoor/Outdoor)
* Enter booking details
* Auto cost calculation
* Unique booking ID
* View previous bookings

---

## 🛠️ Tech Stack

* Python (Tkinter)
* MongoDB (PyMongo)

---

## ⚙️ Setup

```bash
git clone https://github.com/bhooviverma/Restaurant-Seat-Allocation-Python-Project.git
cd dine-reserve
pip install pymongo

Start MongoDB:

```bash
mongod
```

Add sample data:

```json
{
  "name": "Spice Garden",
  "city": "Delhi",
  "available_seats": 20,
  "price_per_person": 500
}
```

Run app:

```bash
python main.py
```

---

## 📂 Collections

* **data** → restaurants
* **bookings** → reservations

---

