# FinanceFlow - Intelligent Finance Dashboard

## 📌 Live Demo
https://vercel.com/sowmya-2125s-projects/finance-dashboard

## 📋 Overview
FinanceFlow is a fully responsive finance dashboard that helps users track income, expenses, and spending patterns. It features role-based UI (Admin/Viewer), interactive charts, transaction management, and persistent storage.

## ✅ Features Implemented

### Core Requirements
- **Dashboard Overview** – Summary cards (Total Balance, Income, Expenses)
- **Time-based Visualization** – 6-month balance trend line chart
- **Categorical Visualization** – Spending breakdown by category (doughnut chart)
- **Transaction List** – Date, description, category, type, amount
- **Transaction Filtering** – By type (income/expense) and category
- **Transaction Search** – Search by description or category
- **Role-Based UI** – Admin (add/edit/delete) vs Viewer (read-only)
- **Insights Section** – Highest spending category, monthly comparison, smart observation
- **State Management** – JavaScript state with localStorage persistence

### Optional Enhancements
- ✅ Dark mode toggle with persistence
- ✅ Data persistence (localStorage)
- ✅ Animations & hover effects
- ✅ Fully responsive (mobile, tablet, desktop)

## 🛠️ Technical Decisions

### Framework: Vanilla JavaScript
**Why not React/Vue?**  
The assignment explicitly allows any framework. I chose vanilla JS to demonstrate:
- Deep understanding of DOM manipulation and events
- Clean state management without abstraction overhead
- Zero build step – runs instantly in any browser
- Easy code review without framework-specific syntax

### Styling: Custom CSS + Flexbox/Grid
**Why not Tailwind/MUI?**  
Custom CSS showcases my design thinking, responsive techniques, and attention to visual polish. No external dependencies keep the dashboard lightweight.

### State Management: Plain JS + localStorage
- Transactions array as single source of truth
- Filter object for UI state
- localStorage for persistence (transactions, role preference, dark mode)

### Charts: Chart.js
Lightweight, easy to implement, provides clean interactive visualizations.

## 🏗️ Project Structure
