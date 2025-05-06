
# 📅 Work Order Calendar Description Generator

A powerful, mobile-friendly tool to generate structured calendar-ready work order descriptions for field techs and dispatchers.

---

## ✨ Features

- ✅ Clean, structured input form for:
  - Company, Platform, Tech Name
  - Location and Arrival Window
  - Pay Rate (with hourly/unit/flat rate option)
  - Work Order number, description, and tool list
  - End User + WO Contact Info
- 🗺️ Travel time estimation using Google Maps Directions API
- 🕒 Auto-calculates **leave time** (includes 30-minute buffer)
- 📋 Generate clean, copy-ready description blocks
- 📌 Automatically generate a **calendar title** from Tech, Location, and WO#
- 📎 Clipboard copy buttons for title and description
- 📆 `.ics` file download for adding to:
  - Fastmail
  - Outlook
  - Apple Calendar
- 🗓️ "Add to Google Calendar" button with full pre-filled details
- 💵 Currency formatting for pay and travel
- 💼 Expandable: plan to integrate **existing WO contact library**

---

## 🚀 Getting Started

### 1. Clone this repo

```bash
git clone https://github.com/yourusername/workorder-calendar-generator.git
cd workorder-calendar-generator
```

### 2. Open `index.html` in your browser

You can also deploy it to your internal tools server or host it statically anywhere (Netlify, GitHub Pages, etc.).

> 📌 Make sure you're serving it over HTTPS or from `localhost` if using `navigator.clipboard`.

---

## 🔧 Configuration

This project uses:
- Google Maps JavaScript API
- Google Places API
- Google Directions API

You must add your **Google Maps API key** inside the script tag URL.

```html
<script async
  src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&libraries=places&callback=initAutocomplete">
</script>
```

---

## 📂 File Structure

```
📁 workorder-calendar-generator/
├── index.html     # Full tool in a single HTML file
└── README.md                    # This file
```

---

## 🧠 Planned Features

- [x] Add .ics calendar file generation
- [x] Format pay/travel in dollars and cents
- [x] Suite number optional
- [x] Travel time in hours/minutes
- [ ] Save and reuse WO Contacts
- [ ] Export PDF version of work order
- [ ] Optional stop/address logic

---

## 📄 License

MIT License. Use, fork, and adapt freely.

---

## 🙌 Credits

Built and maintained by Reborn Core Interactive.

