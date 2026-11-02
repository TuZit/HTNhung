## **1 Mục tiêu**

Sinh viên xây dựng một hệthống nhúng hoàn chỉnh (mô phỏng hoặc thực tế) với đầy đủ:

- Đặc tảhệthống rõ ràng

- Thiết kếphần cứng và sơ đồhệthống

- Thiết kếphần mềm và kiến trúc xửlý

- Mã nguồn có giải thích logic

- Đánh giá kỹthuật và khảnăng ứng dụng

## **2 Yêu cầu chung**

**Lưu ý quan trọng:** Bài làm sẽbịtrừđiểm nặng nếu chỉmô tảlý thuyết hoặc chèn mã nguồn mà không có phân tích kỹthuật hoặc sao chép từcác nguồn mà không có trích dẫn hoặc tổng hợp kiến thức rĩ ràng.

Sinh viên lựa chọn đềtài thuộc:

- IoT, điều khiển, giám sát

- Nông nghiệp thông minh, giao thông, y tế

- Hệthống cảnh báo, tựđộng hóa

1

## **3 Cấu trúc báo cáo bắt buộc**

### **Phần 0: Phân chia công việc**

Yêu cầu một bảng mô tảkhối lượng công việc của từng thành viên trong nhóm và tỷlệ % công việc của mỗi thành viên

### **3.1 Phần 1: Giới thiệu và đặc tảhệthống**

**Bắt buộc có bảng đặc tảhệthống:**

| Thành phần | Mô tả                             |
| ---------- | --------------------------------- |
| Input      | Dữliệu đầu vào (loại, tần suất)   |
| Output     | Hành động hệthống                 |
| Ràng buộc  | Thời gian, năng lượng, môi trường |

**Phải phân biệt rõ:**

- Yêu cầu chức năng (hệthống làm gì)

- Yêu cầu phi chức năng (mô tảrõ ràng ví dụ: độtrễ< 1s)

#### **Không chấp nhận:**

- Mô tảchung chung, không có sốliệu

- Sao chép lý thuyết không liên quan

### **3.2 Phần 2: Thiết kếhệthống**

**1. Sơ đồkhối hệthống (bắt buộc)**

Phải có sơ đồtổng thểdạng: Sensor _→_ MCU _→_ Communication _→_ Server/UI
**Yêu cầu:**

- Có hình vẽriêng vềsơ đồkhối hệthống

- Có giải thích chi tiết sơ đồ(chức năng nhiệm vụcủa từng thành phần) - Trình bày ngắn gọn hạn chếdài dòng.

#### **2. Thiết kếphần cứng**

- Danh sách linh kiện và chức năng

- Giải thích tại sao chọn linh kiện

- Phân tích phương án thay thế(nếu có)

**Không chấp nhận:**

- Chỉmô tảlinh kiện mà không có lý do lựa chọn

#### **3. Sơ đồghép nối**

- Có sơ đồghép nối, đấu dây rõ ràng

- Giải thích từng kết nối (chỉnêu lý do ngắn gọn)

#### **4. Thiết kếphần mềm**

**Bắt buộc có sơ đồluồng xửlý hoặc kiến trúc:** Ví dụnhư dưới đây:

```
main()
```

```
readSensor()
processData()
```

```
sendData()
```

```
controlDevice()
```

#### **5. Mã nguồn và giải thích**

**Yêu cầu:**

- Không chỉchèn code

- Phải giải thích logic hoạt động

- Liên kết với sơ đồluồng

#### **Không chấp nhận:**

- Chỉchú thích từng dòng code

- Không có mô tảtổng thể

#### **6. Kết quảhệthống**

Các giao diện hoặc hình ảnh vềkết quảhệthống khi chạy hoàn chỉnh. (Có giải thích các hình ảnh)

3

### **3.3 Phần 3: Đánh giá hệthống**

**Phải có phân tích:**

- Hiệu năng (độtrễ, tốc độ)

- Tiêu thụnăng lượng

- Độtin cậy (khi lỗi xảy ra)

- Khảnăng mởrộng

#### **Bắt buộc:**

- Nêu hạn chếcủa hệthống

- Đềxuất cải tiến cụthể

## **Tài liệu tham khảo**

Danh sách tài liệu tham khảo từcác nguồn chuẩn, lưu ý tránh các nguồn blog hoặc website chưa được kiểm chứng vềdữliệu.

## **4 Tiêu chí chấm điểm chi tiết**

| Tiêu chí            | Điểm | Yêu cầu                                            |
| ------------------- | ---- | -------------------------------------------------- |
| Nội dung báo cáo    | 25%  | Đặc tảrõ ràng, có phân tích kỹ<br>thuật            |
| Thiết kếphần cứng   | 30%  | Có sơ đồkhối, sơ đồkết nối, giải<br>thích lựa chọn |
| Giải thích mã nguồn | 20%  | Có logic tổng thể, liên kết với hệ<br>thống        |
| Tính ứng dụng       | 15%  | Có kịch bản thực tế, khảnăng mở<br>rộng            |
| Hình thức trình bày | 10%  | Format chuẩn, thống nhất                           |

## **5 Checklist trước khi nộp bài**

- Có sơ đồkhối hệthống riêng

- Có giải thích sơ đồ

4

- Có kết nối giữa mã nguồn và hệthống

- Không sao chép lý thuyết dư thừa

- Có phân tích kỹthuật trong kết luận
