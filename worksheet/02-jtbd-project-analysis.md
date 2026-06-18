---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** AI Hỗ Trợ Đọc Ảnh Y Khoa & Đánh Dấu Vùng Nghi Ngờ (Hỗ Trợ Bác Sĩ Chẩn Đoán Hình Ảnh)  
**Người nộp:** Hoàng Đức Trường (2A202600552)

> Đây là **file duy nhất** của Lab 2.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải brainstorm thêm thật nhiều tính năng AI.
Mục tiêu là:

1. **xác định người dùng thực sự đang cố hoàn thành job gì**
2. **hiểu họ đang dùng giải pháp nào để hoàn thành job đó hôm nay**
3. **chỉ ra AI nên chen vào đúng bước nào trong workflow**
4. **viết ra product hypothesis và assumption còn phải validate**

Quy tắc xuyên suốt: **không rõ job thì đừng bàn feature.**

---

## Cần mở song song 2 thứ

1. **File này** — để điền trực tiếp
2. **`Strategyn_JTBD_Playbook.pdf`** — giảng viên gửi kèm

### Cách dùng playbook cho đúng

Bạn **không cần đọc hết 48 trang**.  
Trong bài này, playbook chủ yếu dùng để tra 4 thứ:

1. **Cách nhìn thị trường qua JTBD lens**
2. **`Job executor` là ai**
3. **Cách viết `job statement`: `verb + object + contextual clarifier`**
4. **8 bước của `job map`**:
   `define -> locate -> prepare -> confirm -> execute -> monitor -> modify -> conclude`

### 2 chương nên mở nhiều nhất

- **Chapter 2 — Define Your Market**
- **Chapter 3 — Build Your Job Map**

> Dùng playbook để **tra framework và ví dụ**.  
> Dùng file này để **làm bài và chốt output**.

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 6 phần trong chính file này:

1. **`Project slice` + market context**
2. **`Job executor` + `core JTBD`**
3. **3 `job stories`**
4. **`JTBD lite map` + pain points**
5. **`AI leverage point` + `product hypothesis`**
6. **`Assumptions to validate` + verdict cuối sau thảo luận**

Nếu thiếu một trong sáu phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (25 phút)

```text
3'  Chốt 1 lát cắt cụ thể của dự án
7'  Viết market context + job executor + core JTBD
6'  Viết 3 job stories + current alternatives
6'  Điền JTBD lite map + AI leverage point + hypothesis
3'  Share trong bàn và sửa version cuối
```

> Nếu dự án làm theo nhóm, cả nhóm có thể thảo luận chung.  
> Nhưng file này vẫn nên có **version chốt rõ ràng** của người nộp.

---

## Bước 0 — Khoanh đúng 1 lát cắt của dự án

Phần lớn dự án nhóm viết quá rộng ở bước này, rồi sau đó mọi thứ mơ hồ theo.

### Khoanh đúng 1 lát cắt theo 4 điểm

- [x] **1 nhóm người dùng chính**
- [x] **1 hoàn cảnh / tình huống rõ**
- [x] **1 job cốt lõi**
- [x] **1 workflow đủ cụ thể để vẽ ra được**

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** AI hỗ trợ đọc ảnh y khoa và đánh dấu vùng nghi ngờ — pipeline: ảnh DICOM X-quang → tiền xử lý → YOLO (phát hiện + bbox + class + confidence) → Med Gemma (phân tích & diễn giải, kèm ảnh gốc) → giao diện cho bác sĩ
- **Lát cắt tôi chọn để phân tích hôm nay là:** Bác sĩ chẩn đoán hình ảnh đọc phim X-quang ngực (DICOM) trong ca trực, khi khối lượng ca cao và cần phát hiện tổn thương nhỏ/khó thấy kịp thời trước khi ký báo cáo
- **Vì sao tôi chọn lát cắt này:**  
  > Đây là workflow cụ thể nhất mà pipeline nhóm đang build (YOLO + Med Gemma trên ảnh X-quang). Nếu viết "AI y khoa cho mọi loại ảnh, mọi bác sĩ" thì không map được pain point và AI leverage point. Lát cắt này khớp pipeline thật và có alternative rõ (đọc thủ công trên PACS).

