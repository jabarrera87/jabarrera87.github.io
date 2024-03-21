<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Activity Calculator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Daily Activity Calculator</h1>
        <div class="tasks">
            <div class="task">
                <label for="task1">Task 1 (Breakfast):</label>
                <input type="number" id="task1_duration" value="0" placeholder="Duration (minutes)">
                <input type="number" id="task1_calories" value="0" placeholder="Calories">
            </div>
            <div class="task">
                <label for="task2">Task 2 (Lunch):</label>
                <input type="number" id="task2_duration" value="0" placeholder="Duration (minutes)">
                <input type="number" id="task2_calories" value="0" placeholder="Calories">
            </div>
            <div class="task">
                <label for="task3">Task 3 (Dinner):</label>
                <input type="number" id="task3_duration" value="0" placeholder="Duration (minutes)">
                <input type="number" id="task3_calories" value="0" placeholder="Calories">
            </div>
            <!-- Add more tasks as needed -->
        </div>
        <button onclick="calculateTotal()">Calculate Total</button>
        <div id="total"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
