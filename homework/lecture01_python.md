# Phần bài tập thực hành Python 

### BT1: cho 1 biến data kiểu string như bên dưới

```
data = '''
Come to the
River
Of my
Soulful
Sentiments
Meandering silently
Yearning for release.
Hasten
Earnestly
As my love flows by
Rushing through the flood-gates
To your heart.
'''
# https://www.poetrysoup.com/poem/cross_my_heart_609765
```

- Yêu cầu: giải mã mật thư, lấy tất cả các chữ cái đầu của từng dòng rồi ghép lại để được 1 câu cụ thể.

### BT2

- Tính tổng tất cả các chữ số trong kết quả của phép tính `2**10000`

### BT3
- Cho đoạn bài hát sau

```
Ngư60ời 'theo hư@ơng' hoa 100mây mù [giăng lối]
Làn 25 sương khó30i phôi phai 90 đưa bư$ớc ai xa rồi 35
100Đơn c#ôi m99ình ta {vấn vương} hồi ức tro^ng ... men say (chiều mưa) buồ80n 
Ng~ăn "giọt lệ" ngừng k2hiến khoé mi sầu bi.1 
```

- làm rõ lời bài hát bằng cách loại bỏ toàn bộ các số và kí tự punctuation :) 
- punctuation là gì? 

```
import string
string.punctuation # :)
```

### BT4

- Giải bài toán lớp 3 sau: https://vnexpress.net/bai-toan-lop-3-co-so-luong-dap-an-khong-lo-3220439.html

- Các biến liệt kê bên dưới nằm trong đoạn từ 1 đến 9, hỏi có bn bộ giá trị thỏa mãn điều kiện sau:

```python
a + 13 * b / c + d + 12 * e - f - 11 + g * h / i - 10 = 66
```

### BT5

- Nếu lần lượt cho các giá trị trong bảng chữ cái tiếng Anh như sau: a = 1, b = 2, c = 3, .... thì tổng giá trị của các từ khi quy đổi ra số là như sau:

```
abc = 1 + 2 + 3 = 6
defgh = 4 + 5 + 6 + 7 + 8 = 30 
....
```

- Hỏi các từ sau có giá trị là bao nhiêu: python, patience, documents, students, homework, practice, success, english, university, congratulation

### BT6

- Viết code sinh các số Fibonacci dưới 1000, lưu giữ kết quả vào 1 list.

### BT7 

- Viết code sinh các số nguyên tố dưới 10000, lưu giữ kết quả vào 1 list.

### BT8

- Cho đoạn văn bản sau

```text
Python is an easy to learn, powerful programming language. It has efficient high-level data structures and a simple but effective approach to object-oriented programming. Python’s elegant syntax and dynamic typing, together with its interpreted nature, make it an ideal language for scripting and rapid application development in many areas on most platforms.

The Python interpreter and the extensive standard library are freely available in source or binary form for all major platforms from the Python Web site, https://www.python.org/, and may be freely distributed. The same site also contains distributions of and pointers to many free third party Python modules, programs and tools, and additional documentation.

The Python interpreter is easily extended with new functions and data types implemented in C or C++ (or other languages callable from C). Python is also suitable as an extension language for customizable applications.

This tutorial introduces the reader informally to the basic concepts and features of the Python language and system. It helps to have a Python interpreter handy for hands-on experience, but all examples are self-contained, so the tutorial can be read off-line as well.

For a description of standard objects and modules, see The Python Standard Library. The Python Language Reference gives a more formal definition of the language. To write extensions in C or C++, read Extending and Embedding the Python Interpreter and Python/C API Reference Manual. There are also several books covering Python in depth.

This tutorial does not attempt to be comprehensive and cover every single feature, or even every commonly used feature. Instead, it introduces many of Python’s most noteworthy features, and will give you a good idea of the language’s flavor and style. After reading it, you will be able to read and write Python modules and programs, and you will be ready to learn more about the various Python library modules described in The Python Standard Library.
```

- Trả về dict chứa 10 phần tử xuất hiện nhiều nhất cùng số lần xuất hiện theo format:

```python
result = {"if": 10, ...}
```

- Lưu ý: không quan trọng uppercase và lowercase

### BT9

- Với 2 list:

```python
A = [1, 2, 3, 4, 5, 6]
B = [3, 4, 5, 6, 7, 8, 9, 10]
```

- Lấy các phần tử:
  - Có trong cả A, B
  - Chỉ có trong A
  - Chỉ có trong B
  - Chỉ có trong A hoặc B (mà không phải cả 2)
  
### BT10

- Trả về 1 list n tuple được định nghĩa như sau:

```python
years = [(1900, "Canh Tí"), ... (2019, "Kỷ Hợi")]
```

- với năm chạy từ 1900 đến 2019, output yêu cầu trả về đúng như format bên trên, bao gồm năm và can chi tương ứng
- Chú ý viết hoa các chữ cái đầu 

---

# Tài liệu tham khảo (Numpy, Matplotlib, Pandas)

- Python for Data Science Handbook: https://jakevdp.github.io/PythonDataScienceHandbook/
