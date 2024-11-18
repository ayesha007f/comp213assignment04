<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Continuing Education Evaluation Form</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <a href="https://www.centennialcollege.ca" target="_blank">
            <img src="https://tse4.mm.bing.net/th?id=OIP.VK9lUV3pLUerqnIy4oenfwHaCY&pid=Api&P=0&h=180" alt="College Logo" style="height: 60px;">
        </a>
        <h1>Continuing Education Evaluation Form</h1>
    </header>

    <!-- Main Form Section -->
    <main>
        <form action="#" method="post">
            <!-- Personal Information -->
            <fieldset>
                <legend>Personal Information</legend>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone"><br><br>
            </fieldset>

            <!-- Course Evaluation -->
            <fieldset>
                <legend>Course Evaluation</legend>
                <label for="courseName">Course Name:</label>
                <input type="text" id="courseName" name="courseName" required><br><br>
                <label for="instructor">Instructor Name:</label>
                <input type="text" id="instructor" name="instructor" required><br><br>
                
                <label>How would you rate the course content?</label><br>
                <input type="radio" id="content-excellent" name="content" value="excellent" required>
                <label for="content-excellent">Excellent</label><br>
                <input type="radio" id="content-good" name="content" value="good">
                <label for="content-good">Good</label><br>
                <input type="radio" id="content-average" name="content" value="average">
                <label for="content-average">Average</label><br>
                <input type="radio" id="content-poor" name="content" value="poor">
                <label for="content-poor">Poor</label><br><br>

                <label>How would you rate the instructor's teaching skills?</label><br>
                <input type="radio" id="skills-excellent" name="teaching" value="excellent" required>
                <label for="skills-excellent">Excellent</label><br>
                <input type="radio" id="skills-good" name="teaching" value="good">
                <label for="skills-good">Good</label><br>
                <input type="radio" id="skills-average" name="teaching" value="average">
                <label for="skills-average">Average</label><br>
                <input type="radio" id="skills-poor" name="teaching" value="poor">
                <label for="skills-poor">Poor</label><br><br>

                <label>Would you recommend this course to others?</label><br>
                <input type="radio" id="recommend-yes" name="recommend" value="yes" required>
                <label for="recommend-yes">Yes</label><br>
                <input type="radio" id="recommend-no" name="recommend" value="no">
                <label for="recommend-no">No</label><br><br>
            </fieldset>

            <!-- Suggestions -->
            <fieldset>
                <legend>Suggestions and Comments</legend>
                <label for="comments">Your Comments:</label><br>
                <textarea id="comments" name="comments" rows="5" cols="40"></textarea>
            </fieldset>

            <!-- Submit Section -->
            <button type="submit">Submit</button>
        </form>
    </main>
</body>
</html>
