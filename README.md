# 📄 Sample Documents — Smart PO & Invoice Auditor

คลังไฟล์เอกสาร PDF จำลองระดับองค์กร สำหรับใช้เป็นชุดข้อมูลทดสอบ (Test Dataset) ในโจทย์ **Smart PO & Invoice Auditor (Vibe Coding Assignment)**

ประกอบด้วยเอกสารทดสอบ **8 ชุดสถานการณ์ (Case 1 ถึง Case 8) รวมทั้งหมด 16 ไฟล์** โดยแต่ละชุดสถานการณ์จะมีเอกสาร 2 ฉบับที่ต้องนำมาเปรียบเทียบกัน:
1. **Invoice PDF (บิลเรียกเก็บเงินของคู่ค้า):** เอกสารที่คู่ค้ายื่นขอเบิกเงิน ระบุยอดเงิน, เลข Tax ID, ธนาคาร, และรายการย่อย
2. **Contract / Certificate PDF (สัญญาแนบท้ายและใบตรวจรับงาน):** เอกสารทางการระบุเงื่อนไขสัญญา, กำหนดส่งมอบ, แคปงวดงาน, และผล QC ของคลังสินค้า

---

## 🚀 วิธีการนำไฟล์ไปใช้งาน (How to Use)

### วิธีที่ 1: Clone โฟลเดอร์นี้เข้าโปรเจกต์โดยตรง (แนะนำ)
รันคำสั่งนี้ที่ Root Directory ของโปรเจกต์ที่คุณกำลังพัฒนา:

```bash
git clone https://github.com/rhiomu/Sample-Document-for-PO_vibe_coding_assignment.git sample_documents
