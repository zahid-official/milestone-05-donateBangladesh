# 🪙 Donate Bangladesh

**Donate Bangladesh** is a clean and responsive donation platform designed to support important humanitarian and social causes in Bangladesh. It brings together multiple donation campaigns, real-time balance updates, contribution history tracking and a dedicated FAQ section in one simple and user-friendly experience.

<div align="center">
  
  ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
  ![Responsive](https://img.shields.io/badge/Responsive-Design-green?style=for-the-badge)
  
</div>

## ✨Features

- Donate to three different causes from a single interface
- Real-time balance deduction after each successful donation
- Separate donation totals for each campaign
- Dynamic donation history generation with timestamp
- Validation for invalid or insufficient donation amounts
- Success confirmation modal after each valid donation
- Toggle between `Donation` and `History` views
- Dedicated `Blog` page with FAQ accordion content
- Responsive layout for mobile, tablet and desktop screens

## 🪙Donation Campaigns

The application currently includes the following causes:

- Flood relief for **Noakhali, Bangladesh**
- Flood relief for **Feni, Bangladesh**
- Aid for those injured in the **Quota Movement**

## 🛠️Tech Stack

- **HTML5** for page structure
- **CSS3** for custom styling
- **JavaScript (Vanilla)** for DOM manipulation and app logic
- **Tailwind CSS** via CDN for utility-first styling
- **DaisyUI** for UI components like buttons, modal and accordion
- **Google Fonts (Lexend)** for typography

## 📄Pages

### 1. Home Page

The main page includes:

- Navbar with logo, balance and blog navigation
- Donation cards for three separate causes
- Donation input fields and action buttons
- Modal confirmation after successful donation
- `Donation` and `History` tab switching

### 2. Blog Page

The blog page contains a styled FAQ section covering:

- What the DOM is
- How to select elements from the DOM
- What event delegation means
- How to manipulate attributes and styles using the DOM

## How It Works

1. The user starts with an initial balance of **5500 BDT**
2. A donation amount is entered into any campaign input field
3. JavaScript validates the amount
4. If the amount is valid and balance is sufficient:
   - The campaign total is updated
   - The main balance is reduced
   - A donation history item is created with the current date
   - A success modal is displayed

## 📂Project Structure

```bash
milestone-05/
├── index.html         # Main donation page
├── style.css          # Global custom styles
├── js/                # JavaScript source files
│   ├── script.js      # Main donation logic and interactions
│   └── utility.js     # Helper functions
├── pages/             # Additional pages
│   └── blog.html      # FAQ / blog page
└── images/            # Project image assets
```

## Key JavaScript Responsibilities

### `js/utility.js`

- Reusable helper functions for selecting elements and reading numeric values

### `js/script.js`

- Blog page navigation
- Donation and history tab toggling
- Donation validation and balance updates
- Donation history rendering
- Success modal handling

### `pages/blog.js`

- Navigation from the blog page back to the home page

## 📚 Learning Focus

This project demonstrates practical understanding of:

- DOM selection and manipulation
- Event listeners and button interactions
- Input validation with JavaScript
- Dynamic HTML rendering using template literals
- State-like UI updates without a framework
- Responsive design with Tailwind CSS and DaisyUI

## Limitations

- Donations are simulated on the frontend only
- Data is not stored in a database or browser storage
- The balance resets when the page reloads
- No payment gateway or backend integration is included

## Future Improvements

- Add local storage support to preserve donation history
- Integrate a backend for persistent donation records
- Add category filtering or campaign search
- Improve date formatting for donation history entries
- Add analytics or summary cards for total donations

## 🌟Author

<div align="center">
  <a href="https://github.com/zahid-official">
    <img src="https://github.com/zahid-official.png" width="100" height="100" style="border-radius: 50%;" alt="Zahid Official" />
  </a>

  <h3>Zahid Official</h3>
  <p><b>Web Developer | Tech Enthusiast</b></p>

  [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/zahid-official)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zahid-web)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:zahid.official8@gmail.com)
  
  <p>Built with passion and dedication to create scalable solutions</p>
</div>

## 🤝 Contributing

Contributions make the project better for everyone. If you would like to improve **Donate Bangladesh**, your contributions are always welcome.

```bash
1. Fork the project
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
```

<p align="center"><b>Donate Bangladesh</b><i> - Where every contribution brings hope closer to those who need it most.</i></p>
