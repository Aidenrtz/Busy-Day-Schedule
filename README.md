<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Busy Day Schedule</title>
    <style>
        /* Styling for the table */
        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
            background-color: #f4f4f9;
        }

/* Styling for table headers */
        th {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            text-align: left;
        }

/* Styling for table cells */
        td {
            padding: 10px;
            text-align: left;
            border: 1px solid #ddd;
        }

 /* Styling for rows with events */
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }

  /* Highlighting the current event */
        .current {
            background-color: #ffeb3b;
        }

  /* Styling for table header */
        caption {
            font-size: 1.5em;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>

 <h1>Aiden's Busy Day Schedule</h1>

 <table>
        <caption>My Daily Schedule</caption>
        <thead>
            <tr>
                <th>Time</th>
                <th>Task/Event</th>
            </tr>
        </thead>
        <tbody>
            <tr class="current">
                <td>7:00 AM</td>
                <td>Wake up and make breakfast</td>
            </tr>
            <tr>
                <td>8:00 AM</td>
                <td>Work on Spanish final assignment</td>
            </tr>
            <tr>
                <td>10:00 AM</td>
                <td>Study HTML coding</td>
            </tr>
            <tr>
                <td>12:00 PM</td>
                <td>Lunch break</td>
            </tr>
            <tr>
                <td>1:00 PM</td>
                <td>Write for my English final</td>
            </tr>
            <tr>
                <td>3:00 PM</td>
                <td>Workout and do small jog</td>
            </tr>
            <tr>
                <td>5:00 PM</td>
                <td>Catch up with my friend Violet</td>
            </tr>
            <tr>
                <td>7:00 PM</td>
                <td>Watch a horror movie</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
