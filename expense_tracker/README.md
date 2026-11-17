# Expense Tracker

A web-based personal finance management application built with **Python and Flask**. Track income and expenses, manage your budget, and monitor your financial activity through a simple dashboard.

This repository contains a customized version of an existing open-source Expense Tracker project, with updated branding, Pakistani Rupee (Rs.) currency display, and interface improvements.

## Features

- **User Authentication:** Register, log in, and manage your account.
- **Dashboard:** View an overview of your financial activity.
- **Transaction Management:** Add, edit, and delete income and expense transactions.
- **Transaction History:** View, search, and filter transactions.
- **Budget Management:** Manage your spending budget.
- **Reports:** Review your financial activity.
- **CSV Export:** Export transaction records.
- **Responsive Interface:** Clean and user-friendly design.
- **Pakistani Currency Display:** Amounts displayed using Rs.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web application framework |
| Flask-SQLAlchemy | Database integration |
| SQLite | Database |
| Flask-Login | User authentication |
| HTML5 | Page structure |
| CSS3 | Styling |
| JavaScript | Frontend interactions |
| Jinja2 | Dynamic HTML templates |
| Chart.js | Data visualization |

## Project Structure

```text
expense-tracker-flask/
│
├── expense_tracker/
│   ├── templates/
│   ├── static/
│   ├── app.py
│   └── requirements.txt
│
├── backend/
├── frontend/
├── tests/
├── test_reports/
├── README.md
└── .gitignore
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Navigate to the project directory

```bash
cd YOUR-REPOSITORY
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
cd expense_tracker
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

### 7. Open the application

Visit:

```text
http://127.0.0.1:5000
```

## Customizations

The following improvements were made to this version:

- Updated application branding to Expense Tracker.
- Changed displayed currency from Indian Rupees (₹) to Pakistani Rupees (Rs.).
- Updated dashboard headings and interface text.
- Improved login and registration page branding.
- Updated transaction form and transaction history presentation.
- Maintained the existing Flask routes and application functionality.

## Future Improvements

Potential improvements include:

- Advanced financial analytics.
- Monthly spending comparisons.
- More detailed expense visualizations.
- Budget notifications.
- PDF report generation.

## Author

**Hamza Asghar**

- GitHub: [hamza5849](https://github.com/hamza5849)
- LinkedIn: [Hamza Asghar](https://linkedin.com/in/hamza-a-asghar)

## Acknowledgement

This project is based on an existing open-source Expense Tracker application. Credit belongs to the original author and contributors. This repository contains personal customizations and interface improvements.

Please retain the original project's license and attribution requirements.

---

**Built with Python, Flask, and a focus on personal finance management.**