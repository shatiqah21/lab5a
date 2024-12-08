<!DOCTYPE html>
<html lang="en">
<head>
    <title>Multiplication Table</title>
    <style>
        table, th, td {
            border: 1px solid black;
        }
    </style>
</head>
<body>
    <?php
    // Define the multiplication function
    function multiplication($multiplier) {
        $results = [];
        for ($i = 1; $i <= 12; $i++) {
            $results[] = [
                'no' => $i,
                'multiplier' => $multiplier,
                'answer' => $i * $multiplier
            ];
        }
        return $results;
    }

    // Call the function with a specific multiplier
    $multiplier = 2; // Change this value as needed
    $multiplicationTable = multiplication($multiplier);
    ?>

    <!-- Display the multiplication table in HTML -->
    <table>
        <tr>
            <th>No</th>
            <th>Multiplier</th>
            <th>Answer</th>
        </tr>
        <?php foreach ($multiplicationTable as $row): ?>
            <tr>
                <td><?php echo $row['no']; ?></td>
                <td><?php echo $row['multiplier']; ?></td>
                <td><?php echo $row['answer']; ?></td>
            </tr>
        <?php endforeach; ?>
    </table>
</body>
</html>
