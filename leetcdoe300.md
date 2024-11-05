* subsequence:子序列
* 在python中空的list[]会被视为false
* 初始化dp为[1,1,1,1,1]-->assume len(nums)=5,在循环中一步步用更大的数替代某个index原来的,最后return dp数组中max的值就是最长子序列
* dp[i]记录的是当前元素nums[i]作为结尾的最长subsequence的长度,而不是整个数组的最长subsequence长度
* 相当于设置两个指针进行比较,外层循环-->遍历数组中每一个元素,内层循环-->遍历外层循环i之前的每一个元素,nums[i]和nums[j]比较
* 要排除List为空列表的情况
* 
