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
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Contact Page</title>
</head>
<body>
    <h1>Contact Information</h1>

    
    <h2>Important Steps</h2>
    <ol type="I">
        <li>Step One: Register
<li>Step Two: Verify Email</li>
        <li>Step Three: Add Contacts</li>
    </ol>

    <h2>Sample Image</h2>
    <img src="https://images.pexels.com/photos/3225510/pexels-photo-3225510.jpeg" alt="Sample Image" width="500">

    <!-- Table of Contacts -->
    <h2>Contact List</h2>
    <table border="1">
<tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
<tr>
              <td>John Doe</td>
              <td>123 Main St, City, Country</td>
              <td>+1 234 567 890</td>
              <td>johndoe@gmail.com</td>
</tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Oak St, City, Country</td>
            <td>+1 987 654 321</td>
<td>janesmith@gmail.com</td>
        </tr>
        <tr>
            <td>Sam Johnson</td>
            <td>789 Pine St, port elizabeth, south africa</td>
<td>+1 555 123 456</td>
            <td>tinashe@gmail.com<</td>
        </tr>
        <tr>
            <td>Alice Brown</td>
<td>101 Maple St, port elizabeth, South africa</td>
            <td>+1 666 777 888</td>
            <td>tinashe@gmail.com<</td>
        </tr>
        <tr>
<td>Bob White</td>
            <td>202 Cedar St, City, Country</td>
            <td>+1 444 555 666</td>
            <td>tinashe@gmail.com</td>
        </tr>
    </table>

    <h2>Registration Form</h2>
    <form action="#" method="post">
        <label for="fname">First Name:</label><br>
        <input type="text" id="fname" name="fname" required><br><br>

        <label for="lname">Last Name:</label><br>
        <input type="text" id="lname" name="lname" required><br><br>

<label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" required><br><br>

        <input type="submit" value="Register">
    </form>
</body>
</html>


