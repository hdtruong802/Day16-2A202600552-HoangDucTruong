---
artifact: 01 — Case Analysis
bai-tap: Lab 1 — Phân tích "tử huyệt" chiến lược
format: Cá nhân trước → share trong bàn → chốt verdict cuối
time: 20 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 1
---

# Lab 1 — Case Analysis / Phân tích "tử huyệt" chiến lược

**Case đã chọn:** NVIDIA — giả định dominance chip AI bị DeepSeek lộ "tử huyệt"  
**Người làm:** Hoàng Đức Trường (2A202600552)  
**Bàn / nhóm bàn:** _______________  
**Ngày:** 18/06/2026

> Đây là **file duy nhất** của Lab 1.  
> File này đồng thời đóng vai trò:
>
> - guide từng bước,
> - worksheet để điền trực tiếp,
> - và file nộp cuối cho người chấm.

Mục tiêu của bài này không phải kể lại "AI đã giết một công ty". Mục tiêu là chỉ ra, bằng bằng chứng thật:

1. **vì sao case đó bị tổn thương trước AI**
2. **điều gì đã thay đổi vĩnh viễn**
3. **và nếu rút một cảnh báo cho dự án của nhóm mình thì đó là gì**

Quy tắc xuyên suốt: **không có bằng chứng = không có nhận định.**

---

## Đầu ra bắt buộc

Người chấm cần thấy đủ 4 phần trong chính file này:

1. **3-5 bằng chứng chốt**
2. **4 nhận định bắt buộc**
3. **ghi chú sau khi share trong bàn**
4. **verdict cuối của cá nhân**

Nếu thiếu một trong bốn phần trên, bài sẽ bị xem là chưa hoàn chỉnh.

---

## Cách làm trong lớp (20 phút)

```text
2'  Chọn case
8'  Làm cá nhân: gom bằng chứng + viết 4 nhận định
7'  Share trong bàn: 90 giây / người + hỏi vặn lại
3'  Tự sửa verdict cá nhân sau thảo luận
```

---

## Bước 0 — Chọn case thật nhanh

Mặc định: **bạn tự chọn case của mình**.

### Một case phù hợp cần có 4 điều

- [x] Có một **AI shock** hoặc mốc đổi cục diện đủ rõ
- [x] Có thể tìm được ít nhất **3-5 bằng chứng công khai**
- [x] Có tác động đủ nhìn thấy được ở user / doanh thu / pricing / traffic / cổ phiếu / usage / vị thế cạnh tranh
- [x] Có thể trả lời câu hỏi: **"Điều gì đã thay đổi vĩnh viễn?"**

### Điền nhanh trước khi làm

- **Case / sản phẩm / công ty:** NVIDIA — chip AI, CUDA ecosystem, data center GPU
- **AI / platform / sản phẩm mới tạo áp lực:** DeepSeek V3 (12/2024) + DeepSeek R1 (20/01/2025) — open-source reasoning model, chi phí train/inference cực thấp
- **Vì sao tôi chọn case này?**  
  > Sự kiện DeepSeek → NVIDIA là AI shock lớn nhất đầu 2025, có đủ bằng chứng công khai (cổ phiếu, báo cáo tài chính, paper, phản ứng chính thức). Case cho thấy cả "tử huyệt chiến lược" (giả định brute-force GPU) lẫn cục diện thị trường mới — không phải câu chuyện "AI giết công ty" mà là "AI lộ điểm yếu trong narrative tăng trưởng".

### Nếu bí case, chọn 1 trong 6 case gợi ý này

| Case | Vì sao đáng phân tích | Một tín hiệu đáng chú ý |
|---|---|---|
| Chegg | entry point học tập đổi rất nhanh | 7,8M → 3,2M thuê bao |
| Stack Overflow | hiệu ứng mạng bị đảo chiều | câu hỏi mới giảm mạnh sau ChatGPT |
| Jasper | lớp vỏ dễ bị generic AI ép | định giá và tăng trưởng chậm lại sau ChatGPT |
| Tome | AI phổ thông "đủ tốt" làm phân khúc cũ yếu đi | nhiều đợt cắt giảm và pivot |
| Inflection / Pi | chatbot tiêu dùng bị ông lớn lấn át | đội ngũ chuyển sang Microsoft |
| Figma / Claude Design | rủi ro "đất thuê" khi platform bước xuống app layer | cổ phiếu Figma phản ứng tiêu cực khi Claude Design ra mắt |

