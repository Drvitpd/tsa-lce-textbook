# แอปประจำเล่ม — การสอบบัญชีตามมาตรฐาน TSA for LCE

เว็บสถิต (GitHub Pages) ที่ https://drvitpd.github.io/tsa-lce-textbook/ สร้างจาก `site/build_site.py` + `site/data/chNN.json`

- `index.html` สารบัญ 12 บท และคำอธิบายการใช้คู่กับเล่ม
- `chNN.html` หน้าต่อบท 5–6 แท็บ: แบบทดสอบ (เฉลย+เหตุผล, อัตนัย) · ประเมินตนเองตาม LO (บันทึกใน localStorage) · อภิธานศัพท์ · กรณีศึกษาเพิ่มเติม (เปิดแนวตอบ) · กระดาษทำการ (+ .docx) · ทบทวนวรรณกรรม (บท 1, 5, 6) — เปิดแท็บตรงด้วย `#quiz #self #gloss #cases #forms #lit`
- `glossary.html` อภิธานศัพท์ทั้งเล่ม · `forms/LCE-x-xx.docx` กระดาษทำการ (TH Sarabun New 14pt) · `qr/chNN.png` รหัส QR ที่พิมพ์ในเล่ม

ที่อยู่ `chNN.html` ต้องคงเดิมเสมอ เพราะ QR ในเล่มชี้ไว้แล้ว · ไม่ใช้ไลบรารีภายนอกนอกจาก Google Fonts (Sarabun)
สร้างใหม่: `cd site && python3 build_site.py` (ต้องมี node และแพ็กเกจ docx ใน `../book/node_modules`)
