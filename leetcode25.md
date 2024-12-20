在每一次反转完成一组 k 个节点后，我们需要进行以下操作：

连接反转后的部分和未反转的部分。
更新指针，准备处理下一组节点。

cur = p0.next 是用来设置当前处理的组的起始位置，即从 p0.next 开始反转。

<img width="605" alt="image" src="https://github.com/user-attachments/assets/3efc7a80-5188-4dfc-a1f5-23a748d6fdb0" />