### Viết quá rộng vs viết sắc hơn

| Viết quá rộng | Viết sắc hơn |
|---|---|
| Giúp SME dùng AI để marketing | Giúp chủ shop online phản hồi câu hỏi trước mua hàng nhanh và nhất quán trong giờ cao điểm |
| Dùng AI để làm slide | Tạo bản nháp deck nội bộ mạch lạc cho buổi họp gấp trong thời gian rất ngắn |
| AI cho tuyển dụng | Giúp recruiter sàng lọc CV đầu vào nhanh hơn trước vòng gọi sơ bộ |

> Nếu bạn không mô tả được **một hoàn cảnh cụ thể**, khả năng cao bạn đang viết quá rộng.

---

## Bước 1 — Viết `Project Snapshot`

### Tóm tắt dự án trong 3 dòng

1. **Nhóm tôi đang nghĩ mình đang giải quyết vấn đề gì?**  
   > Bác sĩ chẩn đoán hình ảnh mất nhiều thời gian và dễ bỏ sót tổn thương nhỏ khi đọc hàng chục ca X-quang liên tục — đặc biệt trong ca trực tối hoặc giờ cao điểm.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > Bác sĩ chẩn đoán hình ảnh (radiologist) hoặc bác sĩ có chức năng đọc X-quang tại bệnh viện tuyến huyện/tuyến tỉnh — người trực tiếp mở ảnh DICOM, đọc, đánh dấu và ký báo cáo.

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > Đọc thủ công trên hệ thống PACS/RIS, tự cuộn/zoom từng vùng ảnh, ghi nhận bằng mắt; đôi khi nhờ đồng nghiệp đọc lại (second read) hoặc dùng CAD thương mại nếu bệnh viện có — phần lớn vẫn là lao động chuyên môn thuần tay.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > Bác sĩ chẩn đoán hình ảnh tại bệnh viện công — nơi tỷ lệ bác sĩ/ảnh chụp thấp, ca trực dày, áp lực thời gian ký báo cáo cao.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > Trong ca đọc ảnh: nhận chỉ định từ khoa lâm sàng → mở study DICOM trên PACS → đọc từng phim X-quang (ưu tiên phân tích: ngực/thorax trong lát cắt này) → đánh dấu vùng nghi ngờ → viết và ký báo cáo — thường lặp lại 20–50+ ca/ca trực.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > (1) Đọc thủ công hoàn toàn trên PACS; (2) CAD/commercial AI nếu bệnh viện đủ ngân sách; (3) Trao đổi nhanh với đồng nghiệp hoặc hội chẩn khi không chắc; (4) Tự ghi chú trên giấy/block note trong lúc đọc.

4. **Vì sao đây là thời điểm đáng giải?**  
   > Khối lượng chụp X-quang/CT tăng; thiếu bác sĩ CĐHA ở tuyến dưới; mô hình vision AI (YOLO) và medical LLM (Med Gemma) đủ mature để hỗ trợ detect + diễn giải; bệnh viện đang tìm công cụ giảm miss rate mà không thay thế hoàn toàn bác sĩ (assistive, không autonomous).

### Tóm tắt market context trong 3-4 dòng

> Bác sĩ CĐHA tại bệnh viện tuyến huyện/tỉnh phải đọc khối lượng lớn phim X-quang trong ca trực, với áp lực thời gian và rủi ro bỏ sót tổn thương nhỏ. Họ chủ yếu đọc thủ công trên PACS; CAD thương mại ít phổ biến vì chi phí và tích hợp. Nhu cầu "hỗ trợ đọc + đánh dấu + gợi ý diễn giải" tăng khi AI đủ chính xác để làm bước sàng lọc — nhưng bác sĩ vẫn phải là người quyết định cuối.

