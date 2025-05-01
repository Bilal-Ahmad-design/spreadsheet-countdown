# spreadsheet-countdown
# ⏳ Google Sheets Countdown Timer

This script allows you to set countdown timers directly inside your Google Sheet cells. It updates every minute and shows the remaining time in `HH:MM:SS` format.

---

## ✅ Features

- Add countdown timers to any single cell
- Custom input for number of hours
- Automatically updates every minute
- Supports multiple timers in the same sheet
- Stops when the time is up and displays `"00:00:00 - Time's up!"`
- Stops individual timers on demand

---

## 📦 How to Install

1. Open your Google Sheet.
2. Go to `Extensions → Apps Script`.
3. Paste the full script code into the editor.
4. Save the project.
5. Reload your spreadsheet.

---

## 🕹️ How to Use

After reloading the sheet, you’ll see a new menu:

> **⏳ Countdown Timer**

Available options:

- `Start Countdown (selected cell)` — Choose a cell, enter hours, and start the countdown.
- `Stop Countdown (selected cell)` — Stops the timer and clears the data.

---

## 💡 Notes

- Make sure to select **only one cell** when starting or stopping a timer.
- The countdown updates every minute.
- Formatting is forced to plain text to avoid unwanted AM/PM conversion.
- Timers are saved using Script Properties, so they persist between sessions.

---

## 📁 File Structure

- `Code.gs` — Main logic (you can rename it if you prefer)

---

## ✏️ Example

If you start a 3-hour countdown in cell `B2`, you’ll see:


And it will tick down every minute until:


---

## 🔒 Permissions

The script requires permission to:
- Edit your spreadsheet
- Store timer data using script properties
- Create a time-based trigger to update the timers

---

## 🧰 Optional Enhancements

- Add support for minutes/seconds
- Add cell color change when time is up
- Email notification when a timer ends
- Record start/end time in a separate sheet

---

## 📬 Contact

If you need help or want to extend this, feel free to reach out or open a pull request.

