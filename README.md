# Neo-Chess: 8x8 RFID Matrix & ESP32-S3 System

This project is a glimpse into the future of Chess. It implements a 64-channel, multiplexed NFC matrix to keep track of the game. Using ESP32 at its heart, it uses web sockets to send moves to a Django-based website in real time, where the move is validated by python-chess library and played on a virtual chessboard while Stockfish analyses and predicts the game. In doing so, this project effectively bridges the gap between physical play and digital intelligence.

## 🛠️ Technical Specifications
* **🧠 Microcontroller:** ESP32-S3
* **📡 NFC Reader:** PN532
* **🟩 PCB Design:**
  * **♟️ Chessboard PCB:** 4-layer Multiplexed RF design; all 160+ SMD components bottom-mounted to leave the top layer exclusively for the 64-antenna matrix.
  * **🎮 Microcontroller PCB:** ESP32-S3 development board handling Django/WebSocket connectivity and system power management.

## 📜 Licensing
This project is licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**. 

* **🎓 Educational Use:** Encouraged
* **💰 Commercial Use:** Prohibited without explicit permission from the author
