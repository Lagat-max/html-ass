<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8"> <!-- Character set meta tag -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Meta tag for display -->
    <title>Basic HTML Template</title> <!-- Title tag -->
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Welcome to My First Website</h1> <!-- Heading -->
    </header>

    <!-- Paragraph -->
    <p>This is a web page that has HTML elements.</p>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="/submit_form" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="phone">Phone Number:</label><br>
        <input type="tel" id="phone" name="phone" required><br><br>

        <input type="submit" value="Submit">
    </form>

    <!-- Table displaying user information -->
    <h2>Common User Information</h2>
    <table border="1">
        <tr>
            <th>Name</th>
            <th>Email</th>
            <th>Phone Number</th>
        </tr>
        <tr>
            <td>Amos Kiplagat</td>
            <td>amos.kiplagat@designer.com</td>
            <td>+254713343074</td>
        </tr>
        
    </table>

    <!-- Image -->
    <h2>Sample Image</h2>
    <img src="https://via.placeholder.com/150" alt="Sample Image" />

    <!-- External Link -->
    <h2>Visit Google</h2>
    <a href="https://google.com" target="_blank">Click here to go to Google</a>

</body>
</html>
