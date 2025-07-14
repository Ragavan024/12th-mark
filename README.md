<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HSE(+2) Examination Results - March 2025</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #f8f9fa;
      color: #000;
      text-align: center;
    }
    .header {
      background-color: #800080;
      color: white;
      padding: 10px;
      font-size: 18px;
      font-weight: bold;
      margin-bottom: 20px;
    }
    table {
      margin: 20px auto;
      border-collapse: collapse;
      width: 90%;
      max-width: 600px;
      background: #fff;
    }
    th, td {
      border: 1px solid #000;
      padding: 10px;
    }
    th {
      background-color: #006400;
      color: white;
    }
    input[type="text"] {
      padding: 10px;
      margin: 10px;
      width: 220px;
      font-size: 16px;
    }
    button {
      padding: 10px 25px;
      font-size: 16px;
      cursor: pointer;
      background-color: #006400;
      color: white;
      border: none;
    }
    button:hover {
      background-color: #004d00;
    }
    .footer {
      font-size: 13px;
      margin-top: 30px;
      color: gray;
    }
    #result {
      display: none;
    }
  </style>
</head>
<body>
  <h2>Government of Tamil Nadu<br>Directorate of Government Examinations</h2>
  <div class="header">HSE(+2) Examination Results - March 2025</div>

  <div>
    <input type="text" id="regNo" placeholder="Enter Register Number">
    <input type="text" id="dob" placeholder="Enter DOB (DD.MM.YYYY)">
    <br>
    <button onclick="showResult()">Submit</button>
  </div>

  <div id="result">
    <table>
      <tr><th colspan="6">VINOTH M (1260945)</th></tr>
      <tr>
        <th>Subject</th><th>Int</th><th>Theory</th><th>Pra</th><th>Total</th><th>Pass</th>
      </tr>
      <tr><td>TAMIL</td><td>010</td><td>076</td><td></td><td>086</td><td>P</td></tr>
      <tr><td>ENGLISH</td><td>010</td><td>063</td><td></td><td>073</td><td>P</td></tr>
      <tr><td>ECONOMICS</td><td>010</td><td>067</td><td></td><td>077</td><td>P</td></tr>
      <tr><td>COMMERCE</td><td>010</td><td>053</td><td></td><td>063</td><td>P</td></tr>
      <tr><td>ACCOUNTANCY</td><td>010</td><td>049</td><td></td><td>059</td><td>P</td></tr>
      <tr><td>BUSINESS MATHS & STA</td><td>010</td><td>067</td><td></td><td>077</td><td>P</td></tr>
      <tr><td colspan="4"><b>TOTAL</b></td><td><b>0435</b></td><td><b>PASS</b></td></tr>
    </table>

    <div class="footer">
      <p><b>Disclaimer:</b> This is a sample page and not an official mark statement.</p>
      <p>Site Designed and hosted for demo purpose only.</p>
    </div>
  </div>

  <script>
    function showResult() {
      const regNo = document.getElementById("regNo").value.trim();
      const dob = document.getElementById("dob").value.trim();
      const resultDiv = document.getElementById("result");

      if (regNo === "1260945" && dob === "06.01.2006") {
        resultDiv.style.display = "block";
      } else {
        resultDiv.style.display = "none";
        alert("Invalid Register Number or Date of Birth!");
      }
    }
  </script>
</body>
</html>
