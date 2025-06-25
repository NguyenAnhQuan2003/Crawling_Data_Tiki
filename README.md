# Crawling_Data_Tiki
Crawling 200.000 sản phẩm của tiki
Dự án được push trên branch master
Project 2: thực hiện crawling data tiki 200.000 sản phẩm, và chuẩn hóa lại data trường description về đúng định dạng text.

sử dụng request để crawl data tiki.
sử dụng tqdm để hiển thị tiến trình crawl.
sử dụng pandas để đọc file_id.csv từng sản phẩm của tiki.
sử dụng ThreadPoolExecutor để có thể thu thập dữ liệu đa luông thay vì dùng for duyệt từng data.
viết thêm hàm chunks sử dụng package math, ceil để thực hiện chia file, hay nói cách khác là lặp vòng loop theo từng đợt.
ghi các kết quả ra file json.
tổng hợp file lỗi và file đúng rồi tính tổng có bao nhiêu % data đúng => có 99.4% data sạch trong project này.
