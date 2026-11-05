HAY DAY FOOD MANAGER - ANDROID PROJECT

Đây là mã nguồn Android Studio đóng gói website HTML hiện tại thành ứng dụng Android WebView.

CÁCH TẠO APK:
1. Cài Android Studio bản mới.
2. Chọn Open và mở thư mục HayDayFoodManager.
3. Chờ Gradle Sync hoàn tất.
4. Chọn Build > Build Bundle(s) / APK(s) > Build APK(s).
5. APK debug được tạo tại:
   app/build/outputs/apk/debug/app-debug.apk

LƯU Ý:
- Ứng dụng mở giao diện HTML trong WebView.
- JavaScript và DOM Storage được bật để hỗ trợ chức năng website và localStorage.
- Thư viện SheetJS hiện được tải từ CDN jsDelivr, vì vậy chức năng Excel cần internet.
- Dữ liệu lưu cục bộ trong vùng dữ liệu của ứng dụng; gỡ cài đặt app có thể xóa dữ liệu.
- Đây là project để build APK, chưa phải file APK đã biên dịch/ký phát hành.
