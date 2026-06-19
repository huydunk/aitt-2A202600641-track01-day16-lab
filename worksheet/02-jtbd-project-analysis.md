---
artifact: 02 — JTBD Project Analysis
bai-tap: Lab 2 — Dùng JTBD để soi lại dự án nhóm
format: Theo nhóm dự án → share trong bàn → chốt hypothesis cuối
time: 25 phút trên lớp
nop-cuoi: Có — đây là file nộp cuối của Lab 2
companion-reference: Strategyn_JTBD_Playbook.pdf (giảng viên gửi kèm)
---

# Lab 2 — JTBD Project Analysis / Dùng JTBD để soi lại dự án nhóm

**Tên dự án / sản phẩm:** Opstream — Tóm tắt ca trực ([C2-App-071](https://github.com/AI20K-Build-Cohort-2/C2-App-071))  

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

- [x] **1 nhóm người dùng chính** — lễ tân / giám sát ca tại boutique hotel
- [x] **1 hoàn cảnh / tình huống rõ** — ngay lúc bàn giao ca (đầu/cuối ca)
- [x] **1 job cốt lõi** — nắm nhanh tình hình ca trước để vào ca không sót việc
- [x] **1 workflow đủ cụ thể để vẽ ra được** — tra PMS → chép note → truyền miệng

### Điền nhanh trước khi làm

- **Dự án của nhóm tôi là:** Opstream — tự động tạo tóm tắt bàn giao ca trực cho lễ tân khách sạn boutique, kéo dữ liệu PMS qua API và sinh tóm tắt có cấu trúc bằng AI trong <30s.
- **Lát cắt tôi chọn để phân tích hôm nay là:** lễ tân/giám sát ca tại boutique hotel phố cổ Hà Nội, đúng thời điểm **bàn giao ca**, cần nắm nhanh việc chưa xong + ngoại lệ cần xử lý — nhất là khi một người ôm nhiều property.
- **Vì sao tôi chọn lát cắt này:**  
  > đây là khoảnh khắc đau nhất và lặp lại mỗi ca: mất 15–20 phút chỉ để tổng hợp thông tin, dễ bỏ sót ETA khách / transfer chưa đặt / yêu cầu đặc biệt, và rủi ro nhân lên khi quản lý 5 property cùng lúc.

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
   > việc bàn giao ca thủ công tốn 15–20 phút mỗi ca và dễ bỏ sót thông tin quan trọng (ETA khách, transfer, yêu cầu đặc biệt, việc còn dang dở) giữa các ca.

2. **Người dùng chính hiện nhóm đang nhắm tới là ai?**  
   > lễ tân và giám sát ca tại boutique hotel phố cổ Hà Nội (phụ: quản lý vận hành theo dõi nhiều property cùng lúc).

3. **Hiện tại người dùng đó đang giải quyết vấn đề này bằng cách nào?**  
   > tra thủ công từng màn hình PMS, chép tay note, rồi truyền miệng cho người vào ca sau.

---

## Bước 2 — Viết `Market Context`

Ở đây chưa cần solution. Chỉ cần bối cảnh thị trường đủ để hiểu:
**ai đang gặp chuyện gì, trong hoàn cảnh nào, và vì sao bây giờ đáng giải.**

### Trả lời 4 câu ngắn

1. **Ai đang gặp vấn đề này?**  
   > lễ tân & giám sát ca ở boutique hotel phố cổ Hà Nội — nơi nhân sự mỏng, một người ôm nhiều đầu việc, và nhiều khi trông cùng lúc vài property.

2. **Vấn đề xuất hiện trong hoàn cảnh nào?**  
   > đúng lúc giao/nhận ca (và giờ cao điểm check-in/check-out), khi phải nhanh chóng hiểu chuyện gì đã xảy ra ở ca trước và còn việc gì chưa xong.

3. **Hiện tại họ đang dùng giải pháp thay thế nào?**  
   > làm thủ công: mở từng màn hình PMS, ghi note tay, truyền miệng; một số nơi chắp vá thêm Excel/Zalo/sổ giao ca.

4. **Vì sao đây là thời điểm đáng giải?**  
   > LLM giờ đủ rẻ & nhanh để tóm tắt có cấu trúc trong <30s, PMS đã có API để kéo dữ liệu, và xu hướng một quản lý/lễ tân lo nhiều property khiến rủi ro sót thông tin tăng mạnh.

### Tóm tắt market context trong 3-4 dòng

> Ở các boutique hotel phố cổ Hà Nội, lễ tân phải bàn giao ca trong điều kiện nhân sự mỏng và dữ liệu nằm rải rác khắp PMS. Cách làm thủ công (tra màn hình + note tay + truyền miệng) vừa chậm vừa dễ sót, và càng rủi ro khi một người lo nhiều property.  
> Bây giờ là thời điểm đáng giải vì PMS đã mở API và LLM đủ rẻ/nhanh để biến mớ dữ liệu rời rạc đó thành một bản tóm tắt ca tập trung vào hành động.

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

- **Job executor của dự án này là:** lễ tân / giám sát ca tại boutique hotel — ở đúng vai trò **bàn giao ca**, gồm cả người giao ca lẫn người nhận ca (hai phía của cùng một khoảnh khắc).
- **Vì sao tôi tin đây là người trực tiếp "thuê" giải pháp để làm job:**  
  > chính lễ tân/giám sát ca là người **trực tiếp tạo ra và đọc** bản giao ca để vận hành — không phải chủ khách sạn (người trả tiền) hay quản lý cấp cao (người ảnh hưởng). Họ là người chịu hậu quả trực tiếp nếu sót việc, nên là người "thuê" một cách bàn giao tốt hơn. *(Lưu ý: chọn "cả hai phía" → cần validate sau xem bên giao hay bên nhận mới là bên đau nhất.)*

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

- [ ] Nếu bỏ tool hiện tại đi, job này vẫn còn tồn tại
- [ ] Trong câu không có tên sản phẩm, AI, chatbot, app, màn hình
- [ ] Câu đang mô tả **điều user muốn hoàn thành**, không phải thứ product đang làm

### Bản nháp 1

**Core JTBD bản nháp:**  
> Vào ca / giao ca mà vẫn nắm chắc toàn bộ việc còn dang dở và tình huống cần xử lý của ca trước, đủ nhanh để không bỏ sót khách nào.

### Gạch bỏ từ solution nếu có

- Các từ solution tôi đang lỡ nhét vào câu: *(không có — câu đã không nhắc tới AI / tóm tắt / app / màn hình / một nút bấm)*

### Bản chốt

**Core JTBD cuối cùng:**  
> **Luôn nắm được việc gì cần xử lý tiếp và đảm bảo nó được xử lý đúng**, trong **suốt ca trực** (từ lúc nhận ca đến lúc giao ca), để **không việc nào hay khách nào bị rơi**.

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
| JS1 | Tôi vừa vào ca tối, ca trước để lại một mớ note tay rời rạc | nắm ngay việc nào còn dang dở + ngoại lệ cần xử lý | bắt đầu phục vụ khách mà không bỏ sót ai | job đau nhất nằm ở lúc **tiếp nhận ca** |
| JS2 | Khách sắp check-out nhưng còn số dư công nợ / transfer chưa đặt | thấy ngay đúng ca này cần thu / xử lý gì kèm mã đặt phòng | không để thất thoát tiền hoặc lỡ dịch vụ của khách | job có **hệ quả tiền bạc**, không chỉ là thông tin |
| JS3 | Giữa ca cao điểm, nhiều việc ập đến cùng lúc và tôi không chắc nên xử lý gì trước | được gợi ý nên làm việc nào tiếp theo và tạo/giao việc ngay từ đó | xử lý đúng việc quan trọng nhất trước, không bị khựng giữa ca | job không chỉ là **biết**, mà là **quyết định & hành động** ngay trong ca (đúng vai lễ tân, không phải GM) |

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
| Note tay + truyền miệng khi giao ca | ghi & truyền việc cần biết cho ca sau | linh hoạt, không cần công cụ, nhanh khi ít việc | dễ sót, không đầy đủ, phụ thuộc trí nhớ, không truy vết được | thấp |
| Tra trực tiếp từng màn hình PMS | lấy dữ liệu gốc (check-in/out, dịch vụ, thanh toán) | dữ liệu chính xác & đầy đủ nguồn | chậm 15–20', rải rác nhiều màn hình, lẫn boilerplate OTA, phải tự tổng hợp | thấp–trung (vẫn buộc dùng PMS) |
| Excel / sổ giao ca / nhóm Zalo | lưu & chia sẻ note có cấu trúc nhẹ, để lại lịch sử | chia sẻ được, có dấu vết | nhập tay thủ công, không đồng bộ PMS, dễ lỗi thời / sai sót | thấp |

### Kết luận nhanh

**Nếu project của tôi biến mất hôm nay, user nhiều khả năng sẽ quay về:**  
> quay lại tra PMS thủ công từng màn hình rồi note tay + truyền miệng (Alt 1 + Alt 2) — tức quay về đúng cái workflow 15–20 phút/ca đang đau.

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
| Define | xác định ca này cần nắm/bàn giao những gì (việc dang dở, khách đặc biệt, ngoại lệ) | kinh nghiệm cá nhân, tự nhớ | không có chuẩn — mỗi người định nghĩa "cần biết" một kiểu | Med |
| Locate | tìm dữ liệu đó nằm ở đâu | mở từng màn hình PMS + note ca trước + Zalo | rải rác nhiều nơi, tốn phần lớn thời gian | **High** |
| Prepare | gom & làm sạch dữ liệu (lọc boilerplate OTA, tính số dư công nợ) | chép tay, tính nhẩm | thủ công, dễ sai, mất công nhất | **High** |
| Confirm | kiểm chéo đã đủ/đúng chưa (đối soát thanh toán, ETA, transfer) | tự rà lại | dễ sót đúng mục quan trọng | Med–High |
| Execute | thực sự bàn giao / tiếp nhận ca | truyền miệng + đưa note tay | phụ thuộc người nói, thông tin rơi rụng | Med |
| Monitor | theo dõi việc carry-over trong ca có được xử lý không | trí nhớ / nhìn note | dễ quên việc tồn | Med |
| Modify | cập nhật khi có thay đổi (đổi ETA, hủy phòng) | sửa note tay | rời rạc, không đồng bộ | Low–Med |
| Conclude | chốt còn gì chuyển tiếp khi hết ca | lại viết note cho ca sau | lặp lại vòng lặp thủ công | Med |

### Chốt 2 bước đau nhất

**Bước đau nhất #1:** Locate — đi tìm dữ liệu rải rác khắp các màn hình PMS  
**Bước đau nhất #2:** Prepare — gom & làm sạch dữ liệu rồi tự tổng hợp (lọc OTA, tính số dư)

**Vì sao đây là nơi đáng chú ý nhất:**  
> phần lớn 15–20 phút mỗi ca cháy ở Locate + Prepare: đi nhặt dữ liệu khắp nơi rồi tự tổng hợp/làm sạch bằng tay. Đây cũng chính là nơi **dễ sót nhất** (ETA, transfer, số dư), và là loại việc **máy làm tốt & nhất quán hơn người** — đúng chỗ đáng để AI chen vào.

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
| Prepare + Confirm | gom & làm sạch dữ liệu PMS rải rác thành **bản tóm tắt ca tập trung hành động** (ngoại lệ, bất thường, tiền cần thu, việc carry-over), sắp theo mức ưu tiên | tổng hợp ngôn ngữ tự nhiên + xử lý text lộn xộn / boilerplate OTA + **ưu tiên việc** — khó hard-code | hallucinate / sai số / **bỏ sót mục quan trọng** → mất niềm tin. *Giảm thiểu: số liệu tính trong code, AI chỉ diễn đạt & ưu tiên.* |
| Confirm → Execute / Monitor | **trợ lý chat gợi ý hành động tiếp theo** và cho **tạo/giao việc** ngay từ một dòng tóm tắt | suy luận theo ngữ cảnh nhiều dữ kiện để gợi ý "nên làm gì tiếp" là việc khó hard-code, hợp với LLM | gợi ý sai / lệch ngữ cảnh thực → lễ tân làm sai việc hoặc mất tin. *Giảm thiểu: gợi ý gắn với dữ liệu thật + người quyết định cuối.* |

### Kết luận nhanh

**AI leverage point quan trọng nhất của dự án tôi là:**  
> biến dữ liệu PMS rải rác thành **bản tóm tắt + gợi ý hành động có ưu tiên**, rồi cho **tạo/giao việc** ngay từ đó — tức AI vừa giúp **hiểu tình hình** vừa giúp **quyết định việc cần làm tiếp** trong ca. (Đây là lý do Opstream là *trợ lý cho lễ tân*, không chỉ là công cụ tóm tắt.)

**Vì sao không phải ở bước khác:**  
> Locate (lấy dữ liệu) là việc của **API/tích hợp**, không cần AI. Giá trị AI nằm ở khâu **tổng hợp → ưu tiên → gợi ý hành động** — chỗ con người vừa chậm (15–20') vừa dễ sót và dễ phân vân nên làm gì trước.

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

> Nếu chúng ta giúp **lễ tân/giám sát ca** biết **việc gì cần làm tiếp và xử lý đúng** trong suốt ca — bằng **tóm tắt tập trung hành động + trợ lý gợi ý + tạo/giao việc** (số liệu tính sẵn trong code) — thì họ sẽ bỏ **tra PMS thủ công + note tay + tự phán đoán** để dùng **Opstream**, vì **xử lý đúng việc quan trọng nhanh hơn và ít sót hơn** trong cả ca.

### Tín hiệu sớm nếu hypothesis này đúng

1. Thời gian nắm tình hình đầu ca giảm rõ rệt (từ 15–20' xuống còn vài phút), đo được trên ca thật.
2. Lễ tân **chủ động dùng Opstream trong ca** (mở đầu ca + hỏi trợ lý + tạo việc từ tóm tắt) thay vì tra PMS, và số vụ sót (ETA / transfer / thu thiếu) giảm.

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
| A1 — chọn đúng job executor (cả giao lẫn nhận) | có thể chỉ một phía thực sự đau, "cả hai" làm loãng trọng tâm | mới chỉ quan sát workflow, chưa đo | shadow/phỏng vấn cả người giao và người nhận ca |
| A2 — pain đủ đau & đủ thường xuyên | ca vắng việc thì note tay là đủ, không cần tool | con số 15–20'/ca từ mô tả nội bộ | bấm giờ thực tế trên nhiều ca / nhiều property |
| A3 — user sẽ bỏ note tay nếu có cái tốt hơn | thói quen + ngại đổi, switching cost thấp cả hai chiều | chưa có | thử 1–2 property, xem có dùng đều sau 2 tuần không |
| A4 — AI thật sự tạo giá trị ở Prepare/Confirm **và ở gợi ý hành động** | nếu tóm tắt/gợi ý sót/sai thì tệ hơn làm tay | demo nội bộ chạy được | so tóm tắt + gợi ý của AI vs bản người làm trên ca thật, đo độ sót & độ hữu ích của gợi ý |
| A5 — user đủ tin AI để đưa vào việc thật | chỉ 1 lần sai số / sót khách là mất niềm tin | đã thiết kế "số liệu tính trong code" để giảm rủi ro | đo tỉ lệ lễ tân hành động theo tóm tắt mà **không** kiểm lại PMS |

### Assumption nguy hiểm nhất nếu tôi đang sai

> **A5 (niềm tin) — gắn chặt A4.** Nếu AI bỏ sót/đọc sai một mục quan trọng (khách VIP, transfer, thu thiếu) dù chỉ một lần, lễ tân sẽ quay lại tra PMS thủ công "cho chắc" → mất luôn lợi thế <30s và cả hypothesis sập. Vì vậy độ tin cậy + chống-sót quan trọng hơn cả tốc độ.

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
| | | |
| | | |
| | | |

---

## Bước 12 — Chốt version cuối sau thảo luận

### Sau khi nghe phản biện, tôi thay đổi gì?

- [ ] Giữ nguyên `job executor`
- [ ] Sửa `job executor`
- [ ] Giữ nguyên `core JTBD`
- [ ] Sửa `core JTBD`
- [ ] Giữ nguyên `AI leverage point`
- [ ] Sửa `AI leverage point`
- [ ] Giữ nguyên `product hypothesis`
- [ ] Sửa `product hypothesis`

### Vì sao tôi giữ / sửa?

> _______________________________________________  
> _______________________________________________

### Version cuối cùng tôi nộp

**Job executor:**  
> lễ tân / giám sát ca tại boutique hotel, ở vai trò bàn giao ca (cả người giao lẫn người nhận).

**Core JTBD:**  
> luôn nắm được việc gì cần xử lý tiếp và đảm bảo nó được xử lý đúng, suốt ca trực (từ nhận ca đến giao ca), để không việc nào hay khách nào bị rơi.

**2 bước đau nhất trong workflow:**  
> Locate (đi tìm dữ liệu rải rác khắp PMS) và Prepare (gom + làm sạch + tự tổng hợp).

**AI leverage point chính:**  
> AI vừa **tổng hợp tình hình thành tóm tắt tập trung hành động** (Prepare/Confirm) vừa **gợi ý việc cần làm tiếp + cho tạo/giao việc** (trợ lý chat) — số liệu tính trong code, AI lo diễn đạt / ưu tiên / gợi ý. Locate là việc của API, không phải AI.

**Product hypothesis:**  
> nếu giúp lễ tân biết việc cần làm tiếp và xử lý đúng suốt ca bằng tóm tắt + trợ lý gợi ý + tạo việc, họ sẽ bỏ tra PMS thủ công + note tay + tự phán đoán để dùng Opstream, vì xử lý đúng việc quan trọng nhanh hơn và ít sót hơn.

**Assumption cần validate đầu tiên:**  
> A5 — user có đủ tin tóm tắt AI để hành động mà không kiểm lại PMS không (vì chỉ một lần sót khách/sai số là mất niềm tin và quay lại làm tay).

---

## Checklist trước khi nộp

- [x] Tôi đã khoanh đúng 1 lát cắt cụ thể của dự án.
- [x] Tôi đã phân biệt được `job executor` với buyer / influencer.
- [x] `Core JTBD` của tôi không nhét solution vào câu.
- [x] Tôi đã viết đủ 3 `job stories`.
- [x] Tôi đã điền `JTBD lite map` và khoanh ra 2 bước đau nhất.
- [x] Tôi đã chỉ ra `AI leverage point` thay vì nhảy thẳng vào feature list.
- [x] Tôi đã ghi rõ `assumptions to validate`.
- [ ] Tôi đã sửa version cuối sau khi share trong bàn.

---

## Nếu còn thời gian / làm về nhà

- Phỏng vấn nhanh 1 người dùng thật để kiểm xem `job story` nào là sát nhất.
- So sánh `current alternatives` với project của nhóm theo 3 tiêu chí: nhanh hơn, rẻ hơn, tin hơn.
- Tự hỏi lại một câu khó: **nếu không dùng AI, project này còn tạo giá trị không?**
- Nếu câu trả lời là "không", hãy xem lại liệu nhóm đang giải **job thật** hay chỉ đang tìm chỗ để nhét AI.
