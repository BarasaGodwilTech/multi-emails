# Email Rotation System

A simple web-based system to manage and rotate through multiple email addresses automatically, ensuring you don't reuse the same email repeatedly.

## Features

- 🔄 **Automatic Email Rotation** - Cycles through your email list automatically
- 📋 **One-Click Copy** - Copy current email to clipboard instantly
- 📊 **Usage Statistics** - Track how many emails have been used
- 📜 **Usage History** - View recent email usage with timestamps
- 💾 **Data Export** - Export your usage data as JSON
- 🔄 **Reset Function** - Reset rotation and clear history when needed

## How to Use

1. Open `index.html` in your web browser
2. The system will automatically load all your email addresses
3. Click "📋 Copy Email" to copy the current email to clipboard
4. Click "➡️ Next Email" to rotate to the next email in the list
5. View usage statistics and history on the dashboard

## File Structure

```
emails multi/
├── index.html          # Main web application
├── emails.json         # Email addresses and rotation data
└── README.md          # This file
```

## Email Addresses

The system includes 120 email variations based on "liucodingcodes" with different dot placements:
- liucodingcodes@gmail.com
- liucodingcode.s@gmail.com
- liucodingcod.es@gmail.com
- ...and 117 more variations

## Data Storage

- Email data is stored in `emails.json`
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
