# Một số tips tiết kiệm tokens khi sử dụng dịch vụ MultiAppAi

Để model AI có thể hiểu được đoạn hội thoại thì mặc định nó sẽ gửi toàn bộ đoạn hội thoại đi, điều này có thể gây lãng phí tokens.
Do đó, để tiết kiệm tokens chúng ta có thể:
1. Thường xuyên tạo chat mới tránh để hội thoại quá dài
2. Set limit context tokens

Sau đây là cách config limit context của một số Apps

## Chatbox AI
1. Vào mục settings -> Max Message Count in Context:

   Trong phần cài đặt Settings , ví dụ trong ảnh mục "Max Message Count in Context" đang đặt là 10. Nghĩa là hệ thống sẽ gửi 10 tin nhắn gần nhất trong cuộc hội thoại đến AI. Bạn có thể tùy chỉnh số này (nhỏ hơn hoặc lớn hơn) để AI hiểu rõ hơn ngữ cảnh của cuộc trò chuyện.

    ![image](https://github.com/user-attachments/assets/b84fda7f-c673-4fac-ba78-ade0564a2fe4)

3. Ngoài ra bạn có thể sử dụng nút Refresh Context để reset context trong quá trình sử dụng
   
    ![image](https://github.com/user-attachments/assets/7c11e62e-70d5-4173-939d-af637354b294)

## Webchat: aichat.itmovnteam.com
1. Ở phẩn bên phải của màn hình bạn mở sidebar chọn "Parameters" để config

   ![image](https://github.com/user-attachments/assets/37725b73-e34a-43b8-8452-e57b5b27bebc)

2. Ở đây bạn sẽ tạo Preset (Model config sẵn) để sử dụng sau đó

   ![image](https://github.com/user-attachments/assets/2612068c-ccaa-46c5-8105-5a3b98450c7c)

3. Đến đây thì các bạn có thể lựa chọn preset của bạn vừa config. Như ở trên hình mình có tạo ra rất nhiều Preset để sử dụng tùy thuộc vào nhu cầu

   ![image](https://github.com/user-attachments/assets/e42d8cf5-473d-4f0f-bb9f-012de7734dd8)
