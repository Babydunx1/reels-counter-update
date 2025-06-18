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
          src="https://raw.githubusercontent.com/Babydunx1/reels-counter-update/main/โปรแกรม%201.png"
          alt="IG Reels Screenshot"
          width="280" /><br>
        <em>📱 IG Reels View</em>
      </td>
      <td align="center">
        <img
          src="https://raw.githubusercontent.com/Babydunx1/reels-counter-update/main/โปรแกรม%202.png"
          alt="FB Reels Screenshot"
          width="280" /><br>
        <em>💻 FB Reels View</em>
      </td>
    </tr>
  </table>

</div>

> **💡 สำหรับ FB ใช้งานได้ดีสำหรับเพจที่มี Reels ล้วน ถ้าเพจที่มีข้อมูลโพสมากต่อวัน มีวิดีโอเยอะต่อวัน โพสภาพเยอะต่อวันอาจเจอบัคบางอย่างและทำงานผิดพลาด
>
> **⚠️ Warning:** อย่าเปิด GUI พร้อมกันหลายหน้าต่าง อาจทำให้ ChromeDriver เองเด้งได้
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

- รายงานบั๊ก / feature request → [Issues](https://github.com/Babydunx1/reels-counter-update/issues)  

---

## 📌 แนะนำโปรแกรม

Social Reels View Counter คือเครื่องมือที่ออกแบบมาสำหรับผู้ใช้งาน Instagram และ Facebook ที่ต้องการดึงยอดวิวและวันที่โพสต์ของคลิป Reels ได้อย่างรวดเร็ว แม่นยำ และมั่นคง ด้วยระบบที่ทันสมัยที่สุด มั่นใจได้ในประสิทธิภาพและเสถียรภาพสูงสุด

---

## 🛠️ Installation

ดูอัปเดตหรือดาวน์โหลดไฟล์ได้ที่  
[Release Page & Downloads](https://github.com/Babydunx1/reels-counter-update/releases)

---

## 🚀 จุดเด่นและความแข็งแกร่งของระบบ

### 🔗 การเชื่อมต่อ Backend & Frontend 

* **แยก UI และ Logic ชัดเจน:** ด้วย Callback และ API ที่เชื่อมโยงระหว่าง Python และ JavaScript การทำงานโปร่งใส มีประสิทธิภาพ พร้อมแสดงผลข้อมูลอย่างแม่นยำและทันที  
* **ChromeDriverManager:** ระบบอัตโนมัติเต็มรูปแบบ รองรับการอัปเดต Chrome อย่างไร้กังวล

### 🧠 ระบบ Smart Pre-Scroll & Stealth Date Fetch อัจฉริยะ

* **Smart Pre-Scroll:** คำนวณการเลื่อนหน้าจออย่างชาญฉลาดและหยุดทันทีเมื่อพบข้อมูลครบชุด ลดเวลาการทำงานได้มากกว่าเดิม  
* คำนวณ max index จากดัชนีสูงสุดในชุดเป้าหมาย ในลูป scroll จะเลื่อนลงทีละความสูงสุดท้ายเพจ แล้วเช็กจำนวน `<article>` ที่โหลดขึ้นมา ถ้าเจอครบ (max index + 1) ชิ้น ก็หยุด หาคลิปน้อยสั่งคำนวน Scroll เมื่อเจอจะหยุด  
* ยิง callback ทุก scroll → JS รู้สถานะแบบเรียลไทม์  
* ระบบหยุดตรงจุดที่ต้องการ (smart pre-scroll) ช่วยประหยัดเวลาโดยไม่เสียความแม่นยำ   
* **Stealth Date Fetch:** เข้าถึงแต่ละคลิปแบบลับเฉพาะ โดยไม่จำเป็นต้องเปิดแต่ละลิงก์จริง ประหยัดเวลาและเพิ่มความแม่นยำ

### 💡 ระบบ Jump Scroll อัจฉริยะ (Intelligent Jump Scroll System)

* เพิ่มความเร็วในการดึงข้อมูลวันที่ของคลิป Reels Facebook โดยการ "กระโดด scroll" ไปยังตำแหน่งที่คาดว่าโพสต์เป้าหมายอยู่ทันที โดยไม่ต้อง scroll ทีละรอบจากจุดเริ่มต้นเหมือนเดิม  
* ระบบจะกระโดดลึกขึ้นตามจำนวนคลิปที่ต้องการค้นหา โดยคำนวณจากจำนวน Scroll แบบ Pixel  
* ⏱️ เร็วขึ้นกว่าเดิมชัดเจน — จากต้อง scroll 8–12 รอบ เหลือแค่ 1–2 รอบ  
* 🎯 แม่นยำสูง — อ้างอิงผลทดสอบจากระยะ DOM จริง  
* 🧷 ปลอดภัยแม้ jump ไม่ถึง — มี fallback scroll ต่ออัตโนมัติ  
* 📊 รองรับทุกจำนวนคลิป (30 – 140 คลิป) — ปรับขนาด jump ให้อัตโนมัติตามคลิปที่ผู้ใช้ระบุ  
* 🔁 ปรับอัตโนมัติเมื่อค้นหาคลิปเกิน 30 คลิป → เริ่มเปิดใช้ Jump Scroll ระบบจะคำนวณ และจับระยะ jump อัตโนมัติตาม max_needed_index

### 📅 การดึงข้อมูลวันที่ **แม่นยำระดับ Pixel-Perfect**

* รองรับวันที่ในรูปแบบภาษาไทยและอังกฤษแบบไร้ขีดจำกัด ไม่ว่าจะเป็น "9 มิ.ย.", "9 Jun", หรือแม้กระทั่ง "เมื่อวาน"  
* ใช้ XPath และ JavaScript Injection แบบ Fallback หลายชั้น ทนทานต่อการเปลี่ยนแปลงของหน้าเว็บ

### 🎯 ระบบดึงยอดวิว

* ดึงยอดวิวจากฟีดหลักทันที ไม่ต้องเปิดแต่ละคลิป ระบบทำงานได้รวดเร็วและแม่นยำที่สุดในตลาด  
* รองรับการแปลงหน่วยยอดวิวทุกประเภท เช่น ร้อย, พัน, หมื่น, แสน, ล้าน พร้อมรับประกันความแม่นยำสูงสุด  
* ดึงยอดวิวได้แม่นยำ มีระบบแปลงตัวเลขทุกรูปแบบ ให้ได้ค่าตัวเลขที่ถูกต้อง เช่น 2.1 หมื่น = 21,000

### 🔍 URL & Reel ID Cleaner ประสิทธิภาพสูง

* ใช้เทคนิค Regex ขั้นสูง จัดการ URL ที่ซับซ้อนจาก Facebook ได้ทุกรูปแบบ ลดปัญหาและความผิดพลาดในการดึงข้อมูล

### 🛡️ **ความเสถียรของระบบ**

* **Headless Mode:** ใช้เบราเซอร์ในโหมดเบื้องหลังที่รวดเร็ว เสถียร และไม่รบกวนการทำงานปกติ  
* ระบบดึงวันที่ไม่พึ่งพา UI เดิมของ Facebook/IG และ Smart Pre-Scroll + Stealth Date Fetch → **ทนต่อการเปลี่ยน Layout**  
* **Robust Error Handling:** จัดการทุกปัญหาได้อัตโนมัติ ไม่ว่าจะเป็น Popup, Cookie consent, Timeout, Stale Elements  
* **ระบบอัปเดตอัตโนมัติเต็มรูปแบบ:** ตรวจสอบและติดตั้งอัปเดตอัตโนมัติ หมดปัญหาการใช้โปรแกรมเวอร์ชันล้าสมัย

### 🎨 UX/UI 

* **Real-time Progress:** แสดงสถานะทุกขั้นตอนอย่างละเอียด ไม่ต้องคาดเดาว่าระบบทำงานถึงไหนแล้ว  
* แจ้งสถานะระหว่าง scroll เช่น "กำลังดึงฟีด 3/15"  
* สรุปยอดรวมตอนจบแบบชัดเจน: "รวม 580,123 วิว จาก 60 คลิป"  
* **Interactive Results:** ผู้ใช้สามารถเลือกหรือคัดแยกรายการที่ไม่ต้องการได้ พร้อมคำนวณยอดวิวใหม่ทันที  
* **Persistent Login:** จัดเก็บ Cookies อัตโนมัติ ผู้ใช้ล็อกอินเพียงครั้งเดียว ใช้งานได้ต่อเนื่องไม่มีสะดุด  
* ตารางแสดงข้อมูลชัดเจน (ลิงก์, วิว, วันที่)  
* **ชัดเจนทุกข้อมูล:** แสดงข้อมูลในรูปแบบตารางที่เข้าใจง่าย พร้อมระบบ Debug Log เพื่อตรวจสอบย้อนหลังอย่างละเอียด

---

🚩 **Social Reels View Counter** คือที่สุดของเครื่องมือที่ตอบโจทย์ทุกความต้องการในด้านการดึงข้อมูล Instagram และ Facebook ที่ถูกออกแบบมาเพื่อความเสถียร ความรวดเร็ว และความแม่นยำระดับสูงสุด

---


## 🔗 ลิงก์ที่เกี่ยวข้อง

- 🔧 [GitHub Repository](https://github.com/Babydunx1/reels-counter-update)
- 📝 [รายงานฟีเจอร์อัปเดต](https://github.com/Babydunx1/reels-counter-update/releases)
- 📦 ดาวน์โหลดเวอร์ชันล่าสุด (ถ้ามี release)

---
### 5. FAQ (ปิดท้ายด้วยคำถามที่พบบ่อย)

## ❓ FAQ

**Q:** เปิดโปรแกรมไม่ได้ ติดตั้งแล้วรันไม่ได้  
**A:** แนะนำให้ปิดแอนตี้ไวรัสก่อน แล้วลงโปรแกรมใหม่ เพราะบางครั้งไฟล์ `.exe` จะถูกมองว่าเป็นไวรัส  

**Q:** โปรแกรมนี้มีไวรัสหรืออะไรที่ดึงข้อมูลส่วนตัวไหม  
**A:** ไม่มีแน่นอน 100% โปรเจกต์นี้โอเพนซอร์ส ตรวจสอบโค้ดได้เอง  

**Q:** โปรแกรมกดแล้วไม่มีอะไรเกิดขึ้น  
**A:** ตรวจสอบว่าคุณได้ติดตั้ง Google Chrome และ ChromeDriver ให้ตรงเวอร์ชันเรียบร้อยแล้ว  

---

<p align="center">
  <sub>Built with ❤️ by <a href="https://github.com/Babydunx1">BabyDunx1</a></sub>
</p>

<p align="right">
  <a href="#top">⬆️ กลับขึ้นบนสุด</a>
</p>



