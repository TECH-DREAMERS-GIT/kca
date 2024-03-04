
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Semantic Form Example</title>
</head>
<body>
    <form action="/submit" method="post">
        <fieldset>
            <legend>Personal Information</legend>
            <label for="firstName">First Name:</label>
            <input type="text" id="firstName" name="firstName" required>
            <br>
            <label for="lastName">Last Name:</label>
            <input type="text" id="lastName" name="lastName" required>
            <br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
        </fieldset>
        <br>
        <input type="submit" value="Submit">
    </form>
</body>
</html>
