<!DOCTYPE html>
<html>
<head>
    <title>Đơn cam kết</title>
    <meta charset="UTF-8">
    <style>
        body {
            font-family: "Times New Roman", serif;
            line-height: 1.5;
            display: flex; /* Bật flexbox cho body */
            justify-content: center; /* Căn giữa theo chiều ngang */
            align-items: center; /* Căn giữa theo chiều dọc */
            min-height: 100vh; /* Đảm bảo căn giữa ngay cả khi nội dung ngắn */
            margin: 0; /* Loại bỏ margin mặc định của body */
            background-color: #f0f0f0; /* Màu nền nhạt cho trang */
        }

        .thong-bao {
            background-color: white;
            border: 1px solid #ccc;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1);
            width: 50%; /* Hoặc một giá trị cố định như 600px để tránh bị kéo giãn quá mức */
            max-width: 800px; /* Giới hạn chiều rộng tối đa */
        }

        .header {
            text-align: center;
            margin-bottom: 20px;
        }

        .content {
            margin-left: 50px;
            margin-right: 50px;
        }

        .signature {
            text-align: right;
            margin-top: 50px;
            margin-right: 50px;
        }

        .signature-name {
            margin-top: 30px;
        }

        .indented {
            margin-left: 30px;
        }
    </style>
</head>
<body>
    <div class="thong-bao">
        <div class="header">
            <p>Cộng Hoà Xã Hội Chủ Nghĩa Việt Nam </p>
            <p>Độc lập - Tự do - Hạnh Phúc</p>
            <h2>ĐƠN CAM KẾT</h2>
        </div>

        <div class="content">
            <p>Tôi: Hoàng Văn Giang</p>
            <p>Ngày tháng năm: 22/07/2006</p>
            <p>Lí do: Ghi đơn này hứa tôi sẽ mãi yêu bé: Phạm Tuyết Mai</p>
            <p>Ngày tháng năm: 12/04/2007</p>
            <p>Tôi xin thề sẽ ko làm em thất vọng</p>
            <p class="indented">[Yêu Em😘]</p>
        </div>

        <div class="signature">
            <p>Người Viết Đơn</p>
            <p class="signature-name">Anh iu❤️</p>
        </div>
    </div>
</body>
</html>
