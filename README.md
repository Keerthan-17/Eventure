# 🎉 Eventure – Event Booking & Catering Management System

Eventure is a full-stack web application built using Django that allows users to explore event packages, customize catering options, book event slots, and view a detailed cost breakdown before confirming their booking.

The platform provides a smooth multi-step booking experience with a modern UI and dynamic pricing system.

---

## 🚀 Features

* 🔐 User Authentication (Register, Login, Logout)
* 🏠 Browse available event packages
* 📅 Slot booking with date & time selection
* 🍽️ Catering selection (Veg / Non-Veg menus)
* 🧾 Menu customization (add/remove items)
* 📊 Dynamic cost calculation with breakdown
* 💰 Final billing & confirmation system
* 🎨 Premium UI with responsive design
* ⚡ Smooth multi-step booking workflow

---

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS, Bootstrap
* **Database:** MySQL
* **Other:** Django Forms, Authentication System

---

## 📂 Project Structure

```
Eventure/
│── accounts/        # User authentication & profiles
│── btrpy/           # App file
│── events/          # Event booking logic
│── templates/       # HTML templates
│── static/          # CSS, JS, images
│── manage.py
│── MySQL
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/eventure.git
cd eventure
```

### 2. Create virtual environment

```
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Configure database

Update `settings.py` with your MySQL credentials.

### 5. Run migrations

```
python manage.py makemigrations
python manage.py migrate
```

### 6. Run server

```
python manage.py runserver
```

---

## 🧠 How It Works

1. User registers and logs in
2. Selects an event package
3. Chooses date & time slot
4. Selects catering type (Veg / Non-Veg)
5. Customizes menu items
6. Enters event details
7. Views cost breakdown
8. Confirms booking

---

## 🔮 Future Improvements

* 💳 Payment gateway integration
* 📧 Email confirmation system
* 📄 PDF invoice generation
* 📊 Admin dashboard
* ⭐ Ratings & reviews system

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Keerthan M**

* Computer Science Engineering
* Passionate about Web Development & AI

---

⭐ If you like this project, don’t forget to star the repo!
