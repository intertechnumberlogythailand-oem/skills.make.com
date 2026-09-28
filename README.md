# skills.make.com

รีโพซิทอรีนี้เป็นจุดเริ่มต้นสำหรับการรวบรวมและพัฒนาทรัพยากรที่เกี่ยวข้องกับ [Make Skills](https://skills.make.com/#install)

## เริ่มต้นอย่างรวดเร็ว

1. โคลนรีโพซิทอรีและสร้างสาขาสำหรับงานของคุณ
2. อ่าน [คู่มือเริ่มต้นสำหรับผู้ร่วมมือ](CONTRIBUTING.md) เพื่อดูการตั้งค่า โครงสร้างโครงการ ไฟล์สำคัญ และขั้นตอนเปิด Pull Request
3. ตรวจสอบ `git diff --check` ก่อน commit ทุกครั้ง

```bash
git clone https://github.com/intertechnumberlogythailand-oem/skills.make.com.git
cd skills.make.com
git switch -c docs/คำอธิบายงาน
```

## โครงสร้างปัจจุบัน

```text
skills.make.com/
├── .github/
│   ├── PULL_REQUEST_TEMPLATE.md       # แบบฟอร์ม Pull Request
│   └── ISSUE_TEMPLATE/                # แบบฟอร์ม Issue
│       ├── bug_report.md
│       └── feature_request.md
├── .gitignore       # รูปแบบไฟล์ที่ไม่ควร commit
├── CONTRIBUTING.md  # คู่มือสำหรับผู้ร่วมมือ
├── LICENSE          # MIT License
└── README.md        # ภาพรวมและจุดเริ่มต้น
```

โครงการยังอยู่ในระยะเริ่มต้น จึงยังไม่มีคำสั่งติดตั้ง, build หรือ test เพิ่มเติมนอกเหนือจากที่อธิบายไว้ในเอกสาร ผู้ร่วมมือควรตรวจสอบ README และ `CONTRIBUTING.md` ทุกครั้งก่อนเริ่มงาน

เมื่อเปิด Issue หรือ Pull Request บน GitHub ให้เลือกเทมเพลตที่ตรงกับงาน กรณีพบข้อผิดพลาดให้ใช้แบบฟอร์มรายงานข้อผิดพลาด และกรณีเสนอความสามารถหรือการปรับปรุงให้ใช้แบบฟอร์มข้อเสนอฟีเจอร์

## ลิขสิทธิ์

เผยแพร่ภายใต้ [MIT License](LICENSE)
