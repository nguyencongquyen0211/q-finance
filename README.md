# Q · Quản lý Tài chính Cá nhân

> Dashboard quản lý danh mục đầu tư cá nhân theo Investment Policy Statement (IPS) - Chứng khoán Việt Nam & Crypto.

🌐 **Live:** [q.giaoducstem.com](https://q.giaoducstem.com)

---

## ✨ Tính năng

- 📊 **Dashboard trực quan** - Tổng giá trị, P&L, phân bổ tài sản, tiến độ mục tiêu
- 💼 **Quản lý giao dịch** - Mua/bán chứng khoán & crypto
- 🔄 **Auto-update giá BTC/ETH** - Real-time qua CoinGecko API
- 📅 **Lịch DCA 12 tháng** - Asymmetric DCA theo 3 kịch bản thị trường
- 🔔 **Cảnh báo thông minh** - Săn đáy / chốt lời / rebalance
- 📋 **Investment Policy Statement** - Tuyên ngôn đầu tư cá nhân
- 💾 **Backup/Restore** - Xuất/nhập dữ liệu JSON
- 🌙 **Dark theme** chuyên nghiệp

## 🛠️ Stack

- **Frontend:** Pure HTML + CSS + Vanilla JS (no framework)
- **Charts:** Chart.js
- **Storage:** localStorage (browser-side)
- **Crypto API:** CoinGecko (free tier)
- **Hosting:** Cloudflare Pages (auto-deploy from GitHub)

## 🚀 Deploy

Đây là static site - chỉ có 1 file `index.html`. Có thể deploy lên:
- Cloudflare Pages (đang dùng) ⭐
- Netlify
- Vercel
- GitHub Pages
- Hoặc upload qua FTP lên bất kỳ shared hosting

## 🔒 Bảo mật & Dữ liệu

- ✅ Dữ liệu lưu cục bộ trên trình duyệt (localStorage)
- ✅ KHÔNG gửi lên server nào
- ✅ KHÔNG ai khác xem được
- ⚠️ Khuyến nghị backup JSON định kỳ (tab Cài đặt)

## 📄 License

Personal use only. Not financial advice.

---

**Made with ☕ for the disciplined investor.**
