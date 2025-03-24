Dự án Công nghệ thông tin

** Các thư file source.zip
source.zip
|-Source
|   |-emotion_of_ai.ipynb
|   `-requirements.txt
|-models
|   |-emotion_bart_model.zip
|   `-no_emotion_bart_model.zip
|-tensorboard_logs
|   |-emotion_bart_log.zip
|   `-no_emotion_bart_log.zip
`-readme.txt

Để tiết kiệm dung lượng, các thư mục models, tensorboard_logs được lưu trong các link ở file external_links.txt
Cấu trúc file source.zip khi nộp
source.zip
|-Source
| |-emotion_of_ai.ipynb
| `-requirements.txt
|-external_links.txt
`-readme.txt


** Chạy các cell trong file emotion_of_ai.ipynb
- Môi trường: Google Colab hoặc máy local (python)
- Nếu train lại từ đầu, thì chạy từ trên xuống dưới
- Nếu chỉ muốn test, thì thực hiện các bước:
    + Bước 1: tải và copy các file zip trong thư mục models, tensorboard_logs đưa vào thư mục Source (cùng cấp với file emotion_of_ai.ipynb)
    + Bước 2: chạy các cell thuộc các mục:
        * Cell đầu tiên (cài đặt thư viện)
        * Giải nén mô hình và log trong trường hợp đã lưu về theo dạng zip
        * So sánh mô hình có cảm xúc và không cảm xúc với các mẫu dữ liệu