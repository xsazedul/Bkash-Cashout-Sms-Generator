# 💰Bkash Cashout SMS Generator

A simple, elegant, and fully client-side web tool to generate formatted cashout confirmation SMS messages. Perfect for mobile financial services (MFS), banking simulations, or testing SMS formatting.

## 🚀 Live Demo

Host this on GitHub Pages or any static hosting.  


## ✨ Features

- **Sender Number Masking** – Automatically masks phone numbers (e.g., `019xxxxxxxx` → `019xxxxx057`).
- **Dark / Light Theme** – Toggle between themes with one click; your preference is saved in `localStorage`.
- **Auto Date & Time** – Automatically fills the current date and time on load.
- **Character Counter** – Live counter shows SMS length; turns yellow (>100) and red (>140).
- **One-Click Copy** – Copy the generated SMS to your clipboard with a single tap.
- **Keyboard Friendly** – Press `Enter` on any input field to generate the SMS instantly.
- **Zero Dependencies** – Pure HTML, CSS, and JavaScript. No external libraries or icons.

## 🛠️ How to Use

1. **Enter the Cashout Amount** – Type the amount (e.g., `500`).
2. **Enter Sender Number** – The tool will automatically mask it in the final output (e.g., `019xxxxx057`).
3. **Enter Transaction ID** – Any unique identifier (e.g., `TRX123456`).
4. **Enter Previous Balance** – The new balance will be calculated automatically (including a 0.4% fee).
5. **Adjust Date/Time** – Auto-filled with current time, but you can edit it manually.
6. Click **Generate SMS** – The formatted message appears in the text area.
7. Click **Copy SMS** – Copies the message to your clipboard.
8. Click **Clear** – Resets all fields.

## 📦 Installation & Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/xsazedul/bkash-cashout-sms-generator.git