---

## Bước 3 — Xác định `Job Executor`

`Job executor` là người **trực tiếp dùng một giải pháp để hoàn thành job**.

### Đừng nhầm với:

- người mua tiền nhưng không trực tiếp làm job
- người ảnh hưởng quyết định
- cả một công ty hay một phòng ban quá rộng

### Gợi ý viết cho đúng

- Sai hoặc quá rộng: `SME`, `doanh nghiệp`, `thị trường`
- Tốt hơn: `chủ shop online`, `nhân viên CSKH`, `recruiter`, `sales ops manager`

### Điền

- **Job executor của dự án này là:** Bác sĩ chẩn đoán hình ảnh (radiologist) — người trực tiếp mở ảnh DICOM trên workstation, đọc phim, xác nhận vùng bất thường và ký báo cáo chẩn đoán
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > Bác sĩ là người ngồi trước màn hình, thao tác PACS, ra quyết định lâm sàng cuối cùng và chịu trách nhiệm pháp lý cho báo cáo. Họ không "mua" sản phẩm (thường là bệnh viện/Giám đốc mua), nhưng họ là người **dùng hàng ngày** để hoàn thành job đọc ảnh. UI của pipeline nhóm (YOLO bbox + Med Gemma output) được thiết kế cho họ — không phải cho IT hay khoa CĐHA quản trị.

**Không phải job executor (nhưng là influencer/buyer):** Giám đốc bệnh viện (mua), kỹ thuật viên chụp (tạo ảnh), bác sĩ lâm sàng (nhận kết quả, không đọc ảnh gốc).

---

## Bước 4 — Viết `Core JTBD`

`Core JTBD` là công việc cốt lõi người dùng đang cố hoàn thành.

### Công thức gợi ý

```text
[verb] + [object] + [contextual clarifier]
```

### Ví dụ

- Chưa tốt: `trả lời inbox bằng AI`
- Tốt hơn: `giải quyết câu hỏi trước mua hàng nhanh và chính xác trong giờ cao điểm`

- Chưa tốt: `dùng AI để viết nội dung`
- Tốt hơn: `tạo bản nháp nội dung chiến dịch phù hợp với brand trong thời gian rất ngắn`

### 3 tiêu chí tự kiểm

- [x] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [x] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [x] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Dùng AI để đọc ảnh X-quang và đánh dấu vùng nghi ngờ giúp bác sĩ chẩn đoán nhanh hơn trong ca trực

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: `dùng AI`, `đánh dấu` (có thể giữ nếu hiểu là hành vi job — nhưng `AI` chắc chắn bỏ), `YOLO`, `Med Gemma`, `app`

### Bản chốt

**Core JTBD cuối cùng:**  
> **Xác định chính xác và kịp thời các vùng bất thường trên phim X-quang** trong ca đọc ảnh khi khối lượng ca cao — để đưa ra kết luận chẩn đoán đáng tin cậy trước khi bệnh nhân rời khỏi quy trình điều trị.

*Cấu trúc: **xác định** (verb) + **vùng bất thường trên phim X-quang** (object) + **trong ca đọc ảnh khi khối lượng ca cao** (contextual clarifier)*

---

## Bước 5 — Viết 3 `Job Stories`

Nếu `core JTBD` là job ở mức cốt lõi, thì `job story` giúp bạn thấy
**job này xuất hiện trong hoàn cảnh nào**.

### Format

```text
When [trigger], I want to [motivation], so I can [outcome].
```

### Ví dụ

`When inbox đổ dồn vào buổi tối, tôi muốn có câu trả lời nhất quán ngay lập tức, so I can không mất đơn vì phản hồi chậm.`

### Bảng 3 job stories

