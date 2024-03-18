<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Submit Code Form</title>
</head>

<body>
    <h2>Submit Code Form</h2>
    <form action="/submit" method="post">
        <label for="username">Username:</label><br>
        <input type="text" id="username" name="username" required><br><br>

        <label for="language">Preferred Code Language:</label><br>
        <select id="language" name="language" required>
            <option value="Python">Python</option>
            <option value="Java">Java</option>
            <option value="JavaScript">JavaScript</option>
            <option value="C++">C++</option>
            <!-- Add more options as needed -->
        </select><br><br>

        <label for="source_code">Source Code:</label><br>
        <textarea id="source_code" name="source_code" rows="10" cols="50" required></textarea><br><br>

        <input type="submit" value="Submit">
    </form>
</body>

</html>
