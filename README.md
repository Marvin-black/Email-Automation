<!DOCTYPE html>
<html>

<head>
  
</head>

<body>
    <h1>Email Automation using Python</h1>
    <p>This repository contains a Python script for automating personalized email communication using the `smtplib` library
        and Jinja2 templating. The script facilitates sending reminder emails to multiple recipients, such as invoice
        reminders, by dynamically rendering email templates with recipient-specific information.</p>

  <h2>Features</h2>
    <ul>
        <li>Personalized Email Content: Utilize Jinja2 templating to customize email content for each recipient.</li>
        <li>Multi-Recipient Handling: Efficiently manage multiple recipients by iterating through the recipient list and
            sending tailored reminder emails.</li>
        <li>Rate-Limiting Prevention: Implement a delay between sending emails to avoid potential rate-limiting issues
            with the email server.</li>
        <li>Logging and Error Handling: Incorporate detailed logging and error handling for enhanced reliability,
            tracking successful email transmissions, and gracefully handling exceptions.</li>
    </ul>

  <h2>How to Use</h2>
    <ol>
        <li>Clone this repository to your local machine:</li>
        <pre><code>git clone https://github.com/your_username/email-automation-python.git</code></pre>
        <li>Navigate to the project directory:</li>
        <pre><code>cd email-automation-python</code></pre>
        <li>Install required dependencies:</li>
        <pre><code>pip install -r requirements.txt</code></pre>
        <li>Configure the `.env` file with your Gmail email and password:</li>
        <pre><code>Email=your_email@gmail.com
Password=your_password</code></pre>
        <li>Customize the email templates in the "templates" folder according to your needs.</li>
        <li>Edit the `recipients` list in the script to include recipient details and template paths.</li>
        <li>Run the Python script:</li>
        <pre><code>python email_automation.py</code></pre>
    </ol>

  <h2>Contributions</h2>
    <p>Contributions to this project are welcome. Feel free to submit issues, suggestions, and pull requests to enhance
        the functionality and usability of the email automation.</p>

  <h2>License</h2>
    <p>This project is licensed under the MIT License. You can find more details in the <a
            href="LICENSE">LICENSE</a> file.</p>

  <h2>Acknowledgments</h2>
    <p>This project was inspired by the need to automate personalized email communication and make it more effective for
        various use cases.</p>

  <p>Happy emailing!</p>
</body>

</html>
