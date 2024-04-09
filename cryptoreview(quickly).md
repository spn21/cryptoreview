

### 1.整数

$Z,N,N^{+}$

$ +,-,×$

$Euclidean Division$ $(a = bq + r)$

$b | a$ 

### 2.质数

[Sieve of Eratosthenes](https://zh.wikipedia.org/wiki/%E5%9F%83%E6%8B%89%E6%89%98%E6%96%AF%E7%89%B9%E5%B0%BC%E7%AD%9B%E6%B3%95)

[Lucas–Lehmer primality test](https://zh.wikipedia.org/wiki/%E5%8D%A2%E5%8D%A1%E6%96%AF-%E8%8E%B1%E9%BB%98%E6%A3%80%E9%AA%8C%E6%B3%95)

[Cyclotomic AKS test](https://zh.wikipedia.org/wiki/AKS%E8%B3%AA%E6%95%B8%E6%B8%AC%E8%A9%A6)

[Miller–Rabin primality test](https://zh.wikipedia.org/wiki/%E7%B1%B3%E5%8B%92-%E6%8B%89%E5%AE%BE%E6%A3%80%E9%AA%8C)

### 3.Euclidean

$gcd$

```python
def euclidean_algorithm(a, b):
    if a < b:
        a, b = b, a
    while b:
        a, b = b, a % b
    return a
num1 = x
num2 = y
gcd_result = euclidean_algorithm(num1, num2)
print(f'{gcd_result}')
```

### 4.Extended Euclidean algorithm

$x_{i} a + y_{i} b = r_{i}$

$gcd(a,b) = ax + by$

### 5.modular arithmetic

##### 同余

1.反身性

2.对称性

3.传递性

##### 剩余类

$Z_{n}$模$n$的剩余类 $Z_n = 0,1,2,...,n -1$

##### 基础模运算

1.平移

2.缩放

3.加法

4.乘法

##### 二次剩余

$x^2 \equiv q (mod n)$

##### 除法

##### 模逆元

$ wy \equiv 1 (modn) $

$gcd(y,n) = 1$

### 6.Chinese remainder theorem

### 7.Fermat's little theorem

$a^p \equiv a (mod p)$

### 8.euler's toitient  function

1.单元集

2.$\Phi (n) = |\mathbb{Z^{*}_n}|$

$\phi(p) = p-1$

$\phi(p^k) = p^k -p^{k-1}$

$gcd(m,n) = 1,有 \phi(mn) = \phi(m)\phi(n)$

### 9.group

##### $(G,\cdot)$

1.封闭性(closure)

2.结合律(associativity)

3.存在单位元(identity Element)

4.存在逆元(inverse Element)

有限群	无限群

##### 子群 subgroup

单位元逆元交集

陪集

