# GitHub Profile Finder 🔍

A simple and interactive web application that allows users to search for GitHub profiles and explore their public information. Built using HTML, CSS, and JavaScript, this project uses the GitHub REST API to fetch and display real-time profile data.

## ✨ Features

- 🔎 **Search GitHub Users:** Find GitHub profiles using a username.
- 👤 **Profile Information:** Display the user's name, username, avatar, and bio.
- 📊 **GitHub Statistics:** View public repositories, followers, and following.
- 📅 **Join Date:** See when the user joined GitHub.
- 🌐 **Social Links:** Access the user's GitHub profile, website, and Twitter account when available.
- 📍 **Additional Information:** Display location and company details.
- 🌙 **Dark Mode & Light Mode:** Switch between themes with saved preferences using Local Storage.
- ⌨️ **Enter Key Support:** Search for profiles by pressing Enter.
- ⚠️ **Error Handling:** Display a message when a GitHub username is not found.
- 📱 **Responsive Design:** Explore profiles across different screen sizes.

## 🛠️ Technologies Used

- **HTML5** — Structure of the application.
- **CSS3** — Styling, layout, and theme customization.
- **JavaScript (ES6+)** — Application logic, DOM manipulation, and event handling.
- **GitHub REST API** — Fetch public GitHub user information.
- **Fetch API** — Handle HTTP requests.
- **Local Storage** — Save the selected theme preference.

## 🔗 API Reference

This project uses the GitHub Users API:

```text
https://api.github.com/users/{username}
```

Replace `{username}` with the GitHub username you want to search for.

Example:

```text
https://api.github.com/users/yarsanjit
```

The API provides information such as the user's avatar, name, bio, public repositories, followers, following, location, company, and account creation date.

API documentation: [GitHub REST API — Users](https://docs.github.com/en/rest/users/users)

## 📂 Project Structure

```text
GitHub-Profile-Finder/
├── index.html
├── style.css
├── script.js
└── assets/
    └── images/
        ├── moon-icon.svg
        └── sun-icon.svg
```

*Note: Update the file names and folder structure above if your actual project uses different names.*

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Navigate to the Project Directory

```bash
cd GitHub-Profile-Finder
```

### 3. Run the Application

Open `index.html` in your browser, or use the **Live Server** extension in Visual Studio Code for a better development experience.

No package installation or API key is required for basic usage.

## 💡 How It Works

1. Enter a GitHub username in the search bar.
2. Click the search button or press Enter.
3. The application sends a request to the GitHub Users API.
4. JavaScript processes the API response and updates the profile information.
5. If the username does not exist, an error message is displayed.
6. Toggle between dark mode and light mode to change the interface theme.
7. Your theme preference is saved in Local Storage and restored when you revisit the application.

## 🧠 Concepts Learned

This project demonstrates practical experience with:

- DOM selection and manipulation.
- JavaScript event listeners.
- Fetch API and asynchronous requests using Promises.
- Working with JSON data.
- Conditional rendering and handling missing values.
- Dynamic CSS variables for theme switching.
- Browser Local Storage.
- Integrating third-party REST APIs.
- Basic error handling and UI state management.

## 🔮 Future Improvements

- Add loading indicators while fetching profile data.
- Improve API error handling for network failures and rate limits.
- Display the user's pinned repositories.
- Add repository search and filtering.
- Improve accessibility and responsive layouts.
- Support automatic theme detection based on system preferences.

## 👨‍💻 Author

**Sanjit Kumar Saha**

- GitHub: [@yarsanjit](https://github.com/yarsanjit)
- LeetCode: [@yarsanjit](https://leetcode.com/u/yarsanjit/)

## 📄 License

This project is open source and available for learning, personal use, and further development. Add an MIT License if you want to distribute it under the MIT License.

---

⭐ If you find this project useful, consider giving the repository a star!