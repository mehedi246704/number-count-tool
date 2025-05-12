<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Number Count Sheet</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poiret+One&display=swap " rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=ITC+Avant+Garde+Gothic+Pro&display=swap " rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'ITC Avant Garde Gothic Pro', sans-serif;
      background-image: linear-gradient(to top, #dbdcd7 0%, #dddcd7 24%, #e2c9cc 30%, #e7627d 46%, #b8235a 59%, #801357 71%, #3d1635 84%, #1c1a27 100%);
      min-height: 100vh;
      position: relative;
      overflow-x: hidden;
    }

    /* Fixed Footer at Top Center */
    .footer {
      position: fixed;
      top: 0;
      left: 50%;
      transform: translateX(-50%);
      width: auto;
      padding: 10px 30px;
      text-align: center;
      z-index: 1000;
    }

    .footer h3 {
      font-family: 'Poiret One', cursive;
      font-size: 24px;
      color: #333;
      margin-bottom: 4px;
    }

    .footer span {
      font-family: 'ITC Avant Garde Gothic Pro', sans-serif;
      font-size: 16px;
      color: #ffffff;
      display: block;
    }

    .container {
      max-width: 600px;
      background: white;
      margin: 100px auto 40px;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0,0,0,0.2);
      position: relative;
      z-index: 1;
    }

    h2 {
      text-align: center;
      font-family: 'Poiret One', cursive;
      font-size: 36px;
      color: #333;
      margin-bottom: 20px;
    }

    textarea {
      width: 100%;
      height: 100px;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      resize: none;
    }

    button {
      width: 100%;
      padding: 12px;
      background: #dc0073;
      border: none;
      color: white;
      font-weight: bold;
      border-radius: 6px;
      cursor: pointer;
      margin: 10px 0;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #5f0050;
    }

    #resultBox {
      max-height: 300px;
      overflow-y: auto;
      margin-top: 15px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }

    th, td {
      border: 1px solid #ddd;
      padding: 10px;
      text-align: center;
    }

    th {
      background-color: #f9f9f9;
    }

    /* 3D Cube Animation - CSS Only */
    .shape {
      width: 100px;
      height: 100px;
      position: absolute;
      left: 50%;
      transform-style: preserve-3d;
      animation: rotateCube 8s linear infinite;
      z-index: 0;
    }

    .shape.top {
      top: -100px;
      transform: translateX(-50%) rotateY(0deg);
    }

    .shape.bottom {
      bottom: -100px;
      transform: translateX(-50%) rotateY(180deg);
    }

    .face {
      position: absolute;
      width: 100px;
      height: 100px;
      background: #dc0073;
      opacity: 0.7;
      border-radius: 10px;
    }

    .front  { transform: translateZ(50px); }
    .back   { transform: rotateY(180deg) translateZ(50px); }

    @keyframes rotateCube {
      from {
        transform: translateX(-50%) rotateX(0deg) rotateY(0deg);
      }
      to {
        transform: translateX(-50%) rotateX(360deg) rotateY(360deg);
      }
    }
  </style>
</head>
<body>

  <!-- Footer Credit at Top Center -->
  <div class="footer">
    <h3>Made By</h3>
    <span>Emam Mehedi</span><br>



  <!-- Top 3D Shape -->
  <div class="shape top">
    <div class="face front"></div>
    <div class="face back"></div>
    <div class="face right"></div>
    <div class="face left"></div>
    <div class="face top"></div>
    <div class="face bottom"></div>
  </div> 

  <!-- Main Container -->
  <div class="container">
    <h2>Number Count Sheet</h2>
    <input type="file" id="csvFile" accept=".csv" style="margin-bottom: 15px;" />
    <textarea id="specificNumbers" placeholder="Enter specific numbers here, separated by comma or space..."></textarea>
    <button onclick="countSpecificNumbers()">Count Now By- Mehedi</button>
    <button onclick="downloadCSV()">Download CSV</button>
    <div id="resultBox">
      <table id="resultTable">
        <thead>
          <tr><th>Serial</th><th>Number</th><th>Count</th></tr>
        </thead>
        <tbody></tbody>
      </table>
    </div>
  </div>

  <!-- Bottom 3D Shape -->
  <div class="shape bottom">
    <div class="face front"></div>
    <div class="face back"></div>
    <div class="face right"></div>
    <div class="face left"></div>
    <div class="face top"></div>
    <div class="face bottom"></div>
  </div>

  <!-- JavaScript -->
  <script>
    let uploadedData = "";

    document.getElementById('csvFile').addEventListener('change', function(e) {
      const file = e.target.files[0];
      if (file && file.name.endsWith('.csv')) {
        const reader = new FileReader();
        reader.onload = function(e) {
          uploadedData = e.target.result;
        };
        reader.readAsText(file);
      } else {
        alert("Please upload a valid CSV file.");
      }
    });

    function countSpecificNumbers() {
      const targetNumbers = document.getElementById('specificNumbers').value.trim().split(/[\s,]+/);
      const dataNumbers = uploadedData.trim().split(/[\s,]+/);

      const countMap = {};
      dataNumbers.forEach(num => {
        countMap[num] = (countMap[num] || 0) + 1;
      });

      const tbody = document.querySelector("#resultTable tbody");
      tbody.innerHTML = "";

      targetNumbers.forEach((num, index) => {
        const count = countMap[num] || 0;
        const row = `<tr><td>${index + 1}</td><td>${num}</td><td>${count}</td></tr>`;
        tbody.innerHTML += row;
      });
    }

    function downloadCSV() {
      const rows = [["Serial", "Number", "Count"]];
      const tableRows = document.querySelectorAll("#resultTable tbody tr");
      tableRows.forEach(row => {
        const cells = row.querySelectorAll("td");
        const rowData = Array.from(cells).map(cell => cell.innerText);
        rows.push(rowData);
      });

      const csvContent = rows.map(e => e.join(",")).join("\n");
      const blob = new Blob([csvContent], { type: "text/csv;charset=utf-8;" });
      const url = URL.createObjectURL(blob);
      const link = document.createElement("a");
      link.href = url;
      link.setAttribute("download", "count_result.csv");
      document.body.appendChild(link);
      link.click();
      document.body.removeChild(link);
    }
  </script>
</body>
</html>
