# 🚀 Typecho (Custom Fork)

Đây là phiên bản tùy chỉnh của [Typecho](https://github.com/typecho/typecho) – một nền tảng blog nhẹ và linh hoạt, được phát triển bằng PHP. Dự án này được fork và điều chỉnh nhằm phù hợp hơn với nhu cầu cá nhân/cộng đồng mà tôi hướng đến.

> Typecho is a free, open-source, and elegant blogging platform developed in PHP.  
> This repository is a customized version to better serve specific requirements.

---

## 🔧 Những thay đổi chính

- Tùy chỉnh giao diện quản trị (*admin UI*) cho trực quan hơn.
- Hỗ trợ tốt hơn với PHP phiên bản mới.
- Cải thiện hiệu năng khi xử lý bài viết có nội dung lớn.
- Fix một số lỗi nhỏ chưa được merge trong repo gốc.
- Thêm plugin/tính năng tùy chỉnh (tuỳ vào bạn, có thể liệt kê cụ thể hơn).

---

## 📦 Cài đặt

### Yêu cầu hệ thống

- PHP >= 7.4 (hoặc phiên bản bạn hỗ trợ)
- MySQL >= 5.7
- Web Server: Apache / Nginx

### Hướng dẫn cài đặt

```bash
git clone https://github.com/cuzinxyz/typecho-custom.git
cd typecho
cp config.inc.php.example config.inc.php
# Chỉnh sửa config.inc.php phù hợp
