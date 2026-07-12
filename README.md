# 🏥 Health+ — Hospital Appointment Booking System

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org)
[![Django](https://img.shields.io/badge/Django-5.0+-092E20?style=flat-square&logo=django&logoColor=white)](https://www.djangoproject.com)
[![License](https://img.shields.io/badge/License-Educational-green?style=flat-square)](https://choosealicense.com)

A production-ready, modern Hospital Appointment Booking Web Application engineered with Django. `Health+` provides patients with a seamless, friction-free workflow to discover departments, select specialist doctors, and book clinical appointments through a highly responsive utility-first layout.
---

## ✨ Features

* **🧑‍⚕️ Intelligent Doctor Allocation:** Dynamically filter and browse certified medical professionals separated by clinical department.
* **📅 Date-Engine Booking:** Real-time appointment scheduling backed by native HTML5 date pickers.
* **📝 Dynamic Validation:** Bulletproof form processing handled natively through secure backend form validations.
* **🎨 Modern Utility UI:** Built on a unified aesthetic pairing the structured components of Bootstrap 5 with the design agility of Tailwind CSS classes.
* **📋 Enterprise Control Center:** Fully integrated Django Admin suite configures real-time management over `Departments`, `Doctors`, and `Appointments`.

---

## 🛠 Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **Python** | High-performance core backend object-oriented execution language. |
| **Django** | Robust web architecture providing strict ORM data security. |
| **SQLite** | Local relation database instance (ideal for development/testing). |
| **Bootstrap 5** | Underlying component architecture and base modal structures. |
| **Tailwind CSS** | Custom micro-layouts and advanced atomic alignment. |
| **Crispy Forms** | Structured, beautiful form rendering with integrated errors. |
---

## 📂 Project Structure

```
Project/
├── djenv/                   # Sandbox environment (Untracked via git)
├── Project/                 # Monolith Workspace Root
│   ├── home/                # Dynamic Application Layer
│   │   ├── migrations/      # Automated Database Evolution Scripts
│   │   ├── admin.py         # Control Panel Registration Layouts
│   │   ├── forms.py         # Form Processing Logic
│   │   ├── models.py        # Relational Data Models (Dept/Doc/Booking)
│   │   ├── urls.py          # Micro-routing Application Paths
│   │   └── views.py         # Request/Response Controllers
│   ├── Project/             # Global Application Config Hub
│   │   ├── settings.py      # Core Manifest Configuration File
│   │   └── urls.py          # Master Global Route Gateway
│   ├── static/              # Compiled Public Assets (CSS, Images, JS)
│   ├── templates/           # Modular Django HTML Templates
│   ├── uploads/             # Managed Server-side Media Storage
│   ├── db.sqlite3           # Live Local State File
│   ├── manage.py            # Active Task Executor Core Script
│   └── requirements.txt     # Locked Dependency Environment Map
└── README.md                # System Documentation Core

```
---
## ⚙️ Quickstart Installation & Setup
Follow these steps to deploy a local instance of `Health+` on your workspace.

### 1. Clone the Source Repository
```bash
git clone [https://github.com/nkswalih/health-appointment-system.git](https://github.com/nkswalih/health-appointment-system.git)
cd health-appointment-system
```

### 2. Configure Virtual Environment Sandbox
```bash
# Initialize instance
python -m venv venv
# Windows Activation Script
venv\Scripts\activate   
# macOS / Linux Activation Script
source venv/bin/activate  
```

### 3. Install Package Dependencies
```bash
pip install django django-crispy-forms crispy-bootstrap5
```

### 4. Database Schema Migration
Initialize the structural state migrations into your engine:

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Instantiate Administrative Superuser
```bash
python manage.py createsuperuser
```

### 6. Spin Up the Local Web Server
```bash
python manage.py runserver
```

Once initialized, navigate to [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to access the portal interface.
---
## 📅 Architecture & Workflows
### Appointment Booking Engine Flow
```
[Patient Enters Interface] ──> [Fills Metadata Details] ──> [Selects Dept / Doctor Instance]
                                                                        │
[Appointment Locked & Saved] <── [Display Toast Success] <── [Validates Backend Form Logic]
```
### Administrative Gateway Access

The backend system panel can be evaluated at [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/). Use your configured Superuser credentials to provision new clinic variables, update metadata records, and clear active patient queues instantly.

---

## 📸 Interface Previews

<img width="1898" height="968" alt="image" src="https://github.com/user-attachments/assets/f44cd89a-aac6-4de6-af17-d9aa95cd4a7d" />
<img width="1897" height="969" alt="image" src="https://github.com/user-attachments/assets/6817a7e7-373d-4536-838b-5355b122031b" />
<img width="1902" height="968" alt="image" src="https://github.com/user-attachments/assets/6bdedf8e-bd7f-4eb8-9470-30b1e7a54f46" />

---

## 🚀 Roadmap Roadmap & Future Enhancements

* [ ] **🔄 Reactive Asynchronous Queries:** Implement AJAX to instantly re-populate specialist selectors without requiring a complete page reload.

* [ ] **📧 Automated Notification Worker:** Connect SMTP mailers or Twilio queues to send direct system email alerts to patients.

* [ ] **⏰ Granular Time-Slot Matrix:** Shift from a basic date selector into an active chronological calendar grid tracking individual doctor hour blocks.

* [ ] **👤 Patient Profile Accounts:** Expand relational data models to include fully authenticated authorization sessions and self-serve history panels.

---

## 🤝 Contributing
Open-source contributions accelerate innovation! To propose modifications:

1. **Fork** the master repository.

2. Formulate a feature specific isolation branch (`git checkout -b feature/AmazingFeature`).

3. Commit your implementations safely (`git commit -m 'Add some AmazingFeature'`).

4. Push to the source upstream branch (`git push origin feature/AmazingFeature`).

5. Open a **Pull Request** file against our review targets.

---
## 📜 License

Distributed strictly for educational, research, and non-commercial learning evaluation purposes.

---

## 👨‍💻 Engineering Author

**Mohammed Swalih N K** *Front-End Architect & Full-Stack Django Engineer* * 🌐 **Portfolio Site:** [nkswalih-portfolio.vercel.app](https://nkswalih-portfolio.vercel.app/)

* 📫 **GitHub Workspace:** [@nkswalih](https://github.com/nkswalih)


