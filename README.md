<div align="center">

<img src="https://img.shields.io/badge/AI%20STV-Discord%20Bot-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="AI STV Bot"/>

# 🖥️ AI STV — Windows VM & Bot Hosting trên Discord

### Tạo máy chủ Windows ảo miễn phí · Deploy bot 24/7 · Kết nối RDP chỉ trong 40 giây

[![Join Discord](https://img.shields.io/badge/💬_Tham_Gia_Discord-5865F2?style=for-the-badge)](https://discord.gg/CdcWWEN9Xv)
[![Website](https://img.shields.io/badge/🌐_aistv.pages.dev-0A66C2?style=for-the-badge)](https://aistv.pages.dev)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Status](https://img.shields.io/badge/Status-Online_24%2F7-2ECC71?style=for-the-badge)](https://discord.gg/CdcWWEN9Xv)

</div>

---

## 🤖 AI STV Bot là gì?

**AI STV** là Discord bot chuyên cung cấp **máy chủ Windows ảo (VM) miễn phí** và dịch vụ **Bot Hosting Ubuntu** ngay trên Discord — không cần cài đặt phần mềm, không cần VPS, không cần kiến thức kỹ thuật phức tạp.

Chỉ cần vài lệnh slash trên Discord, bạn có ngay:
- 🖥️ Máy chủ Windows kết nối RDP/Tailscale trong vòng **~40 giây**
- 🐧 Môi trường Ubuntu chạy bot/server **Python, Node.js, Go, Rust, Java** trong **~60 giây**
- 🤖 Trợ lý AI **LLaMA 3.1** hỗ trợ song ngữ Việt – Anh

> 🔗 Tham gia cộng đồng: **[discord.gg/CdcWWEN9Xv](https://discord.gg/CdcWWEN9Xv)**  
> 🌐 Website chính thức: **[aistv.pages.dev](https://aistv.pages.dev)**

---

## 🖥️ Dịch vụ VM Windows — Thông số & Phiên bản

AI STV cung cấp máy chủ Windows ảo chạy trên **GitHub Actions Runner** — hiệu năng cao, ổn định, sẵn sàng ngay lập tức.

### 🏷️ Phiên bản Windows hỗ trợ

| Runner | Phiên bản | Kiến trúc | Ghi chú |
|--------|-----------|-----------|---------|
| `windows-latest` | Windows Server 2025 | x86_64 | Mặc định — khuyến nghị |
| `windows-2025` | Windows Server 2025 | x86_64 | Bản cố định 2025 |
| `windows-2022` | Windows Server 2022 | x86_64 | Bản ổn định LTS |
| `windows-11-arm` | Windows 11 | ARM64 | Kiến trúc ARM |

> 💡 Gói **Basic** chỉ dùng `windows-latest` · Gói **VIP** mở khoá toàn bộ 4 runner

### ⚙️ Thông số kỹ thuật VM

| Thông số | Chi tiết |
|----------|----------|
| 💻 CPU | 2–4 vCPU (GitHub-hosted runner) |
| 🧠 RAM | 7 GB – 16 GB |
| 💾 Ổ cứng | 14 GB – SSD nhanh |
| 🌐 Kết nối | Tailscale VPN (end-to-end encrypted) + RDP |
| 👤 User mặc định | `AISTV` |
| 🔐 Mật khẩu | Sinh ngẫu nhiên 42 ký tự (gửi qua DM) |
| ⏱️ Thời gian khởi động | ~40 giây |
| ⏳ Thời gian chạy tối đa | 15 phút → 6 giờ (9 mức) |
| 🔄 Cooldown giữa 2 lần tạo | 120 giây |

### ⏰ Các mức thời gian chạy

```
15 phút · 30 phút · 45 phút · 60 phút · 90 phút
120 phút · 180 phút · 240 phút · 300 phút · 360 phút (6h)
```

---

## 🐧 Dịch vụ Bot Hosting Ubuntu

Chạy bot của bạn **24/7** trên Ubuntu trực tiếp từ Discord — không cần VPS, không cần terminal phức tạp.

### ✅ Ngôn ngữ hỗ trợ

| Ngôn ngữ | Runtime | Tính năng đặc biệt |
|----------|---------|--------------------|
| 🐍 Python | python3 + pip | Auto-detect `requirements.txt` |
| 🟩 Node.js | Node LTS | Auto-detect `package.json` |
| 🔵 Go | go latest | Build & run tự động |
| 🦀 Rust | rustup + cargo | Compile & run |
| ☕ Java | OpenJDK | Build & run |

### ✅ Ubuntu Runner hỗ trợ

- `ubuntu-latest` (Ubuntu 24.04)
- `ubuntu-24.04`
- `ubuntu-22.04`

### 🔄 Auto-restart

Bot tự động **khởi động lại** nếu crash — giữ uptime tối đa trong suốt phiên chạy.

---

## 💎 Gói Dịch Vụ & Quyền Lợi

### 🖥️ VM Windows

<table>
<thead>
<tr>
<th>Quyền lợi</th>
<th>🆓 Basic</th>
<th>👑 VIP</th>
</tr>
</thead>
<tbody>
<tr><td>VM chạy đồng thời</td><td>3 máy</td><td>✅ 15 máy</td></tr>
<tr><td>Lượt tạo mỗi ngày</td><td>10 lần</td><td>✅ Không giới hạn</td></tr>
<tr><td>Runner Windows</td><td>windows-latest</td><td>✅ Tất cả 4 runner</td></tr>
<tr><td>Thời gian chạy</td><td>15 phút → 6 giờ</td><td>✅ 15 phút → 6 giờ</td></tr>
<tr><td>Cảnh báo hết hạn qua DM</td><td>✅</td><td>✅</td></tr>
<tr><td>Gia hạn 1 nút bấm</td><td>Theo phút</td><td>✅ Theo ngày</td></tr>
<tr><td>Giá</td><td><strong>Miễn phí</strong></td><td>Từ 30.000đ</td></tr>
</tbody>
</table>

### 🐧 Bot Hosting Ubuntu

<table>
<thead>
<tr>
<th>Quyền lợi</th>
<th>🆓 Basic</th>
<th>👑 VIP</th>
</tr>
</thead>
<tbody>
<tr><td>Bot chạy đồng thời</td><td>1 bot</td><td>✅ 5 bot</td></tr>
<tr><td>File upload tối đa</td><td>2 file</td><td>✅ 5 file</td></tr>
<tr><td>Lượt chạy mỗi ngày</td><td>4 lần</td><td>✅ Không giới hạn</td></tr>
<tr><td>Auto-restart khi crash</td><td>✅</td><td>✅</td></tr>
<tr><td>Gia hạn</td><td>Theo giờ</td><td>✅ Theo ngày</td></tr>
<tr><td>Giá</td><td><strong>Miễn phí</strong></td><td>Từ 30.000đ</td></tr>
</tbody>
</table>

### 💰 Bảng Giá VIP

| Gói | ⏳ Thời hạn | 💵 Giá | Áp dụng cho |
|-----|------------|--------|-------------|
| **Gói 1** | 3 ngày | **30.000đ** | VM Windows hoặc Bot Hosting |
| **Gói 2** | 6 ngày | **40.000đ** | VM Windows hoặc Bot Hosting |
| **Gói 3** | 14 ngày | **59.000đ** | VM Windows hoặc Bot Hosting |
| **Gói 4** | 30 ngày | **70.000đ** | VM Windows hoặc Bot Hosting |

> 📩 Liên hệ admin tại **[discord.gg/CdcWWEN9Xv](https://discord.gg/CdcWWEN9Xv)** để nâng cấp VIP

---

## ⚡ Lệnh Discord — Hướng Dẫn Nhanh

### Bước đầu — Chọn ngôn ngữ (bắt buộc)

```
/lang vi    → Tiếng Việt
/lang en    → English
```

### Tạo VM Windows

```
/vm         → Mở panel → nhấn "Create VM"
/status     → Xem trạng thái VM hiện tại
/plan       → Xem so sánh gói + biểu đồ
```

### Deploy Bot Hosting

```
/bot        → Mở panel → nhấn "Host Bot"
```

### Tiện ích & AI

```
/ai [câu hỏi]    → Hỏi trợ lý AI LLaMA 3.1
/prefix [prompt] → Tuỳ chỉnh tính cách AI (chỉ DM)
/id              → Xem Discord ID của bạn
/help            → Hướng dẫn đầy đủ
```

---

## 🔒 Bảo Mật & Cam Kết

- ✅ **Workflow tự xoá** sau khi dispatch — token không lưu trên repo
- ✅ **Kết nối Tailscale** mã hoá end-to-end, không lộ IP thật
- ✅ **Mật khẩu ngẫu nhiên** 42 ký tự, chỉ gửi riêng qua DM
- ✅ **Token/Key được che giấu** hoàn toàn trong log và thông báo lỗi
- ✅ **Cảnh báo hết hạn** tự động 30 · 20 · 10 · 5 · 2 phút trước khi dừng

---

## ❓ Câu Hỏi Thường Gặp

<details>
<summary><strong>VM Windows chạy trên phần cứng gì?</strong></summary>

VM chạy trên **GitHub Actions hosted runner** — cơ sở hạ tầng của Microsoft Azure, đảm bảo hiệu năng cao và ổn định. CPU 2–4 vCPU, RAM 7–16 GB tuỳ runner.

</details>

<details>
<summary><strong>Làm sao kết nối vào VM?</strong></summary>

Bot gửi **IP Tailscale, username (`AISTV`), password** qua DM Discord trong ~40 giây. Bạn dùng **Remote Desktop Connection** (Windows) hoặc **Remmina** (Linux) để kết nối.

</details>

<details>
<summary><strong>VM bị mất dữ liệu khi hết hạn không?</strong></summary>

Có — VM GitHub Actions là **ephemeral** (tạm thời), toàn bộ dữ liệu mất khi phiên kết thúc. Hãy sao lưu dữ liệu trước khi hết giờ.

</details>

<details>
<summary><strong>Bot Hosting có bị giới hạn internet không?</strong></summary>

Không. Bot chạy trên GitHub Actions có đầy đủ quyền truy cập internet, cài được bất kỳ package nào qua `pip`, `npm`, `cargo`...

</details>

<details>
<summary><strong>Tôi cần chuẩn bị gì để dùng?</strong></summary>

- **GitHub Token** (`ghp_...` hoặc `github_pat_...`) — tạo tại [github.com/settings/tokens](https://github.com/settings/tokens)  
- **Tailscale Auth Key** (`tskey-...`) — tạo tại [login.tailscale.com/admin/settings/keys](https://login.tailscale.com/admin/settings/keys) *(chỉ cần cho VM Windows)*  
- Tên repo GitHub (mới hoặc có sẵn)

</details>

---

## 🌐 Cộng Đồng & Hỗ Trợ

<div align="center">

| 💬 Discord | 🌐 Website |
|:---:|:---:|
| [discord.gg/CdcWWEN9Xv](https://discord.gg/CdcWWEN9Xv) | [aistv.pages.dev](https://aistv.pages.dev) |
| Hỗ trợ · Báo lỗi · Cập nhật | Thông tin · Hướng dẫn |

</div>

---

<div align="center">

**AI STV Bot** — *Tạo VM Windows & Deploy Bot chưa bao giờ dễ đến vậy*

Made with ❤️ by **Trọng Phúc** · [aistv.pages.dev](https://aistv.pages.dev)

[![Discord](https://img.shields.io/badge/Discord-CdcWWEN9Xv-5865F2?style=flat-square&logo=discord)](https://discord.gg/CdcWWEN9Xv)
[![Website](https://img.shields.io/badge/Web-aistv.pages.dev-0A66C2?style=flat-square)](https://aistv.pages.dev)

</div>
