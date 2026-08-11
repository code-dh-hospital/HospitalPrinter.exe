<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#

## [v.3.26.0811.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32608111-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32608111-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32608111-NasDHSolutions.json)</sup></sup></sub>
- ✨: Lỗi - Prescription, Printer bảng kê bệnh nhân ngoại trú in thiếu tên chẩn đoán phụ (BV Ngã Năm) #953
	- PRINTER: cập nhật para: TEN_BENH_KEM_THEO
	
	+ Lấy chẩn đoán kèm theo, theo option:

	![](https://i.vgy.me/AHeZlO.png)

	+ Lấy tất cả chẩn đoán kèm theo:

	![](https://i.vgy.me/9iLQCV.png)

	+ Lấy lấy chẩn đoán kèm theo, theo phòng:

	![](https://i.vgy.me/QruNzE.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/953
<<<<<<< HEAD

## [v.3.26.0811.0]()
- ✨: Lỗi - Prescription, Printer bảng kê bệnh nhân ngoại trú in thiếu tên chẩn đoán phụ (BV Ngã Năm) #953
	- PRINTER: cập nhật para: TEN_BENH_KEM_THEO
	
	+ Lấy chẩn đoán kèm theo, theo option:

	![](https://i.vgy.me/AHeZlO.png)

	+ Lấy tất cả chẩn đoán kèm theo:

	![](https://i.vgy.me/9iLQCV.png)

	+ Lấy lấy chẩn đoán kèm theo, theo phòng:

	![](https://i.vgy.me/QruNzE.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/953
=======

## [v.3.26.0810.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32608100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32608100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32608100-NasDHSolutions.json)</sup></sup></sub>


- 🐛: Sửa lỗi XML4750/XML3175 `bang3.NGAY_KQ` lấy sai giờ trả kết quả.
![](https://lh3.googleusercontent.com/pw/AP1GczNZuEVEcnlaX0nFPuw9244OJGJBD_SHp-_ga2R6a4Gn3Zk6txUT4eHKylw_U11bYM6Uuq2R-0ZDrpT4kf0Zz1NJpISg9sPnGToVDHS9S5Wz3DwRJUUAxXtullL7az69428JRBf6rfwX-qSAc_im2yfh=w1555-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/952#issuecomment-31851

## [v.3.26.0730.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607300-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung `mabvbh = 74167`, cho phép in tem chỉ định uống toa thuốc theo mô tả [CHUC-NANG-RIENG/Chuc-nang-in-tem-chi-dinh-uong-toa-thuoc.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/CHUC-NANG-RIENG/Chuc-nang-in-tem-chi-dinh-uong-toa-thuoc.md).
![](https://lh3.googleusercontent.com/pw/AP1GczOlVwIh_99a9tq1RV-ajMe_lzmKF0Jf1_ClT3RKz7f7R-FfmpO4FkV2in437Xz1IF-GpM72zfTB4yauJamQVZ5Eo-k_2438ph1REDYxde3l5_wi9MxKWmbmZLyb8r_YTsuV35nJQFdZ8C1ueJzBcuYI=w1658-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczMxLMUde-TU_0CZz2VWyCiXSp2InfKCZvGrQJCqKLnzYIJvmT0L2-p-AZxZtQVY7z_9-hWFw-zInSTqE4rycRWqmdWlx1lrStvKNyuHsGe4mgdZaYu_gD00bDnuj29oxM7wUPcXsdcoPKRVye9SAX9S=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/859#issuecomment-31565

## [v.3.26.0729.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607291-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607291-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607291-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: In toa thuốc không in được chữ ký số lên toa (PK Minh Quang) #947
![](https://i.vgy.me/yiZNPU.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/947

## [v.3.26.0729.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607290-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi xuất XML cột `ma_loai_kcb`
1. BN có BANT đợt khám bệnh thuộc phụ lục I, có toa thuốc, không có CLS trừ công khám => ma_loai_kcb = 05. (Hiện tại phần mềm ghi nhận ma_loai_kcb = 02)
![](https://lh3.googleusercontent.com/pw/AP1GczPOti77N8jbpENFMuWaSB4skAxd0_Rwiii87xMlIFZ_oV5mJrLhAyBmhGGqbhIhzEqe3rlouJNrepuUkoHMwu9uwze1SzQijmCxuzP0WhKaajmyfHgcQU7xCluditsqnyKUjjXzGoJFV1EbTt6h9jzs=w1555-h879-s-no-gm?authuser=0)
2. BN có BANT đợt khám bệnh thuộc phụ lục I, có hoặc không toa thuốc, có CLS khác công khám => ma_loai_kcb = 08 (Hiện tại phần mềm ghi nhận ma_loai_kcb = 02)
![](https://lh3.googleusercontent.com/pw/AP1GczPrclyZ8FPZ4TVhR0yjqq8qePKvWRoe-ErTusr1K8Pzw1OplZu33JtCNJpVhPG_nfnRv689vuBs59euvVcC245zjr4rSbLsLvguz-2ihW9IgqkP3qGoP2augJtnRZDdrDt8iN-NA-QZAJ-PHmvT-e8j=w1555-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/839#issuecomment-31482

## [v.3.26.0728.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607280-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung xuất ma_loai_kcb theo cập nhật mô tả [XML130/QD4570/ma_loai_kcb_QD1804.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/ma_loai_kcb_QD1804.md): 
![](https://lh3.googleusercontent.com/pw/AP1GczOa0AWjFF78unZDpPPcSXkectC30WoyPUhy3kOdG7bU_91Jr_aFgIdB0yuKTG7O6l0ihxO6poQq3skkA5VnPfEFg9BoIMWZeMuIpW6jKcYfRHJghzFM88hMuEVdA-_ywIsqhjepVmqClSgePepXDjG4=w1025-h837-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczN68_UmJiyuPSWhsM6ACxTF_7OvO3mjwPk912ETBaGVL4M41oF9hf_5kHEx3CQ26uGzVidXtntmqsuHNGcpWnmHbcGS1GZJocwwmNfGyQ7Q183-Hu5yoGdjMInrb56IhiU3Fw_LXI6WGJuEBQuSD6QQ=w1028-h555-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczNaFOCXcFohOr5kyC_z_n6AuRObYQyQ_QvvmrZMHNNDZRcYFHXqxmfN9TgeQzF2IVhUk7x161N6rNwlAjy9esYHwNjJwbHn9rZonfNjReYarB8nat5bKsOYjTy4y3matxVKWSZ7wikvBEwrNu25HE5j=w1554-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/839#issuecomment-31428

## [v.3.26.0723.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607231-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607231-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607231-NasDHSolutions.json)</sup></sup></sub>

- ✨: Cập nhật cách tính mức hưởng khi xuất XML và phiếu 01 đối với người bệnh bệnh án ngoại trú theo mô tả: [XML130/Nghi-dinh-188-2025/Thuc-hien-Nghi-dinh-188-2025-Kham-benh-trai-tuyen.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/Nghi-dinh-188-2025/Thuc-hien-Nghi-dinh-188-2025-Kham-benh-trai-tuyen.md)
![](https://lh3.googleusercontent.com/pw/AP1GczNg8SjTo5N5ju8W1O73C6DXgSi7tEm4tgTawvHpCpPfKSdMdl48NRoHhb6nc5Ox1kqxuJOJmxSR3KC-b5MN0byKRyvfZRNJiDEmuskpimlcW4cx-dCv7o4JpGXLNB0BYBcfBGieT-XuromB8Qzjvk-Y=w1555-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczOClubb2ZiyJ5Zt-iScibElpXumHM-q204ZZL-QiZ39eYT82CtcVQ6rvVWwpWJ6jzBTVRaXoWKoU9wu9WmdRbK5nIked_IFymQjJVNaMBVcwqXQkwpJp6j7hywGxaazXzQEl-LAg0FE2JGZewrxkAhK=w1555-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczPoCXu4xtcxhSLjejbw9sTNDsz-5lVrs-73EsmZI6AU6y641PIVHmoMziMi9WiM6QDkguWhUwS_CYR_diotl_KrY3PfZnQ61NMNbMdnBgwFuPTxgnA9ZcPoBIO8OQMlq91UYghDy4e0pkvy-umsGp3q=w1555-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczMWT7v9h_BS942DtGp7rP334bzBW2vmW03nxO4OVxkjK9OjfXe0oYdx9wRQMRRyhx_4da0-Q9BbLQiYpuxswC8QCZ6-nUJfGHUwNS1JYs-J0LuCawERXySXw4pD9pdavPYC7yDQ6fJy4FZG1ssULFD8=w763-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/852#issuecomment-31238

## [v.3.26.0723.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607230-NasDHSolutions.json)</sup></sup></sub>
- ✨: cầu - Cấp key HIS và Buiding các module triển khai cho Phòng khám đa khoa Thánh Tâm (TP. HCM (tỉnh Bình Dương cũ))- Yêu
- ✨: **_Bổ sung key theo Hợp đồng: `74167`._**
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/851#issuecomment-31292

## [v.3.26.0721.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607212-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607212-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607212-NasDHSolutions.json)</sup></sup></sub>

- ✨: Xuất dữ liệu XML ma_loai_kcb theo mô tả [XML130/QD4570/ma_loai_kcb_QD1804.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/ma_loai_kcb_QD1804.md).
![](https://lh3.googleusercontent.com/pw/AP1GczMYCP5XTSV4X6YPWI8I5Md_65BN9IPKPgpADRQmYSjR90eUsUW3JIeNgjPxILvDis_9BkLh0sCe73a7h00B1zpLxZ9RAhpCP2pHbaSzBV2Ji6TwQEOkYqJfoCqhKNw-ondO6ibrg3W95HhBz0WYRpvk=w1555-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/839#issuecomment-31029

## [v.3.26.0721.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607211-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607211-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607211-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📗: https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/CAU%20HINH%20IN%20PHIEU%20KCB%206556/BO_SUNG_CAU_HINH_AP_DUNG_VA_IN_BANG_KE_QD_697_BYT.md
- 📕: Cập nhật thay đổi Option 6556

![](https://i.vgy.me/ndvlks.png)

## [v.3.26.0721.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607210-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi Mẫu 01 (697) hiển thị sai bệnh kèm theo (khi không có chẩn đoán phụ).
![](https://lh3.googleusercontent.com/pw/AP1GczO6cBU4bVY21KXYq02beqVHEyGcof79YzUYNrqf6y3BhhVSxBCFGjWykB3lIkl_2KVx_dy2L4TR0JurKpOLaICnqTgYJAyVV-iEwJKIHUQkryxWdSnkoVYsSIoM-580Zp437y1dhbgPJeaxmt1Q9K2k=w1555-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/844#issuecomment-31141

## [v.3.26.0720.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607200-NasDHSolutions.json)</sup></sup></sub>

- ✨: Mẫu 01 (697) ⇒ Điều chỉnh lấy tên bệnh khác không bao gồm bệnh chính không thay thế các ký tự theo tham số `pcchandoan`.
![](https://lh3.googleusercontent.com/pw/AP1GczPW4oytg_7R2-b7ce4_MeDYONWG74sA_9Cj8enaLm1B-eWpdW_XXJrVKhZgeFDDX3_mqbqBHMxOUJ2q6HkonRnetRm4hDtw2hkFplgmqR78tPo3VikcvIxGSPAymQa4f6AmAU9A_9f6dAOAgFt6NSNL=w1654-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczN9sjTp-XhM5SV8YI2bAxdEML26zfIU6e4XP1ZaZZs4vx7DJJdEBNm28jNDI6gmZy-Pm_kmDNI_yO_wIJSe1cXrMpw0L8WPkr2tK8xWS25Cw6EkeLSRkUebEVjXr_WUQSQ9nZO-CriPAWacGRWh3XNl=w1555-h805-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/844#issuecomment-31026

## [v.3.26.0713.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607130-NasDHSolutions.json)</sup></sup></sub>

- ✨: Sử dụng UserControl `MaMayControl` cho phép chọn nhiều mã máy khi thực hiện CLS/TT/PT. Hỗ trợ xuất XML theo nhiều mã máy.
![](https://lh3.googleusercontent.com/pw/AP1GczMUKP9wfiT0u17bkprQXhuhdWdDwzLO6j8FzehyQtFM6AZ7mduluBq0M-6vIZgG9nIdwN6pwuzREvRAF7fdIUM6kPNMNbxDU5d2bYJm2mrOaowoTw6Qf6RAdScHHo6_BwADbBfPiscrrQhwMDiX9wt9=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/706#issuecomment-30270

## [v.3.26.0709.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607090-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer, Prescription hỗ trợ chữ ký số bác sĩ đối với toa thuốc thang TT55 (BV YHCT)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/815

![](https://i.vgy.me/6JQJWk.png)

## [v.3.26.0708.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607080-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng lấy trạng thái và chi phí trái tuyến mẫu 01 theo Nghị định 188/2025/NĐ-CP người bệnh trái tuyến theo mô tả [XML130/Nghi-dinh-188-2025/Thuc-hien-Nghi-dinh-188-2025-Kham-benh-trai-tuyen.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/Nghi-dinh-188-2025/Thuc-hien-Nghi-dinh-188-2025-Kham-benh-trai-tuyen.md).
![](https://lh3.googleusercontent.com/pw/AP1GczNcSBXWZ3dg2656Gq249HHqzmb740h1CU5Qn_IigaJiIC4UlU6wXs-en8waSq16pUQ4qYXUhFSlyS-PqM_o7uCRhhlv6eiT3MUreN4aYO4Xum1wNhM6Wpz0O-geENTNcqV3s3iA7UG6N8dir5gdlnDd=w1288-h671-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczPqyzX3athHC22qYC8cynaHUxVLQhp95MfJpepZqNF3Ep4oLhAnKw2og3G2sjdA-0WNimvF3iIteqeONg3ldZ-3Ifk1z14ocsjj-uWvC1ZoTgjMyhVo4LyTTUy9r5l_Oc3z-8GqpNmwOedWq90LvwmT=w767-h813-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczM0TIcdP0ztoda0tVDkEU39BArwfaAxEOKNtriHdmkhzhe8_ZQu0QAz85IuhcfZrKQwC2aGPj_SRMsYKsbNQc9JQBw4pZAUxByy6n0UQ_tn1suNYBgaWuGApioVi_3srB0fXQuJearVcRN22yKUMAwZ=w770-h844-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/814#issuecomment-30246

## [v.3.26.0707.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607070-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026
- 🐛: Fix xử lý lại sai tên nhóm khi cận lâm sàng có cho toa VTYT và sai nhóm đối với thuốc thuộc toa VTYT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716

![](https://i.vgy.me/aQ8e1A.png)

## [v.3.26.0706.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607060-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi tách sai chi phí thuộc đối tượng miễn phí nhưng tách ra thêm 1 bảng kê BHYT 
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716

![](https://i.vgy.me/gL0hV3.png)

## [v.3.26.0701.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607010-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607010-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32607010-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bổ sung Option 6556 và para để tuỳ chọn ký số cho Người lập bảng kê.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📗: https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/CAU%20HINH%20IN%20PHIEU%20KCB%206556/BO_SUNG_CAU_HINH_AP_DUNG_VA_IN_BANG_KE_QD_697_BYT.md

![](https://i.vgy.me/wmyFxu.png)

![](https://i.vgy.me/7bu2uZ.png)

![](https://i.vgy.me/Rnvjxa.png)

## [v.3.26.0630.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606303-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606303-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606303-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026
- 🐛: Fix lỗi chưa lưu được tên nhóm bảng kê vào XML3 cho VTYT và mất giá trị ma_doituong_kcb trên bảng kê
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: Set giá trị cho Ma_doituong_KCB trên bảng kê

![](https://i.vgy.me/7E2ckV.png)

## [v.3.26.0630.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606302-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606302-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606302-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026
- 🐛: Fix in dư trang in bảng kê KCB
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: Bổ sung EKeToanVienPhi khi in bảng kê FrmInphieuKK để ký số kế toán viện phí lên bảng kê

![](https://i.vgy.me/XVGAeT.png)

![](https://i.vgy.me/tB4FKf.png)

## [v.3.26.0630.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606301-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606301-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606301-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026 #716 (push lại)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: fix lỗi - Trên cùng một máy, khi đang dùng chức năng ký số bệnh nhân trên một module, thì module khác không thể kết nối tới máy ký số.

## [v.3.26.0630.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606300-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi không tìm thấy hàm in PDF khi in bảng kê
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716

![](https://i.vgy.me/o0L2uF.png)

## [v.3.26.0629.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606293-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606293-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606293-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: Bổ sung option sử dụng ký số cho kế toán viện phí
- 📕: Demo ký số kế toán viện phí cho bảng kê 6556
- 📕: Đặt lại tên Gói thiết bị y tế cho nhóm 10 thể hiện trên bảng kế

![](https://i.vgy.me/uo4GDW.png)

![](https://i.vgy.me/jvh9ME.png)

## [v.3.26.0629.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606292-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606292-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606292-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi phiếu 01 theo QĐ6556 không hiển thị được chữ ký người bệnh.
![](https://lh3.googleusercontent.com/pw/AP1GczM_fCLwxAkndMOlPVmyuZaRWa_DqGOcMPp_3GctG7xleqWM6gdnrKlpQBHfbTTiApt-QMGvLaXiESzLKl5P2Ywjyng8iW80WelbVV2JWYVsBCJU76kGfYJGOnauQrXRE4xZpQUbVfATy9lJ9uVmafYq=w1270-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczMzxeRPvaM0LNrg7eA8CWgJ4tbUObXoaixPXEMIw8Ve3rpLOORuKudASz_AAC6632oCdlpMzdQvWOxQFEaJV5BZYlE0MPuj2O_4Z61CHqJffDxtTai7jUEzeRZm7twbtPKhl_iKVhY8TXvS--AvOVt8=w731-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716#issuecomment-30144

## [v.3.26.0629.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606291-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606291-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606291-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026 #716 (push lại)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: fix lỗi khi bấm `xem lại chữ ký` không thấy lưu chữ ký lại.
- 📕: fix lỗi không lấy được tên bệnh nhân trên form ký
![](https://i.vgy.me/NVDOzj.png)

## [v.3.26.0629.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606290-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026 #716
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: fix lỗi khi bấm `bệnh nhân ký` mà chưa tạo bảng đính kèm.

## [v.3.26.0626.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606262-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606262-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606262-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026 #716
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: Bổ sung thêm chức năng view trước khi ký
- 📕: Bổ sung para chữ ký bệnh nhân
![](https://i.vgy.me/j477q4.png)
- 📕: Cập nhật giải quyết vấn đề dll STPadLib 32 pit và 64 pit
- 📕: thay đổi giao diện ký số của bệnh nhân và xem lại chữ ký
![](https://i.vgy.me/nGSdRi.png)

## [v.3.26.0626.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606261-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606261-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606261-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: Demo thêm chức năng ký số kế toán viện phí

![](https://i.vgy.me/DLJxZL.png)

![](https://i.vgy.me/J7T8KW.png)

## [v.3.26.0626.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606260-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026
- Bổ sung các function hổ trợ bệnh nhân ký số
- Bổ sung nút `bệnh nhân ký` và `xem lại chữ ký`
![](https://i.vgy.me/W1Jygq.png)
![](https://i.vgy.me/YoKWu4.png)
![](https://i.vgy.me/weycdR.png)
[Mô tả Scan_chu_ky_Evolis](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Chu-ky-so/Scan_chu_ky_Evolis.md)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716

## [v.3.26.0625.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606253-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606253-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606253-NasDHSolutions.json)</sup></sup></sub>
- ✨: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 🐛: Dư cột khi lưu thông tin xml130.bang3
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📕: Demo in bảng kê theo QĐ697

## [v.3.26.0625.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606252-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606252-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606252-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Mẫu bảng kê chi phí KCB mới theo QĐ 697/QĐ-BYT ngày 19/3/2026
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716
- 📗: https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/CAU%20HINH%20IN%20PHIEU%20KCB%206556/BO_SUNG_CAU_HINH_AP_DUNG_VA_IN_BANG_KE_QD_697_BYT.md
- 📕: Bổ sung option ngày áp dụng mẫu bảng kê theo QĐ 697

![](https://i.vgy.me/iN8NjP.png)

## [v.3.26.0625.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606251-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606251-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606251-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung cấu hình `Chữ ký người bệnh` tại form `Cấu hình phiếu 01 theo QĐ6556` theo mô tả [Chu-ky-so/Scan_chu_ky_Evolis.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Chu-ky-so/Scan_chu_ky_Evolis.md).
![](https://lh3.googleusercontent.com/pw/AP1GczNjzOc7x5fwUJyZbLsPlQHHbd4rdOISLEm3_-Rxf1Z_1o4Ls30ZylbBj0rNS1eHVhw4UI0z6fu5gU6N1U6QI0Cxno-5f2_LHm0J__gC6CGRBioVlEFuKE1UNKuIYunfmnvfBJ6tR5AVgYo2GadPPWyd=w1039-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716#issuecomment-29940

## [v.3.26.0625.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606250-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung cấu hình `Chữ ký người bệnh` tại form `Cấu hình phiếu 01 theo QĐ6556` theo mô tả [Chu-ky-so/Scan_chu_ky_Evolis.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Chu-ky-so/Scan_chu_ky_Evolis.md).
![](https://lh3.googleusercontent.com/pw/AP1GczNjzOc7x5fwUJyZbLsPlQHHbd4rdOISLEm3_-Rxf1Z_1o4Ls30ZylbBj0rNS1eHVhw4UI0z6fu5gU6N1U6QI0Cxno-5f2_LHm0J__gC6CGRBioVlEFuKE1UNKuIYunfmnvfBJ6tR5AVgYo2GadPPWyd=w1039-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/716#issuecomment-29940

## [v.3.26.0608.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606080-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung tự động tính chỉ số BMI trên form thông tin sinh hiệu theo mô tả: [THONG-TIN-BENH-NHAN/Chi-so-BMI.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/THONG-TIN-BENH-NHAN/Chi-so-BMI.md). Chỉ số BMI tự thay đổi khi cân nặng hoặc chiều cao thay đổi giá trị.
![](https://lh3.googleusercontent.com/pw/AP1GczM1yxUP_CUcC3cdYiaWS83c_fFkRlvYeZ7KlX4eXKTo3JJcjF-ofsBq0pxKdllTAmZGrtTtsSh9hspIDmGne71tF_Mlj6Wx64pzg6cFct7u1cX9bz2pax_2KE0o_XXeo3mnsYklGR-89704d7KWCGi6=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/777#issuecomment-29272

## [v.3.26.0605.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606050-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung tự động tính chỉ số BMI trên form thông tin sinh hiệu theo mô tả: [THONG-TIN-BENH-NHAN/Chi-so-BMI.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/THONG-TIN-BENH-NHAN/Chi-so-BMI.md).
![](https://lh3.googleusercontent.com/pw/AP1GczM1yxUP_CUcC3cdYiaWS83c_fFkRlvYeZ7KlX4eXKTo3JJcjF-ofsBq0pxKdllTAmZGrtTtsSh9hspIDmGne71tF_Mlj6Wx64pzg6cFct7u1cX9bz2pax_2KE0o_XXeo3mnsYklGR-89704d7KWCGi6=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/777#issuecomment-28830

## [v.3.26.0604.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606040-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi sai chính tả toa thuốc thang para chidinhuong khi tham số toathuocthang = 1
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/770

![](https://i.vgy.me/VMMxca.png)

## [v.3.26.0603.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606030-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer hỗ trợ toa thuốc YHCT, Thuốc Thang theo thông tư 55/2025/TT-BYT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/770
- 📕: https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Printer/PRINTER_HO_TRO_IN_TOA_THUOC_THANG_TT55.md

- toathuocthang = 0

![](https://i.vgy.me/4gZXwA.png)

- toathuocthang = 1

![](https://i.vgy.me/8EQPcF.png)

- toathuocthang = 2

![](https://i.vgy.me/bjYhKU.png)

## [v.3.26.0602.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606021-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606021-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606021-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi 
1. Hiển thị bệnh nhân BANT sai kho cấp phát:
![](https://lh3.googleusercontent.com/pw/AP1GczNgHDJaIvSjAuh2tMZAMutonp9c8IIe-JRCWryf_QZrGFfUEgnLQg9jWPHzjh_k5GVHEANyiHNCD6vmR_xtYFwmvljbDCdlRvUXn-h6YGIWiz00fSdy1RvTuTH8MbNJToaIEqNAoXFIFSiZj0PYZBVx=w1658-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczMVoTCZhZslQoOap8I1mYM2QxSIiriM2gl5ghtJUTxCtiv-rZFHa1Y15lA4-mSWZMz0qr3EAHGtiDtFnh5DGaeU9uUHtsogKhBOA-nmLDpmrZUm_xa6wAywqPivEtdZWmh9dLhTn5Fmtv-0Ohp3sRno=w1653-h879-s-no-gm?authuser=0)
2. Lỗi mở khóa toa trước ngày:
![](https://lh3.googleusercontent.com/pw/AP1GczMVoTCZhZslQoOap8I1mYM2QxSIiriM2gl5ghtJUTxCtiv-rZFHa1Y15lA4-mSWZMz0qr3EAHGtiDtFnh5DGaeU9uUHtsogKhBOA-nmLDpmrZUm_xa6wAywqPivEtdZWmh9dLhTn5Fmtv-0Ohp3sRno=w1653-h879-s-no-gm?authuser=0)
3. Lưu ý load bệnh nhân theo đối tượng và theo kho cấp phát theo cấu hình: nếu cấu hình mà đối tượng chưa có kho cấp phát
![](https://lh3.googleusercontent.com/pw/AP1GczOKq0Bi0kLsDf-4adAxmLP1YgDyo6WMIxgRJ1yQiM74vNK4KFJ2Xi-bWTYKxDndO-v8Lsx-6LsDIILqtwdaUh9Rsq1LS5ovsp0ijbNABxpPgxLYgxRTl6LPz3Dy7f7Ccx7G_ozU2G4YzRHgxYMD45oA=w1661-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczM1AbvnAqLyFsGMLR4-mU6UL6yoanOY0l_B_yNncPy27N80sqyImxYS0dI8wi6y3GOViOkcCwZ1HHYgYXrm1SBRixVN3Qg6bEhXv86-C-Wo-AT_tgMtZ8q0xEMdhWpnGi0pT5U558BMkouHPsOmy8N3=w1330-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/784#issuecomment-28877

## [v.3.26.0602.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32606020-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi 
1. Hiển thị bệnh nhân BANT sai kho cấp phát:
![](https://lh3.googleusercontent.com/pw/AP1GczNgHDJaIvSjAuh2tMZAMutonp9c8IIe-JRCWryf_QZrGFfUEgnLQg9jWPHzjh_k5GVHEANyiHNCD6vmR_xtYFwmvljbDCdlRvUXn-h6YGIWiz00fSdy1RvTuTH8MbNJToaIEqNAoXFIFSiZj0PYZBVx=w1658-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczMVoTCZhZslQoOap8I1mYM2QxSIiriM2gl5ghtJUTxCtiv-rZFHa1Y15lA4-mSWZMz0qr3EAHGtiDtFnh5DGaeU9uUHtsogKhBOA-nmLDpmrZUm_xa6wAywqPivEtdZWmh9dLhTn5Fmtv-0Ohp3sRno=w1653-h879-s-no-gm?authuser=0)
2. Lỗi mở khóa toa trước ngày:
![](https://lh3.googleusercontent.com/pw/AP1GczMVoTCZhZslQoOap8I1mYM2QxSIiriM2gl5ghtJUTxCtiv-rZFHa1Y15lA4-mSWZMz0qr3EAHGtiDtFnh5DGaeU9uUHtsogKhBOA-nmLDpmrZUm_xa6wAywqPivEtdZWmh9dLhTn5Fmtv-0Ohp3sRno=w1653-h879-s-no-gm?authuser=0)
3. Lưu ý load bệnh nhân theo đối tượng và theo kho cấp phát theo cấu hình: nếu cấu hình mà đối tượng chưa có kho cấp phát
![](https://lh3.googleusercontent.com/pw/AP1GczOKq0Bi0kLsDf-4adAxmLP1YgDyo6WMIxgRJ1yQiM74vNK4KFJ2Xi-bWTYKxDndO-v8Lsx-6LsDIILqtwdaUh9Rsq1LS5ovsp0ijbNABxpPgxLYgxRTl6LPz3Dy7f7Ccx7G_ozU2G4YzRHgxYMD45oA=w1661-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczM1AbvnAqLyFsGMLR4-mU6UL6yoanOY0l_B_yNncPy27N80sqyImxYS0dI8wi6y3GOViOkcCwZ1HHYgYXrm1SBRixVN3Qg6bEhXv86-C-Wo-AT_tgMtZ8q0xEMdhWpnGi0pT5U558BMkouHPsOmy8N3=w1330-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/784#issuecomment-28877

## [v.3.26.0529.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605290-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bệnh án ngoại trú hỗ trợ điều chỉnh ngày diễn biến trước ngày theo mô tả [THAM_SO_HE_THONG/Thay-doi-dien-bien-benh-an-ngoai-tru-truoc-ngay.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/THAM_SO_HE_THONG/Thay-doi-dien-bien-benh-an-ngoai-tru-truoc-ngay.md).
![](https://lh3.googleusercontent.com/pw/AP1GczN9uLX3Bddk7KK4D4RGANPoI-Z-4EEJggG3eCbh4ZE20_dQ21fKsyQVVoVosM_DIWsGDc5Oxw_VK9xO9KQFiJm3oIbVioNqzH0_5_frdiXL5iLVw3GWhr718TaDHZ96We3g5zwCkq4Yzrf3RtkcW6Gj=w1658-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/784#issuecomment-28772

## [v.3.26.0528.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605280-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Lỗi In toa thuốc ký số mẫu A5 in ra giấy A4 (PK Minh Quang)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/861
- 📕: Thiết đặt lại loại giấy lần nữa để in đúng khổ giấy trong hàm PrintReportDirect

![](https://i.vgy.me/FGEMxU.jpg)
![](https://i.vgy.me/EfQubP.jpg)

## [v.3.26.0527.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605270-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Lỗi In toa thuốc ký số mẫu A5 in ra giấy A4 (PK Minh Quang)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/861

- 📕: Cập nhật hàm ký số in trực tiếp không show preview và xác định ký số toa thuốc dựa vào tham số cks.toathuoc

![](https://i.vgy.me/YG0I2i.png)
![](https://i.vgy.me/pwK420.png)

## [v.3.26.0526.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605261-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605261-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605261-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng hiệu chỉnh thông tin tự chỉnh lại mã quyền lợi và hạn dùng thẻ BHYT #867
- 🐛: Phần mềm vẫn còn lỗi khi chọn đối tượng từ danh sách, nếu chọn đối tượng BHYT khác thì mất thông tin thẻ, nếu chọn đúng đối tượng đang có thì mất thông tin thẻ và khóa ô nhập thông tin thẻ:
![](https://i.vgy.me/SLy9oX.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/867

## [v.3.26.0526.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605260-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng hiệu chỉnh thông tin tự chỉnh lại mã quyền lợi và hạn dùng thẻ BHYT #867
- 🐛: Khi chọn đối tượng BHYT khác thì phần mềm tự cập nhật lại hạn dùng thẻ, mất thông tin thẻ, khóa nhập thông tin thẻ:
![](https://i.vgy.me/ELKL3p.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/867

## [v.3.26.0522.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605221-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605221-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605221-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng hiệu chỉnh thông tin tự chỉnh lại mã quyền lợi và hạn dùng thẻ BHYT #867
![](https://i.vgy.me/ad32ts.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/867

## [v.3.26.0522.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605220-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Lỗi In toa thuốc ký số mẫu A5 in ra giấy A4 (PK Minh Quang)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/861

- 📕: Lỗi do truyền vào hàm ký số cũ, khi xuất ra PDF làm thay đổi PaperKind
- 📕: Xử lý gọi và truyền thêm chữ ký vào hàm ký số mới.

![](https://i.vgy.me/b9gr1y.png)

## [v.3.26.0519.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605191-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605191-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605191-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung cấu hình `XML01.NGAY_VAO_NOI_TRU` đối với hồ sơ có `XML01.MA_LOAI_KCB = 02`.
![](https://lh3.googleusercontent.com/pw/AP1GczMvPFIsymuz1Q_pxf-tz2GKYCqVt7Fl_Jxt4W_GSR3nc8wVNR8g6WzmkYUZhD_nnHVEwVjQrBUb2X31RRuOkEsO1AQLJy-i-5nxzRchDzKk6gVVBn2wWf4ECM9DfYEmUbxxh8nn1pAhrPANUe1j-4L4=w1248-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczNgRTLYydV6D6KQ-H62-VDDWQh7QZmuNyeI7ah3Skj5h3fqs5WtdDijuRtWjuOJcZ5opaZl18wxZMWrDgtpviXZR7nEoGGS1hmAcJwIYtRNTDXT9P16LViV8JDirvIt0x9QK5nNiT4Z6G9eXol0V6dy=w1185-h543-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/855#issuecomment-27975

## [v.3.26.0519.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32605190-NasDHSolutions.json)</sup></sup></sub>

- ✨: Xuất XML04.MA_BS_DOC_KQ theo cấu hình lấy Ekip TT/PT từ mô tả [DIAGNOSE/Vuong_mota_chucnang_lap_ekip_thuchien_module_Diagnose.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/DIAGNOSE/Vuong_mota_chucnang_lap_ekip_thuchien_module_Diagnose.md), [XML130/QD4570/Table xml130.bang04 - [Phụ lục - Mô tả XML130 - Bổ sung QĐ 4750].md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang04%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md), [XML130/QD3176/Table xml3176.bang04 - [Phụ lục - Mô tả XML3176].md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD3176/Table%20xml3176.bang04%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML3176%5D.md).
![](https://lh3.googleusercontent.com/pw/AP1GczNrES4WLNZwaoXm_Fqcrt3V2qUv6qkjbdMrMiFmxsa_XObvV0d9cMQuJ3-bDiNVZ3xClujyQ5wqYxaXOGWaBoqAX5F5YN-QdD5GmF8-toB8QIzZTkGqEWleiZ6wGw2FlEFG-iOnSlLxDf90gXcVRQVk=w1576-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/713#issuecomment-27926

## [v.3.26.0429.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604290-NasDHSolutions.json)</sup></sup></sub>
- ✨- ✨: Yêu cầu - Diagnose Bộ ekipt trả kết quả thuộc kho Chẩn đoán hình ảnh cho phép chọn nhiều nhân viên thực hiện y lệnh #713
	- Cập nhật: 
		XML5: Cập nhật printer
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/713

## [v.3.26.0425.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604250-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Admin, service, printer Khi cài đặt mới không tạo được shortcut (BV Thạnh Trị)- Lỗi
- 🐛:  ***Chỉnh lỗi không tạo shortcut khi cài đặt.*** ![](https://images-worker.tlt46.workers.dev/i/019dc306-389a-742c-9786-28e47fccf28b)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/701#issuecomment-26569

## [v.3.26.0422.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604220-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Ẩn trường dain trên giao diện Form in phiếu KCB
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/817

![](https://i.vgy.me/5GqraD.png)

## [v.3.26.0421.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604210-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Ẩn trường dain trên giao diện Form in phiếu KCB
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/817

![](https://i.vgy.me/6yx4SP.png)

## [v.3.26.0413.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32604130-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Không mở khóa được Toa mua ngoài BANT theo đợt (Medic Miền Đông)
- 🐛: Fix lỗi kho BHYT vẫn load thông tin BANT đối tượng thu phí
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/768

![](https://i.vgy.me/AUrtp4.png)

## [v.3.26.0331.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603310-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603310-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603310-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi in toa thuốc mua ngoài BANT đợt sinh ra 2 dòng ở kho 14
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/768

![](https://files.catbox.moe/ywarfg.png)

## [v.3.26.0320.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603200-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Printer : Bảng kê -> Kê tổng hợp chi phí KCB không load được bệnh nhân chỉ có cận lâm sàng của Bệnh án ngoại trú theo ngày- Lỗi
- 🐛:  ***Chỉnh lỗi không thấy được bệnh nhân trong danh sách Mở khóa chứng từ.*** ![](https://images-worker.tlt15.workers.dev/i/019d0540-ff2e-75c2-ae87-103dc62ecb57)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/794#issuecomment-25163

## [v.3.26.0319.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603190-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Printer : Bảng kê -> Kê tổng hợp chi phí KCB không load được bệnh nhân chỉ có cận lâm sàng của Bệnh án ngoại trú theo ngày- Lỗi
- 🐛:  ***Chỉnh lỗi không thấy được bệnh nhân trong danh sách Mở khóa chứng từ.*** ![](https://images-worker.tlt15.workers.dev/i/019d0540-ff2e-75c2-ae87-103dc62ecb57)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/794#issuecomment-25163

## [v.3.26.0318.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603181-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603181-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603181-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi Printer : Bảng kê -> Kê tổng hợp chi phí KCB không load được bệnh nhân chỉ có cận lâm sàng của Bệnh án ngoại trú theo ngày- 
- 🐛:  ***Chỉnh lỗi không lấy được BANT theo ngày thực hiện in chỉ có CLS (nguyên nhân SQL bị sai điều kiện maxt!=07).*** ![](https://images-worker.tlt18.workers.dev/i/019d000a-1e9b-7b6b-8df1-5a2caed61c2b)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/794

## [v.3.26.0318.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603180-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: In phiếu 01 hiển thị lỗi nhưng vẫn in được phiếu #771
	
	- Cập nhật: không được chiều cao từ 2.3m đến 2.5m
		![](https://i.vgy.me/Y7cQqb.gif)

	P/s: @tvnghia: Có chức năng nào liên qua chiều cao em test hết dùm anh hén.

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/771

## [v.3.26.0312.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603120-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung nghiệp vụ hóa đơn điện tử Softdream
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/698

![](https://files.catbox.moe/7e20x6.png)

## [v.3.26.0311.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603110-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Không mở khóa được Toa mua ngoài BANT theo đợt
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/768

![](https://files.catbox.moe/036n1c.png)

![](https://files.catbox.moe/4bie4l.png)

## [v.3.26.0310.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603100-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hỗ trợ In tại Printer là in ra Toa thuốc có ký số luôn không cần view lên
- 🐛: Lỗi - Printer In toa thuốc + Phiếu thu (Thuộc kho nhà thuốc) không Ký số được Toa thuốc #777
![](https://i.vgy.me/KCJ4Km.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/777

## [v.3.26.0309.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603090-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hỗ trợ In tại Printer là in ra Toa thuốc có ký số luôn không cần view lên
- 🐛: Lỗi - Printer In toa thuốc + Phiếu thu (Thuộc kho nhà thuốc) không Ký số được Toa thuốc #777
![](https://i.vgy.me/KCJ4Km.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/777

## [v.3.26.0304.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603041-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603041-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603041-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung nghiệp vụ hóa đơn điện tử Softdream
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/698
- 📗: Mô tả : https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/FEES/BO_SUNG_THONG_TIN_CCCD_VA_QHNS_CHO_HDDT_SOFTDREAM.md

![](https://i.vgy.me/KVj0OB.png)

## [v.3.26.0304.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603040-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: In phiếu 01 hiển thị lỗi nhưng vẫn in được phiếu #771
	- Cập nhật:
		+ Nguyên nhân: nhập chiều cao quá lớn

		![](https://i.vgy.me/w0Novn.png)

		+ Printer chặn không cho in nếu chiều cao không hợp lệ 
		![](https://i.vgy.me/Qa62ji.png)

		+ Chỉnh chiều cao về đúng: 1.2m, in thành công và tạo được xml
		![](https://i.vgy.me/85DJTA.png)


- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/771

## [v.3.26.0302.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32603020-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer cải thiện lại Báo cáo khi xem theo sản phẩm
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/693

![](https://i.vgy.me/NFeITN.png)

## [v.3.26.0228.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602280-NasDHSolutions.json)</sup></sup></sub>
- 🐛: LỖI - PRINTER - In toa mua ngoài (kho nhà thuốc) chưa loại trừ khi đã lập BANT
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/759

![](https://i.vgy.me/dfIwgX.png)

## [v.3.26.0225.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602251-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602251-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602251-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer chức năng mở khóa không load được bệnh nhân chỉ có công khám đã in phiếu 6556
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/756

![](https://i.vgy.me/SYiqdk.png)

## [v.3.26.0225.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602250-NasDHSolutions.json)</sup></sup></sub>
- ✨: YÊU CẦU - XML3176: cột MA_BENH_KT và CHAN_DOAN_RV tự động loại bỏ các khoảng trắng dư thừa mã ICD khi có khoản trắng
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/687

![](https://i.vgy.me/DVP7sU.png)

## [v.3.26.0224.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602242-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602242-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602242-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Admin chức năng gửi tự động XML3 sai tên cls so với danh mục (BV DDKTP CT) - LOI - dh-issue- #730
- 🐛:  ***Xử lý không loại bỏ các ký tự rác (không thể hiện trong unicode) đối với trường TEN_DICH_VU, đảm bảo giống danh mục gửi cổng BHXH.***
- ![](https://images-worker.tlt31.workers.dev/i/019c8e89-0e51-7527-a862-b2a2c76555c8)
![](https://images-worker.tlt34.workers.dev/i/019c8e88-d3d4-754b-bcb5-421444e46ef5)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/730

## [v.3.26.0224.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602241-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602241-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602241-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  LỖI - ADMIN - QĐ 3176: XML1 - CHAN_DOAN_RV không có dữ liệu - LOI - dh-issue- #749
- 🐛:  ***Chỉ lấy bản ghi có kqcdoan không rỗng, thay vì chỉ lấy bản ghi mới nhất bất kể có dữ liệu hay không, đối với trường hợp cấu hình sử dụng chỉ lấy phòng khám cuối.***
- 🐛: Thay đổi chính: Thêm .Where(x => !String.IsNullOrEmpty(x.kqcdoan)) trước OrderByDescending để lọc ra các bản ghi có kết quả chẩn đoán, sau đó mới sắp xếp theo ngày và lấy bản ghi mới nhất — đảm bảo CHAN_DOAN_RV luôn có dữ liệu ![](https://images-worker.tlt33.workers.dev/i/019c8e4c-729c-7ce3-815e-97fe1e0a58d4)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/749

## [v.3.26.0224.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602240-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Admin chức năng gửi tự động XML3 sai tên cls so với danh mục (BV DDKTP CT) - LOI - dh-issue- #730
- 🐛:  ***Chỉnh lỗi mất dấu Tiếng  Việt khi xuất XML4750.*** ![](https://images-worker.tlt36.workers.dev/i/019c8dd1-d764-71df-8881-3e0813f253dd)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/730

## [v.3.26.0205.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602050-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi _ Printer Khi bấm nút In Toa thuốc + Mẫu BHYT (Toa thuốc hiển thị sai tiêu đề)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/731

![](https://i.vgy.me/y4kxtH.png)

## [v.3.26.0204.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602040-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Xem hoặc in toa thuốc lấy sai thông tin para taikhamngaykhi, thiếu thông tin liều dùng, lỗi tachtoa #733
![](https://i.vgy.me/dOKFbk.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/733

## [v.3.26.0203.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602030-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer Bệnh án ngoại trú theo ngày In bảng kê 01KCB và vào Form Mở khóa hiện 2 dòng cùng một bệnh nhân
![](https://i.vgy.me/D2AXKq.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/723

## [v.3.26.0202.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32602020-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Admin bổ sung chức năng Ngưng sủ dụng chữ ký số và thêm nút Xóa Chữ ký số
- Cập nhật lại chức năng ký số, khi kiểm tra chứng thư số, chỉ kiểm tra chứng thư số có `current.dmcts.xoa = 0`
[Mô tả](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Thong-mo-ta-chuc-nang-ngung-su-dung-chu-ky-so.md)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/657

## [v.3.26.0128.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601281-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer hỗ trợ cập nhật lại đúng Chẩn đoán Ra viện của Bệnh án ngoại trú theo ngày khi In phiếu 01KCB
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/665
- 📕: Mô tả https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KHAMBENH/THAY_DOI_LAY_CHAN_DOAN_BANT_NGAY_XML_6556.md

![](https://files.catbox.moe/36ia02.png)

![](https://files.catbox.moe/mw347o.png)

## [v.3.26.0128.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601280-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer hỗ trợ cập nhật lại đúng Chẩn đoán Ra viện của Bệnh án ngoại trú theo ngày khi In phiếu 01KCB
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/665

- 📕: Mô tả https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KHAMBENH/THAY_DOI_LAY_CHAN_DOAN_BANT_NGAY_XML_6556.md

![](https://files.catbox.moe/36ia02.png)

![](https://files.catbox.moe/mw347o.png)

## [v.3.26.0126.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601261-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601261-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601261-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Bảng kê -> Kê toa tổng hợp -> Theo sản phẩm không hiểu thị đơn vị tính của hàng hóa #715
	- Cập nhật:
		
		![](https://i.vgy.me/5DjglL.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/717

## [v.3.26.0126.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601260-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Hiệu chỉnh thông tin cảnh báo thiếu sinh hiệu nhưng nhập vào không lưu được #714
![](https://i.vgy.me/u3ZqgS.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/714

## [v.3.26.0122.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601222-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601222-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601222-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer Toa thuốc thang in sai mẫu so với Prescription (BV YHCT CT)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/703

![](https://files.catbox.moe/9ule34.png)

## [v.3.26.0122.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601221-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601221-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601221-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Hiệu chỉnh thông tin bệnh nhân có BANT không chỉnh được thông tin lãnh thuốc Lao, thông tin chuyển viện #710
![](https://i.vgy.me/44GRcO.png)
![](https://i.vgy.me/8Swtms.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/710

## [v.3.26.0122.0]()

- 🐛: Sửa lỗi chức năng chỉnh thông tin bệnh nhân ngoại trú.
![](https://lh3.googleusercontent.com/pw/AP1GczNyuMsT4TrCA1zLwWcnmyAyU1_wngFutkc97E4Kbq_dJiMSPc_6wyWciF1jdudbVKQQX3VATOzszXePDOD_2LHoD6Gzly0EOKN5RzmI-kP3DppqirmZlo8iiEQAeiACIBMJxSqj2WhuQsnxrKUm5W97=w1653-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/704

## [v.3.26.0114.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601141-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601141-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601141-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer : Bảng kê -> Kê toa theo bác sĩ bổ sung cho lọc theo tài khoản chỉ định #644
	- Cập nhật lại tiêu đề thống kê:

	 ![](https://i.vgy.me/yaCwmT.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/644

## [v.3.26.0114.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601140-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Printer : Bảng kê -> Kê toa theo bác sĩ bổ sung cho lọc theo tài khoản chỉ định #644
	- Cập nhật:
		- Theo sản phẩm:
			- Thống kê theo bác khám

			![](https://i.vgy.me/0UCzsP.png)

			- Thống kê theo tài khoản nhập

			![](https://i.vgy.me/G9csl6.png)

		- Theo hóa đơn:
			- Thống kê theo bác khám

			![](https://i.vgy.me/zV3F0y.png)

			- Thống kê theo tài khoản nhập

			![](https://i.vgy.me/id2zgl.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/644

## [v.3.26.0113.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601130-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bổ sung kiểm tra trường hợp bệnh nhân không lấy thuốc
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/570
- 📕: Điều chỉnh điều kiện kiểm tra số phút tối thiểu in phiếu 6556 trường hợp không lấy thuốc

![](https://files.catbox.moe/4yee0a.png)

- 🐛: Lỗi - Printer chức năng in bảng kê 6556 cảnh báo sai tiền bệnh nhân trả (BV Ô Môn)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/684
- 📕: Set giá trị tiền bệnh nhân trả khi có áp giá BHYT cho thuốc tại EGiamDinh_XML2.GetBntra()

![](https://files.catbox.moe/4yee0a.png)

## [v.3.26.0111.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601110-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi Thuốc không cấu hình loại toa bị in 2 toa khác nhau.
![](https://lh3.googleusercontent.com/pw/AP1GczOYDhrhpSa_sxUL0BZ90OilAjTibgkIgXMf8mgTsPEMNMhHtIhkWmsORpo72l5HnVJzDCh4I8PTA3CHhaCZwK4-hhd7Y9achfake3PlqOe1lgIUODaAkS61NoGOu1b8M_kCCcHEJ30XhFAZgIGGlzu7=w1059-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczM6AEuJqUaLfPL6Ux9Jy-pm4Pk4F1qIRHdoR5rHmJQEyVCx9eP7s-TLz8FKIYlS5wQlEZtgYubLwHxmNapp-7uKUGnaOX4hrcYra_liYp7EBT8T2r5ZNXovgntO7EZF3KdnuAeIQp9YyJrpTU9oDZ0Q=w1050-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/595

## [v.3.26.0110.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601101-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601101-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601101-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung toa thuốc ARV theo mô tả [ARV/Thuoc-ARV-quy-toan-cau.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/ARV/Thuoc-ARV-quy-toan-cau.md).
![](https://lh3.googleusercontent.com/pw/AP1GczPwWjgU5MfqCXeVdrAjrL-IgrISTzl8UkZQYXZpr3k1h3C1KIDAxOyWnn1T6NZPPYriBGVjGZqCQcmFweW3ph0Mbb4MDZNJ4ohaGO_dpcKz187Fs9uII4hjTJ69ke8UMVZFsgOKYqotKg-zvK7t0Ibn=w610-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/595

## [v.3.26.0110.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32601100-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung toa thuốc ARV theo mô tả [ARV/Thuoc-ARV-quy-toan-cau.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/ARV/Thuoc-ARV-quy-toan-cau.md).
![](https://lh3.googleusercontent.com/pw/AP1GczPwWjgU5MfqCXeVdrAjrL-IgrISTzl8UkZQYXZpr3k1h3C1KIDAxOyWnn1T6NZPPYriBGVjGZqCQcmFweW3ph0Mbb4MDZNJ4ohaGO_dpcKz187Fs9uII4hjTJ69ke8UMVZFsgOKYqotKg-zvK7t0Ibn=w610-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/595

## [v.3.25.1231.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512310-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512310-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512310-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer : In toa thuốc + Mẫu BHYT Không lấy đúng chữ Ký số của bác sĩ cho toa thuốc
![](https://i.vgy.me/pCOatS.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/673

## [v.3.25.1230.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512301-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512301-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512301-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - PK Đông Tây: Cấu hình số phút từ ngày giờ cấp toa, kết quả CLS đến ngày giờ in phiếu
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/570

- 📗: Mô tả [CAU_HINH_SO_PHUT_TOI_THIEU_IN_PHIEU_6556.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/CAU%20HINH%20IN%20PHIEU%20KCB%206556/CAU_HINH_SO_PHUT_TOI_THIEU_IN_PHIEU_6556.md)

![](https://i.vgy.me/Ace6Ip.png)

![](https://i.vgy.me/o78ZCV.png)

## [v.3.25.1230.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512300-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Admin chức năng xuất XML 4750 bổ sung XML13.ten_dich_vu đối với bệnh nhân không có chi phí cls (BV Ô Môn) - YEUCAU - dh-issue- #622
- ✨:  ***Bổ sung cấu hình mặc định khi XML13 không có dịch vụ được chỉ định.***
- ![](https://images-worker.tlt30.workers.dev/i/019b6d8a-2fe5-700a-beaf-95dfb1066e14)![](https://images-worker.tlt27.workers.dev/i/019b6d8e-87ab-7509-bbdd-855462d2ed2f)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/622#issuecomment-21413

## [v.3.25.1224.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512240-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi chức năng xuất XML4750 khi in phiếu 01 ngoại trú.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/614

## [v.3.25.1223.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512230-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung cấu hình lấy chẩn đoán theo phòng khám đối với khám ngoại trú khi xuất XML4750 theo mô tả [XML130/QD4570/Table xml130.bang01 - [Phụ lục - Mô tả XML130 - Bổ sung QĐ 4750].md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang01%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md).
![](https://lh3.googleusercontent.com/pw/AP1GczMHUM0iTM8gf48O0TICFZBwpqtfvH6tnYAwfxp9M6reFnk6XV86zfrf4qjHk2HNxDTRZH0WUURy_wgwnOXcvIpF4RnKF272xdOhs8epDfuoT8PYpoM4T2ytkxrVreenzZkmsiRag-XFTfzxgoBey3-J=w954-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/614

## [v.3.25.1219.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512190-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Hỗ trợ chức năng bổ sung chỉ số chuẩn đoán hình ảnh đối với XML4
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/585

- Cập nhật thư viện xuất XML4 theo option tách dòng chỉ số cho CDHA

![](https://i.vgy.me/sgxZQ8.png)

## [v.3.25.1209.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512092-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512092-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512092-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Hỗ trợ hàm tra cứu lịch sử KCB BHYT (BV Ô Môn) - YEUCAU - dh-issue- #549
- ✨:  ***Chỉnh thời gian token (phiên làm việc giá trị 10 phút, tự động lấy lại token mới khi hết hạn).*** ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/09/DESKTOP-2FLMTI6-explorer-2025-12-09-14h09p11.227.png) ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/09/DESKTOP-2FLMTI6-explorer-2025-12-09-13h45p09.655.png)
- ✨: ***Thêm chi tiết cảnh báo từ cổng giám định nếu thực hiện kiểm tra thông tuyến không được.*** ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/09/DESKTOP-2FLMTI6-explorer-2025-12-09-14h06p04.834.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/549#issuecomment-20300

## [v.3.25.1209.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512091-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512091-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512091-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Hỗ trợ hàm tra cứu lịch sử KCB BHYT (BV Ô Môn) - YEUCAU - dh-issue- #549
- ✨:  ***Chỉnh thời gian token (phiên làm việc giá trị 10 phút, tự động lấy lại token mới khi hết hạn).*** ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/09/DESKTOP-2FLMTI6-explorer-2025-12-09-14h09p11.227.png) ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/09/DESKTOP-2FLMTI6-explorer-2025-12-09-13h45p09.655.png)
- ✨: ***Thêm chi tiết cảnh báo từ cổng giám định nếu thực hiện kiểm tra thông tuyến không được.*** ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/09/DESKTOP-2FLMTI6-explorer-2025-12-09-14h06p04.834.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/549#issuecomment-20300

## [v.3.25.1209.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512090-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Admin : Hiệu chỉnh thời gian của ngày đăng ký - Ngày in phiếu 01KCB không lưu được - LOI - dh-issue- #658
- 🐛:  ***Chỉnh lỗi không lưu được dữ liệu khi gõ ngày thay đổi mà không chọn.*** 
- ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/09/DESKTOP-2FLMTI6-explorer-2025-12-09-09h28p18.536.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/658#issuecomment-20267

## [v.3.25.1208.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512082-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512082-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512082-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Printer bổ sung nhật ký in bảng kê tại printer (BV Thạnh Trị) - YEUCAU - dh-issue- #569
- ✨:  ***Bổ sung chức năng ghi nhật ký và phiên bản khi in phiếu thanh toán 01.*** ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/08/DESKTOP-2FLMTI6-explorer-2025-12-08-20h01p05.050.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/569

## [v.3.25.1208.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512081-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512081-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512081-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Hỗ trợ hàm tra cứu lịch sử KCB BHYT (BV Ô Môn) - YEUCAU - dh-issue- #549
- ✨:  ***Cập nhật chức năng lấy thêm thông tin lịch sử KCB theo công văn mới trường hợp cổng không trả về, theo tài liệu: api/egw/Lskcb2025.*** 
- ✨:  ***Xử lý gom chung logic kiểm tra thẻ giữa các phân hệ và Ordinal (theo tham số: kios.taikhoanthongtuyen)***
- ✨:  ***Cải tiến kiểm thông tuyến, lưu phiên làm việc 50 phút để sử dụng cho lần sau, trên cùng phân hệ.***
- ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/08/DESKTOP-2FLMTI6-explorer-2025-12-08-13h19p29.752.png)
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/08/DESKTOP-2FLMTI6-explorer-2025-12-08-11h41p42.454.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/549

## [v.3.25.1208.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512080-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Hỗ trợ hàm tra cứu lịch sử KCB BHYT (BV Ô Môn) - YEUCAU - dh-issue- #549
- ✨:  ***Cập nhật chức năng lấy thêm thông tin lịch sử KCB theo công văn mới trường hợp cổng không trả về, theo tài liệu: api/egw/Lskcb2025.*** 
- ✨:  ***Xử lý gom chung logic kiểm tra thẻ giữa các phân hệ và Ordinal (theo tham số: kios.taikhoanthongtuyen)***
- ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/12/08/DESKTOP-2FLMTI6-explorer-2025-12-08-13h19p29.752.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/549

## [v.3.25.1206.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32512060-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung ghi nhận chẩn đoán đầu tiên cập nhật theo mô tả [XML130/QD4570/bang1.chan_doan_vao.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/bang1.chan_doan_vao.md).
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/586

## [v.3.25.1126.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511261-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511261-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511261-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung cấu hình lấy chẩn đoán ra viện đối với hồ sơ khám ngoại trú theo cập nhật mô tả [XML130/QD4570/Table xml130.bang01 - [Phụ lục - Mô tả XML130 - Bổ sung QĐ 4750].md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang01%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md).
![](https://lh3.googleusercontent.com/pw/AP1GczNhYsTQTp-ge_cJROeHuypsTut15xZ9ywWirItIbXe92eIsKXj6H75tQTyYAjSKl5mIw2CnyM5bTdlFLmnOBPegp_PRIqwT5ceVURkpzgMalLEiNnCt1zHmdlV96r3V-S1_3Eq_Zgfmuhs25eLJU02I=w1160-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczMjE1vzgDUT7hg6Iuz3m0M64YdToJ50nCfzCTXD_Os-pSM0fguTl4J5x5d5VjDroYPxqlTupQhBabeZqA0pKeUZACM1cNiE4diPxJD6Y9TegPsiGG8geGUWs5R24g5qhQ10VACnD9XdgvgEOn8-4mV2=w1246-h494-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczN2lWfBJHlTRHgnppLwh_f_cB7NhM_tR73us4A-blHwI-Vi0UuhOO6XmwOxqhN_G44UBLDzsGnxvtE9KU2Y7tVNaCR_kievD0aeeY7wJDDJ-kgTpW2llSvRCwNBK80uRxvkapSH1xYvsPsLSoo9FtDJ=w1658-h879-s-no-gm?authuser=0)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/576

## [v.3.25.1126.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511260-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung cấu hình lấy chẩn đoán ra viện đối với hồ sơ khám ngoại trú theo cập nhật mô tả [XML130/QD4570/Table xml130.bang01 - [Phụ lục - Mô tả XML130 - Bổ sung QĐ 4750].md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/Table%20xml130.bang01%20-%20%5BPh%E1%BB%A5%20l%E1%BB%A5c%20-%20M%C3%B4%20t%E1%BA%A3%20XML130%20-%20B%E1%BB%95%20sung%20Q%C4%90%204750%5D.md).
![](https://lh3.googleusercontent.com/pw/AP1GczNhYsTQTp-ge_cJROeHuypsTut15xZ9ywWirItIbXe92eIsKXj6H75tQTyYAjSKl5mIw2CnyM5bTdlFLmnOBPegp_PRIqwT5ceVURkpzgMalLEiNnCt1zHmdlV96r3V-S1_3Eq_Zgfmuhs25eLJU02I=w1160-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczMjE1vzgDUT7hg6Iuz3m0M64YdToJ50nCfzCTXD_Os-pSM0fguTl4J5x5d5VjDroYPxqlTupQhBabeZqA0pKeUZACM1cNiE4diPxJD6Y9TegPsiGG8geGUWs5R24g5qhQ10VACnD9XdgvgEOn8-4mV2=w1246-h494-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczN2lWfBJHlTRHgnppLwh_f_cB7NhM_tR73us4A-blHwI-Vi0UuhOO6XmwOxqhN_G44UBLDzsGnxvtE9KU2Y7tVNaCR_kievD0aeeY7wJDDJ-kgTpW2llSvRCwNBK80uRxvkapSH1xYvsPsLSoo9FtDJ=w1658-h879-s-no-gm?authuser=0)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/576

## [v.3.25.1121.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511210-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Điều chỉnh cột bang3.ngay_kq theo mô tả XML4750.
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/627

## [v.3.25.1120.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511200-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi xuất dữ liệu XML4750 không lấy được ngày kết quả XML3.
![](https://lh3.googleusercontent.com/pw/AP1GczN2sAcCYM0ZNjKv7pWgQZ_tM2fruHvN46ua-nI0bj7bu5PWoHrCMIQMppJn1yQptI5E6IWud7ZkN3TJX_kLw2HKv1R1sOwQa_sb2fQb1nVEByzqIuDOjtJRT16abC_xRAsd2PsB16kiIiFJ3727fpQI=w1656-h879-s-no-gm?authuser=0)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/627

## [v.3.25.1114.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511141-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511141-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511141-NasDHSolutions.json)</sup></sup></sub>
- ✨: 🛣️Kết nối QR - Viettinbank cách mới
- ✨: Bổ sung cấu hình `custName` để trả lời đối với bước verify của đối tác, nếu có cấu hình sẽ lấy giá trị này gửi cho đối tác. Cấu trúc sẽ giống với cấu hình `"01":"9TNHLXS{{billNumber}}"`.
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/14/DESKTOP-2FLMTI6-explorer-2025-11-14-16h00p05.896.png)

## [v.3.25.1114.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511140-NasDHSolutions.json)</sup></sup></sub>
- ✨: 🛣️Kết nối QR - Viettinbank cách mới
- ✨: Bổ sung chức năng gửi các thông tin thanh toán lên serverQR để phục vụ cho bank thực hiện nghiệp vụ verify số tiền trước khi xác nhận thanh toán.
- ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/14/DESKTOP-2FLMTI6-sidekick-2025-11-14-08h17p42.333.png)
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/14/DESKTOP-2FLMTI6-explorer-2025-11-14-08h23p11.344.png)

## [v.3.25.1113.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511130-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng hiệu chỉnh thông tin bệnh nhân ngoại trú không load được thông tin bệnh nhân (BV Ô Môn ) #542(tt)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/619

## [v.3.25.1112.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511120-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  LỖI - Phiếu Phẫu thuật: Chọn Mã máy nhưng không hiển thị tên máy - XML3 không load được MA_MAY - LOI - dh-issue- #617
- 🐛:  ***Chỉnh lỗi không lấy được XML03.MA_MAY (Lý do, trong danh mục không lưu dạng Upper, mà lúc lập phiếu, lưu dữ liệu trong bảng current.phauthuat lại Upper lên).*** ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/12/DESKTOP-2FLMTI6-explorer-2025-11-12-18h41p24.397.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/617

## [v.3.25.1109.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511090-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  LỖI - Đăng ký nhận bệnh tìm kiếm tên địa phương - chọn tên đia phương có trùng tên viết tắt thì lỗi khi Chọn - LOI - dh-issue- #455
- 🐛:  ***Chỉnh lỗi khi chọn Xã, lại thể hiện sai thông tin.*** 
- ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/09/DESKTOP-2FLMTI6-explorer-2025-11-09-16h39p42.227.png)
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/09/DESKTOP-2FLMTI6-explorer-2025-11-09-16h35p08.076.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/455

## [v.3.25.1106.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511061-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511061-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511061-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng ghi nhận chẩn đoán sơ bộ theo mô tả [XML130/QD4570/bang1.chan_doan_vao.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/bang1.chan_doan_vao.md) khi xuất XML4750, cột `bang1.chan_doan_vao`:
![](https://lh3.googleusercontent.com/pw/AP1GczPPLQrg0O_KsVekrxgR9tetGMZFB8cz3ZO0F2-XRMzE5pbP4k4iLOGBkRgNa1g-jOBAi87YUCT-fV-POUTmsrpBmhku72u0ZfjOtijSmDSNnumpAavw8QldzxlZfkGk42Utj8P56slLr9kSFcYo6vWL=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/553

## [v.3.25.1106.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511060-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi không thay thế được HDDT Viettel
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/307

![](https://files.catbox.moe/21prmw.png)

## [v.3.25.1104.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511042-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511042-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511042-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi `MA_DOITUONG_KCB = 1.3`: psdangky.trangthaichuyentuyen=2 -> mã 1.3 nhưng phần mềm xuất mã khác.
![](https://lh3.googleusercontent.com/pw/AP1GczM-wVtPzqsiA6dPz1NmR36ddrJr9UJbrfWGZC6o8mWKNG29FORdmpaNfmJ2mXf62kn5kU1QTyUlBzwolkGdOaRxZLGJ3h9TwF8Nx48G-kEOSWzddSKUT988HLbd_lHdE1Olz4wNOexV8Umm-O7HFFYo=w909-h319-s-no-gm?authuser=0)

- 🐛: Cập nhật Mô tả: [XML130/QD4570/ma_doituong_kcb_qd3276.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/ma_doituong_kcb_qd3276.md). Chi tiết tại tại sheet `[MA_DOITUONG_KCB_3276]` của [Google Sheet: MA_DOITUONG_KCB_3276](https://docs.google.com/spreadsheets/d/1BJ-fbwLxY8W1kzgqmW-xd6CwgVw1g28TUTcZxblSans/edit?pli=1&gid=1845462824#gid=1845462824). Gồm:
1. Tại `MA_DOITUONG_KCB = 1.18`: Thêm điều kiện của ngoại trú `&& system.tuyenbv = 3`
![](https://lh3.googleusercontent.com/pw/AP1GczNvX7qZxsC5btnpJNggc1WqF9pTulC15OANKj0lSJm-GV2lqvzxJaqncr9sTphOM38iNKKOZ83N7cqfVCGEHaKklggV-vh6zPCtRg7MIn3UoB65Byl7k7dkHBBOZ3dYpswo5rzHIGMq6q38LNQq8xoj=w1239-h210-s-no-gm?authuser=0)
2. Tại `MA_DOITUONG_KCB = 3.2`: Điều chỉnh điều kiện của nội trú `system.tuyenbv = 3`
![](https://lh3.googleusercontent.com/pw/AP1GczM00wHVkCVMbD3l3d05KKfvXfI3EyqWMbIGgWIrclUEZ9qaKxi-WN_xU9KpLFEAj81GRUTgm0asyBHq3EFWQsn0ezb-xQ7vUT4I5TlQ0e4TpJZRL6nzGMbWT1YJYOcHKeEMaAoNyCoIMX7p-99h5ziO=w1299-h127-s-no-gm?authuser=0)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/537

## [v.3.25.1104.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511041-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511041-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511041-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Printer: Cảnh báo hoặc chặn in phiếu 01 khi có đang trong điều trị nội trú - YEUCAU - dh-issue- #546
- ✨:  ***Bổ sung thêm chức năng kiểm tra theo mã thẻ truyền vào. Trường hợp tìm theo makb không có thì tìm theo mathe, kèm điều kiện ngày nhập viện nhỏ hơn hoặc bằng ngày in phiếu, và trạng thái chưa ra viện.*** 
- ![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/04/DESKTOP-2FLMTI6-explorer-2025-11-04-14h15p07.837.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/546

## [v.3.25.1104.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32511040-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Không load được thông tin BANT đợt khi mở Chỉnh thông tin từ Printer
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/542

![](https://files.catbox.moe/hwn8pd.png)

## [v.3.25.1029.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510290-NasDHSolutions.json)</sup></sup></sub>

- ✨: Cập nhật `ma_doituong_kcb` theo [Quyết định 3276/QĐ-BYT](https://gofile.me/78TQg/twkbxNC6l) và theo mô tả [XML130/QD4570/ma_doituong_kcb_qd3276.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/ma_doituong_kcb_qd3276.md) khi xuất dữ liệu XML4750/XML3176.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/537

## [v.3.25.1024.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510240-NasDHSolutions.json)</sup></sup></sub>
🐛: Fix - Phát sinh lỗi khi thay thế hoá đơn từ Form Printer > Hoá đơn điện tử
☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/307

![](https://i.vgy.me/cG8oiI.png)

## [v.3.25.1023.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510230-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Fees: Lỗi khi thay thế hóa đơn MTT GTGT của VAT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/307

![](https://files.catbox.moe/3c4c6x.png)

## [v.3.25.1020.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510201-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510201-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510201-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Chức năng in phiếu KCB module printer ẩn bệnh nhân không có chi phí (BV Thạnh Trị) - YEUCAU - dh-issue- #520
- ✨:  ***Không lấy bệnh nhân đã lập BANT theo đợt trong phần CLS+CLS.*** ![](https://i.vgy.me/rzkEWm.png) ![](https://i.vgy.me/4WJnjU.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/520#issuecomment-17296

## [v.3.25.1020.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510200-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Chức năng in phiếu KCB module printer ẩn bệnh nhân không có chi phí (BV Thạnh Trị) - YEUCAU - dh-issue- #520
- ✨:  ***Không lấy bệnh nhân đã lập BANT theo đợt trong phần CLS+CLS.*** ![](https://i.vgy.me/rzkEWm.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/520#issuecomment-17296

## [v.3.25.1017.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510170-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510170-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510170-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung chức năng cập nhật thông tin hóa đơn điện tử
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/307

- Cho phép mở khoá, chỉnh toa nhà thuốc khi có phiếu thu và có Mở khoá thay thế.
- Cho phép mở khoá, chỉnh toa bản lẻ nhà thuốc khi có phiếu thu và có Mở khoá thay thế.
- Cập nhật lại chi phí là lý do thu cho đúng với tổng tiền chứng từ khi thực hiện nghiệp vụ Chỉnh phiếu thu đã lập HDDT nhà thuốc

![](https://files.catbox.moe/ra84ia.png)

## [v.3.25.1016.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510161-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510161-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510161-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi Mẫu in phiếu thu bán lẻ bị khuất chữ ở cột STT và chuỗi số tiền bằng chữ.
![](https://lh3.googleusercontent.com/pw/AP1GczOYLeQ19dWU-B8MjpCNalKVP05ENmzcuf7E1mAQRyoYVXUbi1kTzTTkM8i9mdCY7qa88OuCZnvUj1m4l9Lltz7Tfo3zCXjRAdlIXvZnv9honIFhGSpesn9FYyU787doaeRH7O9zG_Ib6x-WHJxdPWlF=w585-h879-s-no-gm?authuser=1)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/574

## [v.3.25.1016.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510160-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510160-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510160-NasDHSolutions.json)</sup></sup></sub>
- ✨: 🛣️Kết nối QR - Viettinbank cách mới

## [v.3.25.1015.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510152-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510152-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510152-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung chức năng kiểm tra hạn dùng thẻ BHYT (BV Thạnh Trị) #517
![](https://files.catbox.moe/a50kqg.png)
https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Thong-mo-ta-tham-so-kiem-tra-han-dung-the.md
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/517

## [v.3.25.1015.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510151-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510151-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510151-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung chức năng kiểm tra hạn dùng thẻ BHYT (BV Thạnh Trị)
![](https://files.catbox.moe/kz88p2.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/517

## [v.3.25.1015.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510150-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi xuất bán lẻ kho nhà thuốc => Chức năng In phiếu thu chỉ in 3 trang (trong khi có tổng cộng 6 trang).
![](https://lh3.googleusercontent.com/pw/AP1GczMUQQii9QBn4K0xgHky-VKEwuvHOmbMT6mJ73NXLebuOCn9YgS0wPqUC5oOrGdwyjiMJ_k0cN7ekeaF1uDQkH6_m-P14jdYbCQvR0dO-6qzlu7JZt8W3z69foB4F8093XoU0-laoZTRcOnoc63-JKop=w1185-h879-s-no-gm?authuser=1)

- 🐛: Sửa lỗi xuất bán lẻ kho nhà thuốc => Chức năng in mẫu C21 ở xuất bán lẻ không lấy được thông tin hàng hóa và đơn vị lên trang in.
![](https://lh3.googleusercontent.com/pw/AP1GczM1LQoLBpdOoQlBVrf2kgrYQgH6yPehMMJ2QrjPvJ0qakqN0Pp2jB2qBx0DjvyYkiraK-kqG_oWDQYYzNviXcS1a0EmZ8dOnXER_gNTtJYuVrdChsFCUl_RhYaCMaqRO3a0CRbi5_S3ZTolrTYbYn4K=w1658-h879-s-no-gm?authuser=1)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/574

## [v.3.25.1014.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510140-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Bổ sung chức năng kiểm tra cân nặng khi in bảng kê 6556 (BV Thạnh Trị) - YEUCAU - dh-issue- #503
- ✨:  ***Bỏ qua chức năng kiểm tra cân năng đối với BANT (vì đã kiểm tra ở chức năng ra viện).*** ![](https://i.vgy.me/yDmf7j.png) ![](https://i.vgy.me/cnL78l.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/503

## [v.3.25.1012.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510120-NasDHSolutions.json)</sup></sup></sub>
- ✨: 🛣️Kết nối QR - Viettinbank cách mới

## [v.3.25.1008.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510081-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510081-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510081-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Printer: Cảnh báo hồ sơ đã gửi Cổng trước khi mở khóa và xóa giờ kết thúc khám. - YEUCAU - dh-issue- #327
- ✨:  ***Bổ sung nhật ký mở khóa đã gửi BHXH.*** ![](https://i.vgy.me/h1NyQ5.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/327

## [v.3.25.1008.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510080-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Bổ sung chức năng kiểm tra cân nặng khi in bảng kê 6556 (BV Thạnh Trị) - YEUCAU - dh-issue- #503
- ✨:  ***Bổ sung chức năng kiểm tra cân nặng khi in phiếu 01, phải lớn hơn 1.*** ![](https://i.vgy.me/9wdxfO.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/503

## [v.3.25.1007.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510071-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510071-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510071-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu Cầu - FEES: Các vấn đề liên quan nghiệp vụ HĐĐT
- 🐛: Fix lỗi khi vừa lập HDDT vừa lập xong bấm xoá thì không lấy được thông tin HDDT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/338
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/307
- Cập nhật dll bổ sung nghiệp vụ xoá HDDT bằng cách thay thế hoá đơn 0 đồng.

![](https://i.vgy.me/DqpkrK.png)

![](https://i.vgy.me/DnlkQ6.png)

## [v.3.25.1007.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510070-NasDHSolutions.json)</sup></sup></sub>

- ✨: Cập nhật/thay đổi `ma_doituong_kcb` theo mô tả: [XML130/QD4570/ma_doituong_kcb_qd2010.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/ma_doituong_kcb_qd2010.md)
=> Thay đổi thứ tự ưu tiên:
![](https://lh3.googleusercontent.com/pw/AP1GczPIMIp3Zb2ii38ELIOeOPdf4tItbeMP-Rldxngmg0drpRa5D2r4GIHgP0AYd5YOlQs8kA6bRkXiPJ44QJrfg6BRn9_z73ZEDUr2yW0eiXPnYzUTHMq8QTjDoiIABDmSVd4_xZ51yjElmzVh-EjVuG9C=w1534-h608-s-no-gm?authuser=1)
![](https://lh3.googleusercontent.com/pw/AP1GczPdmIv7XLQM1x2scHDonWeZwE1Kly-gaUqU22lw6-HSM99W--4zD7wBbBt4Aqltnc1oIr7_KFHaXnx7J_hGCK-SComzeuxBQNUYadWhFwKZZTX8_-4TAZxDWIfKrRKbsAUaoslLKVJ80gAIacLhUdtw=w1658-h879-s-no-gm?authuser=1)

=> Thay đổi điều kiện đối với `ma_doituong_kcb = 1.2`:
![](https://lh3.googleusercontent.com/pw/AP1GczPEUwlFeHlv2oHFVrZMcrTcisPnUyeKpiAeQeW04QEB4UOz_7vZqeJ0pmoV5bpeHHBJCVsk2sNt-fT8rXINLRRp4_jHkQQp1Okkq6y9kOgLEd0dDJt0W-UGsSRDCIM_TXQaHv7JVLTFPv289CZxXE-3=w1397-h387-s-no-gm?authuser=1)
![](https://lh3.googleusercontent.com/pw/AP1GczMA6L-UhO2XZcuUVDUkai-ey5fuITAE9_v6oDWVxgW3lz_CWBQFihi_BVLeRpJb7oCFY2GUG6v0pNP2s015Fmz-XTgJ-6IDdOE5tUecWDo_2nWvFVpTIO88VZXaHkX4XQVaSesUcMlz7KPTxSPyJzx7=w1654-h879-s-no-gm?authuser=1)

=> Thay đổi điều kiện đối với `ma_doituong_kcb = 1.7 và 1.11`:
![](https://lh3.googleusercontent.com/pw/AP1GczNyDlPSKW7kQLRJG-xWgy6L3y3-SyJItWCeAZN8zsth4L6ZMnQbIxuNuuYdKPPApEnR7aOpWGGSiDOxEvRwafbCboQOHXiZOZF35kbyZaBNcx44ijW27oQhg5hj7HBKUClxC8HjynKIWWdC4a_Kybn9=w1411-h604-s-no-gm?authuser=1)
![](https://lh3.googleusercontent.com/pw/AP1GczNg4qBeCX-B8tT1-SbdJRa2dsnRuTj8JmjGs2snT86nJYVkQuJ4OP339Nz9epgR87R-GHHQa7CiuIkEFNr1MRvow1bGGjSJgG--iC8NMTYShliA81Me209qHY1XOxLIwbgnpWucw3riMcRVhzwheCBP=w1654-h879-s-no-gm?authuser=1)
![](https://lh3.googleusercontent.com/pw/AP1GczNAC6VQj7bD-4EIzmLabFfMQrbzy-HUPAcjbsmR30lrgcPK-zmF02j_VGcFgzz82Zt_iAkDfNCh4RIdO95BQ7DJT0O2WGCJs5ESJ25Jvp4Nqisz-ODKV4WIdTouSxO2nmArBk1TLlOlmhglxlYmZvC9=w1658-h879-s-no-gm?authuser=1)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/376

## [v.3.25.1003.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510031-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510031-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32510031-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Admin: XML1 lấy sai Tiền bảo hiểm thanh toán và tiền bệnh nhân cùng chi trả - LOI - dh-issue- #550
- 🐛:  ***Chỉnh lỗi tính sai chi phí đồng chi trả khi theo tham số baohiem.tinhvuotmuc=1.***  ![](https://storage.googleapis.com/accurately-sharp-katydid.appspot.com/ShareX/2025/10/DESKTOP-2FLMTI6-explorer-2025-10-03-15h13p38.426.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/550

## [v.3.25.1003.0]()
- 🐛:  Lỗi - Admin: XML1 lấy sai Tiền bảo hiểm thanh toán và tiền bệnh nhân cùng chi trả - LOI - dh-issue- #550
- 🐛:  ***Chỉnh lỗi tính sai chi phí đồng chi trả khi theo tham số baohiem.tinhvuotmuc=1.***  ![](https://storage.googleapis.com/accurately-sharp-katydid.appspot.com/ShareX/2025/10/DESKTOP-2FLMTI6-explorer-2025-10-03-15h13p38.426.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/550

## [v.3.25.0930.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509300-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bổ sung Thay thế `chuỗi Không chịu thuế` (nếu có) của cấu hình cho các mặt hàng cấu hình thuế nhỏ hơn 0
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/344

- Cập nhật thư viện lấy chuỗi thay thế (nếu có) khi lập hoá đơn điện tử

![](https://i.vgy.me/fg84c7.png)

![](https://i.vgy.me/RRYHQn.png)

## [v.3.25.0923.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509231-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509231-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509231-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Ràng buộc mã QHNS bắt buộc 7 ký tự theo Nghị định 70
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/372

![](https://i.vgy.me/Ibnx4x.png)

## [v.3.25.0923.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509230-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix khi `In BN không ký tên` của lần khám cũ có thông báo đã khoá nhưng vẫn đánh dấu dmthebhyt.chuaky = 1
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/520

![](https://i.vgy.me/VUFl2h.png)

## [v.3.25.0918.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509180-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Fees, Printer: Bổ sung thông tin theo NĐ70 khi lập hóa đơn điện tử
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/372

![](https://i.vgy.me/lI5HJ5.png)

![](https://i.vgy.me/9asQH9.png)

![](https://i.vgy.me/sAo1AH.png)

## [v.3.25.0910.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509100-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Lập hóa đơn điện tử bị sai tên thuốc.
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/491

- Xử trí lại sẽ không Replace ký tự "." khi lập HDDT cho phiếu thu nhà thuốc và sử dụng option chi tiết theo hàng hoá

![](https://i.vgy.me/xGQSPB.png)

![](https://i.vgy.me/sXTrQH.png)

## [v.3.25.0909.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509090-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Mã đối tượng không thuộc kho cấp phát vẫn load được bệnh nhân
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/480

- Chỉnh lại query lấy danh sách bệnh nhân chỉ có CLS+CK theo tham số hienthidsbncls

- hienthidsbncls = 0

![](https://i.vgy.me/OB6u4z.png)

![](https://i.vgy.me/5FYjf4.png)

![](https://i.vgy.me/9JcHkR.png)

- hienthidsbncls = 1

![](https://i.vgy.me/a4VOPj.png)

## [v.3.25.0904.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32509040-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Cột TH không check thực hiện trong form in phiếu KCB đối với PT/TT đã lập phiếu #479
	- Cập nhật:
	![](https://i.vgy.me/FE5Ewm.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/479

## [v.3.25.0829.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508291-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508291-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508291-NasDHSolutions.json)</sup></sup></sub>
- 🐛: LỖI - Mã thẻ có ký Hiệu TQ tại XML4750_Bảng 1 cột gt_the_den không hiển thị hạn thẻ - rebuild
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/468

- Cập nhật thư viện Loại trừ chữ cái TQ của mã thẻ không áp dụng theo option BHXH giá trị thẻ đến khi in bảng kê và xuất XML

![](https://i.vgy.me/Ueq7wb.png)

## [v.3.25.0829.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508290-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Bấm vào nút Không lấy thuốc đối tượng Thu phí báo lỗi tương tác với hệ thống (Push lại do nas đầy -> link ko tải được)
![](https://i.vgy.me/sG9Pyn.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/460

## [v.3.25.0828.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508281-NasDHSolutions.json)</sup></sup></sub>
- 🐛: LỖI - Mã thẻ có ký Hiệu TQ tại XML4750_Bảng 1 cột gt_the_den không hiển thị hạn thẻ
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/468

- Cập nhật thư viện Loại trừ chữ cái TQ của mã thẻ không áp dụng theo option BHXH giá trị thẻ đến khi in bảng kê và xuất XML

![](https://i.vgy.me/Ueq7wb.png)

## [v.3.25.0828.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508280-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Bấm vào nút Không lấy thuốc đối tượng Thu phí báo lỗi tương tác với hệ thống
![](https://i.vgy.me/sG9Pyn.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/460

## [v.3.25.0825.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508251-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508251-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508251-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: In phiếu 01 cột maicd trong psdangky load 2 mã ICD
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/466

![](https://i.vgy.me/987TcI.png)

## [v.3.25.0825.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508250-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Cập nhật nội dung nhật ký thao tác Mở khóa và xóa giờ kết thúc khám
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/429

![](https://i.vgy.me/m29owD.png)

## [v.3.25.0820.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508200-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - BV Phụ Sản: Cập nhật danh mục mã đối tượng khám bệnh chữa bệnh theo QĐ 2010/QĐ-BYT - YEUCAU - dh-issue- #376
- ✨:  ***Cập nhật theo mô tả [ma_doituong_kcb_qd2010.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XML130/QD4570/ma_doituong_kcb_qd2010.md).*** 
- ![](https://live.staticflickr.com/65535/54707350475_f09e427448_b.jpg)
- ![](https://live.staticflickr.com/65535/54707214108_b164970a2c_c.jpg) ![](https://live.staticflickr.com/65535/54733205091_8408f3406f_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/376

## [v.3.25.0819.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508190-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - BV Sa Đéc: XML 130 sai số tiền và số lượng thuốc khi bệnh nhân có chỉ định số lượng 3 số thập phân - LOI - dh-issue- #422
- 🐛:  ***Chỉnh lỗi không xuất được XML130 khi in phiếu 01 ở Prescription, lên Printer xác nhận, nhưng cấu hình số bản in 0.***![](https://live.staticflickr.com/65535/54730920725_aa87f789af_b.jpg) ![](https://live.staticflickr.com/65535/54730567591_f99c1890bb_b.jpg) 
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/422

## [v.3.25.0818.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508182-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508182-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508182-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Prescription: Bảng kê 6556 in thiếu tên chẩn đoán phụ (BV Cù Lao Minh) - LOI - dh-issue- #433
- 🐛:  ***Xử lý lỗi trùng chẩn đoán, điều kiện kiểm tra cùng nếu chẩn đoán phụ có chứa tên chẩn đoán chính, và phải có dấu ; mới tính là trùng.***
- ![](https://live.staticflickr.com/65535/54728172044_e584e921cc_b.jpg) ![](https://live.staticflickr.com/65535/54727946691_4522f6c142_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/433

## [v.3.25.0818.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508181-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508181-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508181-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - BV Sa Đéc: XML 130 sai số tiền và số lượng thuốc khi bệnh nhân có chỉ định số lượng 3 số thập phân - LOI - dh-issue- #422
- 🐛:  ***Chỉnh lỗi in và không tạo xml130 khi in phiếu 01.*** ![](https://live.staticflickr.com/65535/54727146322_cf4c0d193f_b.jpg) ![](https://live.staticflickr.com/65535/54728204079_cb709999f1_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/422

## [v.3.25.0818.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508180-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Lỗi Void DH.XML4750.HOSO..ctor khi in bảng kê - cập nhật tháng kế toán, cập nhật đối chiếu hồ sơ XML - LOI - dh-issue- #448
- 🐛:  ***Chỉnh lỗi khi in và xuất XML130.***
- ![](https://live.staticflickr.com/65535/54728056553_491beb41f0_b.jpg)![](https://live.staticflickr.com/65535/54728071699_5f7318fcaf_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/448

## [v.3.25.0815.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508152-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508152-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508152-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer In Toa thuốc + Mẫu BHYT không xuất được XML 4750
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/429

![](https://i.vgy.me/XwJx38.png)

## [v.3.25.0815.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508151-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508151-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508151-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Không mở khóa chứng từ được.
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/447

![](https://i.vgy.me/RNTGsO.gif)

## [v.3.25.0815.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508150-NasDHSolutions.json)</sup></sup></sub>
- ✨: Lấy số lẻ theo option cấu hình làm tròn số lẻ riêng cho nhà thuốc sử dụng HDDT VAT MTT, Bổ sung thông tin CCCD và QHNS lên Form lập hoá đơn nhà thuốc
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/391
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/339

- Bổ sung thông tin CCCD và QHNS lên Form lập hoá đơn nhà thuốc [YEUCAU/issues/339](https://i.dh-his.com/hdhiswork/YEUCAU/issues/339)

- Mô tả : [BO_SUNG_THONG_TIN_CCCD_VA_QHNS_CHO_HDDT.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/FEES/BO_SUNG_THONG_TIN_CCCD_VA_QHNS_CHO_HDDT.md)

- Lấy số lẻ theo option cấu hình làm tròn số lẻ riêng cho nhà thuốc sử dụng HDDT VAT MTT [YEUCAU/issues/391](https://i.dh-his.com/hdhiswork/YEUCAU/issues/391)

![](https://i.vgy.me/OEEx6G.png)

## [v.3.25.0813.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508130-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Fees/Printer: Bổ sung cấu hình số lẻ cho hóa đơn GTGT MTT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/391

![](https://i.vgy.me/r9L5k6.png)

## [v.3.25.0807.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508070-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - BV Sa Đéc: XML 130 sai số tiền và số lượng thuốc khi bệnh nhân có chỉ định số lượng 3 số thập phân - LOI - dh-issue- #422
- 🐛:  ***Xuất XML2 với số lượng 3 chữ số thập phân.***
- ![](https://live.staticflickr.com/65535/54704797211_8d893a2d41_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/422

## [v.3.25.0806.4]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508064-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508064-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508064-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Lỗi Void DH.XML4750.HOSO..ctor khi in bảng kê - cập nhật tháng kế toán, cập nhật đối chiếu hồ sơ XML - LOI - dh-issue- #448
- 🐛:  ***Chỉnh lỗi in phiếu 01.*** ![](https://live.staticflickr.com/65535/54703854555_cc22e82e9a_b.jpg)![](https://live.staticflickr.com/65535/54702687517_897844de63_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/448

## [v.3.25.0806.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508063-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508063-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508063-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Lỗi Void DH.XML4750.HOSO..ctor khi in bảng kê - cập nhật tháng kế toán, cập nhật đối chiếu hồ sơ XML - LOI - dh-issue- #448
- 🐛:  ***Chỉnh lỗi code không cập nhật được xml.***![](https://live.staticflickr.com/65535/54703098515_0557950e96_b.jpg) ![](https://live.staticflickr.com/65535/54702968608_51f46006dc_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/448

## [v.3.25.0806.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508062-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508062-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508062-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Lỗi Void DH.XML4750.HOSO..ctor khi in bảng kê - cập nhật tháng kế toán, cập nhật đối chiếu hồ sơ XML - LOI - dh-issue- #448
- 🐛:  ***Chỉnh lỗi code không cập nhật được xml.***![](https://live.staticflickr.com/65535/54703098515_0557950e96_b.jpg) ![](https://live.staticflickr.com/65535/54702968608_51f46006dc_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/448

## [v.3.25.0806.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508061-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508061-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508061-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - BV Sa Đéc: XML 130 sai số tiền và số lượng thuốc khi bệnh nhân có chỉ định số lượng 3 số thập phân - LOI - dh-issue- #422
- 🐛:  ***Tăng số chữ số làm tròn đối với tiền thuốc, vtyt lên 3 con số.*** ![](https://live.staticflickr.com/65535/54698688405_7329156e63_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/422

## [v.3.25.0806.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508060-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Lỗi Void DH.XML4750.HOSO..ctor khi in bảng kê - cập nhật tháng kế toán, cập nhật đối chiếu hồ sơ XML - LOI - dh-issue- #448
- 🐛:  ***Chỉnh lỗi code không cập nhật được xml.***![](https://live.staticflickr.com/65535/54703098515_0557950e96_b.jpg) ![](https://live.staticflickr.com/65535/54702968608_51f46006dc_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/448

## [v.3.25.0801.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508011-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508011-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508011-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lấy sai thông tin đơn vị khi sử dụng Hoá đơn VAT MTT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/283

- Không có tên đơn vị
![](https://i.vgy.me/BYoCVG.png)

- Có tên đơn vị
![](https://i.vgy.me/o0bOQA.png)

## [v.3.25.0801.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508010-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508010-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32508010-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix không thể hiện chi tiết theo mặt hàng khi lập hoá đơn nhà thuốc Hoá đơn VNPT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/292

![](https://i.vgy.me/SQBrcj.png)

## [v.3.25.0729.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507292-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507292-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507292-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Prescription in bảng kê 01KCB tại Prescription XML4210 và 4750 mã bệnh chính lại đem qua cột mã bệnh khác #418
	- Cập nhật printer
	- mở khóa
	![](https://i.vgy.me/iSD27k.png)

	- In phiếu:
	![](https://i.vgy.me/bNDFg8.png)

	- Report
	![](https://i.vgy.me/tjWBj2.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/418

## [v.3.25.0729.1]()
- 🐛: Lỗi - Prescription in bảng kê 01KCB tại Prescription XML4210 và 4750 mã bệnh chính lại đem qua cột mã bệnh khác #418
	- Cập nhật printer
	- mở khóa
	![](https://i.vgy.me/iSD27k.png)

	- In phiếu:
	![](https://i.vgy.me/bNDFg8.png)

	- Report
	![](https://i.vgy.me/tjWBj2.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/418
<<<<<<< HEAD

## [v.3.25.0729.0]()
- 🐛: Lỗi - Prescription in bảng kê 01KCB tại Prescription XML4210 và 4750 mã bệnh chính lại đem qua cột mã bệnh khác #418
	- Cập nhật printer
	- mở khóa
	![](https://i.vgy.me/iSD27k.png)

	- In phiếu:
	![](https://i.vgy.me/bNDFg8.png)

	- Report
	![](https://i.vgy.me/tjWBj2.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/418
=======

## [v.3.25.0724.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507240-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi không sử dụng được Nút Lập và in hoá đơn điện tử khi lập hoá đơn tại Printer HDDT VAT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/283

![](https://i.vgy.me/17P68v.png)

## [v.3.25.0723.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507230-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung nghiệp vụ điều chỉnh/thay thế HĐĐT đối với Hóa đơn điện tử - VAT
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/283

- Cập nhật bổ sung tổng tiền thuế khi lập HDDT VAT
![](https://i.vgy.me/yJKygB.png)

## [v.3.25.0722.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507220-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: BV Thanh Bình - Printer không in được bảng kê (Bác sĩ chưa xác nhận kết thúc khám, không thể in phiếu!)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/415

![](https://live.staticflickr.com/65535/54670679749_c061b6616a_b.jpg)
![](https://live.staticflickr.com/65535/54670441796_957e1cc63c_b.jpg)

## [v.3.25.0721.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507211-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507211-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507211-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: BV Tâm Phúc: Printer báo cáo Kê toa theo đối tượng -> Theo sản phẩm thống kê sai chi phí
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/417

![](https://live.staticflickr.com/65535/54668332096_cece00b18c_b.jpg)
![](https://live.staticflickr.com/65535/54668571864_6ddd7c6c1d_b.jpg)

## [v.3.25.0721.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507210-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Cập nhật đối tượng chưa đúng khi bệnh nhân BANT (theo ngày, theo đợt) có hiệu chỉnh thông tin
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/409

- Fix Load sai thông tin madt đối với BANT quyết toán theo đợt.
- Đối với BANT ngày => psdangky.madt. BANT đợt => bnnoitru.madt

![](https://live.staticflickr.com/65535/54667419307_ab069685da_b.jpg)
![](https://live.staticflickr.com/65535/54668474398_3d240486c3_b.jpg)

## [v.3.25.0718.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507180-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer nút In Toa thuốc + Mẫu BHYT (In phiếu 01KCB) không set được trạng thái dain bảng psdangky
![](https://i.vgy.me/E1ooQf.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/416

## [v.3.25.0717.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507170-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507170-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507170-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer nút In Toa thuốc + Mẫu BHYT (In phiếu 01KCB) không set được trạng thái dain bảng psdangky #416
![](https://i.vgy.me/6kQULA.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/416

## [v.3.25.0714.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507140-NasDHSolutions.json)</sup></sup></sub> <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507140-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Printer: Mở chức năng hóa đơn điện tử cho BỆNH VIỆN ĐA KHOA SỐ 10 - YEUCAU - dh-issue- #366
- ✨:  ***Bổ sung theo yêu cầu và biên bản họp tuần.*** ![](https://live.staticflickr.com/65535/54653392961_c3b34ef161_c.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/366

## [v.3.25.0713.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507130-NasDHSolutions.json)</sup></sup></sub>
- ✨:  YÊU CẦU - Bổ sung Danh mục địa phương theo Công văn số 1027/CTK-CSCL (gọi tắt Danh mục theo CV 915/CTK-CSCL) - YEUCAU - dh-issue- #346
- ✨:  ***Cập nhật thêm danh mục địa phương 2 cấp theo mô tả [CONGVAN-YEUCAU/Cong-van-915-CTK-CSCL-2025/Danh-muc-dia-phuong-Cong-van-915-v2.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/CONGVAN-YEUCAU/Cong-van-915-CTK-CSCL-2025/Danh-muc-dia-phuong-Cong-van-915-v2.md).*** 
![](https://live.staticflickr.com/65535/54648317038_e8184fcbfd_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/346

## [v.3.25.0712.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507120-NasDHSolutions.json)</sup></sup></sub>
- ✨:  YÊU CẦU - Bổ sung Danh mục địa phương theo Công văn số 1027/CTK-CSCL (gọi tắt Danh mục theo CV 915/CTK-CSCL) - YEUCAU - dh-issue- #346
- ✨:  ***Cập nhật thêm danh mục địa phương 2 cấp theo mô tả [CONGVAN-YEUCAU/Cong-van-915-CTK-CSCL-2025/Danh-muc-dia-phuong-Cong-van-915-v2.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/CONGVAN-YEUCAU/Cong-van-915-CTK-CSCL-2025/Danh-muc-dia-phuong-Cong-van-915-v2.md).*** 
![](https://live.staticflickr.com/65535/54648317038_e8184fcbfd_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/346

## [v.3.25.0711.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507111-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507111-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507111-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bảng kê 6556 bệnh nhân ngoại trú BV Tim Mạch Cần thơ #294
	- Cập nhật:
	+ Cập nhật script:
	![](https://i.vgy.me/vTbckx.png)

	+ Điều chỉnh tham số tính vượt ngưỡng theo thành tiền bhyt
	![](https://i.vgy.me/UVDU74.png)
	![](https://i.vgy.me/kWYtHU.png)


- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/294
<<<<<<< HEAD

## [v.3.25.0711.0]()
- ✨: Yêu cầu - Bảng kê 6556 bệnh nhân ngoại trú BV Tim Mạch Cần thơ #294
	- Cập nhật:
	+ Cập nhật script:
	![](https://i.vgy.me/vTbckx.png)

	+ Điều chỉnh tham số tính vượt ngưỡng theo thành tiền bhyt
	![](https://i.vgy.me/UVDU74.png)
	![](https://i.vgy.me/kWYtHU.png)


- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/294
=======

## [v.3.25.0708.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507081-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507081-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507081-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Printer: Mở chức năng hóa đơn điện tử cho KHOA SỨC KHỎE SINH SẢN -TT KIỂM SOÁT BỆNH TẬT TP CẦN THƠ - YEUCAU - dh-issue- #333
- ✨:  ***Bổ sung chức năng hddt đối với mã 92000-001.*** ![](https://live.staticflickr.com/65535/54639880067_733439e5a9_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/333

## [v.3.25.0708.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507080-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Printer: Mở chức năng hóa đơn điện tử cho KHOA SỨC KHỎE SINH SẢN -TT KIỂM SOÁT BỆNH TẬT TP CẦN THƠ - YEUCAU - dh-issue- #333
- ✨:  ***Bổ sung chức năng hddt đối với mã 92000-001.*** ![](https://live.staticflickr.com/65535/54639880067_733439e5a9_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/333

## [v.3.25.0703.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507030-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Printer không cho in phiếu 01KCB ***In Toa thuốc + Mẫu BHYT*** nếu Prescription Chưa xác nhận kết thúc khám #280
	- Cập nhật:
	- Tham số: xacnhanketthuckham = 1 và đã xác nhận kết thúc khám mới in phiếu được
	![](https://i.vgy.me/3pk07N.png)
	![](https://i.vgy.me/VJM7SO.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/280

## [v.3.25.0702.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32507020-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Printer Tách Phiếu thu đối với hàng tiện ích và Thuốc tại chức năng In toa nội trú
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/309

![](https://live.staticflickr.com/65535/54626910962_75052defb0_b.jpg)

## [v.3.25.0623.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506230-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung nghiệp vụ mới đối với Hóa đơn điện tử - VAT (BV SỐ 10)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/248

- Bổ sung cho phép chỉnh và thay thế hoá đơn khi lưu.
- Bổ sung không cho xoá khi phiếu thu đã lập hoá đơn điện tử.

![](https://live.staticflickr.com/65535/54607136782_a3ef52f6ee_b.jpg)

## [v.3.25.0620.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506200-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV Tim Mạch CT: Thủ thuật đã lập phiếu in bảng kê báo chưa thực hiện #358
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/358

## [v.3.25.0605.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506051-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506051-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506051-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Chức năng đổi mã bệnh án ngoại trú thanh toán theo ngày (BV Thốt Nốt)
![](https://upanh.tv/image/PgManager-qe337kq2uC.e4Nxn)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/346

## [v.3.25.0605.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32506050-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Printer Tách Phiếu thu đối với hàng tiện ích và Thuốc ra 2 phiếu thu riêng Tại nút In Toa thuốc + Mẫu BHYT tại Printer
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/289

![](https://live.staticflickr.com/65535/54567461097_58e3c1ac66_b.jpg)

## [v.3.25.0531.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505311-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505311-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505311-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Lập hóa đơn điện tử theo cấu hình riêng. - YEUCAU - dh-issue- #278
- ✨:  ***Bổ sung cấu trúc hỗ trợ cấu hình chức năng HDDT-MTT đối với kết nối VNPT.*** ![](https://live.staticflickr.com/65535/54557366089_8f19334b14_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/278

## [v.3.25.0531.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505310-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505310-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505310-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Lập hóa đơn điện tử theo cấu hình riêng. - YEUCAU - dh-issue- #278
- ✨:  ***Bổ sung cấu trúc hỗ trợ cấu hình chức năng HDDT-MTT đối với kết nối VNPT.*** ![](https://live.staticflickr.com/65535/54554444097_c4b438bd88_b.jpg)![](https://live.staticflickr.com/65535/54555659210_389ba462ea_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/278

## [v.3.25.0530.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505300-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Bổ sung cấu hình gen QR theo từng đối tác riêng. - YEUCAU - dh-issue- #228
- ✨:  ***Chỉnh lỗi không lấy được QRSacombank theo chuẩn VietQR.*** ![](https://live.staticflickr.com/65535/54555615049_42d225d6f0_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/228

## [v.3.25.0527.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505270-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Mất toa trả nhà thuốc khi chỉnh toa trả
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/321


- Fix sai kyhieu khi chỉnh toa bệnh nhân trả khám bệnh nhà thuốc 
![](https://i.ibb.co/CsB020Mx/Ct-DGS5-UZz2.png)

## [v.3.25.0520.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505200-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Bổ sung cấu hình gen QR theo từng đối tác riêng. - YEUCAU - dh-issue- #228
- ✨:  ***Bổ sung sinh QR đối với đối tác HDBank, Sacombank theo chuẩn VietQR.*** ![](https://live.staticflickr.com/65535/54532084678_8e20e46734_b.jpg)![](https://live.staticflickr.com/65535/54530964757_9b3ef7c2c2_b.jpg)![](https://live.staticflickr.com/65535/54532087503_431061ec99_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/228

## [v.3.25.0517.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505171-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505171-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505171-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu: Thay đổi cách tính stent thứ 2 ở các module (Reports - Admin - Services -Treatment) - YEUCAU - dh-issue- #232
- ✨:  ***Xử lý XML03.*** 
  - ***Bổ sung mô tả cách ghi nhận đối với VTYT (ma_nhom = 10) và có dmthuoc.stent = 2 thì t_trantt = 18.000.000***
  - ***Bổ sung mô tả cách ghi nhận đối với VTYT (ma_nhom = 10) và có dmthuoc.stent = 2 thì vẫn tính THANH_TIEN_BH = SO_LUONG * DON_GlA_BH * TYLE_TT_DV/100 * TYLE_TT_BH/100.***
  - ***Bổ sung mô tả cách ghi nhận đối với VTYT (ma_nhom = 10) và có dmthuoc.stent = 2 thì tyle_tt_bh = 100.***
- ![](https://live.staticflickr.com/65535/54525106753_40e000f815_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/232

## [v.3.25.0517.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505170-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505170-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505170-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Bệnh nhân in không lấy thuốc không in bảng kê (BV Đông Hải) - LOI - dh-issue- #291
- 🐛:  ***Xử lý không phát sinh XML4750 khi Không lấy thuốc - Không in phiếu 01.*** ![](https://live.staticflickr.com/65535/54525170670_bdfa1a5a11_b.jpg) ![](https://live.staticflickr.com/65535/54524821906_04d40a2f52_b.jpg) ![](https://live.staticflickr.com/65535/54524802476_6b6f3e4887_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/291

## [v.3.25.0508.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505081-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505081-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505081-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Thống nhất cách in phiếu thu tự thiết kế theo tham số - YEUCAU - dh-issue- #203 
- ✨:  ***Mở rộng tham số sdmauphieuthu: (5: in phiếu thu tự thiết kế có thông tin thanh toán QRCode, xem trước in , 6: in phiếu thu tự thiết kế có thông tin thanh toán QRCode, in trực tiếp).*** ![](https://i.imgur.com/YtX5kKA.png)
- ✨: Mẫu tự thiết kế: [Tải về](https://gofile.me/78TQg/Abkw5lw4W) ![](https://i.imgur.com/Hgn0auR.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/203

## [v.3.25.0508.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505080-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Thống nhất cách in phiếu thu tự thiết kế theo tham số - YEUCAU - dh-issue- #203 
- ✨:  ***Mở rộng tham số sdmauphieuthu: (5: in phiếu thu tự thiết kế có thông tin thanh toán QRCode, xem trước in , 6: in phiếu thu tự thiết kế có thông tin thanh toán QRCode, in trực tiếp).*** ![](https://i.imgur.com/YtX5kKA.png)
- ✨: Mẫu tự thiết kế: [Tải về](https://gofile.me/78TQg/Abkw5lw4W) ![](https://i.imgur.com/Hgn0auR.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/20

## [v.3.25.0505.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505051-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505051-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505051-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Xử lý không cho in phiếu đối với BN xử trí nhập viện 
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/13

- Bổ sung option
![](https://i.imgur.com/QPQgcc9.png)

- Chặn
![](https://i.imgur.com/SvtKRWq.png)

- Cảnh báo
![](https://i.imgur.com/uA2PtpX.png)

## [v.3.25.0505.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32505050-NasDHSolutions.json)</sup></sup></sub>
- ✨: YÊU CẦU - SẢN NHI TRÀ VINH - Đăng ký nhận bệnh BHYT có mã nơi ĐKBĐ 84001 thì mặc định Đúng Tuyến
- ✨: https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/BHXH-THONGTUYEN/Tiep-nhan-benh-dung-tuyen-BV-tuyen-tinh.md
- ✨: ![](https://i.imgur.com/NG1PhhF.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/107

## [v.3.25.0429.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504290-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV Tim Mạch: Printer mới không in được toa thuốc có số lượng khi bệnh nhân không lấy thuốc
![](https://i.imgur.com/CTj9xQS.gif)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/264

## [v.3.25.0423.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504232-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504232-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504232-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV QDY CT: Lỗi bảng kê 6556 khi bệnh nhân có CLS thanh BHYT có check lấy giá DV #250
	+ Cập nhật:
		![](https://i.imgur.com/JSJOZDi.png)
		![](https://i.imgur.com/CEZ5nDy.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/250
<<<<<<< HEAD

## [v.3.25.0423.1]()
- 🐛: Lỗi - BV QDY CT: Lỗi bảng kê 6556 khi bệnh nhân có CLS thanh BHYT có check lấy giá DV #250
	+ Cập nhật:
		![](https://i.imgur.com/JSJOZDi.png)
		![](https://i.imgur.com/CEZ5nDy.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/250

## [v.3.25.0423.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504230-NasDHSolutions.json)</sup></sup></sub>
- ✨:  TK - Triển khai 12 trạm xã Châu Thành - Đồng Tháp - TRIENKHAI - dh-issue- #12
- ✨:  ***Bổ sung key bản quyền theo danh sách.***
- ☑: https://i.dh-his.com/hdhiswork/TRIENKHAI/issues/12

## [v.3.25.0422.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504221-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504221-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504221-NasDHSolutions.json)</sup></sup></sub>

- ✨:  TK - Triển khai 12 trạm xã Châu Thành - Đồng Tháp - TRIENKHAI - dh-issue- #12
- ✨:  ***Bổ sung key bản quyền theo danh sách.***
- ☑: https://i.dh-his.com/hdhiswork/TRIENKHAI/issues/12

## [v.3.25.0422.0]()

- ✨:  TK - Triển khai 12 trạm xã Châu Thành - Đồng Tháp - TRIENKHAI - dh-issue- #12
- ✨:  ***Bổ sung key bản quyền theo danh sách.***
- ☑: https://i.dh-his.com/hdhiswork/TRIENKHAI/issues/12

## [v.3.25.0421.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504210-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi XML 4750, C79, 21 khi bệnh nhân có CLS thanh BHYT có check lấy giá DV.
![](https://i.imgur.com/MBKgtk5.png)
![](https://i.imgur.com/XqiI8g0.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/249

## [v.3.25.0416.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504162-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504162-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504162-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Yêu cầu - Bổ sung para QR cho phiếu thu nhà thuốc - YEUCAU - dh-issue- #190
- ✨:  ***Bổ sung thông tin thanh toán QR trên phiếu thu Nhà thuốc.*** ![](https://i.imgur.com/U5cpCMP.png) ![](https://i.imgur.com/P1E4Lie.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/190

## [v.3.25.0416.1]()
- ✨:  Yêu cầu - Bổ sung para QR cho phiếu thu nhà thuốc - YEUCAU - dh-issue- #190
- ✨:  ***Bổ sung thông tin thanh toán QR trên phiếu thu Nhà thuốc.*** ![](https://i.imgur.com/U5cpCMP.png) ![](https://i.imgur.com/P1E4Lie.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/190

## [v.3.25.0416.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504160-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504160-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FHospitalPrinterexe%2F32504160-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Printer: Không hiển thị mã YHCT trong mẫu 01/KBCB (TTYT H. Phước Long BLI)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/226

- Thêm mã YHCT vào mã chẩn đoán phụ theo tuỳ chọn 6556.
![](https://i.imgur.com/UDWY42x.png)
![](https://i.imgur.com/CGEaKPs.png)

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