| # | Trigger / When | Motivation / I want to | Outcome / so I can | Điều story này cho thấy |
|---|---|---|---|---|
| JS1 | Khi ca trực tối có 30+ chỉ định X-quang ngực chờ đọc trong 2 giờ | Tôi muốn nhanh chóng nhận ra vùng đáng chú ý mà không phải zoom từng milimet bằng mắt | Để ký báo cáo đúng hạn và không bỏ sót tổn thương rõ trên phim | Pain = tốc độ + khối lượng; AI detect (YOLO bbox) đáng xuất hiện ở bước Execute |
| JS2 | Khi tôi thấy vùng mờ nhỏ trên phổi nhưng không chắc là tổn thương thật hay artifact/nhiễu | Tôi muốn có gợi ý phân loại và mức độ tin cậy để đối chiếu với kinh nghiệm | Để quyết định có cần chụp thêm, hội chẩn hay theo dõi — tránh báo cáo mơ hồ hoặc overcall | Pain = độ không chắc chắn; Med Gemma (class + confidence + diễn giải) hỗ trợ bước Modify/Conclude |
| JS3 | Khi tôi vừa đọc xong 5 ca liên tiếp và mắt đã mỏi | Tôi muốn có bản tóm tắt sơ bộ các phát hiện chính trên từng ảnh để rà soát lại | Để giảm sai sót do mệt mỏi trước khi ký báo cáo cuối | Pain = fatigue + conclude; AI draft interpretation giúp bước Monitor/Conclude |

### Tự kiểm nhanh

- [x] Mỗi story là một **tình huống thật**, không phải slogan chung chung
- [x] 3 story không trùng hệt nhau
- [x] Sau khi đọc 3 story, tôi hình dung được lúc nào product của mình đáng xuất hiện

---

## Bước 6 — Liệt kê `Current Alternatives`

Qua JTBD lens, đối thủ không chỉ là app cùng ngành.
Đối thủ là **bất kỳ thứ gì user đang "thuê" để làm job**:

- thao tác tay
- file Excel / Google Sheets
- intern / nhân viên
- agency
- ChatGPT / Claude / Gemini
- công cụ chuyên dụng khác
- hoặc thậm chí là **không làm gì cả**

### Bảng alternatives

| Alternative hiện tại | User đang thuê nó để làm gì? | Nó làm tốt gì? | Nó fail ở đâu? | Switching cost hiện tại cao hay thấp? |
|---|---|---|---|---|
| Alt 1: Đọc thủ công trên PACS/RIS | Quan sát toàn bộ ảnh, tự phát hiện và kết luận | Chuẩn vàng lâm sàng; bác sĩ kiểm soát 100%; không phụ thuộc AI | Chậm; mỏi mắt khi nhiều ca; dễ miss tổn thương nhỏ/subtle; không scale | **Cao** — quen workflow, pháp lý rõ, không cần tin AI |
| Alt 2: CAD / AI thương mại (nếu BV có) | Gợi ý vùng nghi ngờ tự động trên ảnh | Đã validate lâm sàng; tích hợp PACS một số nơi | Đắt; ít bệnh viện tuyến dưới có; false positive cao → bác sĩ ignore | **Cao** — đã mua license, IT đã tích hợp |
| Alt 3: Nhờ đồng nghiệp đọc lại (second read) / hội chẩn | Giảm miss khi case khó | Tin cậy cao; học hỏi chéo | Không scale; phụ thuộc người; chậm khi đồng nghiệp bận | **Trung bình** — văn hóa bệnh viện, không phải lúc nào cũng có người |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> Đọc thủ công trên PACS (Alt 1) — vì đó là workflow mặc định, pháp lý an toàn, và switching cost sang tool mới (tin AI, học UI mới, tích hợp DICOM) còn cao nếu chưa chứng minh giá trị rõ.

---

## Bước 7 — Điền `JTBD Lite Map`

Đây là bản rút gọn của `job map` trong playbook.

### Mục tiêu

