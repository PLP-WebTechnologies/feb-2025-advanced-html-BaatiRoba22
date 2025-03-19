# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Forms</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Advanced HTML5 Elements and Forms</h1>
    </header>

    <main>
        <!-- Objectives Section -->
        <section id="objectives">
            <h2>Objectives</h2>
            <ol type="I">
                <li>Implement HTML5 images, lists, tables, forms, and input types.</li>
                <li>Use form validation attributes.</li>
                <li>Apply multimedia elements such as audio and video.</li>
            </ol>
        </section>

        <!-- External Image Section -->
        <section id="image">
            <h2>Visual Representation</h2>
            <img src="https://images.pexels.com/photos/3770581/pexels-photo-3770581.jpeg" alt="Sample Image from Pexels" style="width:100%; height:auto;">
        </section>

        <!-- Contacts Table Section -->
        <section id="contacts">
            <h2>Contact List</h2>
            <table>
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile</th>
                        <th>Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Bati</td>
                        <td>298</td>
                        <td>0768915129</td>
                        <td>bqunyo@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Jane Smith</td>
                        <td>456 Oak St, Tausi lane</td>
                        <td>(234) 567-8901</td>
                        <td>janesmith@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Mike Johnson</td>
                        <td>789 Pine St, Villageburg</td>
                        <td>(345) 678-9012</td>
                        <td>mikej@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Emily Davis</td>
                        <td>321 Elm St, Hamletton</td>
                        <td>(456) 789-0123</td>
                        <td>emilyd@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Chris Wilson</td>
                        <td>654 Spruce St, Boroughtown</td>
                        <td>(567) 890-1234</td>
                        <td>chrisw@gmail.com</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Registration Form Section -->
        <section id="registration">
            <h2>Registration Form</h2>
            <form action="submit_form.php" method="POST">
                <!-- Name Field -->
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" placeholder="Your Name" value="Bati" required>

                <!-- Email Field -->
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Your Email" value="bqunyo@gmail.com" required>

                <!-- Password Field -->
                <label for="password">Password:</label>
                <input type="password" id="password" name="password" placeholder="Your Password" required minlength="6">

                <!-- Date Field -->
                <label for="date">Date of Birth:</label>
                <input type="date" id="date" name="date" required>

                <!-- Dropdown -->
                <label for="gender">Gender:</label>
                <select id="gender" name="gender" required>
                    <option value="" disabled selected>Select your gender</option>
                    <option value="male">Male</option>
                    <option value="female">Female</option>
                    <option value="other">Other</option>
                </select>

                <!-- Radio Buttons -->
                <fieldset>
                    <legend>Preferred Contact Method:</legend>
                    <label>
                        <input type="radio" name="contact" value="email" required>Email
                    </label>
                    <label>
                        <input type="radio" name="contact" value="phone">Phone
                    </label>
                </fieldset>

                <!-- Checkboxes -->
                <fieldset>
                    <legend>Interests:</legend>
                    <label>
                        <

  
- Ensure semantic correctness.

Happy Coding! 💻✨
