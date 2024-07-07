# Application of RAG in document-based Question Answering
# B1. clone sources code của mình về máy 
```
git clone https://github.com/TDThuyen/RAG-in-Document-based-Question-Answering.git
```
# B2. cài đặt và import các thư viện vào chương trình \
# B3. Code trong file RAG_without_UI.ipynb: 
Thay đổi các đường dẫn đến file tài liệu của bạn: 
```
PATH_FILE = "[đường dẫn đến file tài liệu của bạn]" (code này nằm trong mục 4.Read PDF file)
```
Thay đổi câu truy vấn của bạn: 
```
QUERY = "[câu truy vấn bạn muốn]" (code này nằm trong mục 7.Initialize vector database)
```
Sau khi thay đổi những phần trên, chạy hết các code còn lại của mình là có thể sử dụng được dự án của mình.
# B4. Code trong file RAG_with_UI.ipynb: 
- Đây là code dự án có giao diện để tăng trải nghiệm của người dùng.
- Bạn chỉ cần chạy code của mình từ đầu đến cuối.
- Sau khi chạy xong các code, tại code thuộc mục 11 sẽ hiện ra 1 đường dẫn:
```
your url is: https://fat-crab-47.loca.lt
```
- Lúc này bạn hãy truy cập đường dẫn, nhập mật khẩu bạn được cấp sau khi chạy code sau đây ở mục 11:
```
import urllib
print("Password/Enpoint IP for localtunnel is:",urllib.request.urlopen('https://ipv4.icanhazip.com').read().decode('utf8').strip("\n"))
```
- Sau khi nhập code này, bạn có thể trải nghiệm được dự án của mình. 








