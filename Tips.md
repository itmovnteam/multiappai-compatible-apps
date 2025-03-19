# Một số tips tiết kiệm tokens khi sử dụng dịch vụ MultiAppAi

Để model AI có thể hiểu được đoạn hội thoại thì mặc định nó sẽ gửi toàn bộ đoạn hội thoại đi, điều này có thể gây lãng phí tokens.
Do đó, để tiết kiệm tokens chúng ta có thể:
1. Thường xuyên tạo chat mới tránh để hội thoại quá dài
2. Set limit context tokens (xem hướng dẫn bên dưới)
