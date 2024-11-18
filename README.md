<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <header>
    <img src="https://tse4.mm.bing.net/th?id=OIP.VK9lUV3pLUerqnIy4oenfwHaCY&pid=Api&P=0&h=180" alt="Centennial College Logo" style="display: block; margin: 0 auto; height: 100px;">
    <h1>Centennial College</h1>
    <p>Continuing Education Course/Instructor Evaluation</p>
</header>

    <link rel="stylesheet" href="styles.css">
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #808000; /* Olive green background */
            color: #333;
        }

        header {
            background-color: #556B2F;
            color: white;
            text-align: center;
            padding: 15px;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        h1, h2 {
            text-align: center;
        }

        h2 {
            font-weight: bold; /* Subheading bold */
            color: #556B2F;
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
            margin: 10px 0 5px;
        }

        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }

        input[type="radio"] {
            width: auto;
            margin-right: 5px;
        }

        button {
            background-color: #556B2F;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #6B8E23;
        }
    </style>
</head>
<body>
    <header>
        <h1>Centennial College</h1>
        <p>Continuing Education Course/Instructor Evaluation</p>
    </header>
    <main>
        <form>
            <!-- Course Information -->
            <fieldset>
                <legend>Course Information</legend>
                <label for="courseName">Course Name/Code:</label>
                <input type="text" id="courseName" name="courseName">

                <label for="semester">Semester:</label>
                <select id="semester" name="semester">
                    <option value="Fall">Fall</option>
                    <option value="Winter">Winter</option>
                    <option value="Spring/Summer">Spring/Summer</option>
                </select>

                <label for="year">Year:</label>
                <input type="text" id="year" name="year">

                <label for="instructor">Instructor:</label>
                <input type="text" id="instructor" name="instructor">
            </fieldset>

            <!-- Instructor Evaluation -->
            <fieldset>
                <legend>Instructor Evaluation</legend>
                <h2>How would you rate the instructor's:</h2>

                <label>1. Knowledge of Subject:</label>
                <label><input type="radio" name="knowledge" value="Excellent"> Excellent</label>
                <label><input type="radio" name="knowledge" value="Good"> Good</label>
                <label><input type="radio" name="knowledge" value="Fair"> Fair</label>
                <label><input type="radio" name="knowledge" value="Not Satisfactory"> Not Satisfactory</label>

                <label>2. Helpfulness:</label>
                <label><input type="radio" name="helpfulness" value="Excellent"> Excellent</label>
                <label><input type="radio" name="helpfulness" value="Good"> Good</label>
                <label><input type="radio" name="helpfulness" value="Fair"> Fair</label>
                <label><input type="radio" name="helpfulness" value="Not Satisfactory"> Not Satisfactory</label>

                <label>3. Courtesy and Respect for All Students:</label>
                <label><input type="radio" name="courtesy" value="Excellent"> Excellent</label>
                <label><input type="radio" name="courtesy" value="Good"> Good</label>
                <label><input type="radio" name="courtesy" value="Fair"> Fair</label>
                <label><input type="radio" name="courtesy" value="Not Satisfactory"> Not Satisfactory</label>

                <label>4. Communication Skills:</label>
                <label><input type="radio" name="communication" value="Excellent"> Excellent</label>
                <label><input type="radio" name="communication" value="Good"> Good</label>
                <label><input type="radio" name="communication" value="Fair"> Fair</label>
                <label><input type="radio" name="communication" value="Not Satisfactory"> Not Satisfactory</label>

                <label>5. Overall Performance:</label>
                <label><input type="radio" name="performance" value="Excellent"> Excellent</label>
                <label><input type="radio" name="performance" value="Good"> Good</label>
                <label><input type="radio" name="performance" value="Fair"> Fair</label>
                <label><input type="radio" name="performance" value="Not Satisfactory"> Not Satisfactory</label>
            </fieldset>

            <!-- Course Evaluation -->
            <fieldset>
                <legend>Course Evaluation</legend>
                <h2>How would you rate the:</h2>

                <label>6. Course Materials:</label>
                <label><input type="radio" name="materials" value="Excellent"> Excellent</label>
                <label><input type="radio" name="materials" value="Good"> Good</label>
                <label><input type="radio" name="materials" value="Fair"> Fair</label>
                <label><input type="radio" name="materials" value="Not Satisfactory"> Not Satisfactory</label>

                <label>7. How much did this course meet your Expectations?</label>
                <label><input type="radio" name="expectations" value="Excellent"> Excellent</label>
                <label><input type="radio" name="expectations" value="Good"> Good</label>
                <label><input type="radio" name="expectations" value="Fair"> Fair</label>
                <label><input type="radio" name="expectations" value="Not Satisfactory"> Not Satisfactory</label>

                <label>8. Overall Rating:</label>
                <label><input type="radio" name="overall" value="Excellent"> Excellent</label>
                <label><input type="radio" name="overall" value="Good"> Good</label>
                <label><input type="radio" name="overall" value="Fair"> Fair</label>
                <label><input type="radio" name="overall" value="Not Satisfactory"> Not Satisfactory</label>
            </fieldset>

            <!-- General Information -->
            <fieldset>
                <legend>General Information</legend>

                <label>9. Was the Course Outline reviewed/explained?</label>
                <label><input type="radio" name="outline" value="Yes"> Yes</label>
                <label><input type="radio" name="outline" value="No"> No</label>
                <label><input type="radio" name="outline" value="Not Sure"> Not Sure</label>

                <label>10. Would you recommend this Course to a friend?</label>
                <label><input type="radio" name="recommend" value="Yes"> Yes</label>
                <label><input type="radio" name="recommend" value="No"> No</label>
                <label><input type="radio" name="recommend" value="Not Sure"> Not Sure</label>
            </fieldset>

            <!-- Additional Comments -->
            <fieldset>
                <legend>Other Comments</legend>
                <label for="bestThing">11. What is the best thing about this course?</label>
                <textarea id="bestThing" name="bestThing" rows="3"></textarea>

                <label for="improve">12. How could we improve this course?</label>
                <textarea id="improve" name="improve" rows="3"></textarea>

                <label for="other">13. Other Comments:</label>
                <textarea id="other" name="other" rows="3"></textarea>
            </fieldset>

            <button type="submit">Submit</button>
        </form>
    </main>
</body>
</html>