Không phải để làm consultant workshop hoàn chỉnh.  
Mục tiêu là nhìn ra:

1. workflow hiện tại của user đi qua những bước nào
2. bước nào đang đau nhất
3. AI có nên chen vào đó không

### 8 bước tham chiếu từ playbook

1. `Define`
2. `Locate`
3. `Prepare`
4. `Confirm`
5. `Execute`
6. `Monitor`
7. `Modify`
8. `Conclude`

> Không nhất thiết bước nào cũng quan trọng như nhau trong dự án của bạn.  
> Nếu ít liên quan, ghi `N/A`, đừng để trống.

### Bảng JTBD Lite Map

| Step | Trong workflow này user đang cố làm gì? | Hôm nay họ đang dùng gì? | Friction / pain hiện tại | Mức đau |
|---|---|---|---|---|
| Define | Xác định mục tiêu đọc: loại study, lý do chỉ định lâm sàng, câu hỏi cần trả lời | Đọc phiếu chỉ định trên RIS/PACS, ghi chú nhanh | Thông tin lâm sàng đôi khi thiếu/sơ sài → đọc ảnh mù ngữ cảnh | Med |
| Locate | Tìm và mở đúng study/series DICOM của bệnh nhân | PACS worklist, tìm theo mã BN/tên | Nhiều study trùng tên; worklist dài trong ca trực | Low |
| Prepare | Điều chỉnh window/level, chọn view phù hợp (PA/AP/lateral), xem chất lượng ảnh | Thao tác thủ công trên viewer PACS | Mất thời gian với ảnh kém chất lượng; tiền xử lý chưa chuẩn hóa | Med |
| Confirm | Xác nhận ảnh đủ chất lượng để đọc (không motion artifact nặng, đủ coverage) | Mắt bác sĩ + kinh nghiệm | Phải quyết định chụp lại hay đọc tiếp — gián đoạn workflow | Low |
| Execute | Quan sát toàn bộ phim, tìm và đánh dấu vùng bất thường | Mắt + tay (zoom, pan, đo, annotate trên PACS) | **Đau nhất:** nhiều ca liên tục → mỏi mắt, miss subtle finding; quét thủ công tốn thời gian | **High** |
| Monitor | Rà soát lại vùng đã đánh dấu, so sánh với ca cũ nếu có | Tự nhìn lại + mở study prior trên PACS | Dễ bỏ qua khi vội; không có checklist cố định | Med |
| Modify | Loại false positive, điều chỉnh nhận định, quyết định mức độ nghiêm trọng | Kinh nghiệm + hội chẩn nếu cần | CAD/AI hay báo nhầm → bác sĩ mất tin, phải verify từng vùng | **High** |
| Conclude | Viết báo cáo chẩn đoán, ký điện tử, trả kết quả cho khoa lâm sàng | Gõ template trên RIS/PACS hoặc dictation | Lặp lại mô tả giống nhau; mất 3–5 phút/ca; typo khi mệt | Med |

**Mapping pipeline nhóm → job map:**
- Tiền xử lý DICOM → hỗ trợ **Prepare**
- YOLO (bbox, class, confidence) → hỗ trợ **Execute** + **Monitor**
- Med Gemma (ảnh gốc + output YOLO) → hỗ trợ **Modify** + **Conclude**
- UI bác sĩ → xuyên suốt **Execute → Conclude**

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** **Execute** — quan sát và phát hiện tổn thương trên phim  
**Bước đau nhất #2:** **Modify** — xác minh vùng nghi ngờ, loại báo động giả, chốt nhận định

**Vì sao đây là nơi đáng chú ý nhất:**  
> Đây là nơi job cốt lõi ("xác định vùng bất thường chính xác và kịp thời") thực sự xảy ra. Pain tập trung ở tốc độ + độ chính xác khi khối lượng ca cao. Pipeline nhóm đặt YOLO ở Execute và Med Gemma ở Modify/Conclude — khớp 2 điểm đau này, không phải ngẫu nhiên.

