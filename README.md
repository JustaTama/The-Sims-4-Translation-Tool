<div align="center">
  <img src="https://raw.githubusercontent.com/JustaTama/The-Sims-4-Translation-Tool/1126746cc03b688849d540061078e3cdc8ca994f/assets/banner.png" width="500"
</div>

#  TS4 Translation Tool

[![Version](https://img.shields.io/badge/Version-1.0-blue.svg?style=for-the-badge&logo=appveyor)](https://github.com/JustaTama/The-Sims-4-Translation-Tool)
[![Status](https://img.shields.io/badge/Status-Stable-green.svg?style=for-the-badge)](https://github.com/JustaTama/The-Sims-4-Translation-Tool)
[![The Sims 4](https://img.shields.io/badge/The_Sims_4-Modding-green.svg?style=for-the-badge&logo=thesims)](https://www.ea.com/games/the-sims/the-sims-4)

---

[🇻🇳 Tiếng Việt](#-tiếng-việt) | [🇺🇸 English](#-english) | [🛠️ Technical](#-technical-details) | [🤝 Support](#-support--contact)

</div>

---

## 🇻🇳 TIẾNG VIỆT

### 🚀 Giới thiệu
**TS4 Translation Tool** là một trình biên tập XML/JSON mạnh mẽ, được thiết kế chuyên dụng cho việc dịch thuật các bản Mod của The Sims 4. Với giao diện hiện đại, tối ưu hiệu suất và các tính năng bảo vệ cấu trúc tệp, đây là công cụ không thể thiếu cho các dịch giả Simmer chuyên nghiệp.

### ✨ Tính năng nổi bật
- ⚡ **Siêu tốc độ:** Hỗ trợ kéo và thả (Drag & Drop) tệp tin cực kỳ mượt mà, phản hồi ngay lập tức.
- 🔒 **Khóa dòng 1:1:** Đảm bảo cấu trúc file luôn chính xác 100%, ngăn chặn hoàn toàn việc lệch dòng hoặc mất dữ liệu khi xuất.
- 🔍 **Tìm kiếm thông minh:** Highlight chính xác từ khóa đang chọn, hỗ trợ điều hướng xoay vòng (wrap-around) liên tục.
- 🌓 **Chế độ Sáng/Tối:** Giao diện Dark Mode mặc định cực đẹp và Light Mode tinh tế, giúp bảo vệ mắt khi làm việc lâu.
- 🎨 **Cá nhân hóa tối đa:** Tùy chỉnh Font chữ (JetBrains Mono, Nunito, Lexend), kích thước chữ và khoảng cách dòng.
- ⌨️ **Hệ thống phím tắt:** Tối ưu hóa quy trình làm việc với bộ phím tắt chuyên nghiệp (Ctrl+S, Ctrl+F, Alt+R, ...).

### 🛠️ Quy trình hoạt động (Workflow)
<details>
<summary><b>Bấm để xem chi tiết từng bước</b></summary>

1.  **Trích xuất:** Sử dụng các công cụ như TS4 Translator hoặc STBL Editor để chuyển đổi file `.package` sang định dạng `.xml` (DEST/TSD) hoặc `.json`.
2.  **Nạp tệp:** Kéo và thả file trực tiếp vào trình duyệt hoặc nhấn nút **🚀 BẮT ĐẦU** tại màn hình chào mừng.
3.  **Dịch thuật:** Tiến hành dịch các chuỗi văn bản trong Editor.
    > [!IMPORTANT]
    > **LƯU Ý QUAN TRỌNG:** Luôn giữ nguyên các biến trong ngoặc nhọn `{variable}` và ký tự xuống dòng `↵` để đảm bảo file hoạt động chính xác trong Game.
4.  **Xuất bản:** Nhấn **Export** để nhận file đã dịch, sau đó đóng gói ngược lại vào file `.package` ban đầu.
</details>

### ⌨️ Phím tắt chuyên nghiệp
| Phím tắt | Chức năng |
| :--- | :--- |
| `Ctrl + F` | Mở/Đóng thanh tìm kiếm (Tự động Focus) |
| `Enter` / `F3` | Tìm kết quả kế tiếp |
| `Shift + F3` | Tìm kết quả phía trước |
| `Alt + R` | Khôi phục nội dung gốc của dòng đang chọn |
| `Alt + D` | Làm rỗng dòng hiện tại (Clear line) |
| `Ctrl + S` | Xuất file nhanh (Quick Export) |

---

## 🇺🇸 ENGLISH

### 🚀 Overview
**TS4 Translation Tool** is a high-performance XML/JSON editor specifically engineered for translating The Sims 4 Mods. Featuring a modern "Sims-inspired" UI, structural integrity protection, and an optimized workflow, it provides the ultimate workspace for Simmer translators.

### ✨ Key Features
- ⚡ **High Performance:** Lightning-fast Drag & Drop support for seamless file loading and processing.
- 🔒 **1:1 Line Locking:** Guarantees 100% structural accuracy, preventing any accidental line shifts during the export process.
- 🔍 **Smart Navigation:** Precise keyword highlighting with intelligent wrap-around search capabilities.
- 🌓 **Dual Themes:** Beautifully crafted Dark and Light modes, optimized for long-term productivity.
- 🎨 **Rich Customization:** Fully adjustable typography featuring premium fonts (JetBrains Mono, Nunito, Lexend) and layout scales.
- ⌨️ **Pro Shortcuts:** Boost your efficiency with a comprehensive set of productivity hotkeys.

### 🛠️ Workflow
<details>
<summary><b>Click to expand step-by-step guide</b></summary>

1.  **Extract:** Convert your `.package` files to `.xml` (DEST/TSD) or `.json` using standard extraction tools.
2.  **Load:** Simply drag & drop your file into the workspace or click **🚀 START** from the home screen.
3.  **Translate:** Edit the text strings within the professional CodeMirror editor.
    > [!IMPORTANT]
    > **CRITICAL:** Do not modify `{variable}` tags or the `↵` newline indicator to prevent in-game script errors.
4.  **Export:** Click **Export** to save your work, then repackage it into your mod's `.package` container.
</details>

### ⌨️ Productivity Shortcuts
| Shortcut | Action |
| :--- | :--- |
| `Ctrl + F` | Toggle Search Bar (Auto-focus) |
| `Enter` / `F3` | Find Next Match |
| `Shift + F3` | Find Previous Match |
| `Alt + R` | Restore current line to original state |
| `Alt + D` | Clear current line content |
| `Ctrl + S` | Instant Export |

---

## ⚙️ Technical Details

<div align="center">

| Component | Technology |
| :--- | :--- |
| **Core Engine** | HTML5 / Vanilla JavaScript |
| **Editor Base** | CodeMirror 5.65.15 |
| **Styling** | Custom CSS3 + Variables (Modern UI) |
| **Typography** | Google Fonts (Lexend, Nunito, JetBrains Mono) |
| **Architecture** | Single-file Client-side App (No Server required) |

</div>

---

## 🤝 Support & Contact
- **Project Author:** [JustaTama](https://github.com/JustaTama)
- **Personal:** [mtama1204](https://guns.lol/mtama1204)
- **Repository:** [TS4-Translation-Tool](https://github.com/JustaTama/The-Sims-4-Translation-Tool)

---

<div align="center">
  <p>Made with ❤️ for The Sims 4 Community</p>
  <img src="https://static.wikia.nocookie.net/sims/images/5/54/Simspirations_Plumbob.gif/revision/latest/scale-to-width-down/1000?cb=20250213153708" width="50" alt="Plumbob">
</div>
