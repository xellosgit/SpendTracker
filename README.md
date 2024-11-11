# Spend Traker - Personal Finance Tracker

**Spend Traker** is a full-featured web application built with Django, designed to simplify the management of personal finances. Whether you're tracking daily expenses, managing different sources of income, or setting personalized preferences, TrulyExpenses offers a user-friendly solution to keep your financial life organized.

## 🚀 Features

- **Secure User Authentication**: Robust sign-up, login, and password management functionalities with Django's authentication system.
- **Expense Management**: Easily add, edit, categorize, and delete expenses. Track spending with detailed descriptions and timestamps.
- **Income Tracking**: Manage multiple income sources and gain insights into your financial inflows.
- **User Preferences**: Configure settings such as preferred currency, categories, and other user-specific preferences.
- **Currency Conversion**: Supports multiple currencies, enabling tracking of expenses in different regions.
- **Responsive Design**: Fully responsive interface, optimized for both desktop and mobile use.
- **Data Security**: Includes environment variable support for secure configuration management.

## 🛠️ Technologies Used

- **Backend**: Django (Python), SQLite database
- **Frontend**: JavaScript, HTML5, CSS3, Django Templating Engine
- **Deployment**: Uses `Procfile` for easy deployment on platforms like Heroku
- **Environment Management**: `Pipenv` for dependency management and virtual environments

## 📂 Project Structure

- **authentication**: Manages user registration, login, and account-related utilities.
- **expenses**: Core functionality for managing expenses, including views, models, and URLs.
- **userincome**: Handles income-related features, allowing users to log different income streams.
- **userpreferences**: Manages user settings, such as currency preferences and category management.
- **expenseswebsite**: Core project settings, static files, and routing configurations.
- **templates**: HTML templates for rendering views, structured into authentication, expenses, and income management pages.

## 📊 Future Enhancements

- **Analytics Dashboard**: Visualize income vs. expenses trends using charts.
- **Notifications**: Set reminders for upcoming bills or budget limits.
- **API Integration**: Provide a REST API for third-party integration.
