# Login & Forgot Password Interface

A clean, modern login and password reset interface built with HTML, CSS, and JavaScript. This project provides a user-friendly authentication experience with a dedicated "Forgot Password" flow.

## 🚀 Live Demo

Check out the live demo: [https://www.sieu.io.vn/github/login-and-forgot-password](https://www.sieu.io.vn/github/login-and-forgot-password)

## ✨ Features

- **Login Form** – Username/email and password fields with "Remember Me" option
- **Forgot Password** – Reset your password by providing your username or email
- **Toggle Between Forms** – Seamless switching between login and password reset
- **Responsive Design** – Optimized for desktop, tablet, and mobile devices
- **Clean UI** – Modern, user-friendly interface with smooth transitions
- **🌐 Multi-language Support** – Vietnamese, English, and Japanese with a language switcher (saved in `localStorage`)
- **Password Visibility Toggle** – Show/hide password with an eye icon
- **Client-side Validation** – Required fields and email format checked before submission, with localized error popups

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- **JSON** (for language translations)

## 📁 Project Structure

```
login-and-forgot-password/
├── index.html              # Main HTML file
├── style.css               # Stylesheet
├── script.js               # JavaScript functionality
├── lang.json               # Translation data (vi, en, ja)
└── README.md               # Project documentation
```


## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/sieule/login-and-forgot-password.git
   ```
2. **Navigate to the project folder**
   ```bash
   cd login-and-forgot-password
   ```
3. **Run the application with a local server**

⚠️ Important: This project loads data from a JSON file, so you need to use a local development server instead of opening `index.html` directly in your browser to avoid CORS issues.

- **Using VS Code** – Install the "Live Server" extension, right-click on `index.html`, and select "Open with Live Server"
- **Using Python** – Run `python -m http.server` (Python 3) or `python -m SimpleHTTPServer` (Python 2) and open `http://localhost:8000`
- **Using Node.js** – Install `http-server` globally (`npm install -g http-server`) and run `http-server` in the project folder

## 📝 How It Works

- **Login** – Enter your username/email and password, then click "Login"
- **Forgot Password** – Switch to the reset form and enter either your username or email to receive a password reset link
- **Switch Forms** – Click "Login" or "Forgot Password?" links to toggle between forms
- **Remember Me** – Check the box to stay logged in (client-side)
- **Language Switching** – Use the dropdown in the top-right corner to switch between Vietnamese, English, and Japanese. The choice is saved in `localStorage` and persists across reloads.
- **Validation** – Both login and reset forms validate required fields and email format. Errors appear in a localized popup.

## 🌐 Adding a New Language

1. Add a new object to `lang.json` with the language code as the key (e.g., `"fr"`).
2. Add a corresponding `<option>` in the `#langSelect` dropdown inside `index.html`.
3. No changes to JavaScript are needed.

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open-source and available under the MIT License.
