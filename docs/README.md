<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.0520.0 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32405200-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32405200-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FHospitalPrinterexe%2F32405200-NasDHSolutions.json)
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

