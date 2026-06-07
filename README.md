# Nhận-diện-khuôn-mặt-PCA
Nhận diện khuôn mặt là một trong những bài toán trung tâm của thị giác máy tính với nhiều ứng dụng thực tiễn như bảo mật, xác thực danh tính, và tương tác người-máy. Ảnh khuôn mặt thường có chiều dữ liệu rất lớn — một ảnh grayscale kích thước 64×64 pixels đã tương ứng với một vector trong không gian R4096 — khiến việc xử lý trực tiếp trở nên tốn kém cả về tính toán lẫn bộ nhớ. Hơn nữa, dữ liệu chiều cao thường chứa nhiều thông tin dư thừa và tương quan giữa các chiều, dẫn đến hiện tượng "lời nguyền của chiều cao" (curse of dimensionality) làm giảm hiệu quả của các thuật toán học máy.

Sử dụng thuật toán PCA giảm chiều và trích xuất đặt trưng từ đó nhận diện được khuôn mặt những người có trong dataset, nếu người chưa có trong dataste thì kết luận unknowedface
