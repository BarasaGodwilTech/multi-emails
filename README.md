# Email Rotation System

A simple web-based system to generate and track Gmail `+` aliases so you can use a new email every time without creating new inboxes.

## Features

- 🔄 **Infinite Gmail `+` Aliases** - Generates `liutechnationcode+1@gmail.com`, `liutechnationcode+label_2@gmail.com`, etc.
- 📋 **One-Click Copy** - Copy current email to clipboard instantly
- 📊 **Usage Statistics** - Track how many aliases have been generated
- 📜 **Usage History** - View recent email usage with timestamps
- 💾 **Data Export** - Export your usage data as JSON
- 🔄 **Reset Function** - Clear history and restart numbering

## How to Use

1. Open `index.html` in your web browser
2. (Optional) Type a label (example: `facebook`) and click **Set Label**
3. Click "📋 Copy Email" to copy the current alias to clipboard
4. Click "➡️ Next Email" to generate the next alias
5. View usage statistics and history on the dashboard

## File Structure

```
emails multi/
├── index.html          # Main web application
└── README.md          # This file
```

## Data Storage

- Usage history is saved in browser's localStorage
- Data persists between browser sessions
- Export functionality for backup

## Browser Compatibility

Works in all modern browsers that support:
- ES6 JavaScript
- LocalStorage
- Clipboard API
- Fetch API

## Security Note

This system runs entirely in your browser with no server components. Your email data stays local and private.
