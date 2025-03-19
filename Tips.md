# Một số tips tiết kiệm tokens khi sử dụng dịch vụ MultiAppAi

Để model AI có thể hiểu được đoạn hội thoại thì mặc định nó sẽ gửi toàn bộ đoạn hội thoại đi, điều này có thể gây lãng phí tokens.
Do đó, để tiết kiệm tokens chúng ta có thể:
1. Thường xuyên tạo chat mới tránh để hội thoại quá dài
2. Set limit context tokens

Sau đây là cách config limit context của một số Apps

## Chatbox AI
- Vào mục settings -> Max Message Count in Context:
    Như trong hình đang để là 10. Điều này có nghĩa là nó sẽ gửi 10 đoạn tin nhắn gần nhất trong cuộc hội thoại đi. Bạn có thể điều chỉnh số này nhỏ hơn đối với hội thoại đơn lẻ hoặc lớn hơn nếu bạn muốn model AI hiểu đoạn hội thoại dài.

    ![image](https://github.com/user-attachments/assets/b84fda7f-c673-4fac-ba78-ade0564a2fe4)

2. Ngoài ra bạn có thể sử dụng nút Refresh Context để reset context trong quá trình sử dụng
   
    ![image](https://github.com/user-attachments/assets/7c11e62e-70d5-4173-939d-af637354b294)
