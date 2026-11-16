HA NOI BUS OFFICE - DU AN ANDROID

Du an nay dong goi file Java Kotlin goc vao Android WebView:
- Chay offline, khong can ket noi Internet cho giao dien/du lieu co san.
- Bat JavaScript va DOM Storage de cac chuc nang va localStorage hoat dong.
- Ten ung dung: Ha Noi Bus Office
- applicationId: vn.hanoibus.office
- Android toi thieu: Android 6.0 (API 23)

CACH TAO APK
1. Cai Android Studio tren may tinh.
2. Mo Android Studio > Open, chon thu muc HaNoiBusOffice (thu muc chua settings.gradle).
3. Cho Gradle dong bo va cai Android SDK Platform 35 neu duoc yeu cau.
4. Chon Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK debug thuong nam tai:
   app/build/outputs/apk/debug/app-debug.apk
6. Chuyen APK sang dien thoai Android, mo file va cho phep cai ung dung tu nguon nay neu Android hoi.

LUU Y
- Day la bo ma nguon Android Studio, chua phai file APK da bien dich.
- Moi truong tao file hien tai khong co Android SDK/Gradle, nen khong the bien dich APK tai day.
- File HTML goc duoc giu trong app/src/main/assets/index.html.
- Du lieu yeu thich/cai dat luu trong WebView localStorage tren thiet bi.

BAN QUYEN
-Du an ma nguon mo cho phep chinh sua va sap chep ,Nhung hay ghi cong tac gia
-Nha phat hanh : VMN STUDIOS 95
-Nguoi lap trinh : VU MINH NGOC