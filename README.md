# ChillBill: Personal Receipt & Expense Manager

## Description

ChillBill is a personal accounting application designed to help individuals and groups manage digital receipts, split expenses, detect recurring subscriptions, and generate meaningful spending insights. By providing a centralized dashboard, automated reminders, and advanced analytics, ChillBill simplifies personal and group financial management.

### Key Features
- **Receipt Management:** Upload, store, and categorize receipts with OCR capabilities.
- **Expense Splitting:** Easily handle shared expenses for trips, events, or household costs.
- **Financial Insights & Analytics:** Track spending trends, category breakdowns, and get predictive insights.
- **Subscription Detection & Management:** Identify recurring subscriptions and get reminders before they renew.
- **Notifications:** Alerts for due payments, subscription renewals, overspending, and group expense updates.
- **Security:** AES-256 encryption for stored data, robust authentication, and best practices to avoid common web vulnerabilities.

## Motivation

### Primary Problems to Solve
1. **Disorganized Receipts**: Traditional paper receipts are often lost or damaged. ChillBill digitizes receipts and extracts relevant data automatically.
2. **Painful Expense Splitting**: Manually splitting bills among multiple people leads to confusion and errors. ChillBill automates cost-sharing with a clear dashboard.
3. **Recurring Subscriptions**: Many users forget about recurring charges until they see an unexpected bank statement. ChillBill detects subscriptions and sends timely reminders.
4. **Financial Visibility**: Most people lack a holistic view of their spending patterns. ChillBill aggregates receipts and bank transactions to provide actionable insights.
5. **Security & Trust**: Users need confidence that their financial data is safe. ChillBill uses AES-256 encryption and robust security measures.

### Why ChillBill?
- **Paperless Organization**: Store all receipts digitally in one place.
- **Time Savings**: Automated OCR and bank integrations reduce manual data entry.
- **Transparency in Group Expenses**: Automatically calculate each person’s share.
- **Subscription Oversight**: Detect recurring fees and get reminders for renewals.
- **Actionable Insights**: Clear visualizations help users make better financial decisions.
- **Security & Privacy**: AES-256 encryption and secure best practices ensure data safety.

## Installation

### Prerequisites
- Python (>= v3.10)
- Django (backend framework)
- Node.js (for frontend, if using Next.js)
- Tesseract OCR or Google Vision API (for receipt parsing)
- Plaid or Flinks API (for financial aggregation)
- MongoDB 

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ChillBill.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ChillBill
   ```
3. Set up the backend:
   - Install Python dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Set up the database:
     ```bash
     python manage.py migrate
     ```
4. Set up the frontend:
   - Install Node.js dependencies:
     ```bash
     npm install
     ```
   - Start the development server:
     ```bash
     npm run dev
     ```
5. Run the application:
   ```bash
   python manage.py runserver
   ```

## Contribution

We welcome contributions! Here’s how you can help:

### Git Workflow
1. **Git Flow**: Yes, we use Git Flow. Feature branches are created from `develop` and merged back after review.
2. **Branch Naming**: Use the format `feature/your-feature-name`, `bugfix/your-bugfix-name`, or `hotfix/your-hotfix-name`.
3. **Issue Tracking**: We use GitHub Issues to track bugs and feature requests.
4. **Pull Requests**: Submit a pull request with a clear description of your changes. Ensure your code passes all tests and follows the project’s coding standards.

### Steps to Contribute
1. Open [an issue](https://github.com/UTSC-CSCC01-Software-Engineering-I/term-group-project-c01w25-project-ohamaland/issues/new/choose) to discuss your proposed changes.
2. Fork the repository and create a new branch.
3. Make your changes and test thoroughly.
4. Submit a pull request, referencing the related issue.
