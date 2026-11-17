#  Expense Tracker

A simple personal expense tracker built with Flask, SQLite and Chart.js. Track your income and expenses, set a monthly budget and see where your money goes.

##  Features

- **Authentication:** signup, login and logout with hashed passwords and CSRF protection
- **Dashboard:** income, expenses and balance at a glance, budget progress and recent activity
- **Transactions:** add, edit and delete income and expenses, with 13 categories, search, filters and pagination
- **Reports:** income vs expense bar chart and expenses-by-category doughnut chart
- **Budget:** monthly spending cap with color-coded progress (green, yellow, red)
- **Profile:** update your name, email or password
- **Dark / light theme** that is remembered between visits
- **Responsive design** that works on mobile

##  Tech Stack

Python · Flask · Flask-Login · Flask-SQLAlchemy · SQLite · Flask-WTF · Jinja2 · JavaScript · Chart.js · Font Awesome




##  Project Structure

```
expense_tracker/
├── app.py              # Routes and app setup
├── models.py           # User, Transaction, Budget
├── config.py           # Configuration
├── requirements.txt
├── templates/          # HTML pages (Jinja2)
└── static/             # CSS and JavaScript
```

## Configuration

Set these environment variables for production:

| Variable | Purpose |
|---|---|
| `SECRET_KEY` | Signs sessions and CSRF tokens |
| `DATABASE_URL` | Database connection (defaults to SQLite) |

## Roadmap

- Recurring transactions
- CSV import / export
- Per-category budgets
- Multi-currency support

##  Author

Made by [Hamza Asghar](https://github.com/hamza5849)
