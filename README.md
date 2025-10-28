🔐 Password Generator

A simple and responsive Password Generator built using HTML, CSS, and JavaScript.
Users can customize the length and type of characters to generate strong and random passwords instantly.

🚀 Features

Set password length (between 4 and 20 characters).

Choose which character types to include:

✅ Uppercase letters (A–Z)

✅ Lowercase letters (a–z)

✅ Numbers (0–9)

✅ Symbols (!@#$%)

Generates a completely random password every time.

Includes responsive design (mobile-friendly layout using media queries).

User-friendly interface with a modern card-style design.

🧠 How It Works

The user selects:

Password length

Desired character types (uppercase, lowercase, numbers, symbols)

When the “Generate Password” button is clicked:

The JavaScript collects all selected character sets.

A random character is chosen repeatedly (based on the selected length) using:

const randomIndex = Math.floor(Math.random() * charSet.length);
password += charSet[randomIndex];


The generated password is displayed instantly on the screen.

🧩 Technologies Used

HTML – Structure and content

CSS – Styling, layout, and media queries

JavaScript – Password generation logic and interactivity

📱 Responsive Design

The interface adapts to different screen sizes using CSS media queries:

@media (max-width: 600px) {
  .sect1 {
    flex-direction: column;
    align-items: flex-start;
  }
}


This ensures the app works smoothly on both desktop and mobile devices.

🧰 How to Run

Download or clone this repository:

git clone https://github.com/your-username/password-generator.git


Open the index.html file in your browser.

Customize your options and click Generate Password.

💡 Possible Improvements

Add a Copy to Clipboard button.

Add a strength indicator (weak / medium / strong).

Allow more symbol options.

Option to show/hide password.

👨‍💻 Author

Developed by [Mesandu Gunarwardhana]
🕸️ A simple and fun project for learning JavaScript and responsive web design.
