# Final Projects · Capstone I–III

รายการโครงการประกอบรายวิชา Internetworking 2026 ใช้ลิงก์ไปยัง repository ต้นฉบับแทนการคัดลอกโครงการมาไว้ที่นี่

## Capstone I · Network Programmability

แบบจำลอง RESTCONF ด้วย FastAPI พร้อม CLI, Python client และ Pygame GUI ที่เชื่อม backend ร่วมกัน ไม่ใช่ RESTCONF บนเราเตอร์จริง

- [Repository และวิธีใช้งาน](https://github.com/LynxelSins/NetworkProgrammability)
- [Report.pdf](https://github.com/LynxelSins/NetworkProgrammability/blob/main/Report.pdf)
- [เอกสาร Network Programmability](https://github.com/LynxelSins/NetworkProgrammability/blob/main/grp8%20-%20Network%20Programmability.pdf)
- [Architecture](https://github.com/LynxelSins/NetworkProgrammability/blob/main/Architecture.png)
- [Topology Simulation Logic](https://github.com/LynxelSins/NetworkProgrammability/blob/main/TopologySimulationLogic.png)

## Capstone II · NetFlow Monitoring

จำลอง NetFlow ในเครือข่ายองค์กรด้วย Cisco Packet Tracer เพื่อศึกษา Exporter/Collector, traffic ICMP/HTTP/DNS และการแก้ไขปัญหาตาม Runbook

- [Repository และวิธีใช้งาน](https://github.com/poranunb-design/Capstone-project-2)
- [กิจกรรม Packet Tracer](https://github.com/poranunb-design/Capstone-project-2/blob/main/Capstone%20project%202.pka)
- [Lab 23.2.2](https://github.com/poranunb-design/Capstone-project-2/blob/main/Lab%2023.2.2.pdf)
- [Runbook](https://github.com/poranunb-design/Capstone-project-2/blob/main/Runbook.pdf)
- [รายงาน NetFlow](https://github.com/poranunb-design/Capstone-project-2/blob/main/_%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%9B%E0%B8%A3%E0%B8%B1%E0%B8%9A%E0%B9%83%E0%B8%8A%E0%B9%89%20NetFlow%20%E0%B9%83%E0%B8%99%E0%B9%80%E0%B8%84%E0%B8%A3%E0%B8%B7%E0%B8%AD%E0%B8%82%E0%B9%88%E0%B8%B2%E0%B8%A2%E0%B8%AD%E0%B8%87%E0%B8%84%E0%B9%8C%E0%B8%81%E0%B8%A3%E0%B8%88%E0%B8%B3%E0%B8%A5%E0%B8%AD%E0%B8%87.pdf)

README ต้นฉบับระบุว่า Packet Tracer จำลอง NetFlow แบบพื้นฐาน และกรณีภัยคุกคามบางส่วนเป็นการวิเคราะห์เชิงแนวคิด ไม่ใช่ผลการทดสอบจริงทั้งหมด

## Capstone III · Control Plane Policing

ทดลอง CoPP บน Cisco CML ด้วย R1/R2/A1, EIGRP AS 123 และเปรียบเทียบ traffic ที่เข้าตัว R1 กับ traffic จาก R2 ผ่าน R1 ไป A1

- [Repository และวิธีใช้งาน](https://github.com/kojidesu01/Lab-Implement-CoPP)
- [CML topology](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/topology/Lab_26.1.6-Implement_CoPP.yaml)
- [R1 configuration](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/configs/R1-config.txt)
- [R2 configuration](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/configs/R2-config.txt)
- [A1 configuration](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/configs/A1-config.txt)
- [Telnet blocked capture](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/captures/Telnet_Blocked.pcap)
- [Telnet transit capture](https://github.com/kojidesu01/Lab-Implement-CoPP/blob/main/captures/Telnet_pass.pcap)

ดูผลและขอบเขตหลักฐานใน [สรุป CoPP Lab](../README.md#copp-lab) บัญชีทดสอบในโครงการนี้เป็นตัวอย่างสำหรับ isolated lab เท่านั้น

[กลับหน้าหลัก](../README.md)
