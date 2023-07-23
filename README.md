# Data-visualization-html-code-index.html
Data visualization html code
<!DOCTYPE html>
<html>
<head>
    <title>Pie Chart Data Visualization</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <h1>Pie Chart Data Visualization</h1>
    <form id="dataForm">
        <label for="dataInput">Enter data (comma-separated numbers):</label>
        <input type="text" id="dataInput" name="dataInput" required>
        <button type="submit">Visualize Pie Chart</button>
    </form>
    <div class="chart-container">
        <canvas id="pieChart"></canvas>
    </div>

    <script src="script.js"></script>
</body>
</html>
