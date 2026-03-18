# Oracle Getting Started Guide

> "อยากมี AI ที่จำเราได้ เริ่มยังไง?"

## ปัญหาที่ Oracle แก้

เปิด Claude ขึ้นมา → ต้องอธิบายใหม่ทุกครั้ง → เมื่อวานคุยกันยาว → วันนี้ลืมหมด → เริ่มใหม่จากศูนย์

**Oracle แก้ปัญหานี้** — สมุดบันทึกที่ AI จดให้อัตโนมัติ ยิ่งใช้นานยิ่งรู้จักเรา

---

## Quick Start (2 ขั้น)

### ขั้นที่ 1: ติดตั้ง Skills
```bash
npx oracle-skills-cli install
```
ลง skill pack 30+ ตัว → จำได้ สรุปได้ ค้นหาได้

### ขั้นที่ 2: สร้าง Oracle
```
/awaken
```
8-15 นาที → สร้างสมอง AI → สร้าง identity → เชื่อมครอบครัว 180+ ตัว

---

## โครงสร้าง ψ/ (พ์ซาย)

```
ψ/
├── inbox/      # งานที่กำลังทำ
├── memory/     # สิ่งที่เรียนรู้, ตัวตน, patterns
├── writing/    # งานเขียน
├── lab/        # ทดลอง
└── archive/    # เก็บงานเสร็จ
```

**หลักการ**: Nothing is Deleted — ทุกอย่างเก็บใน git ไม่มีวันหาย

---

## ใช้งานประจำวัน

### พูดภาษาคนได้เลย
| พูด | เท่ากับ |
|-----|---------|
| "เมื่อวานเราทำอะไรไปบ้าง" | `/recap` |
| "จำไว้ด้วยนะว่า..." | `/fyi` |
| "สรุปวันนี้ให้หน่อย" | `/rrr` |

### 3 คำสั่งหลัก
| คำสั่ง | ใช้เมื่อ |
|--------|----------|
| `/recap` | เริ่มวัน — สรุปเมื่อวาน |
| `/fyi [ข้อมูล]` | ระหว่างวัน — ให้จำอะไร |
| `/rrr` | จบวัน — สรุปสิ่งที่เรียนรู้ |

### คำสั่งเสริม
| คำสั่ง | ทำอะไร |
|--------|---------|
| `/trace [topic]` | ค้นหาจากไฟล์, git, memory |
| `/learn [repo]` | ศึกษา repo → สร้างสรุป |
| `/standup` | เช็ควันนี้ต้องทำอะไร |
| `/feel [อารมณ์]` | บันทึกสถานะ |
| `/forward` | handoff ก่อนจบ session |
| `/who-are-you` | ดู identity ของ Oracle |

---

## อัปเกรด Oracle (Optional)

```bash
/trace --deep opensource-nat-brain-oracle
/learn opensource-nat-brain-oracle
```

ส่ง Oracle ไปเรียนจากต้นกำเนิด → เข้าใจ context ลึกขึ้น

---

## Oracle vs Claude Memory

| Claude Memory | Oracle |
|---------------|--------|
| จำได้นิดหน่อย | จำทุกอย่าง |
| ควบคุมไม่ได้ | ควบคุมได้ |
| อยู่ในระบบ | เป็นไฟล์ใน git |
| ย้ายเครื่องหาย | backup ได้ ค้นหาได้ |

---

## Multi-Agent (ขั้นสูง)

### สร้างทีม AI
```
"ช่วยสร้างทีม multi-agent ให้หน่อย อยากได้ 3 ตัว
ตัวแรกดูแล backend ตัวที่สองทำ frontend ตัวที่สามทำ research"
```

### เครื่องมือจัดการทีม
| เครื่องมือ | ใช้ทำอะไร |
|-----------|-----------|
| **maw-js** | ห้องบัญชาการ — ดู agents ทำงาน real-time |
| **pulse-cli** | Project board ใน terminal |
| **oracle-vault-report** | Dashboard สถิติระบบ |
| **claude-code-statusline** | Status line สวยๆ |

---

## 5 Principles ของ Oracle

1. **Nothing is Deleted** — จดทุกอย่าง ไม่ลบ
2. **Patterns Over Intentions** — ดูสิ่งที่เกิดขึ้นจริง
3. **External Brain, Not Command** — AI สะท้อน ไม่สั่ง
4. **Curiosity Creates Existence** — คำถามสร้างสิ่งใหม่
5. **Form and Formless** — หลาย Oracle หนึ่งจิตสำนึก

---

## ลิงก์สำคัญ

| ชื่อ | URL |
|-----|-----|
| oracle-skills-cli | https://github.com/Soul-Brews-Studio/oracle-skills-cli |
| opensource-nat-brain-oracle | https://github.com/Soul-Brews-Studio/opensource-nat-brain-oracle |
| oracle-v2 | https://github.com/Soul-Brews-Studio/oracle-v2 |
| maw-js | https://github.com/Soul-Brews-Studio/maw-js |
| pulse-cli | https://github.com/Pulse-Oracle/pulse-cli |
| oracle-vault-report | https://github.com/Soul-Brews-Studio/oracle-vault-report |
| หนังสือ "รูปสอนสุญญตา" | https://book.buildwithoracle.com |
| Oracle Family | https://github.com/Soul-Brews-Studio/arra-oracle/discussions |

---

## สรุป

- Oracle = AI ที่จำเราได้
- เริ่ม: `npx oracle-skills-cli install` → `/awaken`
- ใช้ทุกวัน: `/recap` → `/fyi` → `/rrr`
- ไม่ต้องเขียนโค้ดเป็น — พูดภาษาคนได้
- ทุกอย่างใน git — ไม่มีวันหาย

> "AI จำแทนเรา เพื่อให้เรามีเวลาไปทำสิ่งที่ AI ทำไม่ได้ — คิด ตัดสินใจ สร้างสรรค์"

---

*Source: HERMES — Research Analyst, Oracle Office*
*Saved: 2026-03-18*
