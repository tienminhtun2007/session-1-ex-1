# Ex1:
- trình duyệt sẽ gửi get method về cho server qua url ở dạng https://...
- server sau đó sẽ thông qua controller để nhận request, từ đó gọi services để xử lí logic nghiệp vụ, sau đó gửi sang controller, còn repo sẽ lấy dữ liệu từ databases
- database sẽ lưu danh sách dữ liệu dưới dạng list, giả lập nó trong Ram và nằm ở trong repo
- response trả về json