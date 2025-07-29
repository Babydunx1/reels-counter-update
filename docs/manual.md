<a name="top"></a>
<!-- Badges -->
<!-- Tech Stack Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Selenium-4.x-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium"/>
  <img src="https://img.shields.io/badge/WebDriver–Manager-automated-blue?style=for-the-badge" alt="webdriver-manager"/>
  <img src="https://img.shields.io/badge/PyWebView-3.x-brightgreen?style=for-the-badge" alt="PyWebView"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/ChromeDriverManager-chrome-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="ChromeDriverManager"/>
</p>



<div align="center">

  <!-- Logo -->
  <img
    src="https://raw.githubusercontent.com/Babydunx1/reels-counter-update/main/Reels_Counter_Pro_LOGO_transparent.png"
    alt="Reels Counter Pro Logo"
    width="120" />

  <!-- Title -->
  <h1>🎬 Reels Counter Pro</h1>

  <!-- Divider -->
  **— — —**

  <!-- Screenshot comparison table -->
<table>
  <tr>
    <td align="center">
      <img
        src="https://raw.githubusercontent.com/Babydunx1/reels-counter-update/main/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%81%E0%B8%81%E0%B8%A3%E0%B8%A13.png"
        alt="IG Reels Screenshot"
        width="280" /><br>
      <em>💻 FB Reels View</em>
    </td>
    <td align="center">
      <img
        src="https://raw.githubusercontent.com/Babydunx1/reels-counter-update/main/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%81%E0%B8%81%E0%B8%A3%E0%B8%A14.png"
        alt="FB Reels Screenshot"
        width="280" /><br>
      <em>📱 IG Reels View</em>
    </td>
  </tr>
</table>


</div>

<p align="center">
  <a href="https://github.com/Babydunx1/reels-counter-update/releases">
    <img src="https://img.shields.io/badge/Download–Latest-blue?style=for-the-badge&logo=github" alt="Download"/>
  </a>
  <a href="https://github.com/Babydunx1/reels-counter-update/stargazers">
    <img src="https://img.shields.io/badge/⭐️–Star–on–GitHub-ff69b4?style=for-the-badge&logo=github" alt="Star"/>
  </a>
</p>


---

