🏥 Medicalchat vn nlp

Dự án này là một notebook huấn luyện và đánh giá chatbot y tế tiếng việt, sử dụng transformer và gpt.

📘 nội dung notebook
🗂️ Chuẩn bị dữ liệu hội thoại y tế
✂️ Tiền xử lý và mã hóa bằng byte pair encoding
🧱 Xây dựng mô hình transformer encoder–decoder từ đầu
🤖 Thử nghiệm với mô hình gpt (scratch + pre-trained)
📊 Huấn luyện, suy luận và đánh giá

🚀 Cách chạy
Chạy từng cell theo thứ tự:
  Preparation
  Preprocessing
  Modeling (transformer, gpt)
  Inference & evaluation

Roadmap
 Cải thiện tập dữ liệu hội thoại y tế
 Hỗ trợ đa ngôn ngữ (en ↔ vi)
 Huấn luyện thêm với dữ liệu real-world
 Triển khai web app bằng streamlit hoặc gradio

 🎯 RLHF
- Reinforcement learning from human feedback (rlhf) với transformers
- Notebook này minh họa cách áp dụng rlhf để tinh chỉnh mô hình ngôn ngữ theo phản hồi của con người.

📘 Nội dung notebook
- Cài đặt thư viện: transformers, datasets
- Chuẩn bị dữ liệu: ví dụ hội thoại và phản hồi
- Huấn luyện mô hình: fine-tune bằng phương pháp rlhf
- Demo inference: so sánh trước và sau khi rlhf
