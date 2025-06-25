# Crawling_Data_Tiki
Crawling 200.000 sản phẩm của tiki
dự án được push trên branch master
Project 2: thực hiện crawling data tiki 200.000 sản phẩm, và chuẩn hóa lại data trường description về đúng định dạng text.

Sử dụng request để crawl data tiki.
Sử dụng tqdm để hiển thị tiến trình crawl.
Sử dụng pandas để đọc file_id.csv từng sản phẩm của tiki.
Sử dụng ThreadPoolExecutor để có thể thu thập dữ liệu đa luông thay vì dùng for duyệt từng data.
Viết thêm hàm chunks sử dụng package math, ceil để thực hiện chia file, hay nói cách khác là lặp vòng loop theo từng đợt.
Ghi các kết quả ra file json.
Tổng hợp file lỗi và file đúng rồi tính tổng có bao nhiêu % data đúng => có 99.4% data sạch trong project này.
