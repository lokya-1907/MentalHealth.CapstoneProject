# MindfulMe – Mental Wellness Platform

Welcome to **MindfulMe**, a modern web platform designed to support your mental wellness journey. This project features a clean, responsive UI, light/dark theme toggle, and basic authentication using browser storage.

---

## 🚀 Features

- **Login & Signup:**  
  - Demo user:  
    - Username: `demo`  
    - Password: `demo123`  
  - Sign up for new users (session only).

- **Protected Pages:**  
  - All main pages (`home.html`, `journal.html`, etc.) require login.
  - Unauthenticated users are redirected to `index.html`.

- **Navigation Bar:**  
  - Logo, Dashboard, Journal, Community, Progress, Profile.
  - Profile, Theme Toggle, and Logout buttons are aligned on the same row.

- **Theme Toggle:**  
  - Switch between light and dark mode.
  - Remembers your choice using `localStorage`.
  - Feature headings remain visible in both themes.

- **Wellness Features:**  
  - Daily Journal, Gratitude Wall, Digital Detox, Support Forum, Sleep Dashboard, Focus Coach, and more.

---

## 🗂️ File Structure

```
Mental Wellness MSD/
│
├── index.html      # Login & Signup page
├── home.html       # Main dashboard (requires login)
├── journal.html    # Journal feature (requires login)
├── gratitude.html  # Community gratitude wall (requires login)
├── progress.html   # Progress tracking (requires login)
├── sleep.html      # Sleep dashboard (requires login)
├── focus.html      # Focus & productivity coach (requires login)
├── detox.html      # Digital detox companion (requires login)
├── forum.html      # Support forum (requires login)
└── ...             # Other assets (CSS, images, etc.)
```

---

## 📝 Usage

1. **Open `index.html` in your browser.**
2. **Login** with the demo credentials or sign up for a new account.
3. After login, you are redirected to `home.html`.
4. Use the navigation bar to access other features.
5. Use the 🌙/☀️ button to toggle between dark and light themes.
6. Click **Logout** to end your session.

---

## 🔒 Authentication

- Uses `localStorage` to store a `mindfulme_logged_in` flag.
- All protected pages check for this flag and redirect to `index.html` if not present.

---

## 🎨 Theming

- Theme toggle button in the top-right corner.
- Remembers your theme preference.
- Feature headings and important text remain visible in both themes.

---

## 🛠️ Customization

- **Add new features:** Duplicate a feature card in `home.html` and update the link.
- **Change theme colors:** Edit CSS variables in the `<style>` section.
- **Persistent users:** For real-world use, connect to a backend or use persistent storage.

---

## 📱 Responsive Design

- Fully responsive for desktop and mobile.
- Navigation adapts for smaller screens.

---

## 🙏 Credits

- UI inspired by modern wellness and productivity apps.
- Built with HTML and CSS

---

---

Enjoy your
