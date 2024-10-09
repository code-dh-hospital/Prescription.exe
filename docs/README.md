<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 3.24.1009.0 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FPrescriptionexe%2F32410090-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FPrescriptionexe%2F32410090-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FPrescriptionexe%2F32410090-NasDHSolutions.json)
- 🐛: Fix lỗi y lệnh bị lập lại tất cã các dòng
![](https://i.imgur.com/oLVt3W0.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/652
## [v.3.24.1008.4]()
- ✨: Prescription - Thực hiện cảnh báo chi tiết khi không cho phép ra toa thuốc
![](https://i.imgur.com/LatFtpx.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/685
## [v.3.24.1008.3]()
- 🐛: Lỗi - PHÁT SINH LỖI KHI VÀO MENU KHÁM BỆNH
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/347
## [v.3.24.1008.2]()
- ✨: Presctiption - Thực hiện - Mô tả ICD10 theo QĐ 4469 - BYT
https://github.com/dh-hos/Mo-ta-he-thong/blob/main/ICD/ICD10-quyet-dinh-4469-BYT.md
- Trường hợp `current.dmicd.cdc_loaitru = 1` và tham số `icd.loaitru.chandoanchinh = 1` Cảnh báo mã ICD không được phép chọn làm chẩn đoán chính -> vẫn cho phép lưu chẩn đoán.
![](https://i.imgur.com/4ZWpalZ.png)
- Trường hợp `current.dmicd.cdc_loaitru = 1` và tham số `icd.loaitru.chandoanchinh = 2` Cảnh báo mã ICD không được phép chọn làm chẩn đoán chính -> Không cho phép lưu chẩn đoán.
![](https://i.imgur.com/Nle5JHp.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/677
## [v.3.24.1008.1]()
- 🐛: Fix lỗi - Lưu khám bệnh thì có cảnh báo có muồn thay đổi ngày hẹn không, nếu chọn ngày hẹn khác thì lưu lại ok, còn trường hợp nếu BS không muốn hẹn, chọn Không thì phần mềm không cho lưu
- Xữ lý khi có cảnh báo đã hẹn tái khám, nếu bác sĩ chọn không thay đổi thì hiển thị lại ngày hẹn củ
![](https://i.imgur.com/pWSbITo.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/291
## [v.3.24.1008.0]()
- 🐛: Fix Lỗi - BANT không xem được toa Vật tư y tế ngày củ
![](https://i.imgur.com/woStleT.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/343
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/340
## [v.3.24.1004.0]()
- push lại
- 🐛: Fix Lỗi - BANT theo ngày khi kết thúc bệnh án thì tạo thêm XML130 có mã bệnh án làm tăng số lượng XML Reports (trùng dữ liệu XML)

## [v.3.24.1003.4]()
- ✨: Thêm các para Hổ trợ xuống dòng khi lấy tên thành viên.
`pTenThanhVien_1` : Mỗi tên thành viên cách nhau 1 dòng.
`pTenThanhVien_2` : Mỗi tên thành viên cách nhau 2 dòng.
`pTenThanhVien_3` : Mỗi tên thành viên cách nhau 3 dòng.
![](https://i.imgur.com/vpWsnYB.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/342
## [v.3.24.1003.3]()
- ✨: Thực hiện Yêu cầu - MẪU HỘI CHẨN - CHỪA KHOẢNG TRỐNG KÝ TÊN CHỖ THÀNH VIÊN
![](https://i.imgur.com/YBQCOg5.png)
- ✨: Trích BBHC : Chủ Tọa và Thư Ký bỏ Chức danh phía sau tên
![](https://i.imgur.com/UhYAOTl.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/342
## [v.3.24.1003.2]()
- 🐛: Fix Lỗi - BANT theo ngày khi kết thúc bệnh án thì tạo thêm XML130 có mã bệnh án làm tăng số lượng XML Reports (trùng dữ liệu XML)
![](https://i.imgur.com/2CaJhyJ.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/341
## [v.3.24.1003.1]()
- ✨: Bổ sung chức năng cho phép nhập thêm y lệnh (push lại do thiếu hình)
![](https://i.imgur.com/3PaWfGM.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/652
## [v.3.24.1003.0]()
- ✨: Bổ sung chức năng cho phép nhập thêm y lệnh
![]()
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/652
## [v.3.24.1002.0]()
- ✨: Ấn nút `Khám bệnh` đồng thời gọi bệnh nhân vào phòng khám - BV Thốt Nốt
- ✨: Sau khi khám xong - xóa khỏi danh sách trên Monitor - BV Thốt Nốt
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/649
## [v.3.24.1001.1]()
- ✨: Thực hiện Yêu cầu - Prescription Có tham số cảnh báo hoặc chặn phần HỎI BỆNH cho tất cả bệnh viện
[MÔ TẢ BỔ SUNG THAM SỐ](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Thong-mo-ta-tham-so-bat-buoc-nhap-thong-tin-hoi-benh.md)
- 🐛: Fix lỗi bắt thiếu điều kiện
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/661
## [v.3.24.1001.0]()
- ✨: Thực hiện Yêu cầu - Prescription Có tham số cảnh báo hoặc chặn phần HỎI BỆNH cho tất cả bệnh viện
[MÔ TẢ BỔ SUNG THAM SỐ](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Thong-mo-ta-tham-so-bat-buoc-nhap-thong-tin-hoi-benh.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/661
## [v.3.24.0930.0]()
- 🐛: Fix Lỗi - BV Ô Môn: Không xóa được CLS (Prescription báo CLS đã có toa vật tư)
- Bổ sung `idchidinh` của CLS vào cột `current.chungtu.idchidinh` khi thêm toa vật tư.
- Khi load toa vật tư hoặc xóa CLS thì dựa vào `idchidinh`
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/340

## [v.3.24.0927.0]()
- ✨: Ấn nút `Khám bệnh` đồng thời gọi bệnh nhân vào phòng khám - BV Sa Đéc
- ✨: Sau khi khám xong - xóa khỏi danh sách trên Monitor - BV Sa Đéc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/660
## [v.3.24.0926.2]()
- ✨: Prescription Mở chức năng gọi bệnh nhân vào phòng khám bệnh - BV Sa Đéc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/660
## [v.3.24.0926.1]()
- ✨: Thực hiện yêu cầu - Prescription Hỗ trợ thêm para liều dùng khi thiết kế toa thuốc ngoài Form Chẩn đoán
![](https://i.imgur.com/RrfRUfv.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/655
## [v.3.24.0926.0]()
- 🐛: Fix - Lỗi phát sinh khi chỉnh, thêm diễn biến BANT
![](https://i.imgur.com/DKKrpyf.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/339
## [v.3.24.0924.2]()
- ✨: **💼**: **_Yêu cầu - Thiết kế bảng kê chi phí bệnh nhân thu phí_**
- ✨:Chỉnh lỗi không in theo trang in đã cấu hình theo đối tượng ![](https://i.imgur.com/yrB7pbg.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/626
## [v.3.24.0924.1]()
- ✨: **💼**: **_Yêu cầu - Thiết kế bảng kê chi phí bệnh nhân thu phí_**
- ✨:Chỉnh lỗi không in theo trang in đã cấu hình theo đối tượng ![](https://i.imgur.com/yrB7pbg.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/626
## [v.3.24.0924.0]()
- ✨: **💼**: **_Yêu cầu - Thiết kế bảng kê chi phí bệnh nhân thu phí_**
- ✨:Chỉnh lỗi không in theo trang in đã cấu hình theo đối tượng ![](https://i.imgur.com/yrB7pbg.gif)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/626
## [v.3.24.0923.2]()

- 🐛: Cập nhật hỗ trợ phiếu thanh toán chi phí theo đối tượng
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/626
## [v.3.24.0923.1]()
- 🐛: Chuyển mẫu giấy ra viện sang tự thiết kế - BV YHCT
![](https://i.imgur.com/qW4RlVu.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/337
## [v.3.24.0923.0]()
- 🐛:  BANT theo đợi - Lọc trùng chẩn đoán chính, phụ trước khi so sánh với tham số `ma_benh_kt.soluong`
![](https://i.imgur.com/T5w1zlQ.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/608
## [v.3.24.0919.3]()
- 🐛: Fix - lỗi phát sinh khi load danh sách đã đăng ký khám bệnh
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/77
## [v.3.24.0919.2]()
- 🐛: Lỗi - không xóa được công khám (BV Đặng Thùy Trâm)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/333
## [v.3.24.0919.1]()
- ✨: Thực hiện gởi tối đa 12 ICD
- 🐛: Fix - Kiểm tra ICD theo mã khám bệnh (bant hàng ngày) và mã bệnh án (bant theo đợt)
- 🐛: Fix - Lỗi khi bấm vào QT Điều Trị load sai thông tin
![](https://i.imgur.com/CF5Naoh.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/608
## [v.3.24.0919.0]()
- 🐛: Lỗi - chức năng ra toa thuốc không lấy được thuốc còn tồn kho (BV Hồng Dân) #332
![](https://i.imgur.com/A9hcx6i.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/332
## [v.3.24.0918.1]()
- 🐛: Fix - Thay đổi hiển thị thông báo khi số lượng ICD vượt quá số lượng cấu hình
![](https://i.imgur.com/iyETdtz.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/608
## [v.3.24.0918.0]()
- ✨: Thực hiện gởi tối đa 12 ICD - Kiểm tra số lượng mã ICD theo makb không vượt số lượng cấu hình từ tham số `ma_benh_kt.soluong`
![](https://i.imgur.com/inkbDRq.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/608
## [v.3.24.0917.0]()
- 🐛: Fix - Lỗi BANT khi Kết thúc ĐT vào hồ sơ - Tờ Bệnh án ngoại trú Chẩn đoán ra viện - Chẩn đoán phụ không hiển thị mã chẩn đoán
![](https://i.imgur.com/iDvm7pS.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/329
## [v.3.24.0916.3]()
- 🐛: **💼**: **_Lỗi - BANT MÃ CHẨN ĐOÁN PHỤ KHÔNG HIỂN THỊ_**
- 🐛: Hỗ trợ thể hiện trang in sau khi thiết kế 
- 🐛: Fix lỗi Chọn in Tổng kết lần 2, không hỏi thiết kế trang in ![](https://i.imgur.com/lsY8Hdy.png) ![](https://i.imgur.com/PHBWTZ4.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/329
## [v.3.24.0916.2]()
- 🐛: Fix - Lỗi BANT khi cho Kết thúc ĐT thì mã Bệnh phụ có Khi Kết thúc ĐT xong vào lại bị mất mã Bệnh phụ
![](https://i.imgur.com/kWV40ht.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/329
## [v.3.24.0916.1]()
- 🐛: Fix - Lỗi xóa được CLS khi đã có toa vật tư kèm theo
![](https://i.imgur.com/YWR2jSs.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/331
## [v.3.24.0916.0]()
- ✨: Thực hiện thay đổi theo mô tả nhập bệnh nhân lao, bệnh nhân lĩnh thuốc
- ✨: Đối với `psdangky.trangthaichuyentuyen = 5 hoặc 6`, khi đăng ký khám bệnh chỉ ràng buộc mã nơi giới thiệu
![](https://i.imgur.com/XpJA6V8.png)
- ✨: Đối với người bệnh khám lao có giấy chuyển tuyến: `psdangky.trangthaichuyentuyen = 4` và `psdangky.manoigt <> ''` thì hỗ trợ check chọn mặc định `Bệnh nhân khám lao = true` tại tab `khám lao`
![](https://i.imgur.com/tGjtjWT.gif)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/129
## [v.3.24.0915.0]()
- ✨: **💼**: **_Yêu cầu - Thiết kế bảng kê chi phí bệnh nhân thu phí_**
- ✨: ***Bổ sung option để chọn lấy trang in theo loại bhyt của đối tượng*** (current.dmdoituong.bhyt) ![](https://i.imgur.com/YTA6gML.png) 
- ✨: ***Đăng nhập tài khoản admin để thiết kế trang in*** ![](https://i.imgur.com/sSQTuRG.png)
- ✨: ***Chức năng thiết kế theo loại đối tượng*** ![](https://i.imgur.com/suJzmtd.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/626 
## [v.3.24.0914.0]()
- ✨: Merge code
## [v.3.24.0913.0]()
- 🐛: Sửa lỗi: Form cập nhật thông tin chỉ định giải phẫu bệnh sinh thiết đã lập, khi đóng form mở lại bị thiếu chẩn đoán.
- ![](https://i.imgur.com/Zj0ODxE.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/629 
## [v.3.24.0912.0]()
- 🐛: Fix -Chức năng in tổng kết bệnh án ngoại trú phát sinh lỗi khi in tổng kết và tắt form
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/328
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/327
## [v.3.24.0911.0]()
- ✨: Thay đổi text hiển thị `Chỉ định` thành `cách dùng` trên danh sách toa thuốc
![](https://i.imgur.com/zLtJYZt.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/637
## [v.3.24.0910.1]()
- ✨: Đối với những loại thuốc có số lượng uống nhỏ hơn số ngày uống thì vẫn lấy liều dùng tự động không ràng buộc theo số lượng
- ✨: Thay cụm từ Chỉ định thành Cách dùng cho phù hợp với Quyết định 4750 (Một số phản ánh từ các đơn vị)
![](https://i.imgur.com/oTVDfNA.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/637
## [v.3.24.0910.0]()
- ✨: Thực hiện kiểm tra khi xuất viện xong đã có hồ sơ trong XML130.bang1
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/633
- ✨: Thực hiện xóa hồ sơ XML4750 khi thực hiện trả về điều trị BA Ngoại trú
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/641
## [v.3.24.0913.0]()
- 🐛: Sửa lỗi: Form cập nhật thông tin chỉ định giải phẫu bệnh sinh thiết đã lập, khi đóng form mở lại bị thiếu chẩn đoán.
- ![](https://i.imgur.com/Zj0ODxE.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/629 
## [v.3.24.0909.2]()
- 🐛: Fix - Lỗi tổng kết bệnh án YHCT không in được mã YHCT (BV YHCT)
![](https://i.imgur.com/6Rc6sm7.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/326
## [v.3.24.0909.1]()
- 🐛: Fix - Lỗi hiệu chỉnh thông tin BANT không tìm thấy thông tin bệnh nhân (Load đủ thông tin đối với bệnh nhân đã kết thúc điều trị)
![](https://i.imgur.com/52iDXsQ.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/325
## [v.3.24.0909.0]()
- 🐛: Fix - Lỗi hiệu chỉnh thông tin BANT không tìm thấy thông tin bệnh nhân (nếu ra viện rồi, thì vô chức năng `Hiệu chỉnh TT`, vẫn lấy thông tin dữ liệu của chính ngay bệnh nhân đó, nhưng khi sử dụng chức năng Hiệu chỉnh trên form này thì cảnh báo bệnh nhân đã ra viện không thể điều chỉnh)
![](https://i.imgur.com/ExF0uWX.png)
![](https://i.imgur.com/fk2HDD3.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/325
## [v.3.24.0906.0]()
- 🐛: Fix - Lỗi HS bệnh án ngoại trú yhct không lấy được chẩn đoán ra viện yhct (BV YHCT TPCT)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/320
## [v.3.24.0904.2]()
- 🐛: Lỗi - HS bệnh án ngoại trú yhct không lấy được chẩn đoán ra viện yhct (BV YHCT TPCT)
![](https://i.imgur.com/M6lbSrJ.png)
![](https://i.imgur.com/eDOXk21.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/320

## [v.3.24.0904.1]()
- 🐛: Fix - Lỗi Prescription báo lỗi khi lưu nhập viện đối tượng thu phí
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/324
## [v.3.24.0904.0]()
- 🐛: Lỗi - HS bệnh án ngoại trú yhct không lấy được chẩn đoán ra viện yhct (BV YHCT TPCT)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/320
![](https://i.imgur.com/M6lbSrJ.png)
![](https://i.imgur.com/eDOXk21.png)
## [v.3.24.0901.1]()
- 🐛: Fix - Lỗi Không xóa được công khám bệnh án ngoại trú (BV Cái Răng)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/323
## [v.3.24.0901.0]()
- 🐛: Lỗi - Báo cáo bảng kê xuất tủ trực (bv Cái Răng) - 1 mã khách hàng hiển thị ra 2 tên bệnh nhân
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/321
![](https://i.imgur.com/sAjCbvr.png)
## [v.3.24.0830.1]()
- 🐛: Fix - Lỗi Không lập được phiếu vào viện BỆNH ÁN NGOẠI TRÚ(BV CÁI RĂNG)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/322
## [v.3.24.0830.0]()
- ✨: Prescription thực hiện theo mẫu XtraReport chung theo [Mô tả giấy CNPT tự thiết kế](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Vuong-mo_ta-giay-CNPT-tu-thiet-ke.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/614
![](https://i.imgur.com/TNzTIQl.png)
![](https://i.imgur.com/JtNfFP8.png)
## [v.3.24.0829.2]()
- 🐛: Fix - Chức năng xóa chuyển phòng, xóa luôn quá trình điều trị của bệnh nhân ở phòng được chuyển
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/297
## [v.3.24.0829.1]()
- ✨: Thực hiện theo [mô tả bổ sung tham số để thêm tùy chọn áp dụng khi load ekip PTTT](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Vuong-mota-them-tham-so-load-danh-sach-ekip-pttt.md)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/598
## [v.3.24.0829.0]()
- 🐛: Fix - Lỗi khi thêm toa mẫu
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/318
## [v.3.24.0827.0]()
- ✨: Thực hiện - Hỗ trợ nhập chẩn đoán phụ trên chức năng Kết thúc BANT
- ✨: Thực hiện hỗ trợ gõ chức năng CĐ Phụ giống như phần thay đổi diễn biến bệnh
- ✨: Kiểm tra Mã CĐ phụ khi thực hiện lưu, nếu không đúng mã ICD thì không cho lưu
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/311
![](https://i.imgur.com/1fj2rb6.png)
![](https://i.imgur.com/SYmMOT5.png)
## [v.3.24.0827.0]()
- ✨: Thực hiện - Hỗ trợ nhập chẩn đoán phụ trên chức năng Kết thúc BANT
- ✨: Thực hiện hỗ trợ gõ chức năng CĐ Phụ giống như phần thay đổi diễn biến bệnh
- ✨: Kiểm tra Mã CĐ phụ khi thực hiện lưu, nếu không đúng mã ICD thì không cho lưu
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/311
![](https://i.imgur.com/1fj2rb6.png)
![](https://i.imgur.com/SYmMOT5.png)
## [v.3.24.0826.5]()
- ✨: **💼**: **_Yêu cầu - Bổ sung thêm chức năng lưu Loại bênh nhân 4750_**
- ✨:![](https://i.imgur.com/Q7Wf2qI.png) ![](https://i.imgur.com/G8lPJ5H.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/595
## [v.3.24.0826.4]()
- 🐛: Fix - Lỗi BANT sai trạng thái ra viện khi dùng chức năng thanh toán tháng
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/319
![](https://i.imgur.com/yiK3KbD.png)
![](https://i.imgur.com/SVCt7wU.png)
![](https://i.imgur.com/iJC0fyf.png)
## [v.3.24.0826.3]()
- 🐛: Fix - Lỗi chưa ràng buộc mã công việc khi chọn ekip PT/TT
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/310
![](https://i.imgur.com/grOvDaH.png)
## [v.3.24.0826.2]()
- 🐛: Fix - lỗi chưa khóa danh sách khám bệnh khi chọn cập nhật hiệu sinh mà chưa lưu
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/305
## [v.3.24.0826.1]()
- 🐛: Fix - Lỗi bệnh nhân có chỉ định CLS tự do khi vào phòng khám chỉ định thêm CLS đó thì không ghi nhận thêm được, xóa công khám phòng 2 chỉ định công khám khác thì mất công khám phòng đầu.
* Do thiếu điều kiện idchidinh khi xóa cls dẫn đến Bệnh nhân khám phòng 1 khám nội chuyển qua phòng 2 khám ngoại thì phần mềm tạo thêm 1 CLS công khám 30%, bác sĩ xóa CLS đó chỉ định lại công khám khác thì phần mềm xóa luôn công khám phòng 1 và công khám mới chỉ định chỉ thanh toán 30%.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/304
## [v.3.24.0826.0]()
- 🐛: Fix - Lỗi khi xóa chuyển phòng bệnh nhân BANT thì mất thông tin bệnh nhân ở phòng khám
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/297
## [v.3.24.0823.2]()
- 🐛: Fix - lỗi không kết thúc được bệnh án ngoại trú
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/315
![](https://i.imgur.com/V2j7gMl.png)
## [v.3.24.0823.1]()
- 🐛: Fix - phát sinh lỗi khi ra toa thuốc tại form bệnh án ngoại trú
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/316
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/314
## [v.3.24.0823.0]()
- 🐛: Fix lỗi khi vào chức năng hiệu chỉnh thông tin từ form bệnh án ngoại trú
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/313
## [v.3.24.0822.4]()
- 🐛: Fix Lỗi - CHỨC NĂNG THANH TOÁN THÁNG TẠO BỆNH ÁN MỚI LẤY SAI MABA
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/312
## [v.3.24.0822.3]()
- 🐛: fix lỗi chẩn đoán chính và chẩn đoán phụ trùng nhau trong 1 lần chẩn đoán - xử lý không cho nhập chuẩn đoán phụ trùng với chuẩn đoán chính
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/608
![](https://i.imgur.com/7QV6wow.png)
![](https://i.imgur.com/0XZ0ppN.png)
## [v.3.24.0822.2]()
- 🐛: Fix - Khi nhập ekip PT chưa lưu ekip nhưng vẫn lưu được phiếu PT
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/306
![](https://i.imgur.com/C7AEyL5.png)
## [v.3.24.0822.1]()
- 🐛: Fix - lỗi hiển thị sai chuẩn đoán kết thúc đối với bệnh khám 2 phòng
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
![](https://i.imgur.com/OE6EWaj.png)
![](https://i.imgur.com/QcmGoxi.png)
## [v.3.24.0822.0]()
- 🐛: Fix - Bệnh án ngoại trú chưa bắt số lượng ICD theo tham số `ma_benh_kt.soluong`
- 🐛: Fix - có thể thêm ICD phụ trùng với ICD chính
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/608
![](https://i.imgur.com/wpC8Xla.png)
![](https://i.imgur.com/D8mvra2.png)
## [v.3.24.0821.2]()
- ✨: Cập nhật theo mô tả [ghi nhận ngày hẹn tái khám](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Thong-mo-ta-ghi-nhan-ngay-hen-kham-lai.md)
- 🐛: Fix lỗi thiếu điều kiện - dẫn đến không thể lưu khám bệnh khi ngày hẹn = null
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/291
## [v.3.24.0821.1]()
- ✨: Cập nhật theo mô tả [ghi nhận ngày hẹn tái khám](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/Thong-mo-ta-ghi-nhan-ngay-hen-kham-lai.md)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/291
## [v.3.24.0821.0]()
- 🐛: Fix - Hiệu chỉnh thông tin chưa hỗ trợ tự lấy trạng thái chuyển tuyến = 5(Giấy hẹn lãnh thuốc) khi check bệnh nhân khám lao
- 🐛: Fix - Thiếu thông tin Check giấy xác nhận lưu trú và chọn giấy lưu ở tab Thông tin thêm
- ☑: https://github.com/dh-hos/dhg.hospitaladmin/issues/89
## [v.3.24.0820.0]()
- 🐛: Fix - tắt Form khám bệnh vào xem lại mất chẩn đoán chọn kết thúc.
- 🐛: Fix - Chức năng chuyển phòng Form danh sách khám bệnh vẫn cho phép chuyển bệnh nhân đã xác nhận kết thúc khám.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
![](https://i.imgur.com/y1wgI5n.png)
![](https://i.imgur.com/6dIT9fK.png)
## [v.3.24.0820.0]()
- 🐛: Fix - tắt Form khám bệnh vào xem lại mất chẩn đoán chọn kết thúc.
![](https://i.imgur.com/y1wgI5n.png)
- 🐛: Fix - Chức năng chuyển phòng Form danh sách khám bệnh vẫn cho phép chuyển bệnh nhân đã xác nhận kết thúc khám.
![](https://i.imgur.com/6dIT9fK.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
## [v.3.24.0819.3]()
- 🐛: Fix lỗi in toa bệnh nhân chỉ có năm sinh
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/72
## [v.3.24.0819.2]()
- 🐛: Fix lỗi khi nhập lý do vào viện là khoảng trắng thì vẫn lưu được trên form nhập viện và BA ngoại trú
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/594
![](https://i.imgur.com/xguXeTu.png)
![](https://i.imgur.com/QkhEyGp.png)
## [v.3.24.0819.1]()
🐛: chỉnh lại định dạng tên phường xã trên form nhập viện
☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/302
![](https://i.imgur.com/ya0pZXN.png)
## [v.3.24.0819.0]()
- 🐛: chỉnh lại định dạng tên phường xã
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/302
## [v.3.24.0818.2]()
- 🐛: Giới hạn chỉ có tài khoản "admin" hoặc có quyền Admin phân hệ mới được chỉnh chỉ định uống.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/239
## [v.3.24.0818.1]()
- 🐛: Giới hạn chỉ có tài khoản "admin" hoặc có quyền Admin phân hệ mới được chỉnh chỉ định uống.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/239
## [v.3.24.0818.0]()
- 🐛: Giới hạn chỉ có tài khoản "admin" hoặc có quyền Admin phân hệ mới được chỉnh chỉ định uống.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/239
## [v.3.24.0817.1]()
- ✨: **Thực hiện**: **_💼 Ghi nhận sdnguonkhac vào XML02 và XML03 khi lưu XML4750 ⌛Dự kiến: 2024-08-22_**
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/606
## [v.3.24.0817.0]()
- 🐛: **Chỉnh lỗi**: **_Hỗ trợ - Phiếu 01 sai trạng thái tuyến_**
- 🐛: Sai trạng thái tuyến đối với BA Ngoại trú, không theo mô tả [XML1.MA_LYDO_VVIEN](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML4210/Vinh%20-%20Mo%20ta%20XML4210%20-%20XML1.MA_LYDO_VVIEN.md)![](https://i.imgur.com/KCprwdl.png)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/71


## [v.3.24.0816.0]()
- ✨: Bắt buộc nhập Lý do vào viện form nhập viện, BA ngoại trú phần mềm Prescription (Lý do vào viện không được để trống)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/594
![](https://i.imgur.com/F3AMTke.png)
## [v.3.24.0815.0]()
- 🐛: Fix lỗi không load được bác sĩ chỉ định công khám mặc định
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/303
![](https://i.imgur.com/KCLhENd.png)
## [v.3.24.0814.2]()
- 🐛: Fix lỗi - BANT không hiển thị được hết thông tin hiệu sinh
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/300
![](https://i.imgur.com/4DMFquJ.png)
## [v.3.24.0814.1]()
- 🐛: Fix Lỗi - Sai phường xã form nhập viện và địa chỉ bệnh nhân trên Tem bệnh án lấy danh mục địa phương cũ
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/302
## [v.3.24.0814.0]()
- ✨: Bắt buộc nhập Lý do vào viện trên phiếu nhập viện
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/106
![](https://i.imgur.com/WNlLayX.png)
## [v.3.24.0812.2]()
- ✨: Thực hiện Yêu cầu - EKIP PT/TT CHỈ LOAD NHÂN VIÊN CÓ CHỨNG CHỈ HÀNH NGHỀ
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/584
- 🐛: Fix lỗi vẫn xóa được EKIP PT/TT khi đã lưu phiếu PT/TT
- ☑:https://github.com/dh-hos/dhg.hospitalprescription/issues/298
## [v.3.24.0812.1]()
- ✨: Thêm liều dùng vào form toa thuốc mẫu
- 🐛: Fix lỗi không load được toa mẫu do thiếu liều dùng khi ra toa
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/575
![](https://i.imgur.com/fKHDSxH.png);
## [v.3.24.0812.0]()
- 🐛: **Chỉnh lỗi**: **_Lỗi in bảng kê BANT theo đợt báo lỗi không ghi nhận được XML 4750 lên Admin_**
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/586

## [v.3.24.0811.0]()
- ✨: Yêu cầu - Hỗ trợ hàm kiểm tra thông tuyến theo Công văn 1923/BHXH-CNTT ngày 20/06/2024
- ✨: Mô tả thực hiện [Ham API tra cuu TT - theo CV 1923-BHXHVN.md
](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/XML130/QD4570/Ham%20API%20tra%20cuu%20TT%20-%20theo%20CV%201923-BHXHVN.md)
- ✨:  + Chuyển hàm sử dụng thông tuyến KQNhanLichSuKCB2024 (Không theo cấu hình trên Admin)
- ✨:  + Sử dụng tài khoản kiểm tra theo tài khoản đăng nhập, điều kiện cụ thể để tài khoản có thể sử dụng tra cứu là có tài khoản BHXH cung cấp khác rỗng, có họ lót và Số CCCD
- ✨:  + Trường hợp tài khoản đăng nhập không hợp lệ, sẽ tìm theo tài khoản được cấu hình theo khoa, và theo bệnh viện trên Danh mục Nhân viên
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/565
## [v.3.24.0810.0]()
- 🐛: **Lỗi - Bảng 6556 bệnh án ngoại trú thanh toán theo đợt sai lý do vào viện**![](https://i.imgur.com/QcEfHfO.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/301
## [v.3.24.0809.4]()
- 🐛: Fix Lỗi - BANT vào hiệu chỉnh thông tin báo lỗi (BV Cái Răng)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/299
## [v.3.24.0809.3]()
- 🐛: Fix - Sau khi lưu phiếu PT/TT vẫn cho phép xoá ekip gây ra lỗi XML3 thiếu người thực hiện
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/298
![](https://i.imgur.com/vACUQLz.png)
## [v.3.24.0809.2]()
- 🐛: Fix Lỗi - khi chỉ định cls chỉ định nhiều lần hiển thị ra nhiều dòng cùng ngày kcb dẫn đến không thực hiện được cls.
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/58
## [v.3.24.0809.1]()
- 🐛: Fix lỗi - BANT Y học cổ truyền không vào được chức năng CẬP NHẬT nhập Diễn biến, Tóm tắt KQ CLS các hồ sơ đã ra viện
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/295
![](https://i.imgur.com/N0umd04.png)
## [v.3.24.0809.0]()
- 🐛: Fix - ràng buộc ngày tái khám phải lớn hơn ngày ra toa
- 🐛: Fix - khi nhập ngày uống trên toa thuốc, ấn Enter thì tự động gợi ý ngày tái khám
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/291
![](https://i.imgur.com/GG1Hq4T.png)
![](https://i.imgur.com/ZNEYMNP.png)
## [v.3.24.0808.1]()
- 🐛: Fix Lỗi - BANT đã khám thêm diễn biến có công khám nhưng psdangky.dakham = 0 gây lỗi khi nhập viện
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/294
## [v.3.24.0808.0]()
- 🐛: Fix lỗi - Xem và in toa thuốc form khám HIV không được.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/293
## [v.3.24.0807.0]()
- ✨:Cập nhật theo Mô tả Kiểm tra thời gian kết quả HA-CN-TT-PT
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/571
![](https://i.imgur.com/rLBNVuP.png)
![](https://i.imgur.com/m1jrrll.png)
![](https://i.imgur.com/1tS04Re.png)
## [v.3.24.0806.1]()
- 🐛: fix lỗi cho lưu toa thuốc khi ngày tái khám trùng với ngày khám bệnh
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/291
![](https://i.imgur.com/QehOWEp.png)
## [v.3.24.0806.0]()
- 🐛: Fix lỗi BANT theo ngày khi ấn xem hoặc in toa thuốc thì báo lỗi do nhập cân nặng là số âm
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/290
## [v.3.24.0804.1]()
- ✨:BANT - Kiểm tra chỉ số sinh hiệu khi lưu theo tham số ktsinhhieu.customize đối với đối tượng BHYT như khám thường
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/508
![](https://i.imgur.com/IN9INPM.png)
## [v.3.24.0804.0]()
- ✨: Thêm para liều dùng lên toa thuốc
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/558
![](https://i.imgur.com/hPQGO1R.png)
## [v.3.24.0802.0]()
- ✨: Cập nhật  - nhấn nút Thanh toán tháng thì load form kết thúc để nhập các thông tin, khi ấn Lưu mới thực hiện công tiếp việc.(BV ĐKTP CẦN THƠ - 92004)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/546
![](https://i.imgur.com/tYxD2BJ.png)
## [v.3.24.0731.1]()
- 🐛: Fix - Load thông tin kết thục BANT thiếu Diễn Giải
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/286
![](https://i.imgur.com/b0K7qJY.png)
## [v.3.24.0731.0]()
- 🐛: khóa không cho nhập diễn biến , tóm tắt kết quả CLS trên form ngoại trú chung khi chưa bấm chỉnh, hay bấm cập nhật
- 🐛: Load lại form khi bấm cập nhật rồi bấm bỏ qua
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/501
## [v.3.24.0730.7]()
- 🐛: Fix lỗi chỉ định cận lâm sàng có miễn giảm (bệnh nhân thu phí).
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/213
## [v.3.24.0730.6]()
- 🐛: Fix lỗi view toa không thuốc
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/210
## [v.3.24.0730.5]()
- 🐛: Bệnh nhân xác nhận chỉ có năm sinh, chỉ in năm sinh trên toa
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/209
## [v.3.24.0730.4]()
- 🐛: Chỉnh lại lấy theo phòng kết thúc thành Chẩn đoán và load đúng chẩn đoán
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
![](https://i.imgur.com/gu05L0l.png)
## [v.3.24.0730.3]()
- 🐛: Chỉnh lại lấy theo phòng kết thúc thành Chẩn đoán và load đúng chẩn đoán
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
![](https://i.imgur.com/gu05L0l.png)
## [v.3.24.0730.2]()
- 🐛: Khóa nút khám bệnh khi ấn cập nhật chỉ số sinh hiệu
- ✨: Bổ sung thêm bắt sự kiện Enter sẽ nhảy đến ô sinh hiệu tiếp theo 
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/285
![](https://i.imgur.com/yGrhN1Q.png)
## [v.3.24.0730.1]()
- 🐛: Thay đổ text hiển thị `Chẩn Đoán` sang `Phòng kết thúc`
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
![](https://i.imgur.com/88MIpCc.png)
## [v.3.24.0730.0]()
- 🐛: Thay đổ text hiển thị "Chẩn Đoán" sang "Phòng kết thúc"
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
![](https://i.imgur.com/88MIpCc.png)
## [v.3.24.0729.1]()
- 🐛: Fix lỗi toa thuốc khi in liên tục bị sai cân nặng
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/284
## [v.3.24.0729.0]()
- ✨: Ghi nhận thời gian chỉ định cận lâm sàng theo thời gian chỉ định, không cập nhật thời gian chỉ định cho các cận lâm sàng khác đợt chỉ định.
- ✨: Chỉ đinh cùng 1 cận lâm sàng khác đợt --> tách từng dòng riêng theo đợt.
- ✨: Cập nhật cận lâm sàng theo idchidinh.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/544
## [v.3.24.0727.1]()
- ✨: ghi nhật ký chức năng nhập Diễn biến và tóm tắt kết quả CLS cho các bệnh án nội trú, BANT theo đợt cũ đã xuất viện
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/536
![](https://i.imgur.com/tvATptD.png)
## [v.3.24.0727.0]()
- 🐛: Fix - phát sinh lỗi khi tự động lấy tóm tắt kết quả BANT đối với bệnh án không có kết quả CLS
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/282
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/518
## [v.3.24.0726.4]()
- 🐛: Lỗi - Lỗi in bảng kê bệnh án ngoại trú thanh toán theo ngày (Cảnh báo chưa phát sinh chi phí khi in phiếu 01)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/274
## [v.3.24.0726.3]()
- ✨: BANT theo ngày bổ sung đầy đủ chỉ số sinh hiệu như ngoại trú
- 🐛: Khi chuyển phòng, các chỉ số để rỗng như Phòng khám đầu tiên thay vì chuyển phòng hiển thị 0.00
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/508
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/281
![](https://i.imgur.com/fDg7aeJ.png)
## [v.3.24.0726.2]()
- 🐛: Không cho phép in phiếu 01 đối với bệnh án ngoại trú thanh toán đợt (Có check [`Theo Đợt`]), phải vào chức năng Tổng kết CP thực hiện,
- ![](https://i.imgur.com/wcKWDhT.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/274#issuecomment-2249843169

## [v.3.24.0726.1]()
- 🐛: Fix Lỗi - Lỗi in bảng kê bệnh án ngoại trú thanh toán theo ngày 
- ![](https://i.imgur.com/FxPDEYR.png) 
![](https://i.imgur.com/kKKMvxe.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/274
## [v.3.24.0726.0]()
- 🐛: Fix: Lỗi - Không in được bảng kê 6556 (BV Ung Bướu) ![](https://i.imgur.com/rlXkjn6.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/288
## [v.3.24.0725.3]()
- 🐛: Lỗi - Prescription BANT bị sinh hiệu che mất chuyển phòng máy có độ phân giải thấp
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/525
## [v.3.24.0725.2]()
- 🐛: Fix Lỗi - Lấy lại toa củ bị mất liều dùng
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/280
## [v.3.24.0725.1]()
- 🐛: Fix toa thuốc nhập số lượng liều dùng tại các buổi vượt số lượng tổng vẫn cho phép
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/493
- ✨: load lại dữ liệu khi người dùng bấm chỉnh thông tin chuyển tuyến rồi ấn bỏ qua
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/510
## [v.3.24.0725.0]()
- 🐛: Fix lỗi - BN chuyển phòng, khi ấn khám không có cảnh báo nhập cân nặng.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/281
![](https://i.imgur.com/xrAjChZ.png)
## [v.3.24.0724.2]()
- ✨: Nếu người dùng không phân liều: cả 4 ô bằng 0 hoặc rỗng --> không bắt số lượng và không hỗ trợ ghép liều dùng (liều dùng rỗng).
- ✨: Hỗ trợ phím tắt để người dùng có thể bỏ qua việc phân liều thay vì nhấn enter 4 lần như hiện tại(nhập số lượng xong ấn F4).
- ✨: Hỗ trợ thiết lập danh mục liều dùng tương tự như danh mục chỉ định uống để người dùng tự thực hiện các trường hợp đặc biệt.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/493
![](https://i.imgur.com/LzPS9ba.png)
![](https://i.imgur.com/E56rkKZ.png)
## [v.3.24.0724.1]()
- ✨: Nếu người dùng không phân liều: cả 4 ô bằng 0 hoặc rỗng --> không bắt số lượng và không hỗ trợ ghép liều dùng (liều dùng rỗng).
- ✨: Hỗ trợ phím tắt để người dùng có thể bỏ qua việc phân liều thay vì nhấn enter 4 lần như hiện tại(nhập số lượng xong ấn F4).
- ✨: Hỗ trợ thiết lập danh mục liều dùng tương tự như danh mục chỉ định uống để người dùng tự thực hiện các trường hợp đặc biệt.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/493
![](https://i.imgur.com/LzPS9ba.png)
![](https://i.imgur.com/E56rkKZ.png)
## [v.3.24.0724.0]()
- ✨: Nếu người dùng không phân liều: cả 4 ô bằng 0 hoặc rỗng --> không bắt số lượng và không hỗ trợ ghép liều dùng (liều dùng rỗng).
- ✨: Hỗ trợ phím tắt để người dùng có thể bỏ qua việc phân liều thay vì nhấn enter 4 lần như hiện tại(nhập số lượng xong ấn F4).
- ✨: Hỗ trợ thiết lập danh mục liều dùng tương tự như danh mục chỉ định uống để người dùng tự thực hiện các trường hợp đặc biệt.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/493
![](https://i.imgur.com/LzPS9ba.png)
![](https://i.imgur.com/E56rkKZ.png)
## [v.3.24.0723.4]()
- ✨: Ghi nhận ngày giờ nhập kết quả Xét nghiệm trong from ARV
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/513
## [v.3.24.0723.3]()
- ✨: Ràng buộc không bỏ trống phương tiện vận chuyển khi lập phiếu chuyển tuyến (push lại)
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/77
![](https://i.imgur.com/tmkpgqG.png)
## [v.3.24.0723.2]()
- ✨: Ràng buộc không bỏ trống phương tiện vận chuyển khi lập phiếu chuyển tuyến
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/510
![](https://i.imgur.com/tmkpgqG.png)
## [v.3.24.0723.1]()
- ✨: Thêm chức năng nhập Diễn biến, Tóm tắt KQ CLS các hồ sơ đã ra viện.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/503
![](https://i.imgur.com/RlHT5FE.png)
## [v.3.24.0723.0]()
- 🐛: Fix lỗi - BANT in toa thuốc sai cân nặng
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/278
## [v.3.24.0722.1]()
- ✨: RÀNG BUỘC KHÔNG BỎ TRỐNG HƯỚNG ĐIỀU TRỊ CHO GIẤY CHUYỂN TUYẾN
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/505
![](https://i.imgur.com/7zs9v3m.png)
## [v.3.24.0722.0]()
- 🐛: không load được kết quả điều trị đã chọn đối với bệnh nhân đã xác nhận kết thúc khám.
- 🐛: không cho phép chỉnh chuẩn đoán khi đã chọn kết quả điều trị.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
## [v.3.24.0721.1]()
- ✨: Lấy danh mục theo cấu hình sử dụng (sudung=1)
- ![](https://i.imgur.com/buvcMrS.png)
![](https://i.imgur.com/jvcHXOU.png)
![](https://i.imgur.com/hKERYZv.png)
- ✨: Xử lý Mã xử trí và Mã Phác đồ không liên quan với nhau trên Form Xử trí phác đồ
- 🐛: https://github.com/dh-hos/To_Lap_Trinh/issues/497
## [v.3.24.0721.0]()
- 🐛: Fix Lỗi - Mở form khám bệnh (trường hợp check cấp cứu)  
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/279
## [v.3.24.0721.0]()
- 🐛: Fix Lỗi - Mở form khám bệnh (trường hợp check cấp cứu)  
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/279
## [v.3.24.0720.3]()
- ✨: Hỗ trợ PK Phương Nam (96148), PK Nam Phương(96152) cập nhật các bệnh mãn tính
## [v.3.24.0720.2]()
- ✨: Cập nhật - Bổ sung chức năng hỗ trợ lấy dữ liệu [Tóm tắt kết quả CLS] - lấy đúng định dạng `[Tên CLS] : [Kết quả] ([Đơn vị đo])` và cách nhau bằng dấu `;`
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/474
## [v.3.24.0720.1]()
- 🐛: Fix Lỗi - Mở form khám bệnh 
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/279
## [v.3.24.0720.0]()
- ✨: Bổ sung chức năng hỗ trợ lấy dữ liệu [Tóm tắt kết quả CLS]
- ✨: Hỗ trợ PK Nam Phương(96152) cập nhật các bệnh mãn tính
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/474
![](https://i.imgur.com/d06P7QE.png)
## [v.3.24.0719.0]()
- ✨: Kiểm tra số lượng ICD theo tham số khi thực hiện theo [Mô tả XML130 - Bổ sung QĐ 4750] .
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/480
## [v.3.24.0718.3]()
- 🐛: Fix lỗi - khi lưu phiếu phẫu thuật- thủ thuật không có mã loại PT
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/182
## [v.3.24.0718.2]()
- 🐛: Fix - Không chỉnh được phiếu PT-TT không có cấu hình loại PT: phần mềm báo chưa lập phiếu
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/182
![](https://i.imgur.com/NSuX3EB.png)
## [v.3.24.0718.1]()
- 🐛: Fix - BANT Chuyển phòng - chưa cập nhật được bnnoitru.madv khi chuyển phòng
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/483
- 🐛: Fix - Nhận bệnh trên Prescription không bắt thiếu Trạng thái Chuyển tuyến
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/277
## [v.3.24.0718.0]()
- 🐛: Fix - BANT Chuyển phòng - chưa cập nhật được bnnoitru.madv khi chuyển phòng
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/483
- 🐛: Fix - Nhận bệnh trên Prescription không bắt thiếu Trạng thái Chuyển tuyến\
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/277
## [v.3.24.0717.5]()
- 🐛: Fix lỗi - chưa ghi nhận đúng thông tin đơn vị khi chuyển phòng BANT
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/483
## [v.3.24.0717.4]()
- 🐛: Fix lỗi - Báo cáo sổ TT-PT thống kê phiếu PT-TT load sai do sai tham số
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/182
![](https://i.imgur.com/MOKvLXC.png)
## [v.3.24.0717.3]()
- 🐛: Fix lỗi - BANT chuyển phòng không thấy thông tin bệnh nhân bên phòng chuyển.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/483
## [v.3.24.0717.2]()
- ✨: Báo cáo sổ TT-PT thống kê phiếu PT-TT không có phân loại PT - theo tham số `phanloaipt.thuchien`
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/182
![](https://i.imgur.com/wVctRSI.png)
## [v.3.24.0717.1]()
- 🐛: fix lỗi - chưa lập được phiếu PT-TT đối với CLS PT-TT không cấu hình loại PT trên danh mục
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/182
## [v.3.24.0717.0]()
- 🐛: fix lỗi - chưa lập được phiếu PT-TT đối với CLS PT-TT không cấu hình loại PT trên danh mục
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/182
- 🐛: Form khám bệnh mất tab - push lại
## [v.3.24.0716.2]()
- ✨: Hỗ trợ PK Phương Nam (96148) cập nhật các bệnh mãn tính

## [v.3.24.0716.1]()
- ✨: Thực hiện chức năng mở khóa bệnh nhân đã xác nhận kết thúc khám.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/463
![](https://i.imgur.com/JSkHcJK.png)
## [v.3.24.0716.0]()
- 🐛: Fix lỗi Form khám bệnh Prescription thống kê sai danh sách CLS (lặp lại nhiều lần)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/490
![](https://i.imgur.com/fnwS8vS.png)
## [v.3.24.0715.1]()
- 🐛: Fix lỗi - không load được danh mục kết quả điều trị khai báo tại admin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
## [v.3.24.0715.0]()
- 🐛: Fix lỗi - khi lập toa thuốc với giờ lập nhỏ hơn thời gian kết thúc vẫn chưa có cảnh báo/chặn
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/269
## [v.3.24.0712.4]()
- ✨:Cập nhật - Sổ TT/PT theo Mô tả thực hiện Thủ thuật/Phẫu thuật đối với Cận lâm sàng
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/455
## [v.3.24.0712.3]()
- 🐛: Fix lỗi - Chưa cảnh báo: Toa thuốc ràng buộc thời gian ra toa phải lớn hơn ngày giờ kết thúc của phiếu PT/TT
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/457
## [v.3.24.0712.2]()
- 🐛: Fix lỗi sai trạng thái khám bệnh và mất phân loại khi chỉ định thêm cân lâm sàng
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/201
## [v.3.24.0712.1]()
- 🐛: Fix lỗi - toa thuốc chỉ định số lẻ báo lỗi.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/271
## [v.3.24.0712.0]()
- ✨: sử dụng tham số `phanloaipt.thuchien` - Cho phép thực hiện Phẫu thuật/Thủ thuật (áp dụng đối với kho TT hoặc PT) mà không cần phân loại PT
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/454
## [v.3.24.0711.2]()
- 🐛: Bổ sung tham số ktsinhhieu.customize: Fix lỗi sai bắt chỉ số nhommau
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/37
## [v.3.24.0711.1]()
- 🐛: Chuyển câu thông báo sang dạng cảnh báo.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/457
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/269
![](https://i.imgur.com/ilC5Krd.png)
![](https://i.imgur.com/NBAFjQf.png)
## [v.3.24.0711.0]()
- ✨: Lập phiếu PT,TT - Kiểm tra thời gian bắt đầu và kết thúc không được nhỏ hơn thời gian chỉ định.
- ✨: Toa thuốc ràng buộc thời gian ra toa phải lớn hơn ngày giờ kết thúc của phiếu PT/TT
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/457
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/269
![](https://i.imgur.com/2s9MCBc.png)
![](https://i.imgur.com/8UfoGho.png)
## [v.3.24.0710.3]()
- 🐛: Fix lỗi - Chức năng xác định kết thúc khám không load được danh mục kết quả điều trị đã khai báo trên trên Admin.
- 🐛: Fix lỗi - Bệnh nhân đã xác định kết thúc khám với Kết quả không thay đổi
				-> khi tắt phần mềm Prescription mở lại vào lại bệnh nhân thì không thấy được chẩn đoán và kết quả đã chọn.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/465
![](https://i.imgur.com/muvNZaM.png)
![](https://i.imgur.com/1PMcprD.png)
## [v.3.24.0710.2]()
- 🐛: Fix - báo lỗi khi cấp toa mà không nhập liều dùng.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/464
![](https://i.imgur.com/tMDHDGQ.png)
## [v.3.24.0710.1]()
- 🐛: Fix - báo lỗi khi cấp toa mà không nhập liều dùng.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/464
![](https://i.imgur.com/tMDHDGQ.png)
## [v.3.24.0710.0]()
- 🐛: Fix - báo lỗi khi cấp toa mà không nhập liều dùng.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/464
![](https://i.imgur.com/tMDHDGQ.png)
## [v.3.24.0710.2]()
- ✨: Test msbuild
## [v.3.24.0710.1]()
- ✨: Test msbuild
## [v.3.24.0710.0]()
- ✨: Test msbuild
## [v.3.24.0709.3]()
- 🐛: Fix lỗi - Thủ thuật đã lập phiếu rồi nhưng vẫn báo chưa thực hiện không thể ra toa Prescription.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/452
## [v.3.24.0709.2]()
- 🐛: Fix Lỗi - In toa thuốc không đúng khổ giấy
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/262
## [v.3.24.0709.1]()
- ✨: Ghi nhận giờ, phút khi chọn tái khám (Giá trị mặc định 08 giờ 00 phút).
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/48
![](https://i.imgur.com/uTugueZ.png)
![](https://i.imgur.com/QpdlDbI.png)
## [v.3.24.0709.0]()
- 🐛: Bổ sung tham số ktsinhhieu.customize: Kiểm tra thông tin sinh hiệu bệnh nhận BHYT tùy chọn (Các chỉ số: chieucao|cannang|vongnguc|vongdau|huyetap|nhietdo|mach|nhiptho|hb|fio2|nhommau cách nhau [|], ví dụ: chieucao|cannang - là bắt buộc nhập chiều cao, cân nặng)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/37
## [v.3.24.0708.1]()
- 🐛: Lỗi - Khuất nội dung khi lập phiếu TT/PT #268
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/268
![](https://i.imgur.com/vlaRXep.png)
## [v.3.24.0708.0]()
- ✨: Liều dùng - lấy số ngày uống theo từng mặt hàng, dựa vào số lượng của từng mặt hàng và chỉ định sáng, trưa, chiều, tối
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/43
![](https://i.imgur.com/cWUB6d5.png)
## [v.3.24.0706.0]()
- 🐛: Fix lỗi khi ra toa thuốc tổng tiền thuốc chưa đến số tiền giới hạn đã chặn không cho lưu
- 🐛: Fix - thông báo chỉnh lại số tiền cho đúng định dạng có dấu phân cách hàng nghìn hiện thông báo lấy trực tiếp 1000000
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/267
![](https://i.imgur.com/U929qOw.png)
## [v.3.24.0705.1]()
- 🐛: Fix lỗi khi chỉnh thuốc trong toa thì bị mất liều dùng
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/444
## [v.3.24.0705.0]()
- 🐛: chỉnh lại kiểm tra thời gian khám với đối tượng BHYT (Bắt khi dmdoituong.bhyt = 1 hoặc dmdoituong.bhyt = 2 (BHYT hoặc Trẻ em))
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/440
## [v.3.24.0704.3]()
- 🐛: Bổ sung tham số ktsinhhieu.customize: Kiểm tra thông tin sinh hiệu tùy chọn (Các chỉ số: chieucao|cannang|vongnguc|vongdau|huyetap|nhietdo|mach|nhiptho|hb|fio2|nhomau cách nhau [|], ví dụ: chieucao|cannang - là bắt buộc nhập chiều cao, cân nặng)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/37
## [v.3.24.0704.2]()
- ✨: push test 1
## [v.3.24.0704.1]()
- 🐛: Bổ sung tham số ktsinhhieu.customize: Kiểm tra thông tin sinh hiệu tùy chọn (Các chỉ số: chieucao|cannang|vongnguc|vongdau|huyetap|nhietdo|mach|nhiptho|hb|fio2|nhomau cách nhau [|], ví dụ: chieucao|cannang - là bắt buộc nhập chiều cao, cân nặng)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/37
## [v.3.24.0704.0]()
- 🐛: Bổ sung tham số ktsinhhieu.customize: Kiểm tra thông tin sinh hiệu tùy chọn (Các chỉ số: chieucao|cannang|vongnguc|vongdau|huyetap|nhietdo|mach|nhiptho|hb|fio2|nhomau cách nhau [|], ví dụ: chieucao|cannang - là bắt buộc nhập chiều cao, cân nặng)
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/37
## [v.3.24.0703.1]()
- ✨:  chỉnh lại kiểm tra thời gian khám với đối tượng BHYT, bổ sung tham số `checktime.bhyt` cho đơn vị chọn kiểm hay không kiểm thời gian này.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/440
![](https://i.imgur.com/vLfovEw.png)
## [v.3.24.0703.0]()
- 🐛: Fix Lỗi chỉ định toa thuốc (BV Thanh Bình - Trạm Thuận An) - không lưu được toa thuốc.
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/265
![](https://github.com/dh-hos/dhg.hospitalprescription/issues/265)
## [v.3.24.0702.2]()
- 🐛: Fix lỗi sai đơn vị tuổi trên BBHC
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/264
![](https://i.imgur.com/ztM4vY8.png)
## [v.3.24.0702.1]()
- 🐛: KHÔNG HIỆN FORM CHỌN PHÒNG CẤP STT CLS - BV QUẬN 12
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/263
![](https://i.imgur.com/9NWxuUs.png)
## [v.3.24.0702.0]()
- ✨: Bổ sung chức năng chọn mã máy khi thực hiện PT, TT
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/34
![](https://i.imgur.com/t4OK6OB.png)
## [v.3.24.0701.2]()
- ✨: `Gọi hàm MarkCheckInCanLamSang(String macls)` khi thực lưu chỉ định cls thành công
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/32
## [v.3.24.0701.1]()
- ✨: `Gọi hàm MarkCheckInCanLamSang(String macls)` khi thực lưu chỉ định cls thành công
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/32
## [v.3.24.0701.0]()
- ✨: `Gọi hàm MarkCheckInCanLamSang(String macls)` khi thực lưu chỉ định cls thành công
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/32
## [v.3.24.0701.0]()
- ✨: Ghi nhận XML4750 trong schema xml130
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN-4750/issues/32
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0629.2]()
- ✨: Bổ sung tham số ktsinhhieu.customize: cho phép cấu hình bắt buộc nhập tùy nhu cầu các chỉ số sinh hiệu

## [v.3.24.0629.1]()
- ✨: Bắt buộc phải nhập Ekip mới cho lưu trên phiếu Phẩu thuật
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/432
## [v.3.24.0629.0]()
- 🐛: fix - Form khám bệnh không thấy được chữ viết tắt khi gõ
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
![](https://i.imgur.com/8Izfx1V.png)
## [v.3.24.0628.2]()
- 🐛: fix lỗi form khám bệnh mất xóa viết tắt gỏ lại thì không tìm được phường xã
- 🐛: Không cho nhập vào ô phường xã trên form khám bệnh
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
## [v.3.24.0628.1]()
- 🐛: lỗi mất phường xã 4750 trên form khám bệnh
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
## [v.3.24.0628.0]()
- 🐛: fix lỗi form nhận bênh và hiệu chỉnh thông tin mất phường xã
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
## [v.3.24.0627.3]()
- 🐛: fix lỗi form nhận bệnh và form hiệu chỉnh thông tin chưa lấy được theo dmxa4750
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/71
## [v.3.24.0627.2]()
- 🐛: Fix lỗi không load được danh sách sổ khám bệnh
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/261
## [v.3.24.0627.1]()
- 🐛: Fix lỗi ma_giuong_bak_ trong bảng chidinhcls
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/403
## [v.3.24.0627.0]()
- 🐛: Lỗi - PHÁT SINH LỖI KHI IN BẢNG KÊ NGOẠI TRÚ TẠI PHÒNG KHÁM
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/260
## [v.3.24.0626.1]()
- 🐛: Fix lỗi không dùng được chức năng cập nhật chỉ số hiệu sinh - form khám bệnh
- 🐛: Fix lỗi chỉnh thông tin form khám bệnh xong lưu lại phần mềm load dữ liệu bệnh nhân khác.
- 🐛: Fix lỗi khi ấn Tab để nhập số sinh hiệu không theo thứ tự
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/259
## [v.3.24.0626.0]()
- ✨: liều dùng thuốc cho nhập số lẻ. Thêm cột liều dùng khi hiển thị toa thuốc. Thêm ràng buộc số lượng thuốc khi nhập liều dùng 
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
![](https://i.imgur.com/fkWk8ZP.png)
![](https://i.imgur.com/yMFInCV.png)
## [v.3.24.0625.1]()
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/231
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/246
## [v.3.24.0625.0]()
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/231
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/246
- ✨: Thêm chức năng để tùy chọn in hay preview để set ngayinphieu trong psdangky
- 🐛: Lỗi - Bảng kê 6556 bệnh nhân ngoại trú thu phí in không có ngày kết thúc
- ![](https://i.imgur.com/fdDTJKx.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/258
## [v.3.24.0624.5]()
- 🐛: Fix - Chức năng hiệu chỉnh tại From nhập viện chưa bắt theo ràng buộc khi nhập CMND
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/30
## [v.3.24.0624.4]()
- 🐛: Lỗi - Trùng chẩn đoán chính và chẩn đoán kèm theo bệnh nhân khám nhiều phòng
- 🐛: Lỗi - In lần đầu thiếu chẩn đoán
![](https://i.imgur.com/i8BJyyz.gif)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/253
## [v.3.24.0624.2]()
- ✨: Cập nhật DLL: Cảnh báo số lần đăng ký trong tháng
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/334
## [v.3.24.0624.1]()
- 🐛: Lỗi - Trùng chẩn đoán chính và chẩn đoán kèm theo bệnh nhân khám nhiều phòng
- 🐛: Lỗi - In lần đầu thiếu chẩn đoán
- [](https://i.imgur.com/eR0lBlS.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/253
## [v.3.24.0624.0]()
- 🐛: Fix lỗi không mở được form khám bệnh trường hợp cấu hình cấp cứu
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/257
- 📗: tại hàm `GetDSBenhNhanCC` lấy thêm trường `current.dmbenhnhan.nhom_mau`
## [v.3.24.0622.1]()
- 🐛: Lỗi - Trùng chẩn đoán chính và chẩn đoán kèm theo bệnh nhân khám nhiều phòng
- 🐛: Lỗi - In lần đầu thiếu chẩn đoán
- ![](https://i.imgur.com/sF4SkIj.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/253
## [v.3.24.0622.0]()
- 🐛: Lỗi - BANT THEO NGÀY HIỂN THỊ 2 DÒNG CÙNG BỆNH ÁN #254
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/254
## [v.3.24.0621.0]()
- ✨: bổ sung combobox cho phép chọn, nhập thông tin nhóm máu - form khám bệnh
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/141
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/SscpaRP.png)
## [v.3.24.0620.8]()
- ✨: Thay đổi cách ghi nhận maxa trên form nhận bệnh, khám bệnh, hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/400
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/KGNPU2W.png)
![](https://i.imgur.com/3bky44G.png)
![](https://i.imgur.com/VVaB7q7.png)
## [v.3.24.0620.7]()
- ✨: Pushtest2
## [v.3.24.0620.6]()
- ✨: Pushtest1
## [v.3.24.0620.5]()
- ✨: Thay đổi cách ghi nhận maxa trên form nhận bệnh, khám bệnh, hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/400
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/KGNPU2W.png)
![](https://i.imgur.com/3bky44G.png)
![](https://i.imgur.com/VVaB7q7.png)
## [v.3.24.0620.4]()
- ✨: Push lại lần 2 - Thay đổi cách ghi nhận maxa trên form nhận bệnh, khám bệnh, hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/400
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/KGNPU2W.png)
![](https://i.imgur.com/3bky44G.png)
![](https://i.imgur.com/VVaB7q7.png)
## [v.3.24.0620.3]()
- ✨: Push lại - Thay đổi cách ghi nhận maxa trên form nhận bệnh, khám bệnh, hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/400
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/KGNPU2W.png)
![](https://i.imgur.com/3bky44G.png)
![](https://i.imgur.com/VVaB7q7.png)
## [v.3.24.0620.2]()
- ✨: Thay đổi cách ghi nhận maxa trên form nhận bệnh, khám bệnh, hiệu chỉnh thông tin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/400
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
![](https://i.imgur.com/KGNPU2W.png)
![](https://i.imgur.com/3bky44G.png)
![](https://i.imgur.com/VVaB7q7.png)
## [v.3.24.0620.1]()
- 🐛: Lỗi - Bảng kê 6556 hiển thị sai tên VTYT
- ![](https://i.imgur.com/NWHweKY.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/256
## [v.3.24.0620.0]()
- 🐛: Lỗi - Bảng kê 6556 bệnh nhân thu phí Bệnh án ngoại trú thanh toán theo đợt
- ![](https://i.imgur.com/dpupsDo.png)
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/255
## [v.3.24.0619.0]()
- 🐛: Fix lỗi trùng hồ sơ chuyển viện ![](https://i.imgur.com/Rw1iliX.png)
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/116
## [v.3.24.0618.2]()
- 🐛: Fix lỗi sai định dạng ngaykcb khi chỉ định công khám
- 📕: ép kiểu datetime cho ngaykcb khi nhận giá trị
## [v.3.24.0618.1]()
- ✨: Thêm para pTenThanhVien trên mẫu hội chẩn - chỉ lấy tên thành viên không kèm chức vụ
- 🐛: Mẫu trích BBHC tự thiết kế áp dụng theo tham số hoichan.customize = 0
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/407
![](https://i.imgur.com/jLiQC6Y.png)
## [v.3.24.0618.0]()
- ✨: Thêm para pTenThanhVien trên mẫu hội chẩn - chỉ lấy tên thành viên không kèm chức vụ
- 🐛: Mẫu trích BBHC tự thiết kế áp dụng theo tham số hoichan.customize = 0.
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/407
![](https://i.imgur.com/jLiQC6Y.png)
- 🐛: Lỗi - Trùng chẩn đoán chính và chẩn đoán kèm theo bệnh nhân khám nhiều phòng
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/253 
- ![](https://i.imgur.com/493rDKv.png)
- 📕: Xử lý trim khoảng trắng trước và sau trước khi replace, để loại bỏ trùng
## [v.3.24.0617.2]()
- 🐛: Fix lỗi chọn ngày bắt đầu và kết thúc khi chọn combo loại báo cáo
- ☑: https://github.com/dh-hos/dhg.hospitalreports/issues/116
## [v.3.24.0617.1]()
- ✨: Mở chức năng in Phiếu Trích BBHC cho tự thiết kế hiện có cho Toàn bộ khách hàng theo tham số hoichan.customize = 1
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/407
## [v.3.24.0617.0]()
- 🐛: Fix lỗi phát sinh khi chỉ định công khám - do khám khác phòng đăng ký
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/252
## [v.3.24.0612.2]()
- 🐛: Fix Yêu cầu - Xác định mã lý do vào viện trên bảng kê 6556 và XML 4210 ( trường hợp bệnh nhân có giấy xác nhận cư trú) ![](https://i.imgur.com/lJrTENa.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/389

## [v.3.24.0612.1]()
* Push lại
- ✨: Khóa chức năng chỉnh phiếu nghỉ ốm/dưỡng thai. #377
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/377
- 📗: kiểm tra cột current.psdangky.dain, nếu dain = 1 thì không cho chỉnh sửa phiếu nghĩ ốm và phiếu nghĩ dưỡng thai
## [v.3.24.0612.0]()
- ✨: Khóa chức năng chỉnh phiếu nghỉ ốm/dưỡng thai. #377
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/377
- 📗: kiểm tra cột current.psdangky.dain, nếu dain = 1 thì không cho chỉnh sửa phiếu nghĩ ốm và phiếu nghĩ dưỡng thai
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
## [v.3.24.0610.0]()
- ✨: Thực hiện Yêu cầu - Bổ sung thêm trường phòng khám trên mẫu Phiếu nhập viện tự thiết kế (BV Thanh Bình) #379
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/379
- 📗: lấy tenphong từ dmphong với điều kiệu `current.khambenh.maphong = current.dmphong.maphong`
- 📕: Thêm para tenphong vào xrptGiayNhapVien.cs
![](https://i.imgur.com/a2b6Ghw.png)

## [v.3.24.0609.0]()
- ✨: Yêu cầu thực hiện 4750 - Cập nhật số liệu Liều dùng theo pshdxn
- 📗: Thêm giao diện nhập liều dùng sáng trưa chiều tối, xữ lý tính liều dùng và add vào cột current.pshdxn.lieu_dung
![](https://i.imgur.com/8eSfDaD.png)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/371
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0607.0]()
- ✨: Thêm kiểm tra trước khi lưu đối với CCCD phải có 9,12 ký tự số hoặc hộ chiếu 8 ký tự bắt đầu là chữ in hoa và 7 ký tự số ở sau
- 📕: Build lại với dll HosReg.Plus.dll v1.24.607.0
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/370
- ☑: https://github.com/dh-hos/To_Ho_Tro/issues/20
- ☑: https://github.com/dh-hos/To_Trien_Khai/issues/57
## [v.3.24.0606.1]()
- 🐛: Fix lỗi mất logo
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/68
## [v.3.24.0606.0]()
- 🐛: Fix lỗi mất logo
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/68
## [v.3.24.0531.0]()
- ✨: Yêu cầu - BV Phụ Sản CT: 1. Mẫu tự thiết kế Biên bản hội chẩn và Trích Biên bản hội chẩn trên Prescription và Treatment
- 🐛: Đổi chở chữ và margin
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/346
## [v.3.24.0529.0]()
- 🐛: Fix lỗi khi ấn nhập viện, chỉnh thông tin thì không lưu được
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/247
## [v.3.24.0528.0]()
- 🐛: Fix lỗi in phiếu 01
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/238
## [v.3.24.0527.0]()
- 🐛: Fix lỗi khi ấn nhập viện, chỉnh thông tin thì không lưu được
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/247
## [v.3.24.0526.1]()
- 🐛: Cập nhật chẩn đoán tại phòng khi chỉnh chẩn đoán toa thuốc

## [v.3.24.0526.0]()
- 🐛: Fix lỗi không cập nhật chẩn đoán tại phòng khám khi chỉnh toa.

## [v.3.24.0524.1]()
- ✨: Cập nhật chẩn đoán xml giống chẩn đoán ra viện
- 🐛: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/12
- 📗: Nếu mabvbh=74206, kqcdoanxml = kqcdoan+';'kqcdoanp trong bảng current.bnnoitru
## [v.3.24.0524.0]()
- ✨: thiết kế lại mẫu Biên bản hội chẩn mặc định và mẫu trích Biên bản hội chẩn mặc định
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/346
## [v.3.24.0522.0]()
- 🐛: Fix lỗi hiển thị thiếu thông tin trên bảng kê 6556
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/236
## [v.3.24.0521.3]()
- ✨: Thêm mẫu tự thiết kế Biên bản hội chẩn và Trích Biên bản hội chẩn
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/346

## [v.3.24.0521.3]()
- ✨: Thêm mẫu tự thiết kế Biên bản hội chẩn và Trích Biên bản hội chẩn
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/346
## [v.3.24.0521.2]()
- ✨: Thêm mẫu tự thiết kế Biên bản hội chẩn và Trích Biên bản hội chẩn
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/346
## [v.3.24.0521.2]()
- 🐛: Fix báo cáo bệnh nhân OPC
- ☑:  https://github.com/dh-hos/dhg.hospitalprescription/issues/249
## [v.3.24.0521.0]()
- 🐛: Fix báo cáo bệnh nhân OPC
- ☑:  https://github.com/dh-hos/dhg.hospitalprescription/issues/249
## [v.3.24.0521.1]()
- ✨: test2
## [v.3.24.0521.0]()
- ✨: test
## [v.3.24.0517.0]()
- 🐛: Fix lỗi chức năng Hiệu chỉnh thông tin, lỗi khi lưu chỉnh sửa đối tượng và tiền công khám
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/67
## [v.3.24.0516.0]()
- 🐛: Fix lỗi báo cáo HIV
- ☑: https://github.com/dh-hos/dhg.hospitalprescription/issues/249