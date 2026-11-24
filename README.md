# OwO – build APK
## Cách 1: GitHub (không cần cài gì)
1. Tạo repo mới trên github.com, tải toàn bộ thư mục này lên (kể cả thư mục .github).
2. Vào tab Actions -> "Build OwO APK" -> chạy (Run workflow). Đợi ~5 phút.
3. Mở lần chạy xong -> mục Artifacts -> tải "OwO-apk" -> giải nén ra app-debug.apk -> gửi cho người khác cài.
## Cách 2: Máy tính có Node 20 + Java 17 + Android Studio
npm install && npx cap add android && npx @capacitor/assets generate --android && npx cap sync android
npx cap open android   (Build > Build APK)
