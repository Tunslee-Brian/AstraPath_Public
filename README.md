<div align="center">
  <img src="https://raw.githubusercontent.com/lucide-icons/lucide/main/icons/galaxy.svg" width="120" alt="AstraPath Logo"/>
  <h1>🌌 AstraPath: The Spatial Cognitive Engine</h1>
  <p><strong>Hệ điều hành Không gian Tương tác Đa phương thức (Multi-modal Spatial OS)</strong></p>
  
  [![Status: Private Beta](https://img.shields.io/badge/Status-Private_Beta_for_AI_Young_Guru-blue.svg)]()
  [![Architecture: Edge RAG](https://img.shields.io/badge/Architecture-Edge_Computed_RAG-success.svg)]()
  [![Processing: LPU Accelerated](https://img.shields.io/badge/Processing-Groq_LPU_Accelerated-orange.svg)]()
  [![Vision: Llama 3.2](https://img.shields.io/badge/Vision-Llama_3.2_%7C_Gemini_1.5_Pro-purple.svg)]()

  <p><em>Sách trắng Kỹ thuật (Tech Whitepaper) - Tự hào tham dự <strong>AI Young Guru 2026</strong></em></p>
</div>

---

## 🚀 1. Tuyên ngôn Sản phẩm (The Vision)

Trong kỷ nguyên bùng nổ của Trí tuệ Nhân tạo, chúng ta vẫn đang ép bộ não con người giao tiếp với máy móc qua những ô chat bằng văn bản tĩnh lặng và chật hẹp. **AstraPath ra đời để đập bỏ giới hạn đó.**

Chúng tôi không xây dựng một ứng dụng ghi chú. Chúng tôi kiến tạo một **Hệ sinh thái Nhận thức Không gian (Spatial Cognitive Ecosystem)**. Thay vì giam cầm tri thức trong các "Thư mục" (Folders) vô hồn, AstraPath ánh xạ dữ liệu của bạn lên một Vũ trụ 3D (Vector Space). Tại đây, tri thức không chỉ để đọc, mà để **chạm vào, tương tác vật lý và biến đổi thành hiện thực chỉ trong chớp mắt**.

---

## 💎 2. Tính năng Lõi (The Crown Jewel): MakeReal Engine

> *"Khoảng cách từ Trí tưởng tượng đến Mã nguồn nay chỉ còn vài mili-giây."*

Đối với những người không có chuyên môn lập trình (Non-coders), việc truyền đạt một ý tưởng giao diện là một cực hình. AstraPath giải quyết triệt để rào cản này bằng **MakeReal Engine** – tính năng biến phác thảo nét vẽ tay thành một ứng dụng web hoạt động được ngay lập tức trên màn hình.

<div align="center">
  <!-- YÊU CẦU: HÃY CHÈN 1 ẢNH GIF / VIDEO DEMO TÍNH NĂNG MAKEREAL CỦA BẠN TẠI ĐÂY (CHIẾM TRỌN MÀN HÌNH) -->
  <img src="https://placehold.co/800x400/1e1e1e/cyan?text=[CHÈN_ẢNH_GIF_MAKEREAL_CỰC_ĐẸP_TẠI_ĐÂY]" width="800" alt="MakeReal Demo GIF"/>
  <p><em>Demo: Hệ thống phân tích nét vẽ tay và hydrate UI Component theo thời gian thực ngay trên Canvas.</em></p>
</div>

### ⚙️ Luồng xử lý Kỹ thuật bậc sâu (Deep Data Flow):

Sự kỳ diệu trên giao diện được chống lưng bởi một luồng xử lý (pipeline) kỹ thuật đồ sộ và tinh vi:

1. **User Defining (Khoanh vùng Context):** Người dùng dùng công cụ "Magic Frame" trên nền tảng Canvas vô cực (tích hợp `@excalidraw/excalidraw`).
2. **Edge OCR & Blob Export:** Ngay tại trình duyệt (Client-side), hệ thống chạy thuật toán chụp ảnh chất lượng cao (`exportToBlob`) kết hợp `getTextFromElements` để bóc tách toàn bộ nhãn (labels) văn bản thô, giúp AI hiểu chính xác "ý định" (intent) chứ không chỉ là "hình dáng".
3. **Multi-modal Routing (Điều phối AI):** Dữ liệu Base64 Data URL được nén và đẩy qua service `callVisionModel`. Hệ thống tự động cân bằng tải và lựa chọn giữa **Gemini 1.5 Pro Vision** (cho layout phức tạp) hoặc **Groq Llama 3.2 Vision** (cho tốc độ siêu tốc).
4. **Spatial Reasoning (Tư duy Không gian):** AI đọc `SYSTEM_PROMPT_MAKE_REAL` của chúng tôi (chứa quy tắc Glassmorphism, Responsive CSS), phân tích tọa độ hình học và xuất ra mã nguồn HTML/Tailwind CSS chuẩn xác.
5. **Sanitization & Live Hydration:** Khối `htmlify` dùng Regex lọc sạch mã độc và rác định dạng. Cuối cùng, một `<iframe>` được khởi tạo động, biến nét vẽ của bạn thành một giao diện "sống" ngay tại tọa độ vùng chọn.

---

## 🏗️ 3. Kiến trúc RAG Chuẩn Doanh nghiệp (Enterprise-Grade Edge RAG)

AstraPath không gọi API một cách hời hợt. Chúng tôi giải quyết bài toán lớn nhất của LLM hiện nay: **Sự ảo giác (Hallucination) và Quyền riêng tư (Privacy).**

<div align="center">
  <!-- YÊU CẦU: CHÈN ẢNH SƠ ĐỒ HỆ THỐNG / KIẾN TRÚC MÀ BẠN CÓ (HOẶC VẼ 1 CÁI ĐƠN GIẢN TRÊN FIGMA) -->
  <img src="https://placehold.co/700x300/1e1e1e/gold?text=[SƠ_ĐỒ_KIẾN_TRÚC_HỆ_THỐNG_RAG]" width="700" alt="System Architecture"/>
</div>

### 🔒 Client-Side Parsing (Bảo mật Tuyệt đối)
Thay vì đẩy hàng MB tài liệu PDF của người dùng lên Server rủi ro, AstraPath sử dụng thư viện `unpdf` để **phân rã văn bản ngay tại trình duyệt của người dùng (Edge-computing)**. Dữ liệu nhạy cảm không bao giờ rời khỏi máy tính của bạn cho đến khi nó được mã hóa thành các cụm (chunks) siêu nhỏ.

### 🎯 Zero-Hallucination Pipeline (Tính năng Source Insight)
Khi bạn hỏi, AI của AstraPath không được phép đoán mò. Chúng tôi ép luồng suy luận của mô hình cực lớn (`llama3-70b-8192` qua hạ tầng LPU siêu tốc) phải sinh ra các **Citations (Trích dẫn Metadata)**. 

<details>
<summary>👉 <em>(Click để xem)</em> <b>Kiến trúc JSON Payload Nội bộ của Source Insight</b></summary>

```json
// LLM Response bị ép buộc phải trả về định dạng bọc Citation
{
  "index": 1,
  "sourceId": "uuid-v4-identifier",
  "sourceTitle": "whitepaper_astra.pdf",
  "excerpt": "Hệ thống sử dụng cơ chế so khớp văn bản..."
}