> Nếu có case riêng rõ hơn, dùng case riêng.

---

## Bước 1 — Gom 3-5 bằng chứng chốt

Không cần chép lại mọi số. Chỉ giữ những bằng chứng đủ mạnh để đỡ toàn bộ lập luận của bạn.

### Tìm bằng chứng theo 4 cụm

1. **Case trước AI**
   Sản phẩm là gì, user là ai, họ trả tiền cho cái gì, case từng thắng nhờ gì.

2. **AI shock**
   Mốc Big Tech AI / platform AI / sản phẩm mới xuất hiện và đổi luật chơi.

3. **Tác động quan sát được**
   User, doanh thu, ARR, pricing, traffic, usage, cổ phiếu, sa thải, pivot.

4. **Cục diện mới của thị trường**
   Ai phản ứng tốt hơn, ai thay thế tốt hơn, entry point mới nằm ở đâu, phân khúc còn sống không.

### Ưu tiên nguồn thế nào?

| Mức ưu tiên | Loại nguồn | Ví dụ |
|---|---|---|
| 1 | Nguồn gốc | báo cáo tài chính, investor relations, pricing page, blog chính thức |
| 2 | Báo uy tín | Reuters, CNBC, Bloomberg, FT, TechCrunch |
| 3 | Dữ liệu công khai / tổng hợp | MacroTrends, Similarweb, Stack Overflow Survey, Sacra |

### Bảng bằng chứng chốt

