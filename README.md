| Nhóm | Tài liệu | Năm | Nội dung và ứng dụng |
|---|---|---|---|
| **1. Kiến thức nền EMG** | [Analysis and Biophysics of Surface EMG for Physiotherapists and Kinesiologists](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2020.576729/full) | 2020 | Nguồn gốc sEMG, thu nhận, biên độ, phổ và các yếu tố ảnh hưởng. Dùng làm cơ sở lý thuyết. |
| **1. Kiến thức nền EMG** | [CEDE — Amplitude normalization matrix](https://pubmed.ncbi.nlm.nih.gov/32569878/) | 2020 | Chuẩn hóa biên độ EMG để so sánh giữa các lần đo, tư thế và buổi đo. |
| **2. Phần cứng và PCB** | [A new design of an electromyography sensor for movement detection in human-machine interaction systems](https://journals.sagepub.com/doi/full/10.1177/16878132251338446) | 2025 | Thiết kế mạch thu EMG bốn kênh, khuếch đại, lọc analog, DRL và PCB hai lớp. Tham khảo schematic và phương pháp kiểm chứng phần cứng. |
| **3. Xử lý tín hiệu** | [Filtering the surface EMG signal: Movement artifact and baseline noise contamination — PDF](https://www.bu.edu/nmrc/files/2010/06/103.pdf) | 2010 | Phân tích nhiễu chuyển động, nhiễu nền và ảnh hưởng của bộ lọc lên tín hiệu EMG. |
| **3. Xử lý tín hiệu** | [Continuous wavelet transform-based analysis of shoulder muscle fatigue during dynamic abduction: a surface electromyography study](https://www.frontiersin.org/journals/bioengineering-and-biotechnology/articles/10.3389/fbioe.2026.1855236/full) | 2026 | Tiền xử lý, chia cửa sổ, CWT, median frequency và so sánh FFT. Tham khảo phân tích biến đổi phổ liên quan mỏi cơ khi cử động vai. |
| **4. Đo tĩnh và khi cử động** | [A Real-Time Algorithm to Estimate Shoulder Muscle Fatigue Based on Surface EMG Signal For Static and Dynamic Upper Limb Tasks](https://pubmed.ncbi.nlm.nih.gov/34891249/) | 2021 | Ước lượng mỏi cơ vai trong nhiệm vụ tĩnh và động. Tham khảo thiết kế hai chế độ đo. |
| **4. Đo tĩnh và khi cử động** | [EMG-based evaluation of relationship between muscle activity, joint kinematics, and joint torque in an upper limb exoskeleton supporting range of motion exercises](https://link.springer.com/article/10.1007/s44430-026-00045-1) | 2026 | Quan hệ giữa hoạt động cơ, góc khớp và tải. Tham khảo cách kiểm soát điều kiện khi so sánh EMG trong vận động. |
| **5. AI và đánh giá vận động** | [A Biosignal-Driven Wearable System Integrating Surface Electromyography and Kinematics for Interpretable Upper-Limb Assessment](https://www.mdpi.com/2079-6374/16/10/590) | 2026 | Kết hợp đường bao EMG, IMU và cảm biến lực; dùng CNN nhận dạng động tác và DTW xác định đoạn khác mẫu tham chiếu. |
| **5. AI và đánh giá vận động** | [Machine learning-based prediction of individualized musculoskeletal responses during shoulder exercises using surface electromyography](https://link.springer.com/article/10.1186/s12891-026-10200-9) | 2026 | Dự đoán đáp ứng cơ sinh học với bài tập vai bằng học máy. Tham khảo cách xác định đầu ra AI và phép đo tham chiếu. |
| **6. Dataset** | [A dataset for fatigue estimation during shoulder internal and external rotation movements using wearables](https://www.nature.com/articles/s41597-024-03254-8) | 2024 | Dữ liệu sEMG và cảm biến đeo khi xoay vai. Dùng phát triển xử lý tín hiệu và thử thuật toán trước khi PCB hoàn thành. |

> **Chú thích**
>
> - **sEMG:** điện cơ bề mặt; **IMU:** cảm biến quán tính; **DRL:** mạch phản hồi giảm nhiễu đồng pha.
> - **CWT:** biến đổi wavelet liên tục; **FFT:** biến đổi Fourier nhanh; **DTW:** phương pháp căn chỉnh và so sánh chuỗi tín hiệu theo thời gian.
> - **Đo tĩnh:** cần phân biệt nghỉ hoàn toàn với co cơ giữ tư thế (*isometric*). **Đo động:** thu EMG trong khi thực hiện chuyển động.
> - Bài PCB sử dụng **AD620 + TL074** và nguồn khác dự án. Khi dùng **AD623 + MCP6004**, phải tính lại gain, bộ lọc và dải điện áp hoạt động.
> - Dữ liệu **100 Hz** trong bài Biosensors 2026 là dữ liệu đường bao EMG; không dùng mức này làm tần số lấy mẫu EMG thô để phân tích phổ.
> - Các nghiên cứu trên người khỏe và chỉ số mỏi cơ chưa đủ để kết luận mức phục hồi sau mổ hoặc tình trạng liền xương.
> - Dataset công khai hỗ trợ phát triển thuật toán; cần dữ liệu tự thu để kiểm chứng PCB và toàn bộ hệ thống.
