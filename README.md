# FINZO – Smart Personal Expense Tracker

FINZO is a responsive personal finance web application designed to help users manage daily income, expenses, budgets, savings goals, reports, and future spending insights in one place.

## Live Demo

**Try FINZO:** `YOUR_VERCEL_LINK_HERE`

> This repository is maintained as a portfolio showcase for the FINZO project. The complete deployable source code is kept private.

## Project Overview

FINZO provides an end-to-end personal expense management workflow. Users can manage income and expenses, organize spending by category, track monthly budgets and savings goals, review visual reports, scan receipts with OCR, add expenses by voice, and view spending predictions.

## Key Features

- Login, registration, forgot-password, remember-me, and logout
- Dashboard with total income, total expenses, remaining balance, and savings overview
- Add, edit, delete, and search expenses
- Add, edit, and delete income records
- Expense categories and custom category support
- Monthly category budget tracking
- Savings goal tracker
- Expense reports with category and trend charts
- Challenge Mode
- Future expense prediction
- Receipt Scanner with OCR-based receipt text extraction
- Safe handling for low-confidence handwritten receipts
- Voice-based expense entry
- Typed sentence parser for expense entry
- User profile and profile photo
- Budget and spending notifications
- Backup export and restore
- Responsive laptop, tablet, and mobile interface
- Internal back navigation and exit protection

## Smart Features

### Receipt Scanner
Users can take a receipt photo or upload one from the device. FINZO uses OCR to detect readable receipt information and prepares the expense details for review before saving.

### Voice Expense Entry
Users can speak a sentence such as:

> “Spent 450 rupees on groceries by UPI”

FINZO converts the recognized sentence into expense details such as amount, category, and payment method for review before adding it.

## Technologies Used

- **HTML5** – Application structure and forms
- **CSS3** – Responsive UI, layouts, cards, sidebar, and styling
- **JavaScript** – Application logic, calculations, data management, reports, and predictions
- **Tesseract.js** – Receipt OCR
- **Web Speech API** – Voice-based expense entry
- **HTML Canvas** – Charts and data visualization
- **localStorage / sessionStorage** – Browser-side application and session data
- **Browser File API** – Receipt images, profile photos, and backup import/export
- **Browser History API** – Internal navigation and back-button handling
- **Vercel** – Live project deployment

## Application Flow

Login / Register → Dashboard → Expenses → Income → Categories → Budget → Savings Goals → Reports → Challenge Mode → Predictions → Receipt Scanner → Voice Entry → Profile → Settings → Logout

## Screenshots

Screenshots will be added to the `screenshots` folder.

Recommended showcase screens:

- Login
- Dashboard
- Reports
- Receipt Scanner
- Voice Expense Entry
- Settings

Once uploaded, selected screenshots can be displayed here.

## Project Highlights

- Complete personal expense management workflow
- Responsive interface for desktop and mobile
- OCR-based receipt input
- Voice-based expense entry
- Budget and savings tracking
- Visual reports and spending forecasts
- Backup and restore workflow

## Portfolio Notice

This repository is maintained as a portfolio showcase of the FINZO project.

The complete deployable source code is maintained privately.

## Author

**Yusuf**  
GitHub: [yusuf-digital](https://github.com/yusuf-digital)  
LinkedIn: `YOUR_LINKEDIN_PROFILE_HERE`
