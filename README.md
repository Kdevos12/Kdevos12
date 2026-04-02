<!DOCTYPE html>
<html>
<head>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            border: 20px solid rainbow;
        }
        th, td {
            border: 20px solid magenta;
            padding: 15px;
            text-align: center;
        }
        th {
            background-color: blue;
            color: white;
        }
        tr:nth-child(even) {
            background-color: lightblue;
        }
        tr:nth-child(odd) {
            background-color: lightmagenta;
        }
    </style>
</head>
<body>
    <h2>Gallery</h2>
    <table>
        <tr>
            <th>Image</th>
            <th>Description</th>
        </tr>
        <tr>
            <td><img src='your-image-link.jpg' alt='Sample Image' width='300'></td>
            <td>This is a description of the sample image.</td>
        </tr>
        <!-- Add more rows as needed -->
    </table>
</body>
</html>
