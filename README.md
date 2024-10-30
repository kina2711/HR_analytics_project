# Dự Án Phân Tích Nhân Sự

Đây là một dự án cá nhân nhằm rèn luyện kỹ năng phân tích dữ liệu thông qua việc phân tích một tập dữ liệu giả lập về tình hình nghỉ việc và tuyển dụng nhân sự trong một tổ chức. Dự án bao gồm các bước thu thập dữ liệu, làm sạch, phân tích và trực quan hóa bằng Python và Power BI để rút ra các xu hướng và hiểu biết trong dữ liệu nhân sự.
# Mục Lục

    Tổng Quan Dự Án
    Mục Tiêu
    Thu Thập Dữ Liệu
    Quy Trình Phân Tích
    Công Nghệ Sử Dụng
    Kết Quả
    Định Hướng Phát Triển
    Hướng Dẫn Bắt Đầu

# Tổng Quan Dự Án

Tỷ lệ nghỉ việc cao có thể ảnh hưởng lớn đến năng suất và doanh thu của tổ chức. Dự án này tập trung vào phân tích các yếu tố sau:

- Tỷ lệ nghỉ việc theo vị trí và phòng ban
- Các lý do nghỉ việc
- Xu hướng nhu cầu tuyển dụng theo vị trí và phòng ban

Dự án mô phỏng một tình huống phân tích nhân sự thực tế, với mục tiêu rút ra những hiểu biết để hỗ trợ quá trình ra quyết định của bộ phận nhân sự.
# Mục Tiêu

- Thực hành thu thập dữ liệu qua web scraping để xây dựng tập dữ liệu.
- Làm sạch và chuẩn bị dữ liệu để phân tích chi tiết.
- Sử dụng SQL và Python để truy vấn và phân tích dữ liệu.
- Tạo báo cáo tương tác trong Power BI để trực quan hóa các xu hướng nghỉ việc.

# Thu Thập Dữ Liệu

Dữ liệu được thu thập bằng cách sử dụng các thư viện BeautifulSoup và requests của Python. Quy trình này bao gồm việc crawl các nguồn trực tuyến để tạo ra tập dữ liệu mô phỏng của một công ty, bao gồm:

- Thông tin nhân sự (chức vụ, phòng ban, khu vực làm việc)
- Thống kê nghỉ việc và tuyển dụng hàng tháng
- Các lý do nghỉ việc của nhân viên

# Quy Trình Phân Tích

- Làm sạch dữ liệu: Đảm bảo tính nhất quán và loại bỏ các giá trị không hợp lệ bằng Pandas.
- Phân tích dữ liệu: Sử dụng SQL để truy vấn sơ bộ và các thư viện Python như Pandas, NumPy để xử lý và phân tích các xu hướng.
- Trực quan hóa: Tạo báo cáo trên Power BI với các tính năng Drill-through và Tooltip động để dễ dàng khám phá các xu hướng nghỉ việc theo thời gian, vị trí và lý do nghỉ.

# Công Nghệ Sử Dụng

- Python: Dùng để crawl dữ liệu và tiền xử lý (BeautifulSoup, Pandas, NumPy).
- SQL: Dùng để truy vấn và phân tích sơ bộ.
- Power BI: Dùng để tạo báo cáo trực quan và tương tác (với các tính năng như Drill-through, Tooltip động).

# Kết Quả

**Phân tích cho thấy**:

- Tỷ lệ nghỉ việc cao tại các vị trí và phòng ban cụ thể.
- Thời gian nghỉ việc tập trung đầu năm.
- Các lý do nghỉ việc phổ biến liên quan đến lương thưởng và cơ hội thăng tiến. Các hiểu biết này giúp đề xuất các chính sách cải tiến nhằm giảm tỷ lệ nghỉ việc và tăng sự hài lòng của nhân viên.

**Định Hướng Phát Triển**:

- Bổ sung dữ liệu: Kết hợp thêm các nguồn dữ liệu như điểm hài lòng của nhân viên hoặc chỉ số hiệu suất.
- Phân tích nâng cao: Sử dụng mô hình dự báo để xác định nhân viên có nguy cơ nghỉ việc cao.
- Tự động hóa: Cải tiến quy trình thu thập dữ liệu để cập nhật báo cáo theo thời gian thực.

Dự án này mang lại trải nghiệm thực hành quý báu trong việc thu thập, phân tích và trực quan hóa dữ liệu, mô phỏng một tình huống phân tích nhân sự thực tế.
