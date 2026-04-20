# hw-20
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Page Assignment</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 50px;
            background-color: #f0f0f0; /* Light grey background for the page */
        }

        /* Container to mimic the white box in the screenshot */
        .content-wrapper {
            background-color: white;
            padding: 40px;
            border: 1px solid #ccc;
            box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
            min-height: 300px;
            position: relative;
        }

        /* Table Styling */
        table {
            border-collapse: collapse;
            width: 350px;
            border: 2px solid #000;
        }

        th, td {
            border: 1px solid #000;
            padding: 12px;
            text-align: left;
            font-size: 1.2rem;
        }

        /* Header row background */
        th {
            background-color: #757575;
            color: white;
        }

        /* Logic for different background colors in rows 1 and 3 */
        tbody tr:nth-child(odd) {
            background-color: yellow;
        }

        tbody tr:nth-child(even) {
            background-color: white;
        }

        /* Fixed Div Styling */
        .fixed-element {
            position: fixed;
            top: 100px;    /* Distance from the top of the browser */
            right: 100px;  /* Distance from the right of the browser */
            width: 180px;
            height: 180px;
            border: 4px solid #70AD47; /* The specific green border */
            background-color: white;
            padding: 10px;
            font-size: 1.1rem;
            display: flex;
            align-items: flex-start;
            z-index: 1000;
        }
    </style>
</head>
<body>

    <div class="content-wrapper">
        <table>
            <thead>
                <tr>
                    <th>Firstname</th>
                    <th>Lastname</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>1</td>
                    <td>1</td>
                </tr>
                <tr>
                    <td>2</td>
                    <td>2</td>
                </tr>
                <tr>
                    <td>3</td>
                    <td>3</td>
                </tr>
            </tbody>
        </table>

        <div class="fixed-element">
            This div element has position: fixed;
        </div>
    </div>

</body>
</html>
