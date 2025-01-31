# 🔔 **มาตรฐานข้อความแจ้งเตือน (Notification Standards)**

## 📝 **หลักการเขียนข้อความแจ้งเตือน (Principles for Writing Notifications)**

1. **ชัดเจน (Clarity)** – ใช้ข้อความที่เข้าใจง่ายและตรงประเด็น  
   **Clear** – Make sure the messages are easy to understand and to the point.
2. **กระชับ (Conciseness)** – ใช้ข้อความที่สั้นแต่สื่อสารได้ครบถ้วน  
   **Concise** – Keep the messages short but informative.
3. **มีมารยาท (Politeness)** – ใช้ภาษาที่เป็นมิตรและสุภาพ  
   **Polite** – Use friendly and professional language.
4. **สามารถดำเนินการได้ (Actionability)** – ให้คำแนะนำที่ชัดเจนเกี่ยวกับสิ่งที่ผู้ใช้ควรทำต่อไป  
   **Actionable** – Provide clear guidance on what users should do next.
5. **มีสัญญาณภาพ (Visual Cues)** – ใช้สีและไอคอนเพื่อช่วยให้อ่านและเข้าใจง่าย  
   **Visual Cues** – Use colors and icons to enhance readability.
6. **เกี่ยวข้อง (Relevance)** – แสดงข้อความเฉพาะเมื่อจำเป็นเท่านั้น  
   **Relevant** – Show messages only when needed.
7. **รองรับผู้พิการ (Accessibility)** – รองรับเครื่องอ่านหน้าจอและคำนึงถึงผู้ที่มีภาวะตาบอดสี  
   **Accessible** – Support screen readers and color-blind users.

---

## 🎨 **มาตรฐานสีสำหรับข้อความแจ้งเตือน (Notification Color Standards)**

การใช้สีที่เหมาะสมช่วยให้ผู้ใช้สามารถเข้าใจบริบทของข้อความได้เร็วขึ้น:

- 🟥 **สีแดง (#FF4C4C)** – ใช้สำหรับ **Error & Failure Messages** (ข้อผิดพลาด)
- 🟧 **สีส้ม (#FFA500)** – ใช้สำหรับ **Warning Messages** (คำเตือน)
- 🟨 **สีเหลือง (#FFD700)** – ใช้สำหรับ **Informational Messages** (ข้อความข้อมูลทั่วไป)
- 🟩 **สีเขียว (#4CAF50)** – ใช้สำหรับ **Success Messages** (ความสำเร็จ)
- 🔵 **สีน้ำเงิน (#007BFF)** – ใช้สำหรับ **Processing & Loading Messages** (กำลังดำเนินการ)
- ⚪ **สีเทา (#B0BEC5)** – ใช้สำหรับ **Neutral or Secondary Messages** (ข้อความที่ไม่เร่งด่วน)

---

## 🛑 **ข้อความแสดงข้อผิดพลาด (Error & Failure Messages)**

- ❌ **เกิดข้อผิดพลาด!** กรุณาลองใหม่อีกครั้ง  
  **Something went wrong!** Please try again.
- 🚫 **ไม่สามารถดำเนินการได้** คุณไม่มีสิทธิ์การเข้าถึง  
  **Action not permitted.** You do not have the necessary permissions.
- ⚠️ **การเชื่อมต่อล้มเหลว** โปรดตรวจสอบการเชื่อมต่ออินเทอร์เน็ตของคุณ  
  **Connection failed.** Check your internet connection and try again.
- 🔐 **รหัสผ่านไม่ถูกต้อง** กรุณากรอกข้อมูลให้ถูกต้อง  
  **Incorrect password.** Please enter the correct credentials.
- 📧 **อีเมลไม่ถูกต้อง** กรุณาตรวจสอบอีเมลของคุณ  
  **Invalid email.** Please verify your email format.
- ⛔ **บัญชีของคุณถูกระงับ** ติดต่อฝ่ายสนับสนุน  
  **Your account has been suspended.** Contact support for assistance.
- 🛠️ **ระบบเกิดข้อผิดพลาด** โปรดรายงานปัญหานี้ไปยังทีมสนับสนุน  
  **System error.** Please report this issue to our support team.
- 📂 **อัปโหลดไฟล์ล้มเหลว** ตรวจสอบรูปแบบและขนาดไฟล์  
  **File upload failed.** Ensure the file format and size are correct.
- ⏳ **การร้องขอล้มเหลว** เซิร์ฟเวอร์ใช้เวลานานเกินไปในการตอบกลับ  
  **Request timeout.** The server took too long to respond.
- 🔐 **อีเมลยังไม่ได้ยืนยัน** กรุณายืนยันอีเมลเพื่อเข้าถึงฟีเจอร์ทั้งหมด  
  **Unverified email.** Verify your email to access full features.

---

## ⚠️ **ข้อความเตือน (Warning Messages)**

- 🛑 **คุณกำลังจะลบรายการนี้!** การกระทำนี้ไม่สามารถย้อนกลับได้  
  **You are about to delete this item!** This action cannot be undone.
- 🔄 **การเปลี่ยนแปลงจะมีผลหลังจากรีเฟรชหน้า**  
  **Changes will take effect after refreshing the page.**
- ⏳ **เซสชั่นของคุณกำลังจะหมดอายุ** กรุณาบันทึกข้อมูลเพื่อป้องกันการสูญหาย  
  **Your session is about to expire.** Save your work to avoid losing progress.
- 🚧 **อยู่ในโหมดบำรุงรักษา** บางฟีเจอร์อาจไม่สามารถใช้งานได้ชั่วคราว  
  **Maintenance mode.** Some features may be unavailable temporarily.

---

## ℹ️ **ข้อความข้อมูล (Informational Messages)**

- 🔔 **มีการอัปเดตระบบใหม่!** คลิกที่นี่เพื่อดูรายละเอียด  
  **A new system update is available!** Click here for details.
- 📢 **โปรดยืนยันอีเมลเพื่อเปิดใช้งานบัญชีของคุณ**  
  **Please verify your email to activate your account.**
- 🕒 **การบำรุงรักษาระบบในอีก 30 นาที** กรุณาบันทึกข้อมูลของคุณ  
  **System maintenance in 30 minutes.** Save your work now.

---

## 🔄 **ข้อความระหว่างการโหลดและประมวลผล (Loading & Processing Messages)**

- ⏳ **กำลังประมวลผลคำขอของคุณ...** กรุณารอสักครู่  
  **Processing your request...** Please wait.
- 🔄 **กำลังอัปโหลดไฟล์...** กรุณาอย่าปิดหน้านี้  
  **Uploading file...** Please do not close this page.
- 🚀 **กำลังเปิดแอปพลิเคชัน...** ใกล้เสร็จแล้ว  
  **Launching application...** Almost there.

---

## 🚀 **การนำไปใช้งาน (Usage & Implementation)**

- **Push Notifications** – แจ้งเตือนบนอุปกรณ์มือถือ
- **Email Alerts** – แจ้งเตือนทางอีเมล
- **SMS Notifications** – ข้อความแจ้งเตือนผ่านมือถือ

**ตัวอย่าง HTML:**
```html
<div class="alert alert-success" style="background-color: #4CAF50; color: white;">🎉 Your data has been saved successfully!</div>
```

---

## 🛠 **การสนับสนุนและการปรับปรุง (Contribution & Improvement)**

หากคุณต้องการเพิ่มประเภทข้อความแจ้งเตือนหรือปรับปรุงเนื้อหา สามารถส่ง **Pull Requests** ได้ตลอดเวลา!

---

## 📜 **สัญญาอนุญาต (License)**

โครงการนี้อยู่ภายใต้ **MIT License** คุณสามารถนำไปใช้งานได้อย่างอิสระ

