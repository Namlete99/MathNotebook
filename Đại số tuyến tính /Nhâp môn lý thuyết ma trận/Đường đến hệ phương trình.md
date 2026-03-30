# Đường đến giải hệ phương trình 

<div align="justify">

Dựa trên hai cuốn sách mà mình tự học là "Giáo trình: Nhập môn lý thuyết ma trận" và "Toán học cao cấp: Đại số và hình học giải tích". 

## Ma trận và định thức 

### 1. Lý thuyết tập hợp (hữu hạn)

**Định nghĩa 1.1**: 

> Tập hợp là một khái niệm cơ bản không được định nghĩa, mà được hiểu như là một sự tụ tập những sự vật hoặc những đối tượng nhất định (và thường có cùng một hoặc một số tính chất chung nào đó). Mỗi sự vật hoặc đối tượng đó được gọi là một phần tử  của tập hợp. 

**Ví dụ 1.2**: 

Tập hợp các số tự nhiên: 0, 1, 2, 3, ...

Tập hợp các số nguyên: ...-1, -2, 0, 1, 2, ...

Tập hợp thường được kí hiểu bởi các chữ cái in hoa, chẳng hạn như $X, Y, Z, ...$ Phần tử thường được kí hiệu bởi chữ cái in thường $x, y, z, ...$

**Ví dụ 1.3**:

Tập hợp các số tự nhiên: $\N$

Tập hợp các số nguyên: $\Z$

Nếu phần tử $x$ thuộc tập hợp $X$ thì ta kí hiệu là x $\isin$ X. Nếu phần tử $x$ không thuộc tập hợp $X$ thì ta kí hiệu là $x$ $\notin$ $X$. 


**Ví dụ 1.4**: Cho một tập hợp là các số tự nhiên $\N$:

Phần tử 1 thuộc tập hợp các số tự nhiên $\N$, kí hiệu 1 $\isin \N$.

Phần tử -1 không thuộc tập hợp các số số tự nhiên $\N$, kí hiệu -1 $\notin \N$

Một tập hợp không chứa phần tử nào được gọi là tập rỗng, và được kí hiệu là $\emptyset$. 

**Ví dụ 1.5**:

Tập hợp nghiệm thực của phương trình $x^2 + 1 = 0$ là tập hợp $\emptyset$.

Để biểu diễn một tập hợp, ta có thể liệt kê các phần tử của tập hợp đó:

$$X = \set{x1, x2, ...}$$

**Ví dụ 1.6**: Tập hợp các số tự nhiên $\N$ được biểu diễn ở dạng liệt kê như sau:

$$X = \set{0, 1, 2, 3, ...}$$

Ta cũng có thể biểu diễn tập hợp bằng cách chỉ rõ các tính chất đặc trưng của các phần tử của tập hợp:

$$X = \set{x|P(x)}$$

với $P(x)$ là tính chất của phần tử thuộc tập hợp X.

**Ví dụ 1.7**: Tập hợp các số hữu tỉ $\mathbb{Q}$ được biểu diễn bằng cách chỉ rõ tính chất đặc trưng của mỗi phần tử như sau: 

$$\mathbb{Q} = \set{\frac{a}{b}|a, b \isin \Z, b \ne 0}$$

**Ví dụ 1.8**: Tập nghiệm của hệ phương trình $\begin{cases}
  x + y + z = 1 \\
  x + 2y + 3z = 0
\end{cases}$ là tập hợp:

$$S = \set{(x, y ,x)| x, y, z \isin \R, x + y + x = 1, x + 2y + 3z = 0}$$

Để mô tả tập hợp một cách trực quan, người ta biểu diễn mỗi tập hợp bởi các điểm nằm trong một vòng phẳng mà ta gọi là biểu đồ Ven.

***

### 2. Ánh xạ 

Để nghiên cứu mối quan hệ giữa hai tập hợp, ta tập trung tìm hiểu các quy tắc cho tương ứng mỗi phần tử của tập hợp này với mỗi phần tử của tập hợp kia. Một lớp quy tắc như thế dẫn đến định nghĩa như sau.

**Định nghĩa 2.1**: Cho $X$ và $Y$ là hai tập hợp khác rỗng. Một ánh xạ $f$ từ $X$ đến $Y$ là một quy tắc cho tương ứng mỗi phần tử $x \isin X$ với một và chỉ một phần tử $y \isin Y$. Phần tử $x$ được gọi là tạo ảnh của phần tử $y$ qua ánh xạ $f$. Phần tử $y$ được gọi là ảnh của phần tử $x$ qua ánh xạ $f$ và kí hiệu là $f(x)$.

Ánh xạ $f$ từ $X$ đến $Y$ được kí hiệu là: 

> $$f: X \to Y, x \mapsto y = f(x)$$

Tập $X$ được gọi là tập nguồn hay tập xác định của ánh xạ $f$. Tập $Y$ được gọi là tập đích.

