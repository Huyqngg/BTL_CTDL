📦 Warehouse Management System (WMS) - 倉庫管理システム
📝 Giới thiệu (概要)
Dự án Hệ thống quản lý kho hàng là bài tập lớn cho môn Cấu trúc dữ liệu và giải thuật tại Đại học Bách Khoa Hà Nội. Hệ thống sử dụng ngôn ngữ C++ và cấu trúc dữ liệu danh sách liên kết để quản lý hàng hóa và các giao dịch nhập/xuất kho một cách hiệu quả.

ハノイ工科大学の「データ構造とアルゴリズム」の課題として開発された倉庫管理システムです。C++と連結リストを使用して、効率的な在庫管理を実現しました 。

🛠 Công nghệ sử dụng (技術スタック)

Ngôn ngữ (言語): C/C++.

Cấu trúc dữ liệu (データ構造): Danh sách liên kết đơn (Singly Linked List).

Lưu trữ (ストレージ): Xử lý tệp văn bản (.txt) để lưu trữ dữ liệu bền vững.

🚀 Tính năng chính (主な機能)
Quản lý hàng hóa: Thêm, sửa, xóa và tìm kiếm sản phẩm với mã ID tự động sinh (SP001, SP002...).

Quản lý giao dịch: Tạo phiếu nhập (IMPORT) và xuất (EXPORT), tự động cập nhật số lượng tồn kho và kiểm tra điều kiện xuất hàng.

Thống kê & Báo cáo: Cảnh báo hàng sắp hết (SL < 10), thống kê theo nhà cung cấp và xuất báo cáo ra tệp thongke.txt, soluong.txt.

👥 Nhóm thực hiện và Vai trò (チームの役割)
Dự án được thực hiện bởi nhóm 4 thành viên với sự phân công rõ ràng:

Vũ Việt Anh: Tổng quan hệ thống, thiết kế Menu và cấu trúc dữ liệu.

Đỗ Thanh Bình: Thống kê dữ liệu và xử lý đọc/ghi tệp.

Vũ Trí Dũng: Quản lý nghiệp vụ phiếu nhập và xuất kho.

Nguyễn Quốc Huy (Me): Quản lý thông tin hàng hóa.

Thiết kế và triển khai các thuật toán Sửa, Xóa thông tin hàng hóa.

Phát triển hệ thống Tìm kiếm đa tiêu chí (ID, tên, nhà cung cấp, khoảng giá/số lượng).

私の役割: 主に「商品管理モジュール」を担当しました。商品の編集・削除機能、および多条件検索アルゴリズムの実装を行い、データの整合性を保証しました。
