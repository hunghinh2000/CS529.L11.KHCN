# CHỌN HƯỚNG NGHIÊN CỨU VÀ BÀI TOÁN NGHIÊN CỨU

## Hướng nghiên cứu của nhóm N011:

Cả nhóm đều xác định hướng nghiên cứu là `Computer Vision` và hiện đang hứng thú với bài  báo "DeepFaceDrawing: Deep Generation of Face Images from Sketches"-2020, Shu-Yu Chen, Wanchao Su2, Lin Gao, Shihong Xia, Hongbo Fu.
- **Link bài báo**: http://geometrylearning.com/paper/DeepFaceDrawing.pdf  
- **Input**: là một tấm ảnh trắng, trên đó có vô số các đường nét, và các đường nét đó khi kết hợp bất kì đường nét khác đều cho ra một khuôn mặt với hình dạng có độ tương đồng cao với các nét vẽ. Người dùng sẽ vẽ lên tấm ảnh này để tạo ra `output`.
- **Output**: Hình ảnh một khuôn mặt người thật với hình dáng được người dùng phác thảo dựa trên tấm ảnh `input`.
- **Link git**: https://github.com/IGLICT/DeepFaceDrawing-Jittor
- **Link demo youtube**: https://www.youtube.com/watch?v=HSunooUTwKs
- **Ưu điểm của phương pháp**: Phương pháp đề xuất tốt hơn các phương đã có vì tránh được tình trạng quá khớp với ảnh phác hoạ đầu vào. Tạo ra hình ảnh khuôn mặt người mà vẫn đảm bảo tôn trọng 5 thành phần của ảnh phác hoạ, cụ thể: mắt trái, mắt phải, mũi, miệng và tổng thể khuôn mặt.