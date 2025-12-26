## 📁 Cấu trúc thư mục

S26-65TTNT_DM_Nhom4_PhanLoaiBenhLaLua/
│
├── data/
│   ├── train_images/        # Ảnh huấn luyện
│   ├── test_images/         # Ảnh kiểm tra
│   └── train.csv            # Nhãn các ảnh huấn luyện
│
├── notebooks/
│   ├── 00_EDA.ipynb         # Khám phá dữ liệu (EDA)
│   ├── 01_Preprocessing.ipynb  # Tiền xử lý & tăng cường dữ liệu
│   ├── 02_CNN_Custom_v1.ipynb  # CNN tự xây – baseline
│   └── 03_CNN_Custom_v2.ipynb  # CNN tự xây – cải tiến
│
├── models/
│   └── cnn_person1_best.keras  # Mô hình CNN đã huấn luyện tốt nhất
│
├── paddy_models/            # Các mô hình thử nghiệm khác
│
├── requirements.txt         # Danh sách thư viện cần cài đặt
├── sample_submission.csv    # File mẫu nộp kết quả
├── README.md                # Mô tả dự án
└── .jovianrc                # Cấu hình môi trường Jovian

