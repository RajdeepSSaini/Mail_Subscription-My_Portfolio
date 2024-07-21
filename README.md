# Rajdeep's Portfolio Website - Coming Soon!
Welcome to the repository for Rajdeep's brand new portfolio website subscription. This repository contains the HTML, CSS, and JavaScript code for the email subscription page that will keep you updated about the website's launch. The website is expected to go live in a month after a few rounds of testing.


## Overview
This email subscription page allows visitors to subscribe to receive updates about the upcoming portfolio website. The subscription form is linked to Google Sheets for data collection, ensuring that all email addresses are securely stored.


### HTML
The HTML file sets up the structure of the subscription page. It includes:

- A `DOCTYPE` declaration to specify the HTML version.
- A `meta` tag to ensure the page is responsive.
- A `title` tag to set the page title.
- A link to an external CSS file for styling.
- A `div` element with the class `hero` that contains the main content: headings, a subscription form, and a message span.


### CSS
The CSS file styles the page, making it visually appealing and responsive. Key styles include:

- Resetting margins, padding, and setting a default font.
- Styling for the `.hero` class, including background, text color, and layout.
- Specific styles for `h3`, `h1`, and `p` elements within the `.hero` class to set font size, weight, and margins.
- Styles for the subscription form, input fields, and submit button to ensure a consistent look and feel.


### JavaScript (added directly in the HTML file)
The JavaScript code handles the form submission. It uses the Fetch API to send form data to a Google Sheets script URL, ensuring seamless data collection. Key functionality includes:

- Preventing the default form submission behavior.
- Sending the form data to a Google Sheets script URL.
- Displaying a thank you message upon successful submission.
- Resetting the form after submission.
- Handling errors during form submission.


### Google Sheets Integration
The form data is collected using Google Sheets. The JavaScript code in the HTML file sends a POST request to a Google Sheets script URL, ensuring all email addresses are captured and stored.


## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/portfolio-website-coming-soon.git
    ```
2. Open the `index.html` file in your browser to view the email subscription page.
3. Customize the CSS in `style.css` to match your preferences.
4. Update the Google Sheets script URL in the JavaScript code to link it to your own Google Sheets.

Stay tuned for the launch of Rajdeep's brand new portfolio website! Thank you for subscribing and showing your interest.

---
Feel free to reach out if you have any questions or suggestions.
