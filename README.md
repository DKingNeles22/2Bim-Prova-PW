# 2Bim-Prova-PW

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domain Manager</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Domain Manager</h1>
        <form id="domain-form">
            <input type="text" id="domain-name" placeholder="Domain Name" required>
            <input type="text" id="domain-owner" placeholder="Owner" required>
            <button type="submit">Add Domain</button>
        </form>
        <ul id="domain-list"></ul>
    </div>
    <script src="app.js"></script>
</body>
</html>
