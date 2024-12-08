<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multiplication and More</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        input {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <h1>Multiplication and More</h1>
    <label for="biggerNumber">Enter bigger number:</label>
    <input type="number" id="biggerNumber" required><br>
    <label for="smallerNumber">Enter smaller number:</label>
    <input type="number" id="smallerNumber" required><br>
    <button onclick="calculate()">Calculate</button>

    <h2>Results:</h2>
    <p id="sum"></p>
    <p id="difference"></p>
    <p id="multiplication"></p>
    <p id="division"></p>
    <p id="average"></p>
    <p id="wholeSquare"></p>
<h3>created by *shashwat shukla*</h3>
<h4>*this website allows you to calculate sum, sub,division,multiply,average and whole square</h4>
<img src="path/to/your/image.jpg" alt="Description of the image" width="500" height="300">
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    <img src="https://wallpapercave.com/wp/wp7250087.jpg" alt="Created by java script" width="500" height="300">
</body>
</html>

html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Webpage</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
</body>
</html>
 <script>
        function calculate() {
            const a = parseFloat(document.getElementById('biggerNumber').value);
            const b = parseFloat(document.getElementById('smallerNumber').value);

            if (isNaN(a) || isNaN(b)) {
                alert("Please enter valid numbers.");
                return;
            }

            const multiplication = a * b;
            const division = a / b;
            const average = (a + b) / 2;
            const sum = a + b;
            const difference = a - b;
            const wholeSquare = a * a + b * b + (2 * a * b);

            document.getElementById('sum').textContent = "Sum is: " + sum;
            document.getElementById('difference').textContent = "Difference is: " + difference;
            document.getElementById('multiplication').textContent = "Multiplication is: " + multiplication;
            document.getElementById('division').textContent = "Division is: " + division;
            document.getElementById('average').textContent = "Average is: " + average;
            document.getElementById('wholeSquare').textContent = "Whole square is: " + wholeSquare;
        }
    </script>
</body>
</html>