---

## Bước 8 — Chỉ ra `AI Leverage Point`

Sau khi map workflow, mới hỏi:
**AI nên vào đâu, với vai trò gì, và vì sao là ở đó?**

### Nhắc nhanh

- Đừng nhét AI vào chỉ vì "có AI thì nghe hay"
- Nếu pain lớn nhất không nằm ở chỗ AI giải tốt, hãy thành thật ghi ra
- Nếu current alternative đã đủ tốt, project cần xem lại

### Bảng leverage point

| Step | AI nên giúp bằng cách nào? | Vì sao AI hợp ở đây? | Rủi ro chính nếu dùng AI |
|---|---|---|---|
| **Execute** (chính) | **YOLO** tự động phát hiện vùng nghi ngờ → trả bbox + class + confidence score lên UI; bác sĩ nhìn overlay thay vì quét trắng toàn phim | Vision model giỏi pattern recognition lặp lại trên ảnh; giảm tải nhận thức khi nhiều ca; tốc độ inference nhanh hơn mắt người quét thủ công | False negative (bỏ sót) → hậu quả lâm sàng nghiêm trọng; false positive → alert fatigue, bác sĩ tắt hệ thống |
| **Modify + Conclude** (phụ) | **Med Gemma** nhận ảnh gốc + output YOLO → gợi ý diễn giải lâm sàng, so sánh mức confidence, draft mô tả cho báo cáo | LLM y khoa tổng hợp đa nguồn (ảnh + metadata detection) → giảm thời gian viết báo cáo; hỗ trợ case borderline | Hallucination; diễn giải sai → bác sĩ ký nhầm; pháp lý/trách nhiệm chưa rõ |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> **Bước Execute — YOLO đánh dấu vùng nghi ngờ (bbox + class + confidence)** để bác sĩ tập trung vào vùng đáng chú ý thay vì quét thủ công toàn bộ phim trong ca trực cao tải.

**Vì sao không phải ở bước khác:**  
> Define/Locate/Confirm ít gain từ AI vision — đó là workflow hành chính/PACS. Med Gemma ở Conclude có giá trị nhưng **phụ thuộc detection đúng trước** — nếu YOLO miss thì Gemma không cứu được. Giá trị cốt lõi phải ở "tìm đúng chỗ" (Execute) trước khi "giải thích đúng" (Modify/Conclude).

---

## Bước 9 — Viết `Product Hypothesis`

Bây giờ mới đến lúc viết hypothesis.

### Công thức gợi ý

```text
Nếu chúng ta giúp [job executor] làm [job / sub-job] tốt hơn ở bước [x],
bằng cách [AI leverage],
thì họ sẽ chuyển từ [current alternative] sang [hướng giải pháp của nhóm],
vì [giá trị rõ nhất].
```

### Bản hypothesis của tôi

> Nếu chúng ta giúp **bác sĩ chẩn đoán hình ảnh** **xác định vùng bất thường trên phim X-quang ngực nhanh và đáng tin hơn** ở bước **Execute**,
> bằng cách **YOLO tự động đánh dấu vùng nghi ngờ kèm confidence score, kết hợp Med Gemma diễn giải trên UI workstation**,
> thì họ sẽ chuyển từ **đọc thủ công hoàn toàn trên PACS** sang **đọc có hỗ trợ AI (human-in-the-loop)**,
> vì **giảm thời gian quét ảnh mỗi ca và giảm nguy cơ bỏ sót tổn thương rõ** — mà vẫn giữ bác sĩ là người quyết định cuối.

### Tín hiệu sớm nếu hypothesis này đúng

1. Bác sĩ pilot dùng overlay YOLO trên ≥70% ca trong tuần đầu (không tắt hệ thống vì quá nhiều false positive)
2. Thời gian trung bình từ mở study đến ký báo cáo giảm ≥20% so với baseline đọc thủ công — mà không tăng tỷ lệ miss trên tập case đã biết ground truth

