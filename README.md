Login and Registration Page
This project is a simple login and registration page built using HTML, CSS, and JavaScript. The background features a serene snowy night with a reindeer illustration to enhance the aesthetic experience.

Features
Toggle between Login and Register: JavaScript enables functionality to switch between the login and registration forms on user interaction.
Responsive Design: The page is designed to be fully responsive, adapting to different screen sizes.
Background Image: The page features a scenic background with a reindeer in a snowy night, giving it a calm and wintery feel.
Technologies Used
HTML: Structure of the page, including forms for login and registration.
CSS: Styling the page, making it visually appealing with the snowy background and clean layout.
JavaScript: Adds interactivity to toggle between login and registration forms.
How to Use
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/login-register-page.git
Navigate to the project directory:

bash
Copy code
cd login-register-page
Open the index.html file in a browser to view the login and registration page.

HTML Structure
The HTML file contains two forms, one for login and another for registration. Only one form is visible at a time.
CSS Styling
The background of the page is styled using CSS, featuring an image of a reindeer in a snowy night.
JavaScript
A simple JavaScript function is used to toggle the visibility of the login and registration forms when the user clicks on the respective buttons.
javascript
Copy code
// JavaScript to toggle between login and register forms
function toggleForm() {
  const loginForm = document.getElementById('loginForm');
  const registerForm = document.getElementById('registerForm');
  
  if (loginForm.style.display === 'none') {
    loginForm.style.display = 'block';
    registerForm.style.display = 'none';
  } else {
    loginForm.style.display = 'none';
    registerForm.style.display = 'block';
  }
}
CSS Snippet for the Background
css
Copy code
body {
  background-image: url('reindeer_snowy_night.jpg');
  background-size: cover;
  background-position: center;
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
}

form {
  /* form styling */
  background: rgba(255, 255, 255, 0.8);
  padding: 20px;
  border-radius: 10px;
  width: 300px;
  margin: 100px auto;
}
License
This project is licensed under the MIT License - see the LICENSE file for details.
