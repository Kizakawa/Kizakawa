<div align="center">

# Xin chào, mình là Phan Quốc Bảo (Kizakawa) 👋
### AI & LLM Systems Engineer • Computer Vision & Big Data ML • Backend & Database (SQL) Developer
**Sinh viên ngành Khoa học máy tính (Computer Science)**

[![Email](https://img.shields.io/badge/Email-phanquocbao.vp%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:phanquocbao.vp@gmail.com)
[![GitHub](https://img.shields.io/badge/Portfolio-github.com%2FKizakawa-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kizakawa)
[![AI Focus](https://img.shields.io/badge/Focus-AI_Engineer_%7C_Multi--Agent_LLM_%7C_Computer_Vision-0A66C2?style=for-the-badge)](#-năng-lực-cốt-lõi-core-engineering-competencies)
[![Database & Backend](https://img.shields.io/badge/Backend_%26_Data-FastAPI_%7C_SQL_%7C_PySpark-003B57?style=for-the-badge&logo=postgresql&logoColor=white)](#-điểm-nhấn-kiến-trúc-ai-pipeline--thiết-kế-csdl-sql)
[![Status](https://img.shields.io/badge/Trạng_Thái-Open_to_Opportunities-10B981?style=for-the-badge)](#-liên-hệ-tuyển-dụng--hợp-tác)

*Chuyên sâu thiết kế và triển khai các hệ thống Trí tuệ nhân tạo thực chiến (Multi-Agent LLM, RAG, Multimodal Vision, Deep Learning & ONNX Runtime) kết hợp nền tảng Backend hiệu năng cao (FastAPI) và Cơ sở dữ liệu chuẩn hóa (PostgreSQL, SQL Server, SQLite WAL, PySpark SQL).*

[🎯 Giới thiệu](#-giới-thiệu-tổng-quan--định-hướng-nghề-nghiệp) •
[🧠 Năng lực Cốt lõi (AI / Backend / SQL / BA)](#-năng-lực-cốt-lõi-core-engineering-competencies) •
[🚀 7 Dự án Trọng điểm](#-hệ-sinh-thái-7-dự-án-trọng-điểm-featured-repositories) •
[🏗️ Kiến trúc AI & CSDL SQL](#-điểm-nhấn-kiến-trúc-ai-pipeline--thiết-kế-csdl-sql) •
[🛠️ Công nghệ](#-công-nghệ--công-cụ-sử-dụng-technical-stack)

</div>

---

## 🎯 Giới Thiệu Tổng Quan & Định Hướng Nghề Nghiệp

Mình là **Phan Quốc Bảo**, sinh viên ngành **Khoa học máy tính (Computer Science)** với định hướng trọng tâm là **Kỹ sư Trí tuệ Nhân tạo (AI / LLM & Computer Vision Engineer)** kiêm **Phát triển Sản phẩm Phần mềm & Cơ sở dữ liệu (Backend / Full-Stack / SQL)**.

Điểm mạnh cốt lõi của mình là khả năng **đưa các mô hình AI/LLM và Học sâu vào phần mềm vận hành thực tế (Production-Grade AI Software)** thay vì chỉ dừng ở mức thử nghiệm Notebook:
1. **Kỹ thuật Hệ thống LLM, Multi-Agent & RAG:** Thiết kế luồng tác tử tự phục hồi với **LangGraph**, kiểm duyệt đầu ra bằng **Output Guardrails** chống lộ đáp án và chống Prompt Injection, xây dựng cơ chế chống trùng lặp ngữ nghĩa/thị giác (**Perceptual `dHash` Mini-RAG**) và khung đánh giá thực nghiệm định lượng (**Rubric & Benchmark `M1–M5`**).
2. **Thị giác Máy tính (Computer Vision), Học sâu & Dữ liệu lớn (Big Data ML):** Xây dựng kiến trúc phát hiện 2 tầng thời gian thực (**MediaPipe + YOLOv8n `99.5% mAP50`**), tối ưu hóa suy luận trên CPU bằng **ONNX Runtime (`18.9ms/ảnh`)**, kiểm duyệt đa phương thức **3-Frame Multimodal Gemini Vision**, và huấn luyện mạng **PyTorch `Bi-LSTM + Temporal Attention` / `LightGBM` / `Spark MLlib` / `CQR 90%`** trên tập dữ liệu lớn **2,07 triệu bản ghi**.
3. **Nền tảng CSDL Quan hệ (SQL), Phân tích Nghiệp vụ (BA) & Đóng gói Triển khai:** Thiết kế lược đồ CSDL chuẩn hóa `3NF` (từ 8 đến 20 bảng trên **PostgreSQL / SQLite WAL / SQL Server**), đảm bảo giao dịch nguyên tử **ACID**, truy vấn phân tích bằng **SQL / PySpark Window Functions**, và đóng gói triển khai thực tế qua **Docker Compose** hoặc **Bộ cài đặt Windows Portable (`1-Click Setup` kèm Auto-Backup Migration `v1 → v10`)**.

---

## 🧠 Năng Lực Cốt Lõi (Core Engineering Competencies)

| Lĩnh Vực Chuyên Môn | Kỹ Năng Kỹ Thuật & Minh Chứng Thực Tế Trong Các Dự Án |
| :--- | :--- |
| **🤖 AI, LLM Agents & Multimodal Engineering**<br>*(Định hướng trọng tâm — AI Engineer)* | • **Multi-Agent Orchestration (`LangGraph`):** Thiết kế đồ thị trạng thái đa tác tử tự động hóa quy trình từ phân tích chủ đề, sinh kịch bản theo hợp đồng `Pydantic v2`, chấm điểm phản biện đa vòng (`ScriptCritic`) đến tổng hợp đa phương thức (`AI-YouTube-Studio`).<br>• **LLM Guardrails, Prompt Engineering & Evaluation:** Thiết kế Prompt sư phạm 2 cấp độ (`KM` & `KH`) có rào chắn chống Prompt Injection, bộ lọc **Output Guardrail** (Regex + Token Overlap) tự động sinh lại khi vi phạm, và bộ công cụ đánh giá **Benchmark `M1–M5`** (`do-an-chuyen-nganh`).<br>• **Perceptual Mini-RAG & Context Engineering:** Xây dựng `VideoMemoryRAG` đối chiếu chữ ký thị giác `dHash` 3 khung hình chống lặp cảnh, và tích hợp **Google Gemini 3.5 Flash Context Agent** hỗ trợ lập kế hoạch/tóm tắt học tập (`personal-life-app`).<br>• **Hạ tầng AI Chịu lỗi (`KeyRotator` & Multi-Adapter):** Thiết kế `LLMServiceInterface` chuyển đổi linh hoạt giữa *OpenAI/Groq/Gemini REST API*, *Qwen2.5-Coder-7B trên Colab GPU* và *Offline Mock*; tự động xoay vòng khóa API khi chạm hạn mức `HTTP 429`. |
| **👁️ Computer Vision, Deep Learning & Big Data ML**<br>*(CV & Data Science Engineer)* | • **Real-Time Object Detection & Edge Optimization:** Thiết kế pipeline 2 tầng **MediaPipe FaceMesh + YOLOv8n** đạt **99.5% mAP50**, xuất mô hình sang **ONNX Runtime** giúp suy luận đạt `18.9ms/ảnh` ngay trên CPU (`drowsy-driver-detection-yolov8`).<br>• **Multimodal Vision QA & Programmatic Video/Audio:** Kết hợp **OpenCV** (đo độ nét Laplacian, kiểm tra chuyển động) với **Gemini Vision** duyệt 3 khung hình đầu–giữa–cuối và dựng hình **FFmpeg GPU (`h264_nvenc` / `h264_qsv`)** chuẩn âm thanh `EBU R128 (-14 LUFS)`.<br>• **Time-Series Deep Learning & Uncertainty Quantification:** Huấn luyện **PyTorch `Bi-LSTM + Attention`**, `LightGBM`, `XGBoost`, `Spark MLlib` kết hợp **Conformalized Quantile Regression (`90% CQR`)** và đối soát phân cấp (`smart-hems-bigdata-forecasting`). |
| **🗄️ Thiết Kế CSDL Quan Hệ & Lập Trình SQL**<br>*(Database & Big Data SQL)* | • **Thiết kế Lược đồ Quan hệ (ERD & Chuẩn hóa 3NF):** Thiết kế CSDL **20 bảng** (`personal-life-app`), **8 bảng PostgreSQL** (`do-an-chuyen-nganh`), **Sổ cái 6 bảng** (`tcb-digital-banking-mobile`) và **5 bảng** (`hsk-cosmic-academy`).<br>• **Truy vấn SQL & PySpark Window Functions:** Thành thạo `JOIN`, `GROUP BY`, `HAVING`, `CTE`, `Window Functions (LAG, AVG/STDDEV OVER)` trên cả CSDL giao dịch và tập dữ liệu lớn **2.075.259 bản ghi Parquet**.<br>• **Giao dịch ACID, Concurrency & Schema Migrations:** Xử lý khóa giao dịch tức thời `BEGIN IMMEDIATE TRANSACTION`, `idempotency_key`, `Partial Unique Index`, chuỗi **Alembic (`0001 → 0003`)** và **Auto-Backup Migration Engine (`v1 → v10`)**. |
| **💻 Phát Triển Sản Phẩm, BA & Triển Khai**<br>*(Product Dev, BA & Implementation)* | • **Full-Stack & Microservices:** Phát triển Backend với **Python (`FastAPI`, `SQLAlchemy 2.0`)**, **Node.js (`Express`, `node:sqlite`)** cùng giao diện **React 19, Vite 8, Zustand**, **Streamlit** và **Android Native (Java)**.<br>• **Phân tích Nghiệp vụ (BA) & Đóng gói Triển khai:** Đặc tả Use Cases (`UC01–UC06`), kiểm soát giao dịch hạn mức (`Quota/Cooldown`), đóng gói **Docker Compose** và bộ cài **Windows Portable (`.zip`)** bảo toàn 100% dữ liệu người dùng tại `%APPDATA%` kèm **179 bài kiểm thử tự động `pytest`**. |

---

## 🚀 Hệ Sinh Thái 7 Dự Án Trọng Điểm (Featured Repositories)

> *Tất cả 7 dự án dưới đây đều được trình bày đồng bộ, có đầy đủ tài liệu Kiến trúc AI/Hệ thống, Thiết kế CSDL (SQL), Phân tích Nghiệp vụ và Hướng dẫn Triển khai chi tiết.*

### A. Nhóm Kỹ Thuật Hệ Thống AI, LLM Agents, Computer Vision & Dữ Liệu Lớn (AI & Data Engineering)

| Dự Án & Lĩnh Vực AI | Điểm Nhấn Kiến Trúc AI / ML • CSDL (SQL) • Kiểm Chứng Thực Nghiệm | Công Nghệ Cốt Lõi |
| :--- | :--- | :--- |
| 🎬 **[AI-YouTube-Studio](https://github.com/Kizakawa/AI-YouTube-Studio)**<br>*(Hệ thống Multi-Agent LLM, Multimodal Vision & Tự động hóa Đa kênh)* | • **Đồ thị Đa tác tử Tự phục hồi (`LangGraph` — 242 Python Modules):** Điều phối khép kín từ săn chủ đề, sinh kịch bản chuẩn `Pydantic`, phản biện đa vòng (`ScriptCritic`) đến tổng hợp giọng nói đa tầng và dựng video GPU.<br>• **Kiểm định Thị giác 3 Khung hình & `dHash Mini-RAG`:** Kết hợp **Gemini Multimodal Vision** + **OpenCV** và kho băm thị giác `VideoMemoryRAG` loại bỏ 100% cảnh dính watermark hoặc trùng lặp.<br>• **Hạ tầng Bền vững & 179 Kiểm thử `pytest`:** Tầng **SQLAlchemy ORM** tự động chuyển đổi dự phòng `PostgreSQL` $\leftrightarrow$ `SQLite WAL`, xoay vòng khóa `KeyRotator` và cách ly hạn ngạch 7 cụm OAuth cho 9 kênh. | `Python 3.11+`<br>`LangGraph`<br>`Gemini Vision`<br>`dHash Mini-RAG`<br>`FastAPI & SQL`<br>`FFmpeg GPU`<br>`179 Pytest` |
| 🧠 **[do-an-chuyen-nganh](https://github.com/Kizakawa/do-an-chuyen-nganh)**<br>*(Hệ thống Chấm Code Tự động & Gia sư LLM Sư phạm có Guardrail)* | • **Module Phản hồi Sư phạm LLM 2 Cấp độ (`KM` & `KH`):** Đóng khung ngữ cảnh lỗi `<student_code>` và `<execution_evidence>` chống Prompt Injection; hỗ trợ đa mô hình qua Adapter (`OpenAI/Groq/Gemini API` & `Qwen2.5-Coder-7B` trên Colab T4).<br>• **Output Guardrail & Giao dịch Hạn mức (`HintOrchestrationService`):** Tự động lọc mã lộ đáp án (Regex + `Token Overlap`), sinh lại tối đa 2 lần; quản lý quota 3 lượt/bài, cooldown 120s, lỗi AI tuyệt đối không trừ lượt.<br>• **CSDL PostgreSQL 8 Bảng (3NF) & Benchmark `M1–M5`:** Vận hành với **Judge0 Sandbox**, `Partial Unique Index`, **Alembic Migrations (`0001 → 0003`)**, **Docker Compose** và xuất báo cáo đánh giá thực nghiệm CSV/JSONL. | `LLM Guardrails`<br>`Qwen2.5-Coder`<br>`FastAPI`<br>`Judge0 Sandbox`<br>`PostgreSQL 17`<br>`Alembic`<br>`Docker Compose` |
| ⚡ **[smart-hems-bigdata-forecasting](https://github.com/Kizakawa/smart-hems-bigdata-forecasting)**<br>*(Phân tích Dữ liệu Lớn 2,07 Triệu Dòng & Dự báo Phụ tải bằng Học sâu)* | • **Pipeline PySpark SQL & Window Functions (2.075.259 bản ghi):** Lưu trữ phân vùng **Apache Parquet**, nội suy có giới hạn và trích xuất đặc trưng trễ/trượt (`LAG`, `AVG OVER`, `STDDEV OVER`) đảm bảo **Zero Data Leakage**.<br>• **Hệ mô hình Học sâu & Định lượng Bất định (`CQR 90%`):** Kết hợp **PyTorch `Bi-LSTM + Temporal Attention`**, `LightGBM`, `XGBoost`, `Spark MLlib` cùng đối soát phân cấp (`Hierarchical Reconciliation`).<br>• **Ứng dụng BI & Cảnh báo Quá tải (`app.py`):** Bảng điều khiển **Streamlit** trực quan hóa dải dự báo, cảnh báo vượt ngưỡng công suất `P95` và dự toán chi phí điện năng (`kWh`). | `Apache Spark 4.0`<br>`PySpark SQL`<br>`PyTorch Bi-LSTM`<br>`LightGBM / XGB`<br>`CQR 90%`<br>`Apache Parquet`<br>`Streamlit App` |
| 👁️ **[drowsy-driver-detection-yolov8](https://github.com/Kizakawa/drowsy-driver-detection-yolov8)**<br>*(Hệ thống Thị giác Máy tính 2 Tầng Phát hiện Tài xế Buồn ngủ Real-Time)* | • **Kiến trúc Thị giác 2 Tầng (`99.5% mAP50`):** Tầng 1 định vị 468 điểm mốc khuôn mặt và cắt chuẩn hóa vùng mắt bằng **MediaPipe FaceMesh**; Tầng 2 phân loại trạng thái mắt bằng **YOLOv8n** kết hợp bộ đếm thời gian cảnh báo.<br>• **Tối ưu hóa Suy luận CPU bằng ONNX Runtime (`18.9ms/ảnh`):** Chuyển đổi trọng số PyTorch sang `.onnx` tăng tốc 30% trên CPU, đi kèm công cụ kiểm định phân phối dữ liệu (`check_imbalance.py`) và giao diện Web **Streamlit (`scripts/app.py`)**. | `YOLOv8n`<br>`MediaPipe`<br>`ONNX Runtime`<br>`OpenCV`<br>`PyTorch`<br>`Streamlit` |

### B. Nhóm Phần Mềm Quản Trị Tích Hợp AI, Tài Chính & Cơ Sở Dữ Liệu Quan Hệ (Full-Stack & FinTech)

| Dự Án & Phân Hệ Nghiệp Vụ | Điểm Nhấn Thiết Kế CSDL (SQL) • Tích Hợp AI • Nghiệp Vụ & Triển Khai | Công Nghệ Cốt Lõi |
| :--- | :--- | :--- |
| 📊 **[personal-life-app](https://github.com/Kizakawa/personal-life-app)**<br>*(Phần mềm Quản trị Cá nhân, Ngân sách, Dự án & Trợ lý AI — Bản V16)* | • **Tích hợp Trợ lý AI Ngữ cảnh (`Google Gemini 3.5 Flash`):** Tự động phân tích dữ liệu học tập/chi tiêu, tối ưu hóa **Kế hoạch Ngân sách Sinh tồn**, tóm tắt sổ ghi bài và bóc tách lịch trình thông minh (`ai_schedule_parser.py`).<br>• **CSDL Quan hệ 20 Bảng (`SQLAlchemy 2.0`) & 24 API Routers:** Quản lý đồng bộ *Giao dịch Thu-Chi, Định mức Ngân sách, Dự án, Công việc, Học vụ, Sổ ghi bài & Sự kiện Âm/Dương lịch*.<br>• **Auto-Backup Migration (`v1 → v10`) & Windows Portable:** Tự động sao lưu CSDL trước khi nâng cấp và đóng gói bộ cài `.zip` tách biệt dữ liệu tại `%APPDATA%`. | `Gemini 3.5 Flash`<br>`FastAPI`<br>`SQLAlchemy 2.0`<br>`SQL (20 Tables)`<br>`React 19 + Vite`<br>`Windows Portable` |
| 🏦 **[tcb-digital-banking-mobile](https://github.com/Kizakawa/tcb-digital-banking-mobile)**<br>*(Hệ thống Ngân hàng Số, Sổ cái Giao dịch ACID & Bảo mật OWASP)* | • **Sổ cái CSDL Giao dịch ACID (`SQLite WAL` — 6 Bảng):** Khóa giao dịch tức thời `BEGIN IMMEDIATE TRANSACTION`, kiểm tra số dư nguyên tử trong câu lệnh `UPDATE` và khóa chống gửi trùng `idempotencyKey` (Zero Double-Spending).<br>• **Bảo mật Phần cứng & Kiểm thử Tự động (9/9 E2E Tests):** Mã hóa thông tin nhạy cảm bằng **AndroidKeyStore (`AES-256-GCM`)**, xác thực OTP hằng thời gian, đối soát thu/chi ròng theo tháng và tích hợp CI/CD. | `SQL (ACID Ledger)`<br>`Node.js / Express`<br>`Java (Android)`<br>`AES-256-GCM`<br>`OWASP Top 10`<br>`GitHub Actions` |
| 🛸 **[hsk-cosmic-academy](https://github.com/Kizakawa/hsk-cosmic-academy)**<br>*(Nền tảng Học thuật Thông minh: Chấm nét Chữ Hán, Nhận diện Giọng nói & SM-2)* | • **Chấm điểm Tương tác Đa phương thức:** Chấm nét viết chữ Hán trên lưới Ô Chữ Điền bằng thuật toán **Pixel-Mask IoU Overlap**, chấm phát âm bằng **Web Speech Recognition (`zh-CN`)** và lập lịch ôn tập ngắt quãng **Anki SM-2**.<br>• **CSDL SQLite WAL 5 Bảng & Backend Zero-Dependency:** Quản lý **6 bộ giáo trình, 42 bài học, 930 từ vựng chuẩn hóa**, đồng bộ đám mây và thống kê tiến độ 7 ngày trên nền Node.js Core (`< 50ms` cold start). | `Anki SM-2`<br>`Speech & IoU AI`<br>`SQL (node:sqlite)`<br>`Node.js Core`<br>`HTML5 Canvas`<br>`Docker / PWA` |

---

## 🏗️ Điểm Nhấn Kiến Trúc: AI Pipeline & Thiết Kế CSDL (SQL)

Sự kết hợp giữa **Tầng Suy luận AI/LLM có Kiểm duyệt (Guardrails & Vision Gate)** và **Tầng Cơ sở Dữ liệu Quan hệ Toàn vẹn (ACID & Normalized SQL Schema)** trong các dự án:

```mermaid
flowchart TB
    subgraph AI_Layer["🧠 Tầng Suy Luận AI, Đa Tác Tử & Thị Giác Máy Tính (AI & Multimodal Layer)"]
        AGENT["LangGraph Multi-Agent & Gemini 3.5 Flash\n(Script Generation, Survival Budget & Schedule Parser)"]
        GUARD["Socratic KM/KH Prompt & Output Guardrail\n(Anti-Injection, Regex Filter & Token Overlap Check)"]
        VISION["Multimodal Vision Gate & 2-Stage YOLOv8n/ONNX\n(3-Frame Inspection, dHash Mini-RAG & 18.9ms Eye Detection)"]
        TS_ML["Big Data Time-Series Forecasting\n(PySpark SQL Window + Bi-LSTM Attention + 90% CQR)"]
    end

    subgraph Data_Layer["🗄️ Tầng Cơ Sở Dữ Liệu Quan Hệ, Giao Dịch ACID & Lưu Trữ Phân Vùng (SQL & Persistence Layer)"]
        PG[("PostgreSQL 17 (3NF — 8 Tables)\nAlembic Migrations + Partial Unique Index")]
        PLA_DB[("SQLAlchemy 2.0 (20 Tables)\nExpense, Budget, Project, Academic + Migration v1→v10")]
        LEDGER[("SQLite WAL Core Ledger (6 Tables)\nBEGIN IMMEDIATE + Idempotency Anti-Double-Spending")]
        PARQUET[("Apache Parquet (2,075,259 Rows)\nPartitioned by Year/Month for Spark SQL")]
    end

    AGENT --> PLA_DB & PG
    GUARD --> PG
    VISION --> PG
    TS_ML <--> PARQUET
```

---

## 🛠️ Công Nghệ & Công Cụ Sử Dụng (Technical Stack)

### 🤖 AI, LLM Agents, Computer Vision & Deep Learning
![Python](https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-Bi--LSTM_%26_Deep_Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-Multi--Agent_Orchestration-1C3C3C?style=flat-square)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-Multimodal_Vision_%26_LLM-4285F4?style=flat-square&logo=google&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8_%2B_MediaPipe-Real--Time_Vision-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ONNX Runtime](https://img.shields.io/badge/ONNX_Runtime-Edge_CPU_Optimization-005CED?style=flat-square&logo=onnx&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM_%7C_XGBoost-Tabular_%26_Time_Series-10B981?style=flat-square)

### 🗄️ Cơ Sở Dữ Liệu Quan Hệ, Truy Vấn SQL & Dữ Liệu Lớn (Big Data)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_17-3NF_Schema_%26_Indexing-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/MS_SQL_Server-T--SQL_%7C_Stored_Proc_%7C_ERD-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![SQLite WAL](https://img.shields.io/badge/SQLite_WAL-ACID_Ledger_%26_Embedded_DB-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy_2.0-Async_ORM_%26_Migrations-D71F00?style=flat-square)
![Apache Spark](https://img.shields.io/badge/Apache_Spark_4.0-PySpark_SQL_%26_Window-E25A1C?style=flat-square&logo=apachespark&logoColor=white)

### ⚙️ Backend, Frontend, Đóng Gói Triển Khai & Kiểm Thử (DevOps & QA)
![FastAPI](https://img.shields.io/badge/FastAPI-Async_REST_API-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React_19_%2B_Vite_8-Frontend_SPA-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-Express_%26_Core_API-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-Android_Native_SDK-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-AI_%26_BI_Dashboard-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-Container_Deployment-2496ED?style=flat-square&logo=docker&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-179+_Automated_Tests-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

---

## 📫 Liên Hệ Tuyển Dụng & Hợp Tác

- 👤 **Họ và tên:** **Phan Quốc Bảo** (Nickname: **Kizakawa**)
- 🎓 **Chuyên ngành:** Khoa học máy tính (Computer Science)
- 📧 **Email:** [phanquocbao.vp@gmail.com](mailto:phanquocbao.vp@gmail.com)
- 💼 **GitHub Portfolio:** [https://github.com/Kizakawa](https://github.com/Kizakawa)
- 🎯 **Vị trí ứng tuyển:** **AI Engineer (LLM Systems / Multi-Agent / Computer Vision / Data & ML)** • **Backend & Product Software Engineer (Python / FastAPI / SQL)**
