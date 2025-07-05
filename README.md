<!DOCTYPE html><html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Naru Shop | ร้านขายสัตว์ Goal A Garden</title>
  <style>
    body {
      font-family: 'Kanit', sans-serif;
      background: linear-gradient(to bottom, #ffeaff, #e6f4ff);
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #d8b3ff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      color: white;
      font-size: 2.5rem;
      margin: 0;
    }
    .container {
      max-width: 1000px;
      margin: 20px auto;
      padding: 0 20px;
    }
    .pet-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
    }
    .pet-card {
      background: white;
      border-radius: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      overflow: hidden;
      text-align: center;
      padding: 10px;
    }
    .pet-card img {
      width: 100%;
      border-radius: 10px;
    }
    .pet-card h3 {
      margin: 10px 0 5px;
    }
    .pet-card p {
      margin: 0;
      color: #f06292;
    }
    .payment {
      background: #fff;
      margin-top: 40px;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 3px 10px rgba(0,0,0,0.1);
    }
    .payment h2 {
      color: #ba68c8;
    }
    .payment p {
      font-size: 1rem;
    }
    .btn-copy {
      display: inline-block;
      background-color: #f06292;
      color: white;
      padding: 10px 15px;
      border-radius: 10px;
      cursor: pointer;
      margin-top: 10px;
    }
    .discord {
      margin-top: 20px;
      text-align: center;
    }
    .discord a {
      background: #7289da;
      color: white;
      padding: 10px 20px;
      border-radius: 15px;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Naru Shop</h1>
    <p>ร้านขายสัตว์เลี้ยงในเกม Goal A Garden</p>
  </header>  <div class="container">
    <div class="pet-grid">
      <div class="pet-card">
        <img src="https://i.imgur.com/IRgD6GS.png" alt="Pet Example">
        <h3>แมวสายฟ้า</h3>
        <p>ราคา 89 บาท</p>
      </div>
      <div class="pet-card">
        <img src="https://i.imgur.com/yI4vN7v.png" alt="Pet Example">
        <h3>กระต่ายสายลม</h3>
        <p>ราคา 75 บาท</p>
      </div>
      <div class="pet-card">
        <img src="https://i.imgur.com/oVtT6hU.png" alt="Pet Example">
        <h3>หมาป่าหิมะ</h3>
        <p>ราคา 99 บาท</p>
      </div>
    </div><div class="payment">
  <h2>ชำระเงินผ่าน TrueMoney Wallet</h2>
  <p>📱 เบอร์สำหรับส่งซองของขวัญ: <strong id="walletNumber">094-271-3946</strong></p>
  <div class="btn-copy" onclick="copyWalletNumber()">คัดลอกเบอร์</div>
  <p style="margin-top:10px; color:gray">หลังโอนแล้ว โปรดแคปหลักฐานแล้วส่งใน Discord</p>
</div>

<div class="discord">
  <a href="https://discord.gg/dt5d8Chd" target="_blank">ติดต่อเราผ่าน Discord</a>
</div>

  </div>  <script>
    function copyWalletNumber() {
      const number = document.getElementById("walletNumber").innerText;
      navigator.clipboard.writeText(number);
      alert("คัดลอกเบอร์แล้ว: " + number);
    }
  </script></body>
</html>
