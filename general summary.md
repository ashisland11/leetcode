+ 用while遍历是不知道要循环几次,如果具体知道多少次--比如遍历这个string或者array的长度,就用for loop
+ 关注最优解 时间复杂度最低
+ non-decrasing包括相等和大于---sorted,order是升序
+  "add by one" 就是“每个值加 1”的意思
+  elif 是 "else if" 的缩写，表示“否则，如果...”。当 if 条件不成立时，它会检查 elif 后面的条件是否成立。
+  else 是指“否则”。当上面的所有条件都不成立时执行 else 块的代码。
+  continue 不是跳出整个循环，而是跳过当前循环的剩余部分，直接进入下一次循环。它的作用是在满足特定条件时，跳过当前的逻辑，而不退出整个循环。
  eg: for i in range(5):
    if i == 2:
        continue
    print(i)
0 
1
3
4
+ list.sort() 是一个就地排序方法，不会返回排序后的列表，而是直接修改原列表。这样写会导致 nums 的值变成 None. 排序直接写list.sort()
+ 在 Python 中，float('inf') 用来表示一个无限大的浮点数 float('-inf') 表示负无限大  ---infinite
+ 创建一个空的列表作为栈
+ stack = [] 先进后出
+ push 操作：添加元素到栈顶
+ stack.append(10)
+ stack.pop
+ . —— 表示当前目录。 
.. —— 表示父目录，也就是当前目录的上一级目录。  ".."就表示要回到上一级目录 如果碰到这个就代表要往上跳一级   /a/b/./../c==>/a/c
+ parts = ['home', 'user', 'documents', 'file.txt']
+path = '/'.join(parts)
+ 查看栈顶元素: stack[-1] 栈底元素:stack[0]
+ stack: append, pop
+ ]：在Python中，当使用负数进行除法时，结果向零取整的方式与C++或Java不同。Python中使用的是向负无穷取整，因此需要特别处理，使结果总是向零取整。可以通过使用int(a / b)来实现。
