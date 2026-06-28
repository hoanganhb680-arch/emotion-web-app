# Do_An_Thi_Giac_May_Tinh

## Giới thiệu

Đồ án này là một ứng dụng nhỏ về nhận diện cảm xúc và thị giác máy tính, bao gồm:
- Xử lý ảnh và phát hiện điểm mốc khuôn mặt (`Face_Landmark_Detection.ipynb`)
- Tiền xử lý dữ liệu (`Preprocess.ipynb`)
- Huấn luyện mô hình baseline (`train_baselines_notebook.ipynb`)
- Ứng dụng web demo nhận diện cảm xúc (`emotion_web_app/`)
- Mã nguồn mô hình (`code mo_hinh/`)

## Mục tiêu

- Nhận diện cảm xúc từ khuôn mặt người.
- Trích xuất landmark khuôn mặt để phân tích biểu cảm.
- Triển khai demo web đơn giản cho việc hiển thị kết quả.

## Cấu trúc thư mục

- `Face_Landmark_Detection.ipynb` - Notebook phát hiện landmark và kiểm tra ảnh.
- `Preprocess.ipynb` - Notebook tiền xử lý dữ liệu ảnh.
- `train_baselines_notebook.ipynb` - Notebook huấn luyện mô hình baseline.
- `emotion_web_app/` - Ứng dụng web front-end/back-end để demo.
- `code mo_hinh/` - Tập hợp mã nguồn mô hình và các script liên quan.

## Hướng dẫn chạy

1. Cài đặt môi trường Python (khuyến nghị Python 3.8+).
2. Cài các thư viện cần thiết như OpenCV, TensorFlow/PyTorch, Flask hoặc Streamlit tùy theo app.
3. Mở các notebook để xem chi tiết từng bước và chạy lần lượt.
4. Nếu dùng web app, vào thư mục `emotion_web_app` và chạy server theo hướng dẫn trong thư mục này.

## Gợi ý cài đặt

```powershell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

> Nếu chưa có `requirements.txt`, bạn có thể tạo file từ các thư viện được sử dụng trong các notebook và app.

## Ghi chú

- Không đẩy dữ liệu lớn hoặc mô hình đã huấn luyện lên repo nếu không cần thiết.
- Nếu cần, bạn có thể thêm `requirements.txt` và tài liệu hướng dẫn chi tiết hơn cho mỗi bước.
