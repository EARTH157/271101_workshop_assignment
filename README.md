# 271101_workshop_assignment-650610830-จิรภัทร  เชื้อเมืองพาน
เริ่มต้นโดยการนำ import library cv2,mediapipe เข้ามาเพื่อใช้งานการเปิดกล้องให้ cv2 ตรวจจับการเคลื่อนไหวของมือเรา ส่วน mediapipe ให้เป็นตัวประมวลผลมือของเราว่าเป็นมือไหนบ้างโดยให้เวกเตอร์ที่คำนวณในแต่ละจุดฝ่ามือของนิ้วมาประมวลผล#แล้วเอามาเทียบเงื่อนไขแต่ละตัวที่ตั้งไว้ แล้วประมวลผลออกมาผ่านกล้อง เป็นออกมาแต่ละนิ้ว

# ข้อจำกัดของโปรแกรมนี้
ตัวจับเซนเซอร์เพี้ยนเวลาอยู่ไกลหรือกล้องเบลอหรือไม่ชัด
