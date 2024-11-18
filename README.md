
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Continuing Education Evaluation Form</title>
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: olive;
            color: white;
            margin: 0;
            padding: 0;
        }

        /* Header */
        header {
            text-align: center;
            padding: 20px;
            background-color: darkolivegreen;
            color: white;
        }

        header img {
            vertical-align: middle;
        }

        header h1 {
            margin: 0;
        }

        /* Form Styling */
        form {
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background-color: #3a5c3a;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        fieldset {
            border: 2px solid white;
            border-radius: 5px;
            margin-bottom: 15px;
            padding: 15px;
        }

        legend {
            font-weight: bold;
            color: white;
        }

        label {
            font-weight: bold;
        }

        button {
            display: block;
            width: 100%;
            padding: 10px;
            font-size: 16px;
            background-color: darkolivegreen;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #2e482e;
        }

        /* Text Area */
        textarea {
            width: 100%;
            font-size: 14px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <header>
        <a href="https://www.centennialcollege.ca" target="_blank">
            <img src=""https://tse4.mm.bing.net/th?id=OIP.VK9lUV3pLUerqnIy4oenfwHaCY&pid=Api&P=0&h=180 alt="College Logo" style="height: 60px;">
        </a>
        <h1>Continuing Education Evaluation Form</h1>
    </header>

    <!-- Main Form Section -->
    <main>
        <form action="#" method="post">
            <!-- Personal Information -->
            <fieldset>
                <legend><strong>Personal Information</strong></legend>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone"><br><br>
            </fieldset>

            <!-- Course Evaluation -->
            <fieldset>
                <legend><strong>Course Evaluation</strong></legend>
                <p><strong>1. Rate the course content:</strong></p>
                <input type="radio" id="content-excellent" name="content" value="excellent" required>
                <label for="content-excellent">Excellent</label><br>
                <input type="radio" id="content-good" name="content" value="good">
                <label for="content-good">Good</label><br>
                <input type="radio" id="content-average" name="content" value="average">
                <label for="content-average">Average</label><br>
                <input type="radio" id="content-poor" name="content" value="poor">
                <label for="content-poor">Poor</label><br><br>

                <p><strong>2. Rate the instructor's teaching skills:</strong></p>
                <input type="radio" id="skills-excellent" name="teaching" value="excellent" required>
                <label for="skills-excellent">Excellent</label><br>
                <input type="radio" id="skills-good" name="teaching" value="good">
                <label for="skills-good">Good</label><br>
                <input type="radio" id="skills-average" name="teaching" value="average">
                <label for="skills-average">Average</label><br>
                <input type="radio" id="skills-poor" name="teaching" value="poor">
                <label for="skills-poor">Poor</label><br><br>

                <p><strong>3. Would you recommend this course to others?</strong></p>
                <input type="radio" id="recommend-yes" name="recommend" value="yes" required>
                <label for="recommend-yes">Yes</label><br>
                <input type="radio" id="recommend-no" name="recommend" value="no">
                <label for="recommend-no">No</label><br><br>
            </fieldset>

            <!-- Suggestions -->
            <fieldset>
                <legend><strong>Suggestions and Comments</strong></legend>
                <label for="comments">Your Comments:</label><br>
                <textarea id="comments" name="comments" rows="5" cols="40"></textarea>
            </fieldset>

            <!-- Submit Section -->
            <button type="submit">Submit</button>
        </form>
    </main>
</body>
</html>
