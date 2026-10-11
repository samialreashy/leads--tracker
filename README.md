# Leads Tracker

A lightweight application for saving and managing useful links in one place. Built with vanilla JavaScript, HTML, and CSS, with a focus on simplicity and ease of use.

## Features

- **Save Leads** — Add and store website URLs for future reference.
- **Quick Access** — View saved leads and open them directly.
- **Persistent Storage** — Keep saved leads available between sessions using browser localStorage.
- **Clear Leads** — Remove saved entries when they are no longer needed.
- **Simple Interface** — A clean, minimal design focused on usability.

## Tech Stack

- **HTML5** — Application structure
- **CSS3** — Styling and layout
- **JavaScript (ES6+)** — Application logic and DOM manipulation
- **LocalStorage API** — Client-side data persistence

## Getting Started

### Prerequisites

A modern web browser such as Chrome, Firefox, or Edge.

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/leads-tracker.git
```

**2. Navigate to the project directory**

```bash
cd leads-tracker
```

**3. Run the application**

Open `index.html` in your browser.

## Usage

1. Enter a website URL in the input field.
2. Save the URL to add it to your leads.
3. Click a saved lead to visit its website.
4. Clear your saved leads when they are no longer needed.

## Data Storage

The application uses the browser's `localStorage` API to store leads locally.

Saved data remains available after refreshing or reopening the application, provided the browser's site data is not cleared.

No external database or user account is required.

## Project Structure

```text
leads-tracker/
├── index.html
├── index.css
├── index.js
└── README.md
```

## Future Improvements

- Edit and delete individual leads
- Search and filter saved links
- Organize leads into categories
- Export saved leads

