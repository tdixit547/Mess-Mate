# 🍽️ Hostel Mess Management System

A Django-based web application built to efficiently manage hostel mess operations. This system enables students, mess assistants, and administrators to perform mess-related tasks seamlessly through a centralized digital platform.

---

## 🚀 Features

- **Mess Cut Application:**  
  Apply for mess leave with built-in validation for overlapping dates and monthly limits.

- **QR Code Attendance:**  
  Scan QR codes for meal attendance. Automatically checks against mess cuts and meal schedules.

- **Mess Bill Management:**  
  View detailed bills and make payments online. Admins can generate and export billing data.

- **Weekly Menu Viewer:**  
  Access and review the updated weekly mess menu.

- **Feedback System:**  
  Submit feedback or suggestions directly from your dashboard.

---

## 🛠️ Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/hostel-mess-management.git
cd hostel-mess-management
```

2. **Set Up Virtual Environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a Superuser:**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the Application:**
   Open your browser and navigate to `http://127.0.0.1:8000`.

## Screenshots

*Add screenshots here to demonstrate key features of the application.*

- **Dashboard:**
  ![Dashboard](screenshots/dashboard.png)

- **Apply for Messcut:**
  ![Apply for Messcut](screenshots/apply_messcut.png)

- **QR Code Scanning:**
  ![QR Code Scanning](screenshots/scan_qr.png)

- **View and Pay Mess Bill:**
  ![View and Pay Mess Bill](screenshots/view_pay_bill.png)

## Usage

- **Students**: Log in to apply for mess cuts, view weekly menus, check and pay your mess bills, and submit feedback.
- **Mess Assistants**: Use the QR code scanning feature to mark attendance and manage mess operations.
- **Admins**: Oversee the entire system, manage users, and export bill data to CSV if needed.

## Contribution

Contributions are welcome! Feel free to open issues or submit pull requests.

## Contact

For any inquiries, please contact us at `tanmaydixit547@gmail.com`.
```

You can copy and paste this into your `README.md` file on GitHub.


---

Let me know if you'd like to auto-generate the screenshots layout using placeholders 