**Ví dụ 2.2**: 

Ánh xạ $f: \R \to \R, x \mapsto x^2$. Vì $f(2) = f(-2) = 2^2 = (-2)^2 = 4$ nên 4 là ảnh của 2 và -2. Còn 2 và -2 đều là tạo ảnh của 4.

Từ **định nghĩa 2.1** về ánh xạ, ta có các khái niệm về đơn ánh, toàn ánh, song ánh. 

**Định nghĩa 2.3**: Cho $f: X \to Y$ là một ánh xạ: 

> (i) Ánh xạ $f$ được gọi là ***đơn ánh*** nếu $\forall x_1, x_2 \isin X, x_1 \ne x_2$ kéo theo $f(x_1) \ne f(x_2)$

> (ii) Ánh xạ $f$ được gọi là ***toàn ánh*** nếu với bất kỳ $y \isin Y$, $\exist x\isin X$ để $y = f(x)$. 

> (iii) Ánh xạ $f$ được gọi là ***song ánh*** nếu ánh xạ $f$ vừa là ***đơn ánh*** và đồng thời cũng là ***toàn ánh***.

**Ví dụ 2.4**: Cho $f: [0;\infin] \to \R, x \mapsto x^2$

Với $x_1 = 1 \isin [0;\infin]$ ta được $y_1 = f(x_1) = 1^2 = 1 \isin \R$

Với $x_2 = 2 \isin [0;\infin]$ ta được  $y_2 = f(x_2) = 2^2 =4 \isin \R$

Vì $x_1 \ne x_2$ $(1 \ne 2)$ kéo theo $f(x_1) \ne f(x_2)$ $(1 \ne 4)$ nên $f: [0;\infin] \to \R, x \to x^2$ là ***đơn ánh***.

Với $y = -1$, $\nexists x \isin [0;\infin]$ sao cho $x^2 = -1$. Vậy nên $f: [0;\infin] \to \R, x \to x^2$ không là ***toàn ánh***.

Vì ánh xạ $f: [0;\infin] \to \R, x \to x^2$  chỉ là **đơn ánh** mà không phải là **toàn ánh**, nên ánh xạ này không phải là ***song ánh***.

<u>**Ví dụ 2.5**</u>: Cho $f: \R \to [0; \infin], x \mapsto x^2$

Với $x_1 = -1 \isin \R$ ta được $y_1 = f(x_1) = (-1)^2 = 1 \isin [0;\infin]$

Với $x_2 = \sqrt{2} \isin \R$ ta được $y_2 = f(x_2) = (\sqrt{2})^2 = 2 \isin [0;\infin]$

Vậy $\exist x\isin \R$ để $y = f(x) = x^2$, nên $f: \R \to [0; \infin], x \mapsto x^2$ là ***toàn ánh***.

Với $x_3 = 1 \isin \R$ ta được $y_3 = f(x_3) = 1^2 = 1 \isin [0;\infin]$ 

Vì $x_1 \ne x_3$ $(-1 \ne 1)$ mà kéo theo $f(x_1) = f(x_3)$, nên $f: \R \to [0; \infin], x \mapsto x^2$ không là ***đơn ánh***.

Vì ánh xạ $f: \R \to [0;\infin], x \to x^2$  chỉ là **toàn ánh** mà không phải là **toàn ánh**, nên ánh xạ này không phải là ***song ánh***.

<u>**Ví dụ 2.6**:</u>: Cho $f: [0;\infin] \to [0;\infin], x \to x^2$

Với $x_1 = 1 \isin [0;\infin]$ ta được $y_1 = f(x_1) = 1^2 = 1 \isin [0;\infin]$

Với $x_2 = 2 \isin [0;\infin]$ ta được  $y_2 = f(x_2) = 2^2 =4 \isin [0;\infin]$

Vì $x_1 \ne x_2$ $(1 \ne 2)$ kéo theo $f(x_1) \ne f(x_2)$ $(1 \ne 4)$ nên $f: [0;\infin] \to \R, x \to x^2$ là ***đơn ánh***.

Hơn nữa, $\exist x \isin [0;\infin]$ để $y = f(x) = x^2$, nên $f: [0;\infin] \to [0; \infin], x \mapsto x^2$ là ***toàn ánh***.

Vì ánh xạ $f: [0;\infin] \to [0;\infin], x \to x^2$ vừa là **đơn ánh** và cũng là vừa **toàn ánh** nên ánh xạ này là ***song ánh***.

*** 

### 3. Số phức 

. . .

*** 

### 4. Ma trận 

. . . 

*** 

### 5. Phép thế và dấu của phép thế

. . .

***

### 6. Định thức

. . . 

***

### 7. Hạng của ma trận

. . . 

***

### 8. Hệ phương trình tuyến tính

. . .

</div>