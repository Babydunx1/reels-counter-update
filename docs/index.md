<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Reels Counter Pro | รายละเอียดโปรแกรม</title>
  <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Kanit', sans-serif;
      background: #f7f9fc;
      margin: 0;
      color: #2c3e50;
      line-height: 1.7;
      padding: 0 20px;
    }
    header {
      background: #1e88e5;
      color: white;
      padding: 20px 0;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    h1 {
      margin: 0;
      font-size: 1.8rem;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: white;
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 0 20px rgba(0,0,0,0.08);
    }
    h2 {
      color: #1565c0;
      border-bottom: 2px solid #e3f2fd;
      padding-bottom: 6px;
      margin-top: 40px;
    }
    ul {
      padding-left: 20px;
    }
    li::marker {
      color: #1e88e5;
    }
    .highlight {
      background: #e3f2fd;
      padding: 10px;
      border-left: 4px solid #42a5f5;
      margin-bottom: 20px;
    }
    footer {
      text-align: center;
      font-size: 0.9em;
      color: #888;
      margin-top: 60px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Reels Counter Pro</h1>
    <p>ระบบดึงยอดวิว + วันที่ ของ Reels จาก IG / Facebook อย่างแม่นยำ</p>
  </header>
  <div class="container">
    <h2>📌 จุดเด่นของโปรแกรม</h2>
    <ul>
      <li>แยก UI/Logic แบบ Callback → JS ยืดหยุ่นสุด</li>
      <li>ChromeDriver โหลดอัตโนมัติ ไม่ต้องเซ็ต Path</li>
      <li>ระบบ Scroll ฉลาด: หยุดเมื่อเจอครบ, ประหยัดเวลา</li>
      <li>ดึงวันโพสต์แบบ stealth: ไม่ต้องคลิกลิงก์</li>
      <li>XPath fallback 3 ชั้น: ทนต่อ layout เปลี่ยน</li>
      <li>แปลงยอดวิวทุกรูปแบบ: "2 หมื่น" → 20000</li>
      <li>ระบบอัปเดตอัตโนมัติ, ดึง Log ได้เรียลไทม์</li>
    </ul>

    <h2>🛡️ ระบบดึงวันที่ที่แม่นยำ</h2>
    <div class="highlight">
      ดึง <code>&lt;time&gt;</code>, <code>&lt;abbr&gt;</code>, และ <code>&lt;span&gt;</code> ทั้งภาษาไทยและอังกฤษ เช่น "9 มิ.ย.", "2 ชม.ที่แล้ว", "10 May"
    </div>
    <ul>
      <li>Stealth scroll → หยุดแค่เมื่อโหลดครบ</li>
      <li>ไม่โหลดซ้ำ ไม่ scroll เกิน</li>
    </ul>

    <h2>📊 ระบบดึงยอดวิว</h2>
    <ul>
      <li>ไม่ต้องคลิกทีละคลิป</li>
      <li>ดึงจาก feed หลัก → เร็วกว่า</li>
      <li>แม่นยำ: ใช้ regex + Reel ID ตรวจสอบ</li>
    </ul>

    <h2>🎯 จุดแข็งด้าน UX</h2>
    <ul>
      <li>แสดงสถานะ scroll: "โหลด 3/15"</li>
      <li>ตารางแสดงยอดวิว + วันครบถ้วน</li>
      <li>เลือกคลิปลบแล้วคำนวณใหม่ได้</li>
      <li>Debug log ดูย้อนหลังได้</li>
    </ul>

    <footer>
      &copy; 2025 Reels Counter Pro. All rights reserved.
    </footer>
  </div>
</body>
</html>