| # | Bằng chứng / số liệu chốt | Vì sao số này quan trọng? | Nguồn |
|---|---|---|---|
| E1 | NVDA giảm **17%** trong 1 ngày (27/01/2025), mất gần **$600 tỷ** market cap — mức sụt giảm 1 ngày lớn nhất lịch sử Mỹ | **Triệu chứng** mạnh nhất của shock: thị trường reprice ngay giả định nhu cầu GPU không còn "chắc chắn tăng mãi" | [CNBC, 27/01/2025](https://www.cnbc.com/2025/01/27/nvidia-sheds-almost-600-billion-in-market-cap-biggest-drop-ever.html) |
| E2 | DeepSeek V3: **2,788 triệu GPU-hours H800**, chi phí final training run ~**$5,6 triệu**; R1 (20/01/2025) open-source MIT, benchmark ngang OpenAI o1 | Chứng minh **efficiency shock** — frontier AI có thể đạt được với capex thấp hơn nhiều so với narrative brute-force của Silicon Valley (dù con số $5,6M chỉ là final run, không phải toàn bộ R&D) | [DeepSeek-V3 paper / GitHub](https://github.com/deepseek-ai/DeepSeek-V3); [CNBC về R1](https://www.cnbc.com/2025/01/26/stock-market-news-for-jan-26-2025.html) |
| E3 | NVIDIA FY2024: doanh thu **$60,9 tỷ** (+126% YoY); data center chiếm phần lớn; ~**40%** doanh thu data center từ AI inference | Cho thấy NVIDIA **từng thắng** nhờ arms race compute của hyperscaler — và cũng là điểm fragile nếu capex training chậm lại | [NVIDIA Q4 FY2024 earnings release](https://nvidianews.nvidia.com/news/nvidia-announces-financial-results-for-fourth-quarter-and-fiscal-2024); [Earnings call transcript](https://longbridge.com/en/news/108383919) |
| E4 | NVIDIA official (27/01/2025): DeepSeek là *"excellent AI advancement"*, *"perfect example of Test Time Scaling"* — inference vẫn cần *"significant numbers of NVIDIA GPUs and high-performance networking"*; DeepSeek dùng H800 export-compliant | **Counter-evidence quan trọng**: moat hardware chưa gãy, nhưng NVIDIA buộc phải **pivot narrative** sang inference + full-stack thay vì chỉ "bán thêm GPU training" | [CNBC — NVIDIA statement](https://www.cnbc.com/2025/01/27/nvidia-calls-chinas-deepseek-r1-model-an-excellent-ai-advancement.html) |
| E5 | Sector ripple: Broadcom **-17%**, AMD **-6,4%**, Nasdaq **-3%**; DeepSeek app leo top App Store, vượt ChatGPT tạm thời | Shock lan sang **cả chuỗi giá trị AI**, không chỉ 1 công ty — entry point mới nằm ở model/API rẻ + open-source | [CNBC market wrap, 27/01/2025](https://www.cnbc.com/2025/01/26/stock-market-news-for-jan-26-2025.html) |

### 3 phát hiện ban đầu

Trước khi viết nhận định, ghi nhanh 3 dòng:

1. **Case này từng thắng nhờ...**  
   > CUDA lock-in + GPU là bottleneck duy nhất của AI scaling + hyperscaler đua capex training/inference mà chưa cần chứng minh ROI ngay lập tức.
2. **AI shock làm thay đổi...**  
   > Kỳ vọng "càng nhiều chip càng tốt" bị thách thức — software/architecture efficiency (MoE, test-time scaling) có thể thay thế một phần hardware spend.
3. **Dấu hiệu mạnh nhất cho thấy luật chơi mới là...**  
   > Buyer và investor bắt đầu hỏi ROI trước khi capex; open-source model rẻ làm áp lực margin lan từ model layer xuống infra narrative — dù DeepSeek vẫn chạy trên GPU NVIDIA.

---

## Bước 2 — Viết 4 nhận định bắt buộc

### Nhận định 1 — Trước AI, case này thắng nhờ giả định gì?

Gợi ý:

- Người dùng thuê sản phẩm này để làm gì?
- Giá trị lõi trước AI là gì?
- Họ thắng nhờ workflow, switching cost, brand, distribution, data hay một giả định hành vi nào?
- Job-to-be-done (công việc người dùng "thuê" sản phẩm làm hộ) là gì?

**Trả lời của tôi:**  
> Trước DeepSeek, NVIDIA thắng nhờ giả định: **AI progress = thêm compute** (scaling laws) → mọi hyperscaler và enterprise phải mua GPU NVIDIA để không tụt cuộc đua. Job-to-be-done của buyer (Microsoft, Meta, Google, AWS…): *"Train và deploy frontier AI nhanh nhất, với performance tốt nhất."* Moat nằm ở CUDA ecosystem, switching cost cao ở data center, và vị thế duy nhất cung cấp chip training hiệu năng cao. Doanh thu FY2024 $60,9B (+126%) phản ánh arms race capex mà buyer chấp nhận trả premium mà chưa cần hỏi chi tiết ROI.

**Bằng chứng đỡ nhận định này:** E3, E1

---

### Nhận định 2 — Kỳ vọng người dùng và luật chơi cạnh tranh đã đổi ở đâu?

#### Nhắc nhanh 7 Dịch chuyển Kỳ vọng

1. Làm xong giúp tôi
2. May đo cho tôi
3. Tự lo việc lặt vặt
4. Trả theo kết quả
5. Phản hồi ngay
6. Giao diện tự thay đổi
7. Thấu hiểu ngữ cảnh

#### Nhắc nhanh 5 Competitive Dynamics

- switching costs giảm
- data advantages tăng
- platform risk
- build-copy cycles tăng tốc
- GTM + distribution quan trọng hơn

**Shift kỳ vọng quan trọng nhất:** #4 Trả theo kết quả — buyer muốn model đủ tốt với chi phí hợp lý, không trả premium brute-force  
**Competitive dynamic quan trọng nhất:** Build-copy cycles tăng tốc + switching costs giảm (open-source + API rẻ)

**Trả lời của tôi:**  
> Kỳ vọng buyer đổi từ *"phải có nhiều GPU nhất"* sang *"phải có ROI rõ ràng nhất"*. DeepSeek R1 cho thấy reasoning model có thể đạt benchmark ngang OpenAI o1 với chi phí train/inference thấp hơn nhiều lần — làm giảm willingness-to-pay ở model layer và lan xuống infra. Luật chơi cạnh tranh: open-source MIT + API giá ~1/30 OpenAI làm switching cost giảm; build-copy cycle (distill, fine-tune từ DeepSeek) nhanh hơn kỳ vọng — player bán **efficiency** (DeepSeek) chiếm narrative thay vì player bán **raw FLOPs** (NVIDIA narrative cũ).

**Bằng chứng đỡ nhận định này:** E2, E5

---

### Nhận định 3 — Giả định nào không còn đúng nữa? Điều gì đã thay đổi vĩnh viễn?

Gợi ý:

- Switching cost cũ có từng giữ user ở lại không? Vì sao giờ không còn đủ?
- Entry point cũ của sản phẩm có còn tồn tại không, hay người dùng đã chuyển sang một điểm bắt đầu mới?
- Workflow cũ có còn được chấp nhận không, hay chuẩn mới là "làm xong giúp tôi / ngay trong nơi tôi đang làm việc"?
- "Thay đổi vĩnh viễn" không phải là giá cổ phiếu giảm; nó là **chuẩn mới trong đầu người dùng** hoặc **luật chơi mới của thị trường**.
- Phân khúc này còn tồn tại không? Nếu còn, nó đang được phục vụ theo cách khác ra sao?

**Điều đã thay đổi vĩnh viễn theo tôi là:**  
> **Không phải** "NVIDIA sắp chết" hay "cổ phiếu giảm 17%" — đó chỉ là triệu chứng (E1). **Thay đổi vĩnh viễn** là: (1) consensus thị trường không còn mặc định tin "frontier AI luôn cần capex GPU tăng theo cấp số nhân"; (2) **efficiency + ROI** trở thành tiêu chí song song với performance trong mọi quyết định AI capex; (3) entry point cạnh tranh dịch chuyển — buyer có thể bắt đầu từ open-source model rẻ rồi mới quyết định infra spend, thay vì mua GPU trước rồi build model. Phân khúc chip AI vẫn sống, nhưng được định giá theo **full-stack system** (training + inference + networking + software), không chỉ "monopoly training GPU".

**Bằng chứng đỡ nhận định này:** E2, E4

---

### Nhận định 4 — Case này còn cứu được không? Nếu có, phải đổi bằng cách nào?

Gợi ý:

- Nếu cứu được: họ phải đổi ở moat nào, workflow nào, distribution nào?
- Nếu không cứu được: vì sao đã quá muộn?
- So với một đối thủ phản ứng tốt hơn, họ chậm ở đâu?

**Verdict ban đầu của tôi:** Có nhưng phải đổi rất mạnh

**Trả lời của tôi:**  
> NVIDIA **còn cứu được** — moat hardware thật vẫn còn (E4: DeepSeek vẫn dùng H800, inference cần GPU NVIDIA). Nhưng phải đổi narrative và sản phẩm: pivot từ "chip training monopoly" sang **full-stack AI infrastructure** (Blackwell, networking, CUDA software, sovereign AI, enterprise inference). Rủi ro nếu chậm: buyer delay capex, đàm phán giá mạnh, growth premium bị squeeze. So với DeepSeek (phản ứng tốt ở model layer — efficiency narrative), NVIDIA phải sở hữu cả efficiency story ở system level, không chỉ raw performance. So với Google (TPU nội bộ), NVIDIA vẫn có distribution rộng hơn nhưng phải chứng minh ROI cho từng dollar capex.

**Bằng chứng đỡ nhận định này:** E3, E4, E1

---

## Tóm tắt cá nhân trước khi share trong bàn

Viết đúng 3 câu:

1. `Case này yếu đi vì...`
2. `Điều thay đổi vĩnh viễn là...`
3. `Verdict của tôi là...`

**Bản tóm tắt 3 câu của tôi:**  
1. Case này yếu đi vì giả định "brute-force GPU = cách duy nhất để thắng AI race" bị DeepSeek expose — không phải vì NVIDIA mất khả năng bán chip.  
2. Điều thay đổi vĩnh viễn là ROI + efficiency trở thành constraint song song với performance trong mọi quyết định AI capex — chuẩn mới trong đầu buyer/investor, không phải giá cổ phiếu 1 ngày.  
3. Verdict của tôi là NVIDIA vẫn dominant nhưng phải reframe từ "training chip monopoly" sang "full-stack AI infrastructure" — nếu không, margin và growth premium sẽ bị squeeze dù doanh thu ngắn hạn vẫn tăng.

---

## Bước 3 — Share trong bàn (7')

### Mỗi người chỉ nói 4 thứ trong 90 giây

1. **Case bạn chọn là gì**
2. **Bằng chứng mạnh nhất bạn có là gì**
3. **Điều gì đã thay đổi vĩnh viễn**
4. **Verdict của bạn**

### Nếu chưa biết hỏi ngược gì, dùng 4 câu này

1. **"Bằng chứng mạnh nhất cho nhận định đó là gì?"**
2. **"Điều gì ở đây là triệu chứng, còn điều gì là thay đổi vĩnh viễn?"**
3. **"Nếu switching cost từng cao, vì sao người dùng vẫn rời đi?"**
4. **"Platform mới hoặc đối thủ mới đã chiếm entry point ở đâu?"**

### Ghi nhanh khi nghe các bạn cùng bàn

| Người | Case | Bằng chứng mạnh nhất họ nêu | Điều họ cho là "thay đổi vĩnh viễn" | Verdict của họ |
|---|---|---|---|---|
| Bạn 1 | Chegg | Thuê bao 7,8M → 3,2M sau ChatGPT | Entry point học tập chuyển sang chat AI miễn phí | Không — quá muộn để giữ moat Q&A |
| Bạn 2 | Stack Overflow | Câu hỏi mới giảm mạnh sau ChatGPT | Developer hỏi AI trước, SO sau | Có nhưng phải pivot sang AI-assisted Q&A |
| Bạn 3 | Jasper | ARR/tăng trưởng chậm sau ChatGPT generic | Lớp "wrapper AI" không còn premium | Có nhưng phải đi sâu vertical/workflow |
| Bạn 4 | _(tôi)_ | DeepSeek train ~$5,6M vs capex tỷ USD; NVDA -$600B 1 ngày | ROI + efficiency = constraint mới cho AI capex | Có nhưng NVIDIA phải reframe full-stack |

### Sau khi cả bàn share xong, chốt 3 ý chung

**1. Bàn tôi thấy case nào có bằng chứng mạnh nhất? Vì sao?**  
> Chegg và Stack Overflow có bằng chứng usage/subscriber trực tiếp, dễ chứng minh "user rời đi". Case NVIDIA mạnh ở shock thị trường (E1) nhưng khó hơn vì phải tách triệu chứng (stock drop) vs thay đổi cấu trúc — và counter-evidence E4 (DeepSeek vẫn dùng NVIDIA chip) làm case phức tạp hơn các case "app layer bị thay thế".

**2. Có pattern nào lặp lại giữa nhiều case không?**  
Ví dụ: switching costs giảm, platform bước xuống app layer, user chuyển sang "làm xong giúp tôi", moat cũ quá mỏng…  
> Pattern chung: **generic AI "đủ tốt + rẻ hơn"** làm moat cũ (data Q&A, content gen, brute-force compute) mỏng đi; **entry point đổi** — user/buyer không bắt đầu từ workflow cũ nữa; **switching cost narrative** yếu khi open-source/API rẻ xuất hiện. NVIDIA khác ở chỗ moat hardware vẫn thật, nhưng **growth narrative** (không phải survival) bị shake.

**3. Một cảnh báo cho chính dự án của nhóm tôi là gì?**  
> Đừng xây moat trên giả định "user/buyer luôn trả premium vì thiếu lựa chọn rẻ" — khi AI làm solution generic đủ tốt, **ROI proof và entry point mới** quan trọng hơn feature list. Phải hỏi sớm: nếu open-source hoặc Big Tech làm "đủ tốt" ở layer của mình, giả định nào trong business model sẽ gãy?

---

## Bước 4 — Chốt lại verdict cá nhân sau thảo luận (3')

### Sau khi nghe bàn phản biện, verdict của tôi:

- [ ] Giữ nguyên
- [x] Đổi nhẹ
- [ ] Đổi mạnh

### Vì sao tôi giữ / đổi verdict?

> Bàn hỏi: *"DeepSeek vẫn dùng NVIDIA chip — vậy NVIDIA có thật sự 'yếu' không?"* → Tôi đổi nhẹ framing: "yếu" không phải "sắp chết" mà là **giả định chiến lược bị expose** — shock ở narrative & capex cycle, chưa phải displacement ngay. Recovery cổ phiếu sau vài tuần không negate shift trong buyer mindset (E4 cho thấy NVIDIA tự pivot sang inference). Giữ verdict "Có nhưng phải đổi rất mạnh", thêm nhấn mạnh: thay đổi vĩnh viễn nằm ở **cách thị trường định giá và buyer justify capex**, không phải mất moat hardware ngay lập tức.

### Verdict cuối cùng của tôi (phiên bản nộp)

**Case này tổn thương trước AI vì:**  
> DeepSeek R1/V3 làm lộ "tử huyệt" trong giả định NVIDIA: rằng frontier AI **luôn** cần capex GPU tăng theo kiểu brute-force, và buyer sẽ tiếp tục trả premium mà không hỏi ROI. Shock lan sang cả sector (E5) vì investor reprice toàn bộ AI infra narrative — dù NVIDIA vẫn bán chip cho DeepSeek (E4).

**Điều thay đổi vĩnh viễn là:**  
> Chuẩn mới: **efficiency + ROI** là constraint song song với performance khi quyết định AI capex. Entry point cạnh tranh dịch chuyển sang model/API rẻ trước, infra spend sau. NVIDIA vẫn sống ở phân khúc chip AI nhưng được định giá theo full-stack system (training + inference + networking), không còn premium "monopoly training" vô điều kiện.

**Nếu phải rút 1 bài học cho dự án của nhóm mình, tôi rút ra:**  
> Moat xây trên giả định "buyer không có lựa chọn rẻ" sẽ bị AI commodity hóa nhanh. Phải validate sớm: workflow nào user **thực sự trả tiền** khi đã có open-source/generic AI đủ tốt? Và thiết kế sản phẩm sao cho value nằm ở layer khó bị copy (data, distribution, vertical workflow) — không phải chỉ "wrap" model.

---

## Checklist trước khi nộp

- [x] Tôi đã chọn ít nhất 3 bằng chứng chốt có nguồn.
- [x] Mỗi nhận định đều chỉ vào ít nhất 1 bằng chứng.
- [x] Tôi đã ghi lại phần share trong bàn.
- [x] Tôi đã viết verdict cuối sau thảo luận.

---

## Nếu còn thời gian / làm về nhà

### Đối thủ phản ứng tốt hơn (so sánh ngắn)

| Đối thủ | Phản ứng gì tốt hơn NVIDIA? |
|---|---|
| **DeepSeek** | Chiếm narrative **efficiency** ở model layer — open-source MIT, API rẻ, app top chart (E2, E5) |
| **Google (TPU)** | Vertical integration — tự optimize hardware+software, không phụ thuộc narrative "mua thêm GPU" |

### Nếu tôi là PM NVIDIA trong 6 tháng đầu sau AI shock, tôi sẽ làm gì đầu tiên?

1. **Reframe investor narrative** ngay: publish case study ROI inference (40% data center revenue đã từ inference — E3) + DeepSeek là minh chứng test-time scaling **tăng** GPU demand inference, không chỉ giảm training.
2. **Product**: accelerate Blackwell + networking bundle — bán "tokens/$" system-level, không bán chip đơn lẻ.
3. **Competitive intel**: track open-source adoption (DeepSeek distill) → xác định segment nào vẫn cần H100/B200 vs có thể dùng chip rẻ hơn.

### Case này yếu vì expectation shift, competitive dynamics, hay cả hai?

**Cả hai cùng lúc.** Expectation shift (#4 Trả theo kết quả): buyer muốn ROI rõ. Competitive dynamics: build-copy cycle tăng tốc (open-source), switching cost giảm (API rẻ) — làm pressure lan từ model layer xuống infra pricing narrative.
