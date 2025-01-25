```markdown
# a_compressed - เครื่องมือสำหรับการโจมตีเครือข่าย

เครื่องมือนี้ถูกออกแบบมาเพื่อใช้ในการทดสอบเครือข่ายโดยการส่งแพ็กเก็ตข้อมูลไปยังเป้าหมายที่กำหนด

## วิธีการติดตั้ง


## ให้สิทธิ์การ execute ไฟล์ (สำคัญ)

```bash
chmod +x a_compressed
```

## วิธีการใช้งาน

```bash
sudo ./a_compressed <target_ip> <target_port> <method> <threads>
```

### ตัวอย่างการใช้งาน

```bash
sudo ./a_compressed 127.0.0.1 100 udp 5
```

### คำเตือน

- **threads**: ไม่แนะนำให้ตั้งค่าสูงเกินไปหากคุณใช้คลาวด์หรือพีซีที่ประสิทธิภาพไม่สูง แนะนำให้ตั้งค่าไม่เกิน 10

## คำถามที่พบบ่อย

### a: จะหา IP ของเซิร์ฟเวอร์เกมได้จากที่ไหน?
คุณสามารถหา IP ของเซิร์ฟเวอร์เกมได้จากข้อมูลที่ให้โดยผู้ให้บริการเกม หรือใช้เครื่องมือวิเคราะห์เครือข่ายเพื่อค้นหา

### b: จะดักจับ IP ได้อย่างไร?
คุณสามารถใช้แอพพลิเคชันเช่น **pcapdroid** บน Android เพื่อดักจับและวิเคราะห์แพ็กเก็ตข้อมูลบนเครือข่ายของคุณ

---

**หมายเหตุ**: โปรดใช้เครื่องมือนี้อย่างมีจริยธรรมและตามกฎหมายที่เกี่ยวข้อง
```