## 💬 Support
- 📝 [รายงานฟีเจอร์อัปเดต](https://github.com/Babydunx1/reels-counter-update/releases)
- รายงานบั๊ก / feature request → [Issues](https://github.com/Babydunx1/reels-counter-update/issues)  

---

## 🚀 จุดเด่นและความแข็งแกร่งของระบบ

### 🔗 การเชื่อมต่อ Backend & Frontend

* **แยก UI และ Logic ชัดเจน:** ด้วย Callback และ API ที่เชื่อมโยงระหว่าง Python และ JavaScript การทำงานโปร่งใส มีประสิทธิภาพ พร้อมแสดงผลข้อมูลอย่างแม่นยำและทันที
* **ChromeDriverManager:** ระบบอัตโนมัติเต็มรูปแบบ รองรับการอัปเดต Chrome อย่างไร้กังวล

---

### 🧠 JSON-First Date Engine (ใหม่ล่าสุด)

* ยกเลิกระบบ Jump Scroll + XPath เก่า
* ใช้ `<script type="application/json">` เพื่อดึง `creation_time` หรือ field ที่ลงท้ายด้วย `time`
* ดึงพร้อมกันสูงสุด 30 คลิปแบบขนานด้วย Browser หลายตัว
* ถ้า JSON ล้มเหลว → fallback XPath บางจุดในคลิปนั้นเท่านั้น (เร็วและแม่นยำกว่าหลายเท่า)
* แสดงวันที่แบบ Locale ภาษาไทย เช่น `5 ก.ค. 2567`

---

### 🔧 ระบบเบื้องหลังอัจฉริยะ (Browser + Language)

* **Standby Driver:** เปิดเบราเซอร์แบบเบื้องหลังไว้ล่วงหน้า พร้อมดึงข้อมูลทันทีแบบ Manual Mode
* **Auto-Close Browser:** เคลียร์ session ทันทีเมื่อล้างข้อมูล ลดโอกาสค้าง DOM หรือ session ซ้อน
* **Language Engine ใหม่ล่าสุด** (v1.4)

  * รองรับการเปลี่ยนภาษา Facebook แบบอัตโนมัติ (ทุกภาษา!)
  * รองรับ 20+ ภาษา เช่น ไทย 🇹🇭, อังกฤษ 🇬🇧, ตุรกี 🇹🇷, พม่า 🇲🇲, รัสเซีย 🇷🇺 ฯลฯ
  * ใช้การค้นหาปุ่ม Save จาก aria-label + คีย์เวิร์ด
  * ตรวจสอบว่าเปลี่ยนภาษาสำเร็จแบบไร้รอยต่อใน 0.5 วินาที

---

### 🧪 ระบบดึงยอดวิวและข้อมูลคลิปแบบเรียลไทม์

* ดึงยอดวิวจากหน้า feed โดยไม่ต้องเปิดลิงก์
* แปลงหน่วยอัตโนมัติ เช่น "2.1 หมื่น" → `21000`
* รองรับการดึงวิดีโอในแท็บ "วิดีโอ" ของเพจ Facebook โดยไม่ดึง Playlist มั่ว
* แสดงข้อมูลแบบ Real-time พร้อมสรุปผลแบบสวยงาม

---

### 📊 ระบบแสดงผล & สถานะ (UI / UX)

* **Real-time Progress:** แสดงสถานะการ scroll / ดึงคลิป / ดึงข้อมูลรายคลิปแบบละเอียด
* **สีสถานะเบราเซอร์:** 🟢 พร้อมใช้งาน, 🟠 กำลังดึง, 🔴 ถูกปิดอย่างปลอดภัย
* **สรุปผลอัตโนมัติ:** ยอดรวมวิว, จำนวนคลิป, ตารางพร้อมลิงก์-วันที่-วิว แบบแยก
* **Interactive Table:** กดเลือกคลิป/ลบ/ย้อนกลับได้ พร้อมอัปเดตยอดรวมอัตโนมัติ

> ✅ **ช่วยให้ผู้ใช้มั่นใจในความสะอาดของระบบ** และสามารถตรวจสอบสถานะการทำงานได้ด้วยตนเองแบบ Real-Time

---

### 🎨 UX/UI

* **Real-time Progress:** แสดงสถานะทุกขั้นตอนอย่างละเอียด ไม่ต้องคาดเดาว่าระบบทำงานถึงไหนแล้ว
* สรุปยอดรวมตอนจบแบบชัดเจน เช่น "รวม 580,123 วิว จาก 60 คลิป"
* **Interactive Results:** ผู้ใช้สามารถเลือกหรือคัดแยกรายการที่ไม่ต้องการได้ พร้อมคำนวณยอดวิวใหม่ทันที
* ตารางแสดงข้อมูลชัดเจน (ลิงก์, วิว, วันที่)
* **ชัดเจนทุกข้อมูล:** แสดงข้อมูลในรูปแบบตารางที่เข้าใจง่าย พร้อมระบบ Debug Log เพื่อตรวจสอบย้อนหลังอย่างละเอียด

---

### 🔐 เสถียรภาพและความปลอดภัย

* **Headless + Parallel + Auto Update:** ทำงานเบื้องหลัง, รันพร้อมกัน, อัปเดตอัตโนมัติ
* **Error Handling ครบถ้วน:** รองรับ timeout, cookie popup, stale DOM, แปลก UI, layout ใหม่
* **ใช้งานง่าย:** ล็อกอินเพียงครั้งเดียว ระบบจดจำ cookies ถาวร

---

### 🧩 เทคโนโลยีและการต่อยอด

* ระบบรองรับการอัปเกรดสู่ Facebook - Instagram API ในอนาคต
* โครงสร้างรองรับฟีเจอร์ใหม่ เช่น การจัดกลุ่มพนักงาน, การเปรียบเทียบรายเดือน, การแจ้งเตือนอัตโนมัติ ฯลฯ

---

🚩 **Social Reels View Counter** คือที่สุดของเครื่องมือวิเคราะห์ข้อมูลยอดวิวบน Facebook และ Instagram ที่เร็ว เสถียร แม่นยำ และสวยงามที่สุดในยุคนี้

---

## 🔗 ลิงก์ที่เกี่ยวข้อง

* 🔧 [GitHub Repository](https://github.com/Babydunx1/reels-counter-update)

---

### ❓ FAQ

**Q:** เปิดโปรแกรมไม่ได้ ติดตั้งแล้วรันไม่ได้
**A:** ปิดแอนตี้ไวรัสชั่วคราว แล้วติดตั้งใหม่ (บางไฟล์ `.exe` ถูกตรวจผิดพลาดว่าเป็นไวรัส)

**Q:** โปรแกรมนี้มีไวรัสหรือดึงข้อมูลส่วนตัวไหม?
**A:** ไม่มีแน่นอน 100% โอเพนซอร์ส ตรวจสอบได้ทั้งหมด

**Q:** กดแล้วไม่มีอะไรเกิดขึ้น?
**A:** ตรวจสอบให้แน่ใจว่าติดตั้ง Google Chrome ไว้ในเครื่องแล้ว

---

<p align="center">
  <sub>Built with ❤️ by <a href="https://github.com/Babydunx1">BabyDunx1</a></sub>
</p>

<p align="right">
  <a href="#top">⬆️ กลับขึ้นบนสุด</a>
</p>





