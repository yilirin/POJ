## CodingExercise
#### 1007 DNA Sorting
1. 使用gets进行字符串接收。
2. map是自带按key顺序排列。里面是用红黑树实现的。
3. 将(key,value)的map重新按（value，key）放在新map中就实现了按value排序，用迭代器输出即可。
4. 注意map和multimap的区别。尤其在3的情况下，可能出现重复，所以应用multimap。

#### 1922 Ride to School
1. 不必管中间过程，只考虑结果。
2. 有些题目数学性很强，可以不要上来直接编，而是考虑数学解法。
3. 用limits.h来表示无穷大。

## Mathematics
#### 1401 Factorial
1. 阶乘末尾的0的个数： 累加对5各幂的商。

#### 2262 Goldbach's Conjecture
1. prime算法：用tag，［2，sqrt(n)］遍历，注意不要漏了==sqrt。

#### 2693 Chocolate Chip Cookies
1. 过两点的定半径圆心坐标：
2. edge case啊！初始化。

## DataStructures
###2418 Hardwood Species
1. 符号表、字典。

###1330 Nearest Common Ancestors
1. LCA算法

###3367 Expression
1. 树的遍历，后缀表达式。
2. 如何要用到动态内存，或者要利用指针来实现如树一样的关系，不必用new的堆的方法，这样很慢。可以在栈中先开辟一块空间，如申请一个数组，利用数组中元素的地址作为引用来实现树结构，不必花费new的开销，提高速度。

###1984 Navigation Nightmare
1. Union-Find并查集
