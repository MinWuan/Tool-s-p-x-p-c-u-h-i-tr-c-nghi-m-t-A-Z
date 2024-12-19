# Tool sắp xếp câu hỏi trắc nghiệm từ A-Z

Yêu cầu đã cài đặt **Node js**, có thể cài đặt [Tại đây](https://nodejs.org/en/download/package-manager)
Kiểm tra version đã cài đặt:
```bash
node -v
```

### - Nếu câu hỏi có định dạng: `xxx. (nội dung)`
```
1. Phát biểu nào dưới đây KHÔNG ĐÚNG về Hệ điều hành?
A. Hệ điều hành quản lý các phần cứng máy tính.
B. __Hệ điều hành trực tiếp điều khiển hoạt động cho từng thiết bị phần cứng.
C. Hệ điều hành hỗ trợ phần mềm giao tiếp phần cứng trên máy tính.
D. Hệ điều hành hỗ trợ người dùng điều hành máy tính.
```
Nhập vào file `input.txt` và chạy câu lệnh sau:
```javascript
node run-opt-1.js
```
Kết quả hiển thị ở file `output.txt`

### - Nếu câu hỏi có định dạng: `Câu xxx: (nội dung) `
```
Câu 1: Hệ điều hành là chương trình hoạt động giữa người sử dụng với:
A. Phần mềm của máy tính
B. __Phần cứng của máy tính
C. Các chương trình ứng dụng
D. CPU và bộ nhớ
```
Nhập vào file `input.txt` và chạy câu lệnh sau:
```javascript
node run-opt-2.js
```
Kết quả hiển thị ở file `output.txt`

### - Gắn đáp án vào câu trắc nghiệm: 
Yêu định dạng nội dung ở file `input.txt` câu hỏi có dạng `xxx - (nội dung)` và `Đề xxx`
> Ghi đúng chính tả `Đề/đề/ĐỀ,...` không ghi `dề,dè,...`

```
Đề 1
1 - Thiết bị nào hoạt động ở tầng Vật lý (Physical)?
A. Switch
B. Card mạng
C. Hub và repeater
D. Router
...
```

Yêu định dạng câu hỏi ở file `answer.txt` (chữ đáp án có thể viết hoa / viết thường)
> Ghi đúng chính tả `Đề/đề/ĐỀ,...` không ghi `dề,dè,...` , `thứ tự đáp án` trùng với `thứ tự đề` 
```
Đề 1
C
B
D
...
Đề 2
A
D
E
...

```

Sau khi nhập xong ở file `input.txt` và `answer.txt` chạy lệnh sau:
```javascript
node run-opt-3.js
```
Kết quả hiển thị ở file `output.txt`

## Lưu ý
> `xxx` là số chạy từ 1-999 ngoài phạm vi sẽ không nhận diện được câu hỏi và không nằm trong file `output.txt`

# License

### Contact

If you have any questions regarding copyright or the use of this document, please contact us at: quantk4268@gmail.com.


