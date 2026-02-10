# Neo-Chess: 8x8 RFID Matrix & ESP32-S3 System

This project is a glimpse into the future of Chess. It implements a 64-channel, multiplexed NFC matrix to keep track of the game. Using ESP32 at its heart, it uses web sockets to send moves to a Django-based website in real time, where the move is validated by python-chess library and played on a virtual chessboard while Stockfish analyses and predicts the game. In doing so, this project effectively bridges the gap between physical play and digital intelligence.

## 🛠 Technical Specifications
* **Controller:** ESP32-S3
* **Reader:** PN532
* **Sensor Array:** 8x8 Matrix (64 individual RFID antennas)
* **PCB Design:** 4-Layer stackup optimized for 13.56 MHz RF signal integrity
* **Unique Layout:** **All 500+ components are on the bottom layer** to provide a perfectly flush sensor surface on top
* **Schematics:** Detailed multi-sheet design including multiplexing logic for high-speed scanning

## 📜 Licensing
This project is licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**. 

* **Educational Use:** Encouraged.
* **Commercial Use:** Prohibited without explicit permission from the author.
