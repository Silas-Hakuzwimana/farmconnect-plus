
# 🌾 FarmConnect+

**FarmConnect+** is a global platform that empowers farmers by directly connecting them with local and international markets. By leveraging technology, FarmConnect+ aims to improve market access, reduce exploitation, and create sustainable agricultural trade networks worldwide.

---

## 🌍 Overview

Millions of farmers around the world face challenges in reaching the right buyers for their products. **FarmConnect+** bridges this gap by offering a digital platform that facilitates:

* Direct communication between farmers and buyers
* Transparent and fair trade practices
* Real-time market data and product availability
* Improved agricultural supply chains

---

## 🚀 Key Features

* 👩‍🌾 **Farmer Registration & Crop Listings**
* 🛒 **Marketplace for Buyers & Sellers**
* 📊 **Dynamic Dashboard for Prices and Trends**
* 🧭 **Location-Based Produce Discovery**
* 📦 **Order and Delivery Management**
* 🌐 **Multi-language & Mobile-Friendly UI**
* 🔐 **Secure Authentication and Transactions**

---

## 🛠 Tech Stack

| Layer      | Technology                             |
| ---------- | -------------------------------------- |
| Frontend   | HTML, CSS, JavaScript                  |
| Backend    | Django (Python)                        |
| Database   | MySQL                                  |
| API Layer  | Django REST Framework                  |
| Deployment | Docker / Gunicorn / Nginx              |
| Hosting    | DigitalOcean / Heroku / AWS (Optional) |

---

## 📦 Installation Guide

### ✅ Prerequisites

* Python 3.9+
* MySQL Server
* pip, virtualenv
* Git

### 📥 Clone the Repository

```bash
git clone https://github.com/Silas-Hakuzwimana/farmconnect-plus.git
cd farmconnect-plus
```

### ⚙️ Setup Virtual Environment

```bash
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
```

### 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

### 🛠 Configure Environment

Create a `.env` file or edit `settings.py` with your MySQL database credentials:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'farmconnect_db',
        'USER': 'farmconnectplusadmin',
        'PASSWORD': '',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

### 🔨 Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 👤 Create Superuser (for admin panel)

```bash
python manage.py createsuperuser
```

### ▶️ Start the Development Server

```bash
python manage.py runserver
```

Visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🧪 Testing

```bash
python manage.py test
```

---

## 📂 Project Structure

```
farmconnect-plus/
├── frontend/         # HTML, CSS, JS files
├── backend/          # Django project files
│   ├── core/         # Main app logic
│   └── users/        # Auth and user-related models
├── templates/        # Django templates
├── static/           # Static files
├── media/            # Uploaded images/media
└── manage.py
```

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file.

---

## 🤝 Contributing

We welcome contributions from developers, designers, and agriculture experts.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

---

## 📫 Contact & Support

* 📧 Email: [hakusilas@gmail.com](mailto:hakusilas@gmail.com)


---

## 🌱 *Empowering Farmers. Connecting Markets. Feeding the World.*


