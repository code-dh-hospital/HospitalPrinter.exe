<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.0606.1 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32406061-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32406061-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32406061-NasDHSolutions.json)
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

