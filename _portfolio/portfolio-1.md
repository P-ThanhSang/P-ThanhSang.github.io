---
title: "Arduino LM35 Temperature Monitor"
excerpt: "He thong giam sat nhiet do 3 kenh LM35 voi Arduino UNO, xuat JSON qua Serial, hien thi do thi tren PC"
collection: portfolio
---

## Mo ta
Du an doc nhiet do tu **3 cam bien LM35** (kenh A0, A1, A2) qua Arduino UNO, gui du lieu dinh dang **JSON** qua Serial, hien thi do thi thoi gian thuc tren PC bang ung dung **C# WinForms** voi thu vien ZedGraph.

## Tinh nang chinh
- Doc dong thoi 3 kenh nhiet do LM35
- Chuyen doi ADC sang nhiet do (°C)
- Xuat du lieu JSON: `{"T1":25,"T2":30,"T3":28}`
- Hien thi do thi real-time tren PC
- Mo phong mach tren Proteus

## Cong nghe su dung
- **Firmware:** Arduino C++ (analogRead, sprintf, Serial)
- **Ung dung PC:** C# WinForms + ZedGraph
- **Mo phong:** Proteus
- **Quan ly phien ban:** Git/GitHub (branch, merge, PR, conflict resolution)

## Ket qua hoc duoc
- Quan ly du an bang Git: tao branch, merge PR, xu ly conflict
- Lam viec nhom bang GitHub: collaborator, code review
- Viet README.md chuyen nghiep
- Su dung git log, git blame de truy vet lich su

## Link
[Xem tren GitHub](https://github.com/P-ThanhSang/Arduino_LM35_TempMonitor)