---

## Bước 10 — Liệt kê `Assumptions to Validate`

Job story chưa có research vẫn chỉ là **giả thuyết tốt hơn**, chưa phải sự thật.

### 5 assumption thường đáng kiểm

- Tôi đã chọn đúng `job executor`
- Pain này thật sự đủ đau và xảy ra đủ thường xuyên
- User sẽ đổi khỏi alternative hiện tại nếu có giải pháp tốt hơn
- AI thực sự tạo giá trị ở step tôi chọn
- User đủ tin kết quả AI để đưa vào workflow thật

### Bảng assumptions

| Assumption | Vì sao assumption này rủi ro? | Tôi đang có bằng chứng gì? | Cần validate bằng cách nào tiếp theo? |
|---|---|---|---|
| A1: Bác sĩ CĐHA là job executor đúng | Bệnh viện tuyến dưới đôi khi bác sĩ đa khoa đọc X-quang, không phải radiologist chuyên | Pipeline thiết kế UI cho người đọc ảnh trực tiếp; chưa phỏng vấn thật | Phỏng vấn 3–5 bác sĩ tại BV pilot: ai thực sự ngồi đọc và ký? |
| A2: Pain "miss + tốc độ" đủ đau trong ca trực | Có thể bác sĩ quen và chấp nhận workflow hiện tại | Giả định từ bối cảnh thiếu nhân lực CĐHA; chưa có số liệu nội bộ BV | Shadowing 1 ca trực; đo thời gian đọc/ca và hỏi "điều gì làm bạn mệt nhất?" |
| A3: Bác sĩ sẽ dùng AI overlay thay vì ignore | Alert fatigue — nếu false positive cao, bác sĩ tắt layer YOLO | Chưa có pilot; YOLO accuracy trên tập test nội bộ chưa ghi | Pilot 2 tuần: track % ca bác sĩ bật/tắt overlay; khảo sát sau pilot |
| A4: YOLO đủ tốt ở Execute trên ảnh X-quang ngực BV | Model train trên dataset khác → generalize kém; ảnh máy cũ/nhiễu cao | Pipeline đã chạy demo; chưa có metrics sensitivity/specificity trên data BV thật | Đánh giá trên 100+ ca có ground truth từ bác sĩ senior; báo cáo ROC |
| A5: Bác sĩ tin Med Gemma đủ để dùng draft báo cáo | Hallucination y khoa = rủi ro pháp lý; bác sĩ có thể chỉ tin detection, không tin text | Med Gemma mới; chưa test với bác sĩ thật | A/B: nhóm có/không có draft Gemma; đo thời gian viết báo cáo + tỷ lệ sửa draft |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A4 — YOLO chưa đủ chính xác trên data thực tế của bệnh viện.** Nếu sensitivity thấp (miss lesion thật), toàn bộ giá trị "giảm bỏ sót" sập — và bác sĩ sẽ quay về đọc thủ công ngay, không tin hệ thống. Đây là assumption phải validate **trước** khi đầu tư Med Gemma và UI hoàn chỉnh.

---

## Bước 11 — Share trong bàn (3')

### Mỗi người / mỗi nhóm chỉ nói 4 thứ

1. **Job executor của bạn là ai**
2. **Core JTBD của bạn là gì**
3. **Step đau nhất đang nằm ở đâu**
4. **AI leverage point + assumption rủi ro nhất là gì**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Câu JTBD này có đang lỡ nhét solution vào không?"**
2. **"Alternative hiện tại của user là gì, và tại sao họ chưa bỏ nó?"**
3. **"Pain mạnh nhất nằm ở bước nào trong workflow, có chắc AI giải tốt được không?"**
4. **"Assumption nào nếu sai thì cả hypothesis sẽ sập?"**

### Ghi nhanh sau khi nghe bàn phản biện

