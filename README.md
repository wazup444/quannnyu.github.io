<!DOCTYPE html>
<html>
<head>
    <title>Dynamic Web Page Example</title>
</head>
<body>
    <h1>Dynamic Web Page Example</h1>
    
    <?php
    // Connect to the MySQL database
    $host = 'your_database_host';
    $username = 'your_username';
    $password = 'your_password';
    $database = 'your_database_name';

    $connection = mysqli_connect($host, $username, $password, $database);

    if (!$connection) {
        die("Connection failed: " . mysqli_connect_error());
    }

    // Query the database to retrieve data
    $sql = "SELECT * FROM your_table";
    $result = mysqli_query($connection, $sql);

    if (mysqli_num_rows($result) > 0) {
        echo "<ul>";
        while ($row = mysqli_fetch_assoc($result)) {
            echo "<li>" . $row['data_column'] . "</li>";
        }
        echo "</ul>";
    } else {
        echo "No data found.";
    }

    // Close the database connection
    mysqli_close($connection);
    ?>
</body>
</html>

        $('.container').css('background-color', '#f0f0f0');
    });
</script>

</body>
</html>
