 <!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Góc học tập của Thanh Tuyết - 12a2</title>
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; }
        body { background-color: #f4f6fa; color: #1e293b; padding-bottom: 80px; }
        .hero { background: linear-gradient(135deg, #2563eb, #1d4ed8); color: white; padding: 24px 20px; border-bottom-left-radius: 24px; border-bottom-right-radius: 24px; }
        .hero-top { display: flex; justify-content: space-between; align-items: center; margin-bottom: 16px; font-size: 13px; opacity: 0.9; }
        .hero h1 { font-size: 22px; margin-bottom: 6px; }
        .hero p { font-size: 14px; opacity: 0.9; }
        .container { padding: 16px; max-width: 600px; margin: 0 auto; }
        .card { background: white; border-radius: 16px; padding: 18px; margin-bottom: 14px; box-shadow: 0 2px 8px rgba(0,0,0,0.04); }
        .card h3 { font-size: 17px; margin-bottom: 6px; color: #0f172a; }
        .card p { font-size: 13px; color: #64748b; margin-bottom: 14px; line-height: 1.4; }
        .btn { display: inline-block; background-color: #2563eb; color: white; padding: 10px 18px; border-radius: 10px; text-decoration: none; font-size: 13px; font-weight: 500; }
        .section-title { font-size: 18px; font-weight: 600; margin: 20px 0 12px 4px; color: #0f172a; }
        .footer { text-align: center; font-size: 12px; color: #94a3b8; margin-top: 24px; }
        /* Thanh menu dưới đáy */
        .bottom-nav { position: fixed; bottom: 0; left: 0; width: 100%; background: white; display: flex; justify-content: space-around; padding: 10px 0; border-top: 1px solid #e2e8f0; box-shadow: 0 -2px 6px rgba(0,0,0,0.02); }
        .nav-item { text-decoration: none; color: #64748b; font-size: 11px; text-align: center; display: flex; flex-direction: column; align-items: center; gap: 4px; }
        .nav-item.active { color: #2563eb; font-weight: 500; }
        .nav-item span { font-size: 18px; }
    </style>
</head>
<body>

    <div class="hero">
        <div class="hero-top">
            <span>✨ MY STUDY SPACE</span>
            <span>Thanh Tuyết - 12a2</span>
        </div>
        <h1>Góc học tập của mình</h1>
        <p>Học từng chút mỗi ngày, tiến bộ từng bước một.</p>
    </div>

    <div class="container">
        <div class="card">
            <h3>👋 Chào mừng bạn đến với góc học tập!</h3>
            <p>Mọi tài liệu, bài luyện tập và ghi chú đều được sắp xếp tại đây. Chúc bạn học tập thật hiệu quả 💙</p>
        </div>

        <div class="section-title">Hôm nay bạn muốn học gì?</div>

        <div class="card">
            <h3>📚 Tài liệu học tập</h3>
            <p>Tập hợp tài liệu, lý thuyết theo từng môn học lớp 12.</p>
            <a href="#" class="btn">Mở tài liệu</a>
        </div>

        <div class="card">
            <h3>📝 Trắc nghiệm</h3>
            <p>Luyện tập câu hỏi ôn thi và xem điểm số ngay.</p>
            <a href="#" class="btn">Làm bài</a>
        </div>

        <div class="card">
            <h3>💡 Công thức cần nhớ</h3>
            <p>Ôn nhanh kiến thức trọng tâm Hóa, Lý, Toán.</p>
            <a href="#" class="btn">Xem công thức</a>
        </div>

        <div class="card">
            <h3>📅 Thời khóa biểu & Ghi chú</h3>
            <p>Theo dõi lịch học trong tuần và lưu lại những điều quan trọng.</p>
            <a href="#" class="btn">Xem chi tiết</a>
        </div>

        <div class="footer">
            MY STUDY SPACE • Made for learning 💙
        </div>
    </div>

    <div class="bottom-nav">
        <a href="#" class="nav-item active"><span>🏠</span>Trang chủ</a>
        <a href="#" class="nav-item"><span>📚</span>Tài liệu</a>
        <a href="#" class="nav-item"><span>📝</span>Trắc nghiệm</a>
        <a href="#" class="nav-item"><span>📅</span>Lịch học</a>
        <a href="#" class="nav-item"><span>✍️</span>Ghi chú</a>
    </div>

</body>
</html>