| Ý phản biện tôi nghe được | Nó chạm vào phần nào? | Tôi sẽ giữ / sửa gì? |
|---|---|---|
| "JTBD có nhét 'đánh dấu' — đó là feature YOLO không?" | Core JTBD | **Sửa** — giữ bản chốt "xác định vùng bất thường", bỏ hàm ý tool |
| "Bác sĩ tuyến dưới có phải radiologist không?" | Job executor | **Giữ** executor là "người đọc và ký ảnh" — nhưng validate A1: có thể là bác sĩ đa khoa |
| "Med Gemma ở Conclude — bác sĩ có tin draft không?" | AI leverage / A5 | **Giữ** YOLO là leverage chính; **giảm kỳ vọng** Gemma ở giai đoạn 1, chỉ draft không auto-ký |
| "False positive YOLO → bác sĩ tắt hệ thống" | A3, Execute | **Thêm validate:** ngưỡng confidence có thể điều chỉnh; ưu tiên precision ở giai đoạn pilot |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [x] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [x] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [x] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [x] Giữ nguyên `product hypothesis`
- [x] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> Giữ executor và JTBD — đã solution-free và khớp pipeline. Giữ leverage point ở Execute/YOLO. **Sửa nhẹ hypothesis:** nhấn mạnh giai đoạn 1 chỉ ship **detection overlay + confidence**, Med Gemma draft báo cáo là **giai đoạn 2** sau khi validate A4 (YOLO accuracy). Phản biện bàn về alert fatigue → thêm yêu cầu tunable confidence threshold trong pilot.

### Version cuối cùng tôi nộp

**Job executor:**  
> Bác sĩ chẩn đoán hình ảnh (hoặc bác sĩ được phân công đọc và ký phim X-quang) — người trực tiếp mở DICOM, đọc ảnh, xác nhận phát hiện và ký báo cáo.

**Core JTBD:**  
> Xác định chính xác và kịp thời các vùng bất thường trên phim X-quang trong ca đọc ảnh khi khối lượng ca cao — để đưa ra kết luận chẩn đoán đáng tin cậy.

**2 bước đau nhất trong workflow:**  
> **Execute** (quan sát và phát hiện tổn thương) và **Modify** (xác minh, loại false positive, chốt nhận định)

**AI leverage point chính:**  
> **Execute — YOLO** tự động phát hiện và đánh dấu vùng nghi ngờ (bbox + class + confidence) trên UI; bác sĩ đọc có hỗ trợ thay vì quét thủ công toàn phim.

**Product hypothesis:**  
> Nếu giúp bác sĩ CĐHA xác định vùng bất thường nhanh hơn ở bước Execute bằng YOLO overlay đáng tin (tunable confidence), họ sẽ chuyển từ đọc thủ công PACS sang đọc human-in-the-loop — vì giảm thời gian/ca và nguy cơ bỏ sót, mà bác sĩ vẫn giữ quyền quyết định cuối. Med Gemma (draft diễn giải) triển khai sau khi validate độ chính xác YOLO trên data BV thật.

**Assumption cần validate đầu tiên:**  
> **A4** — YOLO đạt sensitivity/specificity chấp nhận được trên tập ảnh X-quang ngực thực tế của bệnh viện pilot (ground truth từ bác sĩ senior).

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [x] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 bác sĩ CĐHA tại bệnh viện pilot để kiểm JS1/JS2/JS3 cái nào sát nhất.
- So sánh alternatives theo 3 tiêu chí: **nhanh hơn** (thời gian/ca), **tin hơn** (miss rate), **rẻ hơn** (so với CAD thương mại).
- Tự hỏi: **nếu không có Med Gemma, chỉ có YOLO bbox — project còn giá trị không?** → Có, nếu Execute pain đủ lớn; Gemma là accelerator, không phải core.
- Shadowing 1 ca trực để đo baseline thời gian Define → Conclude trước khi pilot.
