# Check Your Name 👤

Ứng dụng web tra cứu cách đọc tên Việt theo âm Hán tự và dịch sang tiếng Trung, Hàn, Nhật.

##  Tính năng

- ✅ Nhập tên tiếng Việt có dấu
- ✅ Dịch sang Pinyin (Trung Quốc)
- ✅ Dịch sang Romanized (Hàn Quốc)
- ✅ Dịch sang Romaji (Nhật Bản)
- ✅ Giải thích nguồn gốc Hán tự

##  Cài đặt

### Chạy trên trình duyệt (Development)

```bash
# Clone repo
git clone https://github.com/Khang-ayart/Check-Your-Name.git
cd Check-Your-Name

# Cài đặt dependencies
npm install

# Tạo thư mục www và copy index.html vào
mkdir www
cp index.html www/

# Chạy server
npm start
```

Truy cập: `http://localhost:8080`

### Build Android APK

#### Cách 1: GitHub Actions (Khuyến nghị)

1. Push code lên GitHub
2. Vào tab **Actions**
3. Chọn **Build Android APK** → **Run workflow**
4. Đợi build xong và tải APK từ **Artifacts**

#### Cách 2: Build local (cần Android Studio)

```bash
# Sync Capacitor
npm run android:sync

# Mở Android Studio
npm run android:open

# Trong Android Studio:
# Build → Build Bundle(s) / APK(s) → Build APK(s)
```

## 📁 Cấu trúc dự án
