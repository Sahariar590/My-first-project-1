<!DOCTYPE HTML>
<html lang="en" dir="ltr">
<head>
    <meta charset="utf-8">
    <title>Registration Form</title>
</head>
<body>
    <h4>Registration Form</h4>
    <form action="/action.php" method="post">
        <label for="username">Username:</label>
        <input type="text" name="username" id="username" placeholder="Enter your username">
        <br><br>

        <label for="password">Password:</label>
        <input type="password" name="password" id="password" placeholder="Enter your password">
        <br><br>

        <h5>Select your class</h5>
        <label for="classXI">
            <input type="radio" name="class" value="class XI" id="classXI">Class XI
        </label>
        <br><br>
        <label for="classXII">
            <input type="radio" name="class" value="class XII" id="classXII">Class XII
        </label>

        <h5>Select Favorite Subjects</h5>
        <label for="math">
            <input type="checkbox" name="subject" value="math" id="math">Math
        </label>
        <br><br>
        <label for="phy">
            <input type="checkbox" name="subject" value="phy" id="phy">Physics
        </label>
        <br><br>
        <label for="chem">
            <input type="checkbox" name="subject" value="chem" id="chem">Chemistry
        </label>
        <br><br>
        <label for="CS">
            <input type="checkbox" name="subject" value="CS" id="CS">Computer Science
        </label>
        <br><br>

        <label for="city">Select your City:</label>
        <select name="city" id="city">
            <option value="Dhaka">Dhaka</option>
            <option value="Rajshahi">Rajshahi</option>
            <option value="Chapai">Chapai</option>
            <option value="Jessore">Jessore</option>
            <option value="Khulna">Khulna</option>
        </select>
        <br><br>

        <label for="feedback">Feedback:</label>
        <textarea name="feedback" id="feedback" placeholder="Please give your valuable feedback here" rows="2"></textarea>
        <br>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
