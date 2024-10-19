****** Hướng dẫn cách cài đặt và chạy phần mềm. *******
Đầu tiên, tải xuống tệp estate-list.zip trên Github: https://github.com/DangVanVu-ctdl/estate-list

Thứ hai, giải nén tệp zip vào vị trí bạn chọn
Thứ ba, mở folder bạn vừa giải nén nhấp chuột phải và chọn Mở trong Terminal
Thứ tư, nhập lệnh: "pip install -r requirements.txt" để cài đặt các thư viện mà dự án cần 

Cuối cùng, sau khi mã trước đó hoàn tất, hãy mở "engine.py" và nhấn "run" để khởi chạy ứng dụng.

****** CÁCH CHẠY "Mô hình dự đoán giá bất động sản với NLP và FastAPI" ******

Bước 1: Mở tệp python "engine.py" trước, sau đó nhấn "run"

Bước 2: Mô hình sẽ yêu cầu bạn lựa chọn: 
        Enter 1: huấn luyện mô hình 
        Enter 2: dùng ứng dụng FastAPI 

Bước 3: Sẽ xuất hiện đường link URL:  http://127.0.0.1:8000 để bạn truy cập. Click, sau đó thêm đuôi "/docs" vào đường link để mở ra giao diện người dùng

Bước 4: Chọn mục "POST/ predict Predict Price" >> chọn Try it out 

Bước 5: Bây giờ bạn có thể chọn những đặc tính mà bạn muốn. (Ví dụ: "PropertyType": 1,"ClubHouse": 0,...)

Bước 6: Nhấn "Execute". Lúc này mô hình sẽ dự đoán giá bất động sản dựa vào những đặc tính bạn chọn ban đầu.
        Bạn có thể thay đổi các đặc tính và tiếp tục ấn "Execute" 