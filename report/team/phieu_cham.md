# Phiếu chấm hội đồng Gate 2a

## Phần 1: Phiếu chấm của nhóm HAHAHA (Hội đồng) chấm nhóm TruongConNamDinh

Nhóm số n chấm nhóm số n + 1; nhóm cuối chấm nhóm 1. Chấm theo bằng chứng trong hồ sơ, không theo cách trình bày: một đề xuất No-go có lý do bằng số được điểm cao hơn một đề xuất Go bỏ qua con số bất lợi.

- Nhóm chấm (hội đồng): HAHAHA (L3A)
- Nhóm được chấm: TruongConNamDinh (L3A)
- Bản hồ sơ dùng để chấm: [commit `618b74a`](https://github.com/emvuthosan/K5-L3A-DAY13-TruongConNamDinh-LaunchEconomics/commit/618b74af2946c9d6ab3080c1c3e0fb000920a280)

| Tiêu chí | 0 điểm | 5 điểm | 10 điểm | Điểm | Lý do (có số) |
| --- | --- | --- | --- | ---: | --- |
| Đề xuất khớp bằng chứng | Mâu thuẫn với số của chính nhóm | Khớp nhưng bỏ qua một con số bất lợi | Khớp, nêu cả con số bất lợi và cách xử lý | **10** | Đề xuất Go có điều kiện dựa trên chi phí **4.599 đ/việc thành công (0,38×, simulated)** sau khi cộng cố định. Nhóm nêu cả kịch bản xem lại 100% **11.743–12.415 đ (0,98–1,03×, simulated)** và power chỉ **0,64** nếu hiệu ứng thật là 5 điểm. Bốn điều kiện có vai trò và ngày kiểm tra, trong đó có đo phút làm thật và giảm xem lại theo bậc. [Hồ sơ launch](https://github.com/emvuthosan/K5-L3A-DAY13-TruongConNamDinh-LaunchEconomics/blob/618b74af2946c9d6ab3080c1c3e0fb000920a280/report/team/ho_so_launch_v0.md), [bảng chi phí](https://github.com/emvuthosan/K5-L3A-DAY13-TruongConNamDinh-LaunchEconomics/blob/618b74af2946c9d6ab3080c1c3e0fb000920a280/report/team/bang_chi_phi.md) |
| Số giả lập và phạm vi | Không nhãn; phạm vi “mọi yêu cầu” | Có nhãn hoặc có thu hẹp phạm vi | Nhãn ở mọi số giả lập; phạm vi thu hẹp có lý do bằng số | **5** | Pilot giới hạn `noi_dia` và `hang_nang` tại **6 depot**, với chi phí lần lượt **0,22×** và **0,69×** mức nhân viên tự làm (simulated). Loại `quoc_te` (**1,88×**) và `doi_tac` (**0,85×** và có điều khoản riêng). Các bảng chính có nhãn, nhưng mục 4 báo cáo nhóm còn ghi **6.901.220 đ** cho giới hạn 2 lần chạy mà thiếu nhãn `simulated` ở câu chứa số này. B3 xác nhận khoản này gồm chi phí giả lập. [Pilot plan](https://github.com/emvuthosan/K5-L3A-DAY13-TruongConNamDinh-LaunchEconomics/blob/618b74af2946c9d6ab3080c1c3e0fb000920a280/report/team/pilot_plan.yaml), [báo cáo nhóm](https://github.com/emvuthosan/K5-L3A-DAY13-TruongConNamDinh-LaunchEconomics/blob/618b74af2946c9d6ab3080c1c3e0fb000920a280/report/team/group_report.md), [B3](https://github.com/emvuthosan/K5-L3A-DAY13-TruongConNamDinh-LaunchEconomics/blob/618b74af2946c9d6ab3080c1c3e0fb000920a280/report/team/bang_chi_phi.md#b3--giới-hạn-chạy-lại-có-thật-sự-rẻ-hơn) |
| Pilot ra được quyết định | Không đối chứng hoặc thiếu cỡ mẫu | Đủ cỡ mẫu, luật dừng chung chung | Tách được tác động, đủ mẫu, luật dừng có ngưỡng, thời hạn, người có quyền dừng | **5** | Có đối chứng đồng thời, ngẫu nhiên theo nhân viên **20 + 20**, MDE **6 điểm** và ba luật dừng có ngưỡng, thời hạn và người phụ trách. Phép tính đạt khoảng **859 yêu cầu hiệu dụng/nhánh** nếu thu đủ **299 yêu cầu/người**, tức **5.980 yêu cầu thực/nhánh**. YAML chỉ đo chỉ số chính từ bước 50% và ghi mỗi bước một tuần. Thu đủ mẫu hai nhánh trong 7 ngày cần khoảng **1.709 yêu cầu đủ điều kiện/ngày**, cao hơn **1.500/ngày** của toàn hệ thống. Cần ghi rõ có duy trì bước 50% sau tuần rollout hay không, sản lượng ở 6 depot và ngày khóa tuyển mẫu để còn theo dõi mở lại đủ 7 ngày. [Pilot plan](https://github.com/emvuthosan/K5-L3A-DAY13-TruongConNamDinh-LaunchEconomics/blob/618b74af2946c9d6ab3080c1c3e0fb000920a280/report/team/pilot_plan.yaml), [quy mô dữ liệu](https://github.com/emvuthosan/K5-L3A-DAY13-TruongConNamDinh-LaunchEconomics/blob/618b74af2946c9d6ab3080c1c3e0fb000920a280/docs/du_lieu_va_cong_thuc.md) |
| **Tổng** | | | | **20 / 30** | |

**Quyết định của hội đồng (đề xuất để duyệt):** Go có điều kiện cho kế hoạch pilot.

**Lý do:** Hồ sơ giải thích vì sao chọn hai loại yêu cầu và nêu rõ trường hợp lợi thế chi phí biến mất. Trước khi khởi động, nhóm cần bổ sung nhãn `simulated` ở số còn thiếu và chứng minh lịch ở bước 50% đủ để thu 5.980 yêu cầu thực mỗi nhánh, theo dõi mở lại đủ 7 ngày và ra quyết định vào 05/01/2027. Nếu sản lượng thực tế ở 6 depot thấp hơn yêu cầu, ghi lại thời gian thu mẫu và điều chỉnh ngày quyết định trước khi chạy.

**Một câu hỏi cho đội trình:** Từ khi rollout đạt 50%, sáu depot dự kiến có bao nhiêu yêu cầu `noi_dia` và `hang_nang` đủ điều kiện mỗi ngày, và ngày nào phải khóa tuyển mẫu để thu đủ 5.980 yêu cầu thực mỗi nhánh đồng thời theo dõi mở lại đủ 7 ngày trước 05/01/2027?

**Câu trả lời của đội trình (ghi lại tại buổi):** Sáu depot có khoảng 614 yêu cầu noi_dia + hang_nang mỗi ngày, tức khoảng 307 yêu cầu mỗi nhánh. Để mọi yêu cầu được theo dõi mở lại đủ 7 ngày trước 05/01/2027, phải khóa tuyển mẫu chậm nhất hết ngày 28/12/2026. Nhưng đến ngày đó mỗi nhánh mới có khoảng 4.296 yêu cầu, chưa đủ 5.980. Như vậy, với lịch hiện tại không thể đạt cả hai điều kiện cùng lúc.

---

## Phần 2: Phiếu đánh giá tiếp nhận từ Hội đồng phản biện (MyBloodyValentine chấm HAHAHA)

**Trạng thái: Đã chấm theo hồ sơ và ghi nhận câu trả lời phản biện do nhóm được chấm cung cấp.** Đây là đánh giá của Bùi Quang Hiếu (nhóm MyBloodyValentine) đối với nhóm HAHAHA. Hồ sơ đối chiếu tại commit [`5b017aa`](https://github.com/Ein05/K5-L3A-DAY13-HAHAHA-LaunchEconomics/tree/5b017aa53c93140121523a8e2501c48aa34ba560).

- Nhóm chấm (hội đồng): MyBloodyValentine — Bùi Quang Hiếu (chấm cá nhân).
- Nhóm được chấm: HAHAHA.

| Tiêu chí | 0 điểm | 5 điểm | 10 điểm | Điểm | Lý do (có số) |
| --- | --- | --- | --- | ---: | --- |
| Đề xuất khớp bằng chứng | Mâu thuẫn với số của chính nhóm | Khớp nhưng bỏ qua một con số bất lợi | Khớp, nêu cả con số bất lợi và cách xử lý | 10 | [Hồ sơ launch](https://github.com/Ein05/K5-L3A-DAY13-HAHAHA-LaunchEconomics/blob/5b017aa53c93140121523a8e2501c48aa34ba560/report/team/ho_so_launch_v0.md) đề xuất Go có điều kiện, loại `quoc_te` (22.515 đ/việc = 1,88× mức nhân viên tự làm); nêu kịch bản xem lại 100% có thể lên 12.414 đ/việc (1,03×) và điều kiện giảm xem lại. |
| Số giả lập và phạm vi | Không nhãn; phạm vi "mọi yêu cầu" | Có nhãn hoặc có thu hẹp phạm vi | Nhãn ở mọi số giả lập; phạm vi thu hẹp có lý do bằng số | 5 | Phạm vi `noi_dia` + `hang_nang` có lý do bằng số; nhiều khoản đã ghi `simulated`. Tuy nhiên, các giá trị 4.723 đ và 4.346 đ ở [bảng B1](https://github.com/Ein05/K5-L3A-DAY13-HAHAHA-LaunchEconomics/blob/5b017aa53c93140121523a8e2501c48aa34ba560/report/team/bang_chi_phi.md) vẫn bao gồm chi phí thời gian giả lập nhưng không có nhãn tại dòng, nên chưa đạt mức 10 về nhãn ở mọi số giả lập. |
| Pilot ra được quyết định | Không đối chứng hoặc thiếu cỡ mẫu | Đủ cỡ mẫu, luật dừng chung chung | Tách được tác động, đủ mẫu, luật dừng có ngưỡng, thời hạn, người có quyền dừng | 10 | [Pilot plan](https://github.com/Ein05/K5-L3A-DAY13-HAHAHA-LaunchEconomics/blob/5b017aa53c93140121523a8e2501c48aa34ba560/report/team/pilot_plan.yaml) chia ngẫu nhiên theo nhân viên, phân tầng depot, đối chứng đồng thời; 20 nhân viên/nhánh, MDE 6 điểm, giả định ít nhất 299 yêu cầu/nhân viên. Ba luật dừng nêu ngưỡng, thời hạn và vai trò hành động; câu trả lời phản biện bên dưới làm rõ cách xử lý khi chưa đủ khối lượng. |
| **Tổng** | | | | **25 / 30** | |

**Quyết định của người chấm:** Go có điều kiện cho kế hoạch pilot trong phạm vi đã nêu; không phải phê duyệt triển khai chính thức.

**Lý do:** Đề xuất tính đến chi phí và rủi ro bất lợi, pilot có đối chứng và luật dừng; cần bổ sung nhãn cho một số kết quả còn dùng thời gian giả lập.

**Một câu hỏi cho đội trình:** Kế hoạch cần ít nhất 299 yêu cầu/nhân viên và 20 nhân viên mỗi nhánh để đạt MDE 6 điểm. Nếu đến ngày quyết định chưa đủ số yêu cầu này, nhóm sẽ kéo dài pilot hay thay đổi tiêu chí ra quyết định? Ai phê duyệt thay đổi đó?

**Câu trả lời của đội trình (do người chấm chuyển lại, chưa kiểm chứng việc thực thi):** “Nếu đến ngày quyết định chưa đủ 5.980 yêu cầu mỗi nhánh (20 nhân viên × 299 yêu cầu), Giám đốc vận hành phê duyệt gia hạn pilot, giữ nguyên MDE và các ngưỡng đã đăng ký trước. Nếu hết thời hạn gia hạn vẫn thiếu mẫu, kết luận chưa đủ bằng chứng và không mở rộng pilot; mọi thay đổi tiêu chí phải được Giám đốc vận hành phê duyệt trước khi xem dữ liệu tiếp theo.”
