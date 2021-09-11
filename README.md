# JavaScript-for-scratch

### QUESTION 1: JavaScript là gì?
*Javascript là một ngôn ngữ lập trình dạng thông dịch, thường được dùng với frontend của web thủa sơ khai. Tuy nhiên gần đây do sự phát triển của công nghệ nên JavaScript đã được sử dụng bên phía backend như platform NodeJS hay desktop app như Electronjs hoặc gần đây nhất là trong Machine Learning với tensorflow.js

### QUESTION 2: Cú pháp?
*Việc cú pháp của JavaScript cũng có một mindset giống với các trình thông dịch khác như khi khai báo biến ta không cần phải định nghĩa kiểu tử đầu

Example:
#### Python
```python
x = 10
x = "Hello Merchize"
```

#### JavaScript
```javascript
var x = 10;
x = "Hello Merchize";
```
Đều không có lỗi do trình thông dịch sẽ chạy line-by-line và sẽ biết được kiểu của biến khi thông dịch

### QUESTION 3, 4: Biến và kiểu dữ liệu? Operators và phép gán?

*Javascript có 6 kiểu dữ liệu cơ bản
`
* Number
* Boolean
* String 
* Null
* Undefined
* Object
`
Các phần kiến thức khác cũng khá giống các ngôn ngữ thông thường. Chỉ đặc biệt ở chỗ Javascript thì ** function like object ** nên ta mới có thể truyền callback mà không ảnh hưởng ngữ nghĩa

*Về operators thì JS có thứ quan trọng là hai toán tử == và ===
Toán tử == sẽ so sánh tham trị của 2 biến còn toán tử === sẽ so sánh tham chiếu của 2 biến

### QUESTION 5: Hàm, scope

* Giống như các ngôn ngữ khác, hàm của Js cũng như một blackbox, ta chỉ biết input là gì và output là gì nếu như ta không được can thiệp vào source code của hàm. Tuy nhiên hàm trong JS có một chút đặc biết là function like object. Việc này giúp ta có thể truyền hàm như một parameter, có thể return giá trị là hàm hay truyền callback
* Scope trong JS cũng có 2 loại như các ngôn ngữ khác là Global scope và Local scope. Tuy nhiên trong JS ta có khái niệm mới là function scope, chỉ cần tạo một function mới thì scope mới sẽ ccuwocj tạo ra

### QUESTION 6: Object, Array

* Object của JS có chút đặc biệt hơn so với các ngôn ngữ khác là function cũng có type là object nên ta mới có các khái niệm closure, callback, ...
* Array của JS hơi khác so với Array của các ngôn ngữ như C++ khi mà việc cấp phát bộ nhớ được flexible. Ví dụ khi cấp phát mảng trong C++ gồm 5 phần tử số nguyên, C++ sẽ cấp phát 4x5 = 20 byte ô nhớ liên tục trong memory và ta không thể thay đổi độ dài của mảng đã cấp phát. Còn JS mảng sẽ được cấp phát động, sẽ có hiện tượng phân mảnh dữ liệu vào các memory còn trống và có thể thay đổi độ dài của mảng khi ta thêm phần tử vào

### QUESTION 7: Điều kiện và vòng lặp

*Chúng ta vẫn sẽ có các vòng lặp while, for, ... như các ngôn ngữ khác. Ta còn có thêm for...in để đọc các dữ liệu trong object còn for...of để đọc trong array

### Practice code with JS:
https://github.com/dnam-uet/Code/tree/master/JavaScript

