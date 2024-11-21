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

