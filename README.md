# Networking 2026 · Network & Network Security Portfolio

แฟ้มสะสมงานรายวิชา **Internetworking 2026** รวบรวม Lab ด้าน Routing, Switching และ Wireless พร้อม Final Project ทั้ง 3 ส่วน: Network Programmability, NetFlow Monitoring และ Control Plane Policing (CoPP)

| ผู้จัดทำ | รหัสนักศึกษา | Section |
| --- | --- | --- |
| นาย ธีรเมธ สายคำ | 673380273-9 | 1 |

## สารบัญ

- [Portfolio Overview](#portfolio-overview)
- [Coursework Labs](#coursework-labs)
- [Final Projects](#final-projects)
- [CoPP Lab](#copp-lab)
- [Lab Usage](#lab-usage)
- [Certificates](#certificates)
- [Repository Structure](#repository-structure)
- [Lab Credentials](#lab-credentials)

## Portfolio Overview

| หมวด | เนื้อหา | เปิดดู |
| --- | --- | --- |
| Coursework Labs | Lab 1–14: PDF 14 ไฟล์ และกิจกรรม Packet Tracer 9 ไฟล์ | [PDF](LAB/PDF/) · [Packet Tracer](LAB/Pka/) |
| Final Projects | Capstone I–III เก็บใน repository ของแต่ละโครงการ | [รายการ Final Project](pre_capstone_list/README.md) |
| Certificates | พื้นที่สำหรับใบ Certificate จาก Cisco Networking Academy (NetAcad) | [certificate](certificate/) — ยังไม่มีใบ Certificate แนบ |

## Coursework Labs

ลิงก์ตรงกับไฟล์ที่มีอยู่จริงใน repo; **—** หมายถึงยังไม่มีไฟล์กิจกรรม `.pka` ของ Lab นั้นใน repo

| Lab | หัวข้อ | เอกสาร | Packet Tracer |
| --- | --- | --- | --- |
| 1 | Introduction to Networks | [PDF](LAB/PDF/Lab1%20-%20ITN%207.pdf) | — |
| 2 | Basic Router Configuration | [PDF](LAB/PDF/Lab2%20-%20basic%20config%20router.pdf) | [PKA](LAB/Pka/Lab2%20basic_configuration_router.pka) |
| 3 | VLAN Configuration | [PDF](LAB/PDF/Lab3%20-%20VLAN%20Configuration.pdf) | [PKA](LAB/Pka/Lab3%20.3.12%20Packet%20Tracer%20-%20VLAN%20Configuration.pka) |
| 4 | STP Loop Prevention | [PDF](LAB/PDF/Lab4%20-%20Investigate%20STP%20Loop%20Prevention.pdf) | — |
| 5 | Configure a Wireless Network | [PDF](LAB/PDF/LAB5%20-%20Configure_WirelessNetwork.pdf) | [PKA](LAB/Pka/Lab5%2013.1.10%20Packet%20Tracer%20-%20Configure%20a%20Wireless%20Network.pka) |
| 6 | WLAN Configuration | [PDF](LAB/PDF/Lab6%20-%20WLAN_Configuration.pdf) | — |
| 7 | Wireless Technology Exploration | [PDF](LAB/PDF/Lab7%20-%20Wireless_Technology_Exploration.pdf) | — |
| 8 | Basic Router Configuration Review | [PDF](LAB/PDF/Lab8%20-%20Basic_Router.pdf) | [PKA](LAB/Pka/lab8%2014.3.5%20Packet%20Tracer%20-%20Basic%20Router%20Configuration%20Review%20%281%29.pka) |
| 9 | IPv4/IPv6 Static and Default Routes | [PDF](LAB/PDF/Lab9%20-%20Static%20and%20Default%20Routes.pdf) | [PKA](LAB/Pka/lab%209%2015.6.1%20Packet%20Tracer%20-%20Configure%20IPv4%20and%20IPv6%20Static%20and%20Default%20Routes%20%281%29.pka) |
| 10 | Single-Area OSPFv2 | [PDF](LAB/PDF/Lab10%20-%20OSPFv2.pdf) | [PKA](LAB/Pka/Lab10%20-%20Modify%20Single-Area%20OSPFv2.pka) |
| 11 | Propagate a Default Route in OSPFv2 | [PDF](LAB/PDF/Lab11%20-%20Propagate%20a%20Default%20Route%20in%20OSPFv2.pdf) | — |
| 12 | Verify Single-Area OSPFv2 | [PDF](LAB/PDF/Lab12%20-%20Packet%20Tracer%20-%20Verify%20Single-Area%20OSPFv2%20-%20ILM.pdf) | [PKA](LAB/Pka/Lab12%202.6.6%20Packet%20Tracer%20-%20Verify%20Single-Area%20OSPFv2.pka) |
| 13 | Single-Area OSPFv2 Configuration | [PDF](LAB/PDF/Lab13%20-%202.7.1%20Packet%20Tracer%20-%20Single-Area%20OSPFv2%20Configuration%20-%20ILM.pdf) | [PKA](LAB/Pka/Lab13%202.7.1%20Packet%20Tracer%20-%20Single-Area%20OSPFv2%20Configuration.pka) |
| 14 | WAN Concepts | [PDF](LAB/PDF/Lab14%20-%20%207.6.1%20Packet%20Tracer%20-%20WAN%20Concepts%20-%20ILM.pdf) | [PKA](LAB/Pka/Lab14%207.6.1%20Packet%20Tracer%20-%20WAN%20Concepts.pka) |

## Final Projects

ใช้ลิงก์ไปยัง repository ต้นฉบับเพื่อเปิดเอกสารและไฟล์ของแต่ละโครงการ โดยไม่คัดลอกทั้งโครงการมาไว้ใน repo นี้

| ส่วน | โครงการ | เนื้อหาและเครื่องมือ |
| --- | --- | --- |
| Capstone I | [Network Programmability](https://github.com/LynxelSins/NetworkProgrammability) | Mock RESTCONF ด้วย FastAPI, CLI และ Python client ที่ใช้ backend ร่วมกัน พร้อม Pygame GUI; เป็นแบบจำลอง ไม่ใช่ RESTCONF บนเราเตอร์จริง |
| Capstone II | [NetFlow Monitoring](https://github.com/poranunb-design/Capstone-project-2) | จำลอง NetFlow Exporter/Collector และ traffic ICMP, HTTP, DNS ใน Cisco Packet Tracer พร้อม Runbook |
| Capstone III | [Lab Implement CoPP](https://github.com/kojidesu01/Lab-Implement-CoPP) | Cisco CML, EIGRP และ MQC เพื่อควบคุม traffic ที่เข้าสู่ Control Plane ของ R1 |

ดู [รายการไฟล์สำคัญของทั้ง 3 โครงการ](pre_capstone_list/README.md) สำหรับรายงาน, Runbook, topology และ configuration

## CoPP Lab

### วัตถุประสงค์และสภาพแวดล้อม

Capstone III ทดลอง **Control Plane Policing (CoPP)** บน **Cisco Modeling Labs (CML)** ผ่าน Cisco DevNet Sandbox เพื่อศึกษาการควบคุม traffic ที่เข้าตัวเราเตอร์ และเปรียบเทียบกับ traffic ที่ส่งผ่านไปยังอุปกรณ์ปลายทาง

| อุปกรณ์ | บทบาท | Interface / IP address |
| --- | --- | --- |
| R1 | เราเตอร์ที่ใช้ CoPP; node แบบ CSR1000v | Gi1: `10.10.1.1/24` ไป A1; Gi2: `172.16.12.1/30` ไป R2 |
| R2 | ต้นทางทดสอบ; node แบบ IOL | Ethernet0/0: `172.16.12.2/30` |
| A1 | สวิตช์ปลายทาง; node แบบ IOL-L2 | Vlan1: `10.10.1.4/24`; default gateway `10.10.1.1` |

```text
R2                         R1                              A1
172.16.12.2/30 -- 172.16.12.1/30 | 10.10.1.1/24 -- 10.10.1.4/24
       E0/0          Gi2              Gi1             E0/0 (VLAN 1)

Telnet เข้าตัว R1:  R2 --> R1
Telnet ผ่าน R1:     R2 --> R1 --> A1
```

R1 และ R2 ตั้งค่า **EIGRP AS 123** บนเครือข่าย `172.16.12.0/30`; R1 ประกาศเครือข่าย `10.10.1.0/24` ด้วย ส่วน A1 ใช้ default gateway และปิด IP routing รายละเอียดตรวจได้จาก [CML topology](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/topology/Lab_26.1.6-Implement_CoPP.yaml), [R1 config](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/configs/R1-config.txt), [R2 config](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/configs/R2-config.txt) และ [A1 config](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/configs/A1-config.txt)

### CoPP policy บน R1

ไฟล์ R1 config ใช้ ACL → class-map → policy-map `PM-COPP` และผูกนโยบายเข้ากับ Control Plane ขาเข้า:

```text
control-plane
 service-policy input PM-COPP
```

| Class | Traffic ที่จับคู่ | Police rate ใน config | Conform / Exceed |
| --- | --- | --- | --- |
| `CM-TELNET` | TCP destination port 23 | 8,000 bps | drop / drop |
| `CM-EIGRP` | EIGRP | 10 pps | transmit / transmit |
| `CM-SSH` | TCP destination port 22 | 50,000 bps | transmit / transmit |
| `CM-ICMP` | ICMP | 10 pps | transmit / drop |
| `CM-CATCH-ALL` | IP traffic ที่ไม่เข้า class ก่อนหน้า | 50,000 bps | transmit / drop |
| `class-default` | Traffic ที่ไม่เข้า class ที่กำหนด | 12,000 bps | transmit / transmit |

Telnet ถูก drop ทั้งกรณี conform และ exceed ส่วน EIGRP/SSH ตั้งให้ transmit ทั้งสองกรณี จึงไม่ควรตีความค่า police ของสองคลาสนี้ว่าเป็นขีดจำกัดที่ทำให้แพ็กเก็ตส่วนเกินถูก drop

### ผลการทดสอบและขอบเขตหลักฐาน

| กรณี | ผลที่บันทึกหรือรายงาน | หลักฐานและข้อจำกัด |
| --- | --- | --- |
| R2 → R1: Telnet `172.16.12.1:23` | **Blocked** | [Telnet_Blocked.pcap](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/captures/Telnet_Blocked.pcap); README โครงการระบุว่าพบ SYN แต่ไม่มี SYN-ACK สอดคล้องกับ policy ที่ drop |
| SSH เข้าถึง R1 | **Allowed** ตามผลที่เจ้าของโครงการรายงาน | Config อนุญาต SSH แต่ยังไม่มีผล CLI/SSH capture ใน repo สำหรับยืนยัน session |
| ICMP | **ตอบกลับ 14/20 ครั้ง (70%)** ตามผลที่เจ้าของโครงการรายงาน | Config จำกัด ICMP ที่ 10 pps แต่ยังไม่มีผล CLI/counters ของรอบนี้; ไม่สรุปว่าทั้ง 6 ครั้งที่ไม่ตอบกลับเกิดจาก CoPP |
| R2 → R1 → A1: Telnet `10.10.1.4:23` | **ผ่านได้** ในระดับ TCP session และการแลกเปลี่ยนข้อมูล Telnet | [Telnet_pass.pcap](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/captures/Telnet_pass.pcap); เป็น transit traffic ผ่าน R1 ไป A1 ไม่ใช่ Telnet เข้าตัว R1 |

ผล Telnet ในตารางอ้างอิงคำอธิบาย PCAP ใน [README ของ CoPP Lab](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/README.md) ไม่ได้ใช้ยืนยันการล็อกอินสำเร็จหรือการเปลี่ยน policy บนปลายทางเดียวกัน การปรับ README นี้ไม่ได้รันการทดลองใหม่ และค่า ICMP 14/20 ไม่ใช่ผลที่รับประกันในการรันซ้ำ

## Lab Usage

### เปิด Coursework Lab

```bash
git clone https://github.com/kojidesu01/Networking_2026.git
cd Networking_2026
```

เลือก PDF จาก [Coursework Labs](#coursework-labs) แล้วเปิดไฟล์ `.pka` ที่มีคู่กันด้วย Cisco Packet Tracer เพื่อทำตามกิจกรรม

### เปิด CoPP Lab ใน Cisco CML

1. ดาวน์โหลด [topology YAML](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/topology/Lab_26.1.6-Implement_CoPP.yaml) จาก repo Capstone III
2. เตรียม node/image ที่รองรับ CSR1000v, IOL และ IOL-L2 ใน CML แล้วนำเข้า topology ซึ่งมี configuration ฝังอยู่ จากนั้นเริ่ม R1, R2 และ A1
3. ตรวจ interface, EIGRP neighbors และ routing ก่อนทดสอบ
4. ตรวจ policy บน R1 และบันทึก counters ก่อน/หลังแต่ละกรณี ใช้คำสั่งที่ image/version รองรับ
5. ทดสอบจาก R2 โดยแยกปลายทาง R1 และ A1 ให้ชัดเจน แล้วเปรียบเทียบกับหลักฐานเดิม

คำสั่งตรวจสอบ:

```text
show ip interface brief
show ip eigrp neighbors
show ip route
show access-lists
show policy-map control-plane
```

ตัวอย่างคำสั่งทดสอบจาก R2:

```text
telnet 172.16.12.1
ssh -l admin 172.16.12.1
ping 172.16.12.1 repeat 20
telnet 10.10.1.4
```

สำหรับ ICMP ให้บันทึกขนาดแพ็กเก็ตและช่วงเวลาส่งด้วย เพราะคำสั่งตัวอย่างไม่ได้ระบุเงื่อนไขครบเท่ารอบที่รายงาน 14/20 หาก SSH ใช้ไม่ได้หลังนำเข้า ให้ตรวจบัญชี, VTY และ SSH key บน instance ของ Lab นั้นก่อนสรุปว่า CoPP บล็อก

แนวคิด CoPP และการอ่าน counters อ้างอิง [Cisco: Control Plane Policing Implementation Best Practices](https://www.cisco.com/c/en/us/about/security-center/copp-best-practices.html)

## Certificates

โฟลเดอร์ [certificate](certificate/) เตรียมไว้สำหรับใบ Certificate จาก **Cisco Networking Academy (NetAcad)** ปัจจุบันยังไม่มีใบ Certificate แนบ จึงยังไม่ระบุชื่อหลักสูตรหรือสถานะการรับรอง

## Repository Structure

```text
Networking_2026/
├── README.md
├── LAB/
│   ├── PDF/                  # เอกสาร Lab 14 ไฟล์
│   └── Pka/                  # กิจกรรม Packet Tracer 9 ไฟล์
├── pre_capstone_list/
│   └── README.md             # ลิงก์ Final Project ทั้ง 3 ส่วน
└── certificate/
    └── README.md             # พื้นที่สำหรับใบ Certificate จาก NetAcad
```

## Lab Credentials

บัญชี `admin` และรหัสผ่านตัวอย่างใน repo CoPP เป็น **lab-only credentials สำหรับ isolated lab เท่านั้น** ไม่ใช้ซ้ำในระบบจริง README นี้ไม่คัดลอกรหัสผ่าน, password hash หรือ private key จาก configuration

ก่อนนำ configuration หรือ packet capture มาเผยแพร่เพิ่มเติม ให้ลบข้อมูลลับออก โดยเฉพาะข้อมูล login ที่อาจปรากฏใน Telnet traffic
