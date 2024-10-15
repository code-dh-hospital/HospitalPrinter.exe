<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.1015.2 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32410152-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32410152-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32410152-NasDHSolutions.json)
- ✨: **💼**: **_Yêu cầu - in bảng kê lấy đơn vị khám cuối (BV Quảng Ngãi)_**
- ✨: ***Lấy đơn vị in phiếu theo cấu hình chức năng lấy chẩn đoán theo phòng đầu hay phòng cuối của cấu hình 6556*** ![](https://i.imgur.com/2qDROdC.png) ![](https://i.imgur.com/rwKvd5b.png) ![](https://i.imgur.com/UCFZjYV.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/708
## [v.3.24.1015.1]()
- 🐛: **💼**: **_Lỗi - PHÁT SINH LỖI KHI IN BẢNG KÊ NGOẠI TRÚ _**
- 🐛: Chỉnh lỗi khi in phiếu 01. ![](https://i.imgur.com/vPeDCMf.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/176
## [v.3.24.1015.0]()
- 🐛: **💼**: **_Lỗi - PHÁT SINH LỖI KHI IN BẢNG KÊ NGOẠI TRÚ _**
- 🐛: Chỉnh lỗi khi in phiếu 01. ![](https://i.imgur.com/sZ0el9b.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/176
## [v.3.24.1014.1]()
- 🐛: **💼**: **_Lỗi - Phần mềm xuất XML 4750 sai mã bệnh chính và mã bệnh kèm theo khi bệnh nhân khám nhiều phòng_**
- 🐛: ***Chỉnh lỗi Mã ICD chính không giống XML4750*** ![](https://i.imgur.com/V6K87z9.png) ![](https://i.imgur.com/gGuveoM.png) ![](https://i.imgur.com/xTAa6Bq.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/174
## [v.3.24.1014.0]()
- 🐛: **💼**: **_Lỗi - Phần mềm xuất XML 4750 sai mã bệnh chính và mã bệnh kèm theo khi bệnh nhân khám nhiều phòng_**
- 🐛: Thêm chức năng load XML không cập nhật ICD vào psdangky để, chủ yếu tính chi phí ![](https://i.imgur.com/V6K87z9.png) ![](https://i.imgur.com/gGuveoM.png) ![](https://i.imgur.com/xTAa6Bq.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/174
## [v.3.24.1010.2]()
- 🐛: Hiệu chỉnh thông tin - Trường hợp bệnh nhân khám lao có giấy hẹn lãnh thuốc : khi chọn psdangky.trangthaichuyentuyen = 6 (giấy hẹn lãnh thuốc người bệnh lao) thì hỗ trợ check chọn mặc định [Bệnh nhân khám lao] = true đồng thời không bắt buộc phải nhập mã bệnh viện nơi giới thiệu
![](https://i.imgur.com/mThubHZ.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/173
## [v.3.24.1010.1]()
- 🐛: **💼**: **_Lỗi - GHI NHẬN SAI THÁNG QUYẾT TOÁN KHI IN BẢNG KÊ BỆNH NHÂN THÁNG CŨ_**
- 🐛: Chỉnh lỗi liên quan tới xuất XML4750 trên báo cáo Admin, Reports ![](https://i.imgur.com/1DKpyWX.png) ![](https://i.imgur.com/bn684Rf.png)![](https://i.imgur.com/ryo2V1I.png)![](https://i.imgur.com/NUJNtfn.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/172
## [v.3.24.1010.0]()
- 🐛: **💼**: **_Lỗi - BA TRẢ VỀ ĐIỀU TRỊ KẾT THÚC TẠI THÁNG MỚI GHI NHẬN SAI THÔNG TIN TRÊN 4750_**
- 🐛: Kiểm soát hồ sơ XML trường hợp trả về điều trị, cho xuất viện, thay đổi tháng ra viện ![](https://i.imgur.com/gGSup0k.png) ![](https://i.imgur.com/pqBY5NR.png) ![](https://i.imgur.com/4tT8wcp.png)
- ☑: https://github.com/dh-hos/dhg.hosptaltreatment/issues/276
## [v.3.24.0930.0]()
- 🐛: **💼**: **_Lỗi - Không in phiếu 6556 được đối với BN có thuốc tỷ lệ và được hỗ trợ ngân sách._**
- 🐛: Chỉnh lỗi không in được phiếu 01 ![](https://i.imgur.com/2YuHGga.png) ![](https://i.imgur.com/ZTNjQME.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/171
## [v.3.24.0921.0]()
- 🐛: **💼**: **_Lỗi - Chỉnh toa và lưu chưa bắt được trạng thái đang thu._**
- 🐛: Thêm chức năng hỗ trợ kiểm tra số chứng từ đã được lập phiếu thu ![](https://i.imgur.com/ozigJQk.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/170
## [v.3.24.0916.0]()
- ✨: **💼**: **_Yêu cầu - Printer - Triển khai thanh toán mã QR MOMO_**
- ✨: Cập nhật các chức năng thể hiện QR giống như Fees
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/417
## [v.3.24.0915.0]()
- ✨: **💼**: **_Yêu cầu - Thiết kế bảng kê chi phí bệnh nhân thu phí_**
- ✨: ***Bổ sung option để chọn lấy trang in theo loại bhyt của đối tượng*** (current.dmdoituong.bhyt) ![](https://i.imgur.com/YTA6gML.png) 
- ✨: ***Đăng nhập tài khoản admin để thiết kế trang in*** ![](https://i.imgur.com/sSQTuRG.png)
- ✨: ***Chức năng thiết kế theo loại đối tượng*** ![](https://i.imgur.com/suJzmtd.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/626 
## [v.3.24.0910.0]()
- 📕: Sử dụng DH.XML4750.HOSO.RemoveXML130();
- ✨: **💼**: **_💼 Printer - Thực hiện xóa hồ sơ XML4750 khi thực hiện mở khóa phiếu 01⏳Dự kiến : 2024-09-11_**
- ✨: Thêm chức năng xóa hồ sơ XML4750 (đối với cấu hình Khoa dược) ![](https://i.imgur.com/KibRy3f.png) ![](https://i.imgur.com/4ywEOHF.png) ![](https://i.imgur.com/5Zjcmi5.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/639
## [v.3.24.0825.0]()
- ✨: **💼**: **_Yêu cầu - Printer - Triển khai thanh toán mã QR MOMO_**
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/417
## [v.3.24.0821.1]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - Toa thuốc không load được liều dùng (BV YHCT CT)_**
- 🐛: Truyền lieu_dung khi in toa thuốc ![](https://i.imgur.com/M00xA5y.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/168
## [v.3.24.0821.0]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - TEST - HIỆU CHỈNH THÔNG TIN NGOẠI TRÚ CHECK BN LAO KHÔNG GÁN psdangky.trangthaichuyentuyen = 5_**
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/89

## [v.3.24.0820.1]()
- ✨: **Thực hiện**: **_Yêu cầu - Printer Hỗ trợ chọn máy in mặc định khi in tem dán lên thuốc_**
- ✨: Không giới hạn số lượng trên control Chỉ định trên form Xuất bán lẻ
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/605
## [v.3.24.0820.0]()
- ✨: **Thực hiện**: **_Yêu cầu - Printer Hỗ trợ chọn máy in mặc định khi in tem dán lên thuốc_**
- ✨: Không giới hạn số lượng trên control Chỉ định trên form Xuất bán lẻ
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/605
## [v.3.24.0818.2]()
- ✨: **Thực hiện**: **_Yêu cầu - Printer Hỗ trợ chọn máy in mặc định khi in tem dán lên thuốc_**
- ✨: Bổ sung chức năng nhập chỉ định uống và in tem trên phiếu bán lẻ![](https://i.imgur.com/qnAEi6V.png)
- ✨: In tem chỉ định uống đối với **96133** sẽ theo tham số **temchidinhuong.tenmayin** (Cấu hình tên máy in tem chỉ định uống (chỉ áp dụng đối với 96133): Khác rỗng sẽ in theo giá trị cấu hình, ngược lại sẽ thể hiện form để chọn máy in.)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/605
## [v.3.24.0818.1]()
- ✨: **Thực hiện**: **_Yêu cầu - Printer Hỗ trợ chọn máy in mặc định khi in tem dán lên thuốc_**
- ✨: Bổ sung chức năng nhập chỉ định uống và in tem trên phiếu bán lẻ![](https://i.imgur.com/qnAEi6V.png)
- ✨: In tem chỉ định uống đối với **96133** sẽ theo tham số **temchidinhuong.tenmayin** (Cấu hình tên máy in tem chỉ định uống (chỉ áp dụng đối với 96133): Khác rỗng sẽ in theo giá trị cấu hình, ngược lại sẽ thể hiện form để chọn máy in.)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/605

## [v.3.24.0818.0]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - Không in phiếu 6556 khi chưa phát sinh cùng chi trả._**
- 🐛: Tính sai chi phí đối với PHAM_VI=2 ![](https://i.imgur.com/q6QjHnw.png) ![](https://i.imgur.com/KhNIfU3.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/164
## [v.3.24.0817.0]()
- ✨: **Thực hiện**: **_💼 Ghi nhận sdnguonkhac vào XML02 và XML03 khi lưu XML4750 ⌛Dự kiến: 2024-08-22_**
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/606
## [v.3.24.0814.0]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - THIẾU CÂN NẶNG KHI IN TOA THUỐC TẠI PRINTER_** ![](https://i.imgur.com/6szvFNA.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/167
## [v.3.24.0813.0]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - không in được phiếu 01 đối với bệnh nhân đã có phiếu thu chi phí không thanh toán bhyt (KP Đông Tây)_** ![](https://i.imgur.com/76b6T6c.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/165

## [v.3.24.0812.0]()
- 🐛: **Chỉnh lỗi**: **_Lỗi - Không in phiếu 6556 khi chưa phát sinh cùng chi trả._** ![](https://i.imgur.com/gu2LQMt.png) ![](https://i.imgur.com/0fdzRDS.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/164

## [v.3.24.0811.0]()
- ✨: Yêu cầu - Hỗ trợ hàm kiểm tra thông tuyến theo Công văn 1923/BHXH-CNTT ngày 20/06/2024
- ✨: Mô tả thực hiện [Ham API tra cuu TT - theo CV 1923-BHXHVN.md
](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Ham%20API%20tra%20cuu%20TT%20-%20theo%20CV%201923-BHXHVN.md)
- ✨:  + Chuyển hàm sử dụng thông tuyến KQNhanLichSuKCB2024 (Không theo cấu hình trên Admin)
- ✨:  + Sử dụng tài khoản kiểm tra theo tài khoản đăng nhập, điều kiện cụ thể để tài khoản có thể sử dụng tra cứu là có tài khoản BHXH cung cấp khác rỗng, có họ lót và Số CCCD
- ✨:  + Trường hợp tài khoản đăng nhập không hợp lệ, sẽ tìm theo tài khoản được cấu hình theo khoa, và theo bệnh viện trên Danh mục Nhân viên
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/565
## [v.3.24.0810.1]()
- ✨: Yêu cầu - BỔ SUNG THÔNG TIN LIỀU DÙNG LÊN LƯỚI TẠI PRINTER ![](https://i.imgur.com/xNjydyN.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/578
## [v.3.24.0810.0]()
- 🐛: Lỗi - Printer không in được bảng kê 01KCB![](https://i.imgur.com/5utpQkn.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/163
## [v.3.24.0805.0]()
- 🐛: Lỗi - Printer không in được bảng kê 01KCB khi bệnh nhân có thuốc Thanh bhyt và thuốc Check không thanh BHYT
 ![](https://i.imgur.com/lLogXbf.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/162
## [v.3.24.0731.0]()
- 🐛: Lỗi - Không in được 6556 cho BN đã thu tiền rồi, sai do chưa trừ tiền ngân sách ![](https://i.imgur.com/jY847Ef.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/161
## [v.3.24.0724.0]()
- ✨: Yêu cầu - Mở chức năng in tem chỉ định uống (Dược và nhà thuốc) [mabvbh=96133] ![](https://i.imgur.com/WEkNH5F.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/498
## [v.3.24.0702.0]()
- 🐛: Fix Lỗi - Lỗi in toa ngoại trú (Toa xuất viện) không trừ kho 
 ![](https://i.imgur.com/Ix2bed7.png)
 ![](https://i.imgur.com/JB9wX8r.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/158
## [v.3.24.0701.0]()
- ✨: Ghi nhận XML4750 trong schema xml130
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/32
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0627.0]()
- 🐛: Fix lỗi ma_giuong_bak_ trong bảng chidinhcls
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/403
## [v.3.24.0626.2]()
- ✨: Test KS
## [v.3.24.0626.0]()
- ✨: Test KS
## [v.3.24.0625.2]()
- ✨: Bổ sung chức năng cấu hìn máy, cho chọn phân khu số thứ tự
 ![](https://i.imgur.com/OwReH26.png)
- ✨: Bổ sung para PhanKhu_Monitor_Sott trên bảng kê 6556
 ![](https://i.imgur.com/HxcxiWN.png)
 ![](https://i.imgur.com/z5gM7LM.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/413
## [v.3.24.0625.1]()
- ✨: Bổ sung chức năng cấu hìn máy, cho chọn phân khu số thứ tự
 ![](https://i.imgur.com/OwReH26.png)
- ✨: Bổ sung para PhanKhu_Monitor_Sott trên bảng kê 6556
 ![](https://i.imgur.com/HxcxiWN.png)
 ![](https://i.imgur.com/z5gM7LM.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/413
## [v.3.24.0625.0]()
- ✨: Bổ sung chức năng cấu hìn máy, cho chọn phân khu số thứ tự
 ![](https://i.imgur.com/OwReH26.png)
- ✨: Bổ sung para PhanKhu_Monitor_Sott trên bảng kê 6556
 ![](https://i.imgur.com/HxcxiWN.png)
 ![](https://i.imgur.com/z5gM7LM.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/413
## [v.3.24.0624.0]()
- 🐛: Lỗi - Bảng kê hiển thị sai tên VTYT toa kèm theo
![](https://i.imgur.com/PJEJDwU.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/157
## [v.3.24.0618.0]()
- 🐛: Lỗi - Trùng chẩn đoán chính và chẩn đoán kèm theo bệnh nhân khám nhiều phòng
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/253 
- ![](https://i.imgur.com/493rDKv.png)
- 📕: Xử lý trim khoảng trắng trước và sau trước khi replace, để loại bỏ trùng
## [v.3.24.0617.0]()
- ✨: Yêu cầu - Form Hóa đơn điện tử hiển thị đúng kho
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/376#issuecomment-2172211678
## [v.3.24.0612.0]()
- 🐛: Fix Yêu cầu - Xác định mã lý do vào viện trên bảng kê 6556 và XML 4210 ( trường hợp bệnh nhân có giấy xác nhận cư trú) ![](https://i.imgur.com/lJrTENa.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389

## [v.3.24.0611.1]()
- ✨: Thực hiện [CHỦ ĐỀ: CÁCH GHI NHẬN GIÁ TRỊ CỘT XML1.MA_LYDO_VVIEN (cột 16, bảng 1 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md)
![](https://i.imgur.com/sDpfvF4.png)
![](https://i.imgur.com/eNNVLHF.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0611.0]()
- ✨: Thực hiện [CHỦ ĐỀ: CÁCH GHI NHẬN GIÁ TRỊ CỘT XML1.MA_LYDO_VVIEN (cột 16, bảng 1 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md)
![](https://i.imgur.com/BlhPztm.png)
![](https://i.imgur.com/dVtIYn3.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389
## [v.3.24.0606.1]()
- ✨: Yêu cầu - Form Hóa đơn điện tử hiển thị đúng kho (lấy theo khocp cấu hình)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/376

## [v.3.24.0606.0]()
- 🐛: Lỗi - Hiển thị sai BN chuyển viện vào danh sách CK+CLS
- ![](https://i.imgur.com/wugBdE9.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/143
## [v.3.24.0605.0]()
- 🐛: Fix lỗi in bệnh nhân ở đầu danh sách bị mất các tên còn lại trên lưới
- ![](https://i.imgur.com/wdIGlQn.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/140
## [v.3.24.0601.1]()
- ✨: Ẩn chức năng Mở khóa và xóa giờ kết thúc khám đối với nhà thuốc
- 🐛: Lỗi - Chức năng Mở khóa và xóa giờ kết thúc khám ở kho nhà thuốc xóa ICD, chẩn đoán, ngày in phiếu BHYT
![](https://i.imgur.com/cZ0pQ9R.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/149
## [v.3.24.0601.0]()
- 🐛: Lỗi - In Toa thuốc và Vật tư y tế tại Printer lấy sai tiêu đề
![](https://i.imgur.com/9obPAFx.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/139
## [v.3.24.0531.0]()
- 🐛: Kiểm nếu đã in phiếu thu thì không in lại đối với phiếu thu nhà thuốc
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/142
## [v.3.24.0526.0]()
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/144
- ✨: Bổ sung Tham số trong Footer đối với bảng kê 6556 (SYSTEM_DATETIME: Ngày giờ hệ thống, psdangky_ngayinphieu: Ngày giờ in phiếu)
## [v.3.24.0524.1]()
- ✨: Mở chức năng xuất màn hình tivi lúc phát thuốc đối với ~84006
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.3.24.0524.0]()
- ✨: Thực hiện theo mô tả [CÁCH GHI NHẬN GIÁ TRỊ CỘT XML1.MA_LYDO_VVIEN (cột 16, bảng 1 - XML4210)](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md) để xác định MA_LYDO_VVIEN và check THÔNG TUYẾN
![](https://i.imgur.com/xBKCcAB.png)
- 🐛: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/12
## [v.3.24.0522.1]()
- ✨: Fix lỗi không load lại được chi phí mới nếu thời gian chọn bệnh nhân và in phiếu lớn hơn 60 giây
- 🐛: https://github.com/dh-hos/dhg.hospitalprinter/issues/140
## [v.3.24.0522.0]()
- 🐛: Fix lỗi không in được phiếu thu đối với Nhà thuốc
![](https://i.imgur.com/l7Cmjgf.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/150
- 📕: Fix code kiểm tra tham số `DongvaTayDuoc` bị sai
## [v.3.24.0521.1]()
- ✨: Thêm button với chức năng Mở khóa và xóa giờ kết thúc khám
![](https://i.imgur.com/5larpF1.png)
- 🐛: https://github.com/dh-hos/To_Lap_Trinh/issues/364
## [v.3.24.0521.0]()
- ✨: Bổ sung Logo Vietin trên màn hình thể hiện QRCode
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/93
## [v.3.24.0520.0]()
- ✨: Bổ sung chức năng để kiểm tra trạng thái thanh toán QRCode
![](https://i.imgur.com/Fok6cJm.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/363
## [v.3.24.0518.5]()
- ✨: Thêm chức năng tự động lấy lại chi phí sau khi thời gian giữa lúc chọn bệnh nhân và in phiếu lớn hơn 60s, để tránh tình trạng chi phí có thay đổi  khi in phiếu, không đánh dấu đúng trạng thái của bệnh nhân
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/140
## [v.3.24.0518.4]()
- ✨: Thêm chức năng cho phép cấu hình in toa nghiện, hướng thần khi tham số kd.khoaduoc=0
![](https://i.imgur.com/i2ydDCH.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/135
## [v.3.24.0518.3]()
- 🐛: Lỗi - Bệnh nhân nội trú không in được phiếu thu từ kho nhà thuốc
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/150
## [v.3.24.0518.1]()
- 🐛: Fix lỗi không build được dll mới trên hệ thống build tự động
![](https://i.imgur.com/EcJSMmr.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/153#issuecomment-2118137206
- 📕: Build lại và kiểm tra build tự động không lấy được phiên bản mới
## [v.3.24.0518.0]()
- 🐛: Fix lỗi không build được dll mới trên hệ thống build tự động
![](https://i.imgur.com/EcJSMmr.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/153#issuecomment-2118137206
- 📕: Build lại và kiểm tra build tự động không lấy được phiên bản mới
## [v.3.24.0517.1]()
- 🐛: Fix lỗi cảnh báo sai số tiền trên form ![image](https://i.imgur.com/JCGGlH0.png)
Nguyên nhân do module ghi nhận phiếu phẫu thuật bị double row. Cái này phải ghi nhận lại để module Prescription kiểm tra lại. ![image](https://i.imgur.com/7ccdrBw.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/148

## [v.3.24.0517.0]()
- 🐛: Cập nhật lại readme.md
## [v.3.24.0514.7]()
- ✨: Xuất QRCode đối với phiếu in phiếu khám chữa bệnh đối với nhà thuốc (Bệnh viện Nội Tiết Quảng Ngãi)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/300

