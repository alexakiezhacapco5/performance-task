<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>First Performance Task</title>
</head>
<body>

    <h2>First Performance Task</h2>
    <form action="submit.php" method="post">
        <label for="first-name">First Name:</label>
        <input type="text" id="first-name" name="first_name" required>
        <br><br>

        <label for="last-name">Last Name:</label>
        <input type="text" id="last-name" name="last_name" required>
        <br><br>

        <label for="sport">Favorite Sport:</label>
        <select id="sport" name="favorite_sport" required>
            <option value="">-- Select Sport --</option>
            <option value="Badminton">Badminton</option>
            <option value="Basketball">Basketball</option>
            <option value="Volleyball">Volleyball</option>
            <option value="Soccer">Soccer</option>
            <option value="Tennis">Tennis</option>
        </select>
        <br><br>

        <button type="submit">Submit</button>
    </form>

</body>
</html>
