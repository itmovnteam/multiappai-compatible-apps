# Một số mẹo tiết kiệm tokens khi sử dụng dịch vụ MultiAppAI

Trong quá trình sử dụng AI, để hiểu rõ ngữ cảnh hội thoại, hệ thống mặc định sẽ gửi toàn bộ lịch sử cuộc trò chuyện đến AI. Tuy nhiên, điều này có thể gây lãng phí tokens không cần thiết. Để giảm thiểu chi phí và tối ưu hiệu quả, bạn có thể áp dụng các mẹo sau:

### 1. Thường xuyên tạo cuộc trò chuyện mới
Hãy bắt đầu một cuộc trò chuyện mới khi không cần thiết giữ lại ngữ cảnh từ các cuộc trò chuyện trước đó. Điều này giúp giảm lượng dữ liệu gửi đi, từ đó tiết kiệm tokens.

### 2. Thiết lập giới hạn ngữ cảnh (Limit Context Tokens)
Việc giới hạn số lượng tin nhắn được gửi trong mỗi lần xử lý giúp bạn kiểm soát tốt hơn lượng tokens sử dụng. Dưới đây là cách thiết lập giới hạn ngữ cảnh trên một số ứng dụng phổ biến:

---

## **Chatbox AI**
1. Truy cập mục **Settings** -> **Max Message Count in Context**:
   - Trong phần cài đặt, bạn sẽ thấy mục "Max Message Count in Context". Ví dụ: nếu giá trị này được đặt là **10**, hệ thống sẽ chỉ gửi 10 tin nhắn gần nhất trong cuộc trò chuyện đến AI. 
   - Bạn có thể tùy chỉnh số lượng này (tăng hoặc giảm) dựa trên nhu cầu để đảm bảo AI hiểu đủ ngữ cảnh mà không lãng phí tokens.

   ![image](https://github.com/user-attachments/assets/b84fda7f-c673-4fac-ba78-ade0564a2fe4)

2. Sử dụng nút **Refresh Context**:
   - Trong quá trình sử dụng, nếu cảm thấy không cần lưu lại ngữ cảnh trước đó, bạn có thể bấm **Refresh Context** để làm mới ngữ cảnh hội thoại.

   ![image](https://github.com/user-attachments/assets/7c11e62e-70d5-4173-939d-af637354b294)

---

## **Webchat: aichat.itmovnteam.com**
1. Mở **Sidebar** và chọn **Parameters**:
   - Ở giao diện bên phải màn hình, nhấn vào **Sidebar** và chọn mục **Parameters** để thiết lập các thông số.

   ![image](https://github.com/user-attachments/assets/37725b73-e34a-43b8-8452-e57b5b27bebc)

2. Tạo **Preset** (cấu hình sẵn cho Model):
   - Trong mục này, bạn có thể tạo các **Preset** để lưu cấu hình ngữ cảnh, bao gồm số lượng tin nhắn, mô hình AI sử dụng, hoặc các thông số liên quan khác.

   ![image](https://github.com/user-attachments/assets/2612068c-ccaa-46c5-8105-5a3b98450c7c)

3. Sử dụng Preset đã tạo:
   - Sau khi tạo các Preset, bạn có thể dễ dàng chọn và áp dụng chúng trong các cuộc trò chuyện tùy theo nhu cầu cụ thể.

   ![image](https://github.com/user-attachments/assets/e42d8cf5-473d-4f0f-bb9f-012de7734dd8)

---

### Kết luận
Việc quản lý ngữ cảnh và sử dụng các tính năng như giới hạn tin nhắn hay làm mới ngữ cảnh không chỉ giúp tiết kiệm tokens mà còn tối ưu hóa hiệu suất của AI. Hãy áp dụng các mẹo trên để sử dụng dịch vụ MultiAppAI một cách hiệu quả và tiết kiệm hơn!
