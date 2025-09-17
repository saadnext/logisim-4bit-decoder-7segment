# 4-Bit Binary to Decimal (0–9) Decoder with 7-Segment Display  
*A Logisim Evolution Project*

## 📖 Description
This project is a **Logisim Evolution circuit** that takes a **4-bit binary input** (values 0000 → 1001, i.e., decimal 0 → 9) and decodes it to drive a **7-segment display**.  
The circuit ignores inputs above 9 (1010 → 1111).

It’s useful for learning about **decoders, combinational logic, and display systems**.

---

## ⚡ Features
- 4-bit binary input (`D C B A`).
- Decoder logic for digits **0–9**.
- Output connected to a **7-segment display**.
- Clear, minimal design built in **Logisim Evolution**.

---

## 🔢 Truth Table (0–9)

| Decimal | Binary (D C B A) | Segments (a b c d e f g) |
|---------|------------------|--------------------------|
| 0       | 0000             | 1111110                  |
| 1       | 0001             | 0110000                  |
| 2       | 0010             | 1101101                  |
| 3       | 0011             | 1111001                  |
| 4       | 0100             | 0110011                  |
| 5       | 0101             | 1011011                  |
| 6       | 0110             | 1011111                  |
| 7       | 0111             | 1110000                  |
| 8       | 1000             | 1111111                  |
| 9       | 1001             | 1111011                  |

(1 = ON, 0 = OFF)

---

## 🖼 Screenshot  
![screnshot](https://github.com/user-attachments/assets/b2af552f-e350-4b60-a7dc-d9d7c4a3c06f)

---

## 🚀 How to Use
1. Install **[Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution)**.
2. Open the file `7SegmentDecoder.circ`.
3. Provide a 4-bit input (switches or binary pins).
4. Observe the output on the 7-segment display.

---

## 📂 Files
- `7segmentdecoder.circ` → Main Logisim project file.
- `README.md` → Documentation.
- `screenshot.png` → Example circuit image.

---

## ✨ Future Improvements
- Add support for hexadecimal digits (A–F).
- Extend to multiple digits using multiplexing.

---

## 👨‍💻 Author
Project created by **Saad Rabia** 🎓
