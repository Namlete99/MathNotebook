# Đường đến giải hệ phương trình 

<div align="justify">

Dựa trên hai cuốn sách mà mình tự học là "Giáo trình: Nhập môn lý thuyết ma trận" và "Toán học cao cấp: Đại số và hình học giải tích". 

## Ma trận và định thức 

### 1. Lý thuyết tập hợp (hữu hạn)

**Định nghĩa 1.1**: 

> Tập hợp là một khái niệm cơ bản không được định nghĩa, mà được hiểu như là một sự tụ tập những sự vật hoặc những đối tượng nhất định (và thường có cùng một hoặc một số tính chất chung nào đó). Mỗi sự vật hoặc đối tượng đó được gọi là một phần tử  của tập hợp. 

**Ví dụ 1.2**: 

> Tập hợp các số tự nhiên: 0, 1, 2, 3, ...

> Tập hợp các số nguyên: ...-1, -2, 0, 1, 2, ...

Tập hợp thường được kí hiểu bởi các chữ cái in hoa, chẳng hạn như $X, Y, Z, ...$ Phần tử thường được kí hiệu bởi chữ cái in thường $x, y, z, ...$

**Ví dụ 1.3**:

> Tập hợp các số tự nhiên: $\N$

> Tập hợp các số nguyên: $\Z$

Nếu phần tử $x$ thuộc tập hợp $X$ thì ta kí hiệu là x $\isin$ X. Nếu phần tử $x$ không thuộc tập hợp $X$ thì ta kí hiệu là $x$ $\notin$ $X$. 


**Ví dụ 1.4**: Cho một tập hợp là các số tự nhiên $\N$:

> Phần tử 1 thuộc tập hợp các số tự nhiên $\N$, kí hiệu 1 $\isin \N$.

> Phần tử -1 không thuộc tập hợp các số số tự nhiên $\N$, kí hiệu -1 $\notin \N$

Một tập hợp không chứa phần tử nào được gọi là tập rỗng, và được kí hiệu là $\emptyset$. 

**Ví dụ 1.5**:

> Tập hợp nghiệm thực của phương trình $x^2 + 1 = 0$ là tập hợp $\emptyset$.

Để biểu diễn một tập hợp, ta có thể liệt kê các phần tử của tập hợp đó:

$$X = \set{x1, x2, ...}$$

**Ví dụ 1.6**: Tập hợp các số tự nhiên $\N$ được biểu diễn ở dạng liệt kê như sau:

> $$X = \set{0, 1, 2, 3, ...}$$

Ta cũng có thể biểu diễn tập hợp bằng cách chỉ rõ các tính chất đặc trưng của các phần tử của tập hợp:

$$X = \set{x|P(x)}$$

với $P(x)$ là tính chất của phần tử thuộc tập hợp X.

**Ví dụ 1.7**: Tập hợp các số hữu tỉ $\mathbb{Q}$ được biểu diễn bằng cách chỉ rõ tính chất đặc trưng của mỗi phần tử như sau: 

> $$\mathbb{Q} = \set{\frac{a}{b}|a, b \isin \Z, b \ne 0}$$

**Ví dụ 1.8**: Tập nghiệm của hệ phương trình $\begin{cases}
  x + y + z = 1 \\
  x + 2y + 3z = 0
\end{cases}$ là tập hợp:

> $$S = \set{(x, y ,x)| x, y, z \isin \R, x + y + x = 1, x + 2y + 3z = 0}$$

Để mô tả tập hợp một cách trực quan, người ta biểu diễn mỗi tập hợp bởi các điểm nằm trong một vòng phẳng mà ta gọi là biểu đồ Ven.

### 2. Ánh xạ 

Để nghiên cứu mối quan hệ giữa hai tập hợp, ta tập trung tìm hiểu các quy tắc cho tương ứng mỗi phần tử của tập hợp này với mỗi phần tử của tập hợp kia. Một lớp quy tắc như thế dẫn đến định nghĩa như sau.

**Định nghĩa 2.1**: Cho $X$ và $Y$ là hai tập hợp khác rỗng.

</div>