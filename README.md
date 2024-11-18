<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CE Course Evaluation Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #0055A5;
            color: white;
            text-align: center;
            padding: 20px;
        }

        header a {
            text-decoration: none;
            color: white;
        }

        header img {
            max-width: 150px;
            display: block;
            margin: 0 auto;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        form {
            display: flex;
            flex-direction: column;
        }

        fieldset {
            border: 1px solid #ccc;
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 5px;
        }

        legend {
            font-weight: bold;
        }

        label {
            display: block;
            margin-top: 10px;
        }

        input, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }

        button {
            background-color: #0055A5;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #003f7f;
        }
    </style>

<body>
    <!-- Header with Banner -->
    <header>
        <a href="https://www.centennialcollege.ca" target="_blank">
            <img src="https://tse4.mm.bing.net/th?id=OIP.VK9lUV3pLUerqnIy4oenfwHaCY&pid=Api&P=0&h=180" alt="Centennial College Logo">
        </a>
        <h1>CE Course Evaluation Form</h1>
    </header>

    <!-- Evaluation Form -->
    <main>
        <form action="/submit" method="post">
            <fieldset>
                <legend>Course Details</legend>
                <label for="course-name">Course Name:</label>
                <input type="text" id="course-name" name="course-name" required>

                <label for="instructor-name">Instructor Name:</label>
                <input type="text" id="instructor-name" name="instructor-name" required>

                <label for="course-code">Course Code:</label>
                <input type="text" id="course-code" name="course-code" required>
            </fieldset>

            <fieldset>
                <legend>Evaluation Questions</legend>
                <p>1. The course content met my expectations:</p>
                <label>
                    <input type="radio" name="question1" value="strongly-agree" required> Strongly Agree
                </label>
                <label>
                    <input type="radio" name="question1" value="agree"> Agree
                </label>
                <label>
                    <input type="radio" name="question1" value="neutral"> Neutral
                </label>
                <label>
                    <input type="radio" name="question1" value="disagree"> Disagree
                </label>
                <label>
                    <input type="radio" name="question1" value="strongly-disagree"> Strongly Disagree
                </label>

                <p>2. The instructor demonstrated knowledge of the subject:</p>
                <!-- Repeat similar structure for other questions -->
            </fieldset>

            <fieldset>
                <legend>Additional Comments</legend>
                <label for="comments">Please share your feedback:</label>
                <textarea id="comments" name="comments" rows="5"></textarea>
            </fieldset>

            <!-- Submit Button -->
            <button type="submit">Submit</button>
        </form>
    </main>
</body>
</html>
