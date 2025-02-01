# Project Title

A personal accounting app that allows users to store digital receipts, categorize them, split expenses, and generate meaningful insights.

## Description

Project title is a digital receipt management and expense tracking application designed to simplify personal and group financial management. It allows users to upload, store, and categorize receipts, split expenses among groups, and gain insights into their spending habits. The app leverages OCR technology, financial aggregator APIs, and advanced analytics to provide a seamless experience.

### Key Features
- **Receipt Management**: Upload, store, and categorize receipts using OCR technology (Tesseract or Google Vision API).
- **Expense Splitting**: Create groups for splitting expenses among friends, family, or housemates.
- **Manual Transaction Entry**: Add transactions manually for flexibility.
- **Financial Insights**: Analyze spending trends, category breakdowns, and predictive insights.
- **Subscription Tracking**: Detect recurring subscriptions and send reminders for cancellations.
- **Multi-Currency Support**: Automatically convert expenses in foreign currencies.
- **Offline Mode**: Log expenses without an internet connection and sync later.
- **Security**: Utilizes AES-256 encryption and protects against XSS, CSRF, SQL injection, and other attacks.

## Motivation

### Primary Problems to Solve
1. **Receipt Organization**: Managing paper or scattered email receipts is a hassle. ReceiptWise stores receipts digitally in a standardized format for easy tracking.
2. **Expense Sharing and Splitting**: Manually splitting costs for group events or shared expenses is time-consuming. ReceiptWise automates tracking and reconciliation.
3. **Financial Insights**: Disorganized data makes it hard to understand spending patterns. ReceiptWise provides clear insights to help users make data-driven budgeting decisions.

### Why ReceiptWise?
- Eliminates paper clutter by storing all receipts in one place.
- Simplifies group expense tracking with automated splitting.
- Provides actionable insights into spending habits.

## Installation

### Prerequisites
- Python (v3.8 or higher)
- Flask or Django (backend framework)
- Node.js (for frontend, if using Next.js)
- Tesseract OCR or Google Vision API (for receipt parsing)
- Plaid or Flinks API (for financial aggregation)
- PostgreSQL or another database system

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ReceiptWise.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ReceiptWise
   ```
3. Set up the backend:
   - Install Python dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Set up the database:
     ```bash
     python manage.py migrate  # For Django
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
   python manage.py runserver  # For Django
   flask run  # For Flask
   ```

## Contribution

We welcome contributions! Here’s how you can help:

### Git Workflow
1. **Git Flow**: Yes, we use Git Flow. Feature branches are created from `develop` and merged back after review.
2. **Branch Naming**: Use the format `feature/your-feature-name`, `bugfix/your-bugfix-name`, or `hotfix/your-hotfix-name`.
3. **Issue Tracking**: We use GitHub Issues to track bugs and feature requests.
4. **Pull Requests**: Submit a pull request with a clear description of your changes. Ensure your code passes all tests and follows the project’s coding standards.

### Steps to Contribute
1. Open an issue to discuss your proposed changes.
2. Fork the repository and create a new branch.
3. Make your changes and test thoroughly.
4. Submit a pull request, referencing the related issue.

## Resources

Here are some helpful resources for writing a great README and managing your project:
- [How to Write a Good README](https://www.makeareadme.com/)
- [Tips for Writing a README](https://dev.to/merlos/how-to-write-a-good-readme-bog)

## Development Priorities

### Sprint 0 Deliverables
- Team Contract (`team_contract.pdf`)
- Product Description (`product.md`)
- 2-3 User Personas
- README (`readme.md`)
- Product Backlog (`productbacklog.md`)
- Wireframes and Doodles (simple prototype)

### Long-Term Deliverables
1. **Receipt Data Structure**: Date, Amount, Line Items, Store Name, etc.
2. **Group Data Structure**: Group Name, Members, Amounts Owed, Receipts, Percentage per Item.
3. **Expense Splitting Logic**: Simplify amount owed per person.
4. **Frontend Components**: Display groups, receipts, etc. (functional but not polished).
5. **Backend Endpoints**: CRUD operations for receipts and user-specific features (e.g., credit card bill reconciliation).
6. **Spending Insights**: Backend endpoint for analytics.
7. **User Account Logic**: Authentication and encryption (AES-256).

### Code Setup
- Set up Flask/Django server.
- Set up a database (read/write functionality).
- Implement OCR for receipt parsing.
- Create transaction data models.
- Design frontend components (e.g., upload component, header, page wrapper) using Next.js.

## Key Value Proposition
- **Store All Receipts**: Eliminate paper clutter by storing receipts digitally.
- **Group and Tag Receipts**: Organize receipts for specific events (e.g., “Camping Trip”).
- **Split Expenses**: Automate expense splitting among group members.
- **Financial Insights**: Gain insights into spending patterns and make data-driven decisions.

## MVP Scope and Features
- **Receipt Capture and Storage**: Manual upload or OCR for data extraction.
- **Grouping/Tagging**: Create groups and tag receipts.
- **Expense Splitting**: Split receipts evenly, by percentage, or manually.
- **Basic Reporting**: Show total spending per group and personal spending across all receipts.
- **Simple UX**: Easy sign-up, receipt upload, and group assignment.

## Potential Extensions
- **Automated Receipt Import**: Integrate with email providers or bank accounts.
- **Advanced Analytics**: Monthly budgeting, overspending notifications, and AI-driven insights.
- **Collaboration Tools**: Real-time group dashboards and in-app chat.
- **Expense Reimbursement**: Integrate with payment solutions like PayPal or Venmo.
- **Accounting Integration**: Export data to QuickBooks or Xero.

---

Feel free to adjust or expand this template as needed for your project!
