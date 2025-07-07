# reCAPTCHA
This project is a secure login form using HTML, CSS, and PHP with Google reCAPTCHA v2. It protects against bots by requiring users to complete a CAPTCHA. The form runs locally on XAMPP and verifies the CAPTCHA server-side using Google’s API.
http://localhost/test-recaptcha/testrecap.html     This link will directly take you to the page of where the captcha is tested
This project is a secure login web form built using HTML, CSS, and PHP, integrated with Google reCAPTCHA v2 to prevent bots and spam logins.

The form collects a user's username and password, and before submission, requires the user to verify they're human using Google’s “I’m not a robot” checkbox (reCAPTCHA). The form data is then submitted to a PHP backend script, which uses Google's API to validate the CAPTCHA response. Only after a successful CAPTCHA verification will the server allow access or display a success message.

The project is designed to run on a local server using XAMPP and works on any system using Google’s public test keys, making it portable and easy to demonstrate.
