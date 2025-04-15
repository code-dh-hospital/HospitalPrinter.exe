<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#

## [v.3.25.0415.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504150-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Prescription cho xử trí lập BANT theo đợt và chuyển chi phí vào Bệnh án ngoại trú nếu có toa và cls.
- ✨: Tại form [In phiếu]: Kiểm tra nếu người bệnh BHYT đã có lập bệnh án ngoại trú thì KHÔNG CHO PHÉP in phiếu 01/6556 trên các chi phí đã phát sinh tại khám ngoại trú. 
- 🐛: Bổ sung Chỉ áp dụng chặn và cảnh báo đối với Bệnh án ngoại trú quyết toán cuối đợt (bnnoitru.bant = 0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/136

## [v.3.25.0414.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504140-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi lệch MA_LOAI_KCB trên XML4750 giữa Admin và Reports (Sai do xuất XML130 khi in phiếu 01).
![](https://i.imgur.com/bngZQpM.png)
![](https://i.imgur.com/QEAxO9V.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/227

## [v.3.25.0410.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504100-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Form Hóa đơn điện tử hiển thị đúng kho - YEUCAU - dh-issue- #164
- ✨:  ***Mở rộng tất cả hóa đơn điện tử chỉ lấy chứng từ theo kho trong phần cấu hình máy.*** ![](https://i.imgur.com/ivZjcL0.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/164

## [v.3.25.0409.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504090-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer: Bổ sung chức năng tự thiết kế cho mẫu xuất bán lẻ (BV Tam Nông)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/170

![](https://i.imgur.com/VcN3dTV.png)

## [v.3.25.0408.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504080-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Prescription cho xử trí lập BANT theo đợt và chuyển chi phí vào Bệnh án ngoại trú nếu có toa và cls
- Cập nhật theo mô tả
![](https://i.imgur.com/Xd6bMiL.png)
https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KHAMBENH/Benh-an-ngoai-tru-BHYT.md
![](https://i.imgur.com/biAi8hg.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/136

## [v.3.25.0322.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503220-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  LỖI - PRINTER - Không hiển thị tên BN in phiếu 01 khi Trạng thái khambenh.dakham =3 - LOI - dh-issue- #153
- 🐛:  ***Xử lý lấy thêm những bệnh nhân CK+CLS chỉ có toa mua ngoài (không toa BHYT) vào danh sách CK+CLS.*** ![](https://i.imgur.com/vfrh4xE.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/153#issuecomment-3773

## [v.3.25.0318.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503180-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer (thuốc có check tiện ích) khi chọn không lấy thuốc, không có tác dụng đối với bệnh nhân nội trú đã xử trí xuất viện
![](https://i.imgur.com/TbDP8BI.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/138

## [v.3.25.0313.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503130-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bắt buộc nhập CCCD đối với đối tượng Khám sức khỏe (BV Thanh Bình)
- Cập nhật theo mô tả
![](https://i.imgur.com/LmAEkAd.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/82

## [v.3.25.0312.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503120-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bắt buộc nhập CCCD đối với đối tượng Khám sức khỏe (BV Thanh Bình)
- Cập nhật theo mô tả: Khi Click Lưu, dựa vào madt kiểm tra bảng current.dmdoituong.
	Nếu `current.dmdoituong.cccd_required == 0 `=> Cho phép lưu lại bình thường
	Nếu `current.dmdoituong.cccd_required == 1 ` và `txtCMND.text == ''` => Cảnh báo bắt buộc nhập căn cước công dân, không cho lưu lại.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/82

## [v.3.25.0307.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503071-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503071-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503071-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  LỖI - PRINTER - BN có chi phí Thu phí đã thu tiền - nhưng không in được phiếu 01 - LOI - dh-issue- #120
- 🐛:  ***Xử lý lỗi khi có miễn giảm cận lâm sàng, dẫn đến không in phiếu 01.*** ![](https://i.imgur.com/FD3goVd.png)![](https://i.imgur.com/AL6CEGn.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/120

## [v.3.25.0307.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503070-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Đông Tây: Không mở khóa và phục hồi được toa mua ngoài không lấy thuốc
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/96

![](https://i.imgur.com/vfO5zsx.png)
![](https://i.imgur.com/hll30UC.png)

## [v.3.25.0303.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32503030-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - BV Sa Đéc: Phần mềm Printer và Fees không ẩn danh sách quyển Biên lai (gọi chung các quyển thu phí) đã ngưng sử dụng - LOI - dh-issue- #112
- 🐛:  ***Xử lý loại bỏ những quyển hóa đơn ngưng sử dụng (sudung=1).*** ![](https://i.imgur.com/8kM1fHF.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/112

## [v.3.25.0228.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502281-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Đông Tây: Không mở khóa và phục hồi được toa mua ngoài không lấy thuốc
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/96

![](https://i.imgur.com/zqmFXvt.png)

## [v.3.25.0228.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502280-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Ràng buộc số điện thoại bệnh nhân Form hiệu chỉnh thông tin
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/74

![](https://i.imgur.com/NwmUWj2.png)

## [v.3.25.0224.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502240-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  LỖI - XML4 - DON_VI_DO: Đơn vị đo % không hiển thị - LOI - dh-issue- #76
- 🐛: ***Chỉnh lỗi mất XML04.DON_VI_DO, những hồ sơ đã ghi nhận sai phải thực hiện đối soát lại. Cập nhật hồ sơ khi in phiếu 01 thông tin lỗi DON_VI_DO.*** ![](https://i.imgur.com/8JNfwKW.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/76

## [v.3.25.0220.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502200-NasDHSolutions.json)</sup></sup></sub>
- ✨: DUAN - Tách nguồn quản lý thuốc BV Phụ sản - fix lỗi Bảng kê tổng hợp chưa lọc được tiện ích
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/3

![](https://i.imgur.com/UYu0bIX.gif)

## [v.3.25.0218.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502180-NasDHSolutions.json)</sup></sup></sub>
- ✨: DUAN - Tách nguồn quản lý thuốc BV Phụ sản - Bổ sung control lọc hàng hoá tiện ích trên các báo cáo 
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/3

- [x] 1. Bảng kê-> Kê Toa theo Bác sĩ (Theo sản phẩm)

![](https://i.imgur.com/0YuwuRp.png)

- [x] 2. Bảng kê-> Kê xuất bán lẻ (tab Theo sản phẩm)

![](https://i.imgur.com/tnB9Nfy.png)

- [x] 3. Bảng kê-> Kê bệnh nhân trả (Theo sản phẩm)

![](https://i.imgur.com/c74VbLw.png)

- [x] 4. Bảng kê-> Kê theo đối tượng (Theo sản phẩm)

![](https://i.imgur.com/2rGWpiX.png)

- [x] 5. Bảng kê-> Kê Toa tổng hợp (Theo sản phẩm)

![](https://i.imgur.com/ilnFGNe.png)

## [v.3.25.0212.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502120-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - in toa thuốc bệnh nhân ngoại trú (BV YHCT TPCT)
![](https://i.imgur.com/huytBU1.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/61

## [v.3.25.0207.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502070-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - HIS không cập nhật được trạng thái thanh toán QR của nhà thuốc. - (dh-issue/LOI/#57)
- 🐛: ***Chỉnh lỗi thêm phần in toa thuốc từ phòng khám*** ![](https://i.imgur.com/zgbQQtV.png) ![](https://i.imgur.com/xeDfMsQ.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/57

## [v.3.25.0206.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502061-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502061-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502061-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Thực hiện kết nối QR (HD Bank) - BV Cù Lao Minh - (dh-issue/YEUCAU/#32)
- ✨: Bổ thanh PrivateCode: `thanhtoanqr`, ![](https://i.imgur.com/UpTWyVA.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/32

## [v.3.25.0206.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32502060-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - HIS không cập nhật được trạng thái thanh toán QR của nhà thuốc. - (dh-issue/LOI/#57)
- 🐛: Thay đổi cách cập nhật QRID tạm, nếu có mã tạm trước sẽ lấy mã đó cập nhật các mặt hàng còn lại, ngược lại sẽ tạo qrid mới để cập nhật. Thêm điều kiện chỉ cập nhật khi qrid trong database là tạm hoặc rỗng. ![](https://i.imgur.com/pQQaIA2.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/57

## [v.3.25.0121.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501210-NasDHSolutions.json)</sup></sup></sub>
- ✨: DUAN - Tách nguồn quản lý thuốc BV Phụ sản - Hỗ trợ lọc và in phiếu thu và phiếu xuất kho riêng cho hàng hoá tiện ích
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/3

- Hỗ trợ lọc theo mặt hàng tiện ích

![](https://i.imgur.com/eJZ0E9d.gif)

- Tách riêng in hàng hoá tiện ích

![](https://i.imgur.com/QXowNQU.png)

![](https://i.imgur.com/G2A2cP0.png)

![](https://i.imgur.com/lHQhCvl.png)

## [v.3.25.0120.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501200-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Hiển thị màn hình QR cho chức năng xuất bán lẻ nhà thuốc. - (dh-issue/YEUCAU/#29)
- ✨: Chỉnh lỗi không thể hiện ngày sinh trên màn hình QR. ![](https://i.imgur.com/dOVYf6U.png) ![](https://i.imgur.com/E0tIJV8.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/29

## [v.3.25.0119.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501190-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Hiển thị màn hình QR cho chức năng xuất bán lẻ nhà thuốc. - (dh-issue/YEUCAU/#29)
- ✨: ***Bổ sung chức năng sinh cấu hình sử dụng QRCode trên chức năng xuất bán lẻ, thiết kế riêng cho Khoa dược và Nhà thuốc.*** ![](https://i.imgur.com/ku6BAW5.png) ![](https://i.imgur.com/kVtRSxt.png)
- ✨: ***Bổ sung chức năng sinh QRCode khi in phiếu thu tại chức năng xuất bán lẻ.*** ![](https://i.imgur.com/ApJTVc2.png) ![](https://i.imgur.com/FLo9SUp.png)
- ✨: ***Bổ sung chức năng sinh QRCode ra màn hình phụ thứ 2 trên chức năng xuất bán lẻ.***
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/29

## [v.3.25.0113.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501130-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Bảng kê 6556 lấy tên bệnh chính bị sai khi bệnh nhân khám nhiều phòng và có phòng có chẩn đoán YHCT - (dh-issue/LOI/#12) ![](https://i.imgur.com/aZMy9Ys.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/12

## [v.3.25.0108.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501080-NasDHSolutions.json)</sup></sup></sub>
- ✨: Lỗi - Bảng kê 6556 lấy tên bệnh chính bị sai khi bệnh nhân khám nhiều phòng và có phòng có chẩn đoán YHCT
- 🐛: ***Không phải lỗi:*** `Thiết kế bảng kê 6556 bệnh chính lấy para TEN_BENH chỉ lấy tên bệnh ICD 10 nhưng phần mềm lấy tên bệnh có YHCT` phụ thuộc vào tham số `xml421yhct` 
- ✨: ***Xử lý thêm để không trùng do tham số xml421yhct***: `Thiết kế bảng kê 6556 bệnh chính lấy para TEN_BENH_CO_YHCT bị trùng tên bệnh YHCT` ![](https://i.imgur.com/1vH33GU.png)
- ✨: ***Xử lý không ghép tên YHCT vào tham số TEN_BENH_CO_YHCT theo phòng khám*** ![](https://i.imgur.com/zssaJHE.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/12

## [v.3.25.0104.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32501040-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng cấu hình khu vực.
![](https://i.imgur.com/wyLjxMx.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/1

## [v.3.24.1227.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412271-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412271-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412271-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Các module add mã chính thức 96176 Phòng khám đa khoa Y Đức Sài Gòn - YEUCAU
- ☑: https://i.dh-his.com/test/YEUCAU/issues/4

## [v.3.24.1227.0]()
- ✨: Yêu cầu - Các module add mã chính thức 96176 Phòng khám đa khoa Y Đức Sài Gòn - YEUCAU
- ☑: https://i.dh-his.com/test/YEUCAU/issues/4

## [v.3.24.1220.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412200-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Các module add mã tạm 96151 Phòng khám đa khoa Sài Gòn Y Đức ·
- ☑: https://github.com/dhhiswork/YeuCau/issues/60

## [v.3.24.1218.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412181-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412181-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412181-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Lấy giá BH làm giá BV 
- 🐛: ***Chỉnh lỗi lấy sai giá BV*** 
![](https://i.imgur.com/KViBEGt.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/96

## [v.3.24.1218.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412180-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Lấy giá BH làm giá BV 
- 🐛: ***Chỉnh lỗi lấy sai giá BV*** ![](https://i.imgur.com/KViBEGt.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/96

## [v.3.24.1217.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412170-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412170-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412170-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Bảng kê 6556 lấy luôn chi phí không thanh toán BHYT (BV Tâm Phúc) ![](https://i.imgur.com/uZC9CBA.png)
- ☑: https://github.com/dhhiswork/Loi/issues/88

## [v.3.24.1216.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412160-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412160-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412160-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Triển khai Kios và phát thuốc hiển thị ra Tivi Bệnh viện Tâm Phúc
- ✨: ***Bổ sung cấu hình cho phép Phát file âm thanh khi chọn chức năng mời nhận thuốc*** ![](https://i.imgur.com/L9WNQGy.png) ![](https://i.imgur.com/LD5Oriw.png)
- ✨: Có thể sử dụng các công cụ sau để tạo tệp tin mp3: https://j2team.dev/tools/text-to-speech (có app cho window), https://tts.klmedia.vn/
- ☑: https://github.com/dhhiswork/YeuCau/issues/34

## [v.3.24.1214.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412140-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Triển khai Kios và phát thuốc hiển thị ra Tivi Bệnh viện Tâm Phúc ![](https://i.imgur.com/c3KsZuM.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/34

## [v.3.24.1213.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412130-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV QDY CT: Printer in không lấy thuốc không hiện thông báo in phiếu, trạng thái dain có lúc = 2 (không hiện thông báo in phiếu), có lúc = 3 (có hiện thông báo có in phiếu không bấm bỏ qua), ... ·
- 🐛: Bổ sung chức năng ghi nhật ký đối Khi in BN không ký tên, Không lấy thuốc không in phiếu ![](https://i.imgur.com/aP7DfkT.png)
- ☑: https://github.com/dhhiswork/Loi/issues/33#issuecomment-2539577215

## [v.3.24.1211.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412110-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng hiệu chỉnh thông tin bệnh nhân trên Admin, Register, Prescription, Printer, hiệu chỉnh thông tin BANT không cập nhật lại trạng thái tuyenxml từ 1 thành 0 khi đổi BV cấp thẻ trong psdangky, bnnoitru -> khi in bảng kê bị sai trang thái tuyến (trái tuyến) đúng là thông tuyến.
![](https://i.imgur.com/PCmnZNx.gif)
- ☑: https://github.com/dhhiswork/YeuCau/issues/14

## [v.3.24.1206.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412060-NasDHSolutions.json)</sup></sup></sub> <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412060-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: TYT Long Hưng: Phần mềm in bảng kê khi chưa đủ thời gian tối thiểu in phiếu ![](https://i.imgur.com/kgGb7vX.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/74

## [v.3.24.1205.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412050-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Triển khai Kios và phát thuốc hiển thị ra Tivi Bệnh viện Tâm Phúc
- 🐛: Mở chức năng thể hiện tivi đối với `mabvbh: 60152`
- ☑: https://github.com/dhhiswork/YeuCau/issues/34

## [v.3.24.1203.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32412030-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật chức năng mở QRCODE đối với 92014, 60152
- ☑: https://github.com/dhhiswork/YeuCau/issues/2

## [v.3.24.1129.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411290-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Thêm cách nhập Hộ chiếu mẫu mới gồm 1 chữ cái + 8 số (hiện tại phần mềm chưa cho nhập)
- 🐛: Cho phép nhập thêm dạng hộ chiếu 9 ký tự (1 chữ, 8 số) ![](https://i.imgur.com/FIXDzaJ.png) ![](https://i.imgur.com/PsbqqQY.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/28

## [v.3.24.1128.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411283-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411283-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411283-NasDHSolutions.json)</sup></sup></sub>
- ✨: Lỗi - Test: Prescription In không lấy thuốc và In bệnh nhân không ký tên không lấy được XML130 lên Reports và XML4750 lên Admin, in ngày cũ phần mềm ghi nhận ngày in là ngày hiện tại
- 🐛: Thêm chức năng cập nhật giờ kết thúc khi Không lấy thuốc khác ngày. ![](https://i.imgur.com/1J5tkbS.png) ![](https://i.imgur.com/GQ04rGl.png) ![](https://i.imgur.com/oSjWSEH.png)
- ☑: https://github.com/dhhiswork/Loi/issues/55

## [v.3.24.1128.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411282-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411282-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411282-NasDHSolutions.json)</sup></sup></sub>
- ✨: Lỗi - Test: Prescription chỉnh toa thuốc phần mềm tự ghi nhận trạng thái tái khám
- ✨: Loại bỏ chức năng hẹn thanh toán (taikham) khi thực hiện thao tác in phiếu, không lấy thuốc ![](https://i.imgur.com/MijYnf7.png) ![](https://i.imgur.com/8SUPv9o.png)
- ☑: https://github.com/dhhiswork/Loi/issues/53

## [v.3.24.1128.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411281-NasDHSolutions.json)</sup></sup></sub>
- ✨: - 🐛: Lỗi - Admin load sai danh sách đối tượng KHÔNG BHYT
- 🐛: Chỉnh lỗi ghi nhận sai giá trị XML01.T_TONGCHI_BH khi tạo XML4750 (những trường hợp có PHAM_VI=2). Những trường hợp đã ghi nhận sai phải dùng Chức năng đối soát, nếu không có hồ sơ đối soát phải dùng module mới để in lại phiếu 01.
- ![](https://i.imgur.com/KIRuxe5.gif)
- ☑: https://github.com/dhhiswork/Loi/issues/27

## [v.3.24.1128.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411280-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register, Prescription không nhập được cân nặng với 4 kí tự
- 🐛: Kiểm tra cân nặng vượt quá 200 thì cảnh báo
![](https://i.imgur.com/El7nflk.png)
- ☑: https://github.com/dhhiswork/Loi/issues/35

## [v.3.24.1127.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411270-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - BỔ SUNG NGÀY CẤP - NƠI CẤP CỦA CMND TRONG FROM HIỆU CHỈNH THÔNG TIN
![](https://i.imgur.com/pR3bRVS.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/18
<<<<<<< HEAD

## [v.3.24.1127.0]()
- ✨: Yêu cầu - BỔ SUNG NGÀY CẤP - NƠI CẤP CỦA CMND TRONG FROM HIỆU CHỈNH THÔNG TIN
![](https://i.imgur.com/pR3bRVS.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/18
=======

## [v.3.24.1125.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411252-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411252-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411252-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - PRINTER IN PHIẾU 01 KHÔNG HIỂN THỊ HỌ TÊN NGƯỜI LẬP BẢNG KÊ
- 🐛: Chỉnh lỗi in lần đầu thiếu tên người in phiếu. ![](https://i.imgur.com/zb55LKA.png)
- ☑: https://github.com/dhhiswork/Loi/issues/34

## [v.3.24.1125.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411251-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411251-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411251-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer In tem xuất bản lẻ và in tem trong phần In phiếu KCB thêm para cột số lượng
- 🐛: Chỉnh lỗi mất tên hàng hóa khi in tem ![](https://i.imgur.com/aRol7XC.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/8

## [v.3.24.1125.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411250-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer In tem xuất bản lẻ và in tem trong phần In phiếu KCB thêm para cột số lượng
- 🐛: Bổ sung các para vào tem toa thuốc (soluong, soluongstr,dvt) ![](https://i.imgur.com/49MB8GW.png) ![](https://i.imgur.com/Lke5Q08.png)
- ☑: https://github.com/dhhiswork/YeuCau/issues/8

## [v.3.24.1119.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411192-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411192-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411192-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Trường XML1.MA_BENH_YHCT không lấy được mã yhct đã chỉ định (BV Hồng Ngự) ![](https://i.imgur.com/USUxBqr.png)
- ☑: https://github.com/dhhiswork/Loi/issues/14

## [v.3.24.1119.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411191-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411191-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411191-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Trường XML1.MA_BENH_YHCT không lấy được mã yhct đã chỉ định (BV Hồng Ngự)
- ☑ : https://github.com/dhhiswork/Loi/issues/14

## [v.3.24.1119.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411190-NasDHSolutions.json)</sup></sup></sub>
- 🐛: **Lỗi - Bảng kê 6556 hiển thị VTYT kèm theo bằng tên cận lâm sàng** ![](https://i.imgur.com/F638XwF.png)
- ☑: https://github.com/dhhiswork/Loi/issues/7

## [v.3.24.1118.4]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411184-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411184-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411184-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Cập nhật chức năng thể hiện QR Nhà thuốc bị chậm (cập nhật SQL để cập nhật giá trị QRID lại, để tốc độ nhanh hơn)

## [v.3.24.1118.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411183-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411183-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411183-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Cập nhật chức năng thể hiện QR Nhà thuốc bị chậm (cập nhật SQL để cập nhật giá trị QRID lại, để tốc độ nhanh hơn)

## [v.3.24.1118.2]()
- 🐛: Cập nhật chức năng thể hiện QR Nhà thuốc bị chậm (cập nhật SQL để cập nhật giá trị QRID lại, để tốc độ nhanh hơn)

## [v.3.24.1118.1]()
- 🐛: Cập nhật chức năng thể hiện QR Nhà thuốc bị chậm (cập nhật SQL để cập nhật giá trị QRID lại, để tốc độ nhanh hơn)

## [v.3.24.1118.0]()
- 🐛: Cập nhật chức năng thể hiện QR Nhà thuốc bị chậm (cập nhật SQL để cập nhật giá trị QRID lại, để tốc độ nhanh hơn)

## [v.3.24.1114.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411140-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411140-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411140-NasDHSolutions.json)</sup></sup></sub>
- 🐛: **💼**: **_Lỗi - Không hiên thị tên BYT trên mẫu 19_**
- 🐛: ***Chỉnh lỗi không ghi nhận mahh khi lưu trữ hồ sơ XML4750 trên XML02,XML03***. Trường hợp những hồ sơ chưa lưu được mahh, thì thực hiện chức năng kiểm tra hồ sơ giữa 4210 và 4750 để cập nhật lại.
- ![](https://i.imgur.com/SJoH7Ap.png) ![](https://i.imgur.com/oBRMKPJ.png)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/38

## [v.3.24.1107.2]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411072-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411072-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32411072-NasDHSolutions.json)</sup></sup></sub>
Push lại lần 2
- 🐛: Fix lỗi khi đăng ký không nhập ngày chứng nhận lao nhưng vào hiệu chỉnh thông tin lại thấy có ghi nhận
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/699

## [v.3.24.1107.1]()
- 🐛: Fix lỗi khi đăng ký không nhập ngày chứng nhận lao nhưng vào hiệu chỉnh thông tin lại thấy có ghi nhận
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/699

## [v.3.24.1107.0]()
- 🐛: Fix lỗi khi đăng ký không nhập ngày chứng nhận lao nhưng vào hiệu chỉnh thông tin lại thấy có ghi nhận 
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/699

## [v.3.24.1022.1]()
- 🐛: Lỗi - Giao diện che khuất thông tin trên Form chỉnh thông tin bệnh nhân ngoại trú
![](https://i.imgur.com/lwbarva.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/717

## [v.3.24.1022.0]()
- 🐛: **💼**: **_Lỗi - Bảng kê 6556 hiển thị chi phí ngoài BHYT_**
- 🐛: ***Chỉnh lỗi số bản in tách trang in không theo cấu hình*** ![](https://i.imgur.com/jw8OaFU.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/175

## [v.3.24.1021.0]()
- ✨: `--- 🐛: **💼**: **_Lỗi - Phần mềm xuất XML 4750 sai mã bệnh chính và mã bệnh kèm theo khi bệnh nhân khám nhiều phòng_**
- 🐛: ***Chỉnh lỗi khi in phiếu 01 không sinh đúng dữ liệu XML4750 và chẩn đoán bị sai*** ![](https://i.imgur.com/cRXTjTR.png) ![](https://i.imgur.com/mQ29Ykw.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/174

## [v.3.24.1018.1]()
- ✨: `--- 🐛: **💼**: **_Lỗi - Phần mềm xuất XML 4750 sai mã bệnh chính và mã bệnh kèm theo khi bệnh nhân khám nhiều phòng_**
- 🐛: ***Chỉnh lỗi khi in phiếu 01 không sinh đúng dữ liệu XML4750 và chẩn đoán bị sai*** ![](https://i.imgur.com/cRXTjTR.png) ![](https://i.imgur.com/mQ29Ykw.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/174

## [v.3.24.1018.0]()
- ✨: `--- 🐛: **💼**: **_Lỗi - Phần mềm xuất XML 4750 sai mã bệnh chính và mã bệnh kèm theo khi bệnh nhân khám nhiều phòng_**
- 🐛: ***Chỉnh lỗi khi in phiếu 01 không sinh đúng dữ liệu XML4750*** ![](https://i.imgur.com/r4t57mw.png) ![](https://i.imgur.com/pJdvSHb.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprinter/issues/174

## [v.3.24.1015.2]()
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