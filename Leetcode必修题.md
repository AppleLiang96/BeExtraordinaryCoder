Leetcode必修题

1. [无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters)
2. ~~[最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring)~~
3. [删除链表的倒数第N个节点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list)head可能不存在的情况别忘了dummy
4. [合并K个排序链表](https://leetcode-cn.com/problems/merge-k-sorted-lists) 优先队列
5. [删除排序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array)
6. [在排序数组中查找元素的第一个和最后一个位置](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array)
7. [接雨水](https://leetcode-cn.com/problems/trapping-rain-water)
8. [最大子序和](https://leetcode-cn.com/problems/maximum-subarray)
9. [合并区间 ](https://leetcode-cn.com/problems/merge-intervals) 优先队列，按照区间的第一个字符进行排序
10. [旋转链表](https://leetcode-cn.com/problems/rotate-list)
11. [编辑距离](https://leetcode-cn.com/problems/edit-distance)
12. [删除排序链表中的重复元素 II](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list-ii)
13. [分隔链表](https://leetcode-cn.com/problems/partition-list)
14. [合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array)
15. [二叉树的中序遍历](https://leetcode-cn.com/problems/binary-tree-inorder-traversal)
16. [不同的二叉搜索树](https://leetcode-cn.com/problems/unique-binary-search-trees)
17. [验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree)
18. [相同的树](https://leetcode-cn.com/problems/same-tree)
19. [二叉树的锯齿形层次遍历](https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal)
20. [买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock)
21. [买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii)
22. [单词接龙](https://leetcode-cn.com/problems/word-ladder)
23. [分发糖果](https://leetcode-cn.com/problems/candy)
24. [环形链表](https://leetcode-cn.com/problems/linked-list-cycle)
25. [环形链表 II](https://leetcode-cn.com/problems/linked-list-cycle-ii)
26. [二叉树的前序遍历](https://leetcode-cn.com/problems/binary-tree-preorder-traversal)
27. [二叉树的后序遍历](https://leetcode-cn.com/problems/binary-tree-postorder-traversal)
28. [排序链表](https://leetcode-cn.com/problems/sort-list)
29. [岛屿数量](https://leetcode-cn.com/problems/number-of-islands)
30. [数组中的第K个最大元素](https://leetcode-cn.com/problems/kth-largest-element-in-an-array)
31. [滑动窗口最大值](https://leetcode-cn.com/problems/sliding-window-maximum)
32. [回文链表](https://leetcode-cn.com/problems/palindrome-linked-list)
33. [最长回文串](https://leetcode-cn.com/problems/longest-palindrome)
34. [二叉树的序列化与反序列化](https://leetcode-cn.com/problems/serialize-and-deserialize-binary-tree)
35. [最长上升子序列](https://leetcode-cn.com/problems/longest-increasing-subsequence)
36. [前 K 个高频元素](https://leetcode-cn.com/problems/top-k-frequent-elements)
37. [无重叠区间](https://leetcode-cn.com/problems/non-overlapping-intervals)
38. [最长回文串](https://leetcode-cn.com/problems/longest-palindrome)
39. [最长回文子序列](https://leetcode-cn.com/problems/longest-palindromic-subsequence)
40. [字符串的排列](https://leetcode-cn.com/problems/permutation-in-string)
41. [回文子串](https://leetcode-cn.com/problems/palindromic-substrings)
42. [最后一块石头的重量](https://leetcode-cn.com/problems/last-stone-weight)
43. 
44. [重建二叉树](https://leetcode-cn.com/problems/zhong-jian-er-cha-shu-lcof)
45. [二叉树的镜像](https://leetcode-cn.com/problems/er-cha-shu-de-jing-xiang-lcof)
46. [二叉搜索树与双向链表](https://leetcode-cn.com/problems/er-cha-sou-suo-shu-yu-shuang-xiang-lian-biao-lcof)
47. [数组中的逆序对](https://leetcode-cn.com/problems/shu-zu-zhong-de-ni-xu-dui-lcof)
48. [丑数](https://leetcode-cn.com/problems/chou-shu-lcof)](https://leetcode-cn.com/problems/chou-shu-lcof) dp

汉诺塔问题

顺时针打印矩阵

正方形旋转90度

快排

topK

逆序对

两数之和 三数之和

大数相加 大数相乘

1到n 最大的那个数

二叉树打家劫舍

前序中序后序 层次遍历

判断是不是后序遍历

完全二叉树判断

二叉搜索树判断

平衡二叉树

二叉树镜像

重建二叉树

二叉树和为某一值的路径（从根）

二叉树左下角得值

二叉树最大路径 124

反转链表

k个一组链表翻转 25

O1删除链表

删除链表的重复元素

从未到头打印链表

回文链表

两个有序链表头结点，打印相同元素

荷兰国旗

复制随机指针

1.  无重复字符的最长子串  hashset+双指针，找到一个重复的元素之后，左指针移动到跟这个重复元素相等的字符，并且移动掉这个字符 ishs 运动到第四个s了，left要移动到h才行

2.  最长回文串 记录left和max两个指针 expand方法  注意里面是while

3.  整数反转 判断溢出方法

    ```JAVA
    if (res > Integer.MAX_VALUE/10 ||(res == Integer.MAX_VALUE/10 && tail > 7) ) return 0;
    if (res < Integer.MIN_VALUE/10 || (res == Integer.MIN_VALUE/10 && tail < -8)) return 0;
    ```

4.  盛最多水的容器 两边往中间找，每次往里面移动较短的边，因为往中间移动，宽度必然变小，所以移动长边，只会让体积更小

5.  最长公共前缀 按照大小排序 找第一个和最后一个的最长公共前缀

6.  threeSum 三指针，两步跳过，continue前后相同的，while也是跳过两项相同的

7.  括号校验 栈

8.  括号生成  dfs入参左右剩余括号数量，右边剩余不能大于左边，要注意判断左右剩余不要小于0

9.  合并K个有序链表  优先队列

10.  交换链表的相邻两个节点  递归

11.  K个一组翻转链表 递归，首先把前K个链表翻转，然后递归后面的链表，把前面链表的最后一个节点指向后面递归的返回值即可

12.  数组原地移除重复元素removeDuplicates   A[count++] = A[i] 维护一个count 只有在一个元素不等于前一个元素的时候，才++

13.  就地算法将数组中所有等于这个值的元素删除 双指针，i，j，i一直找这个元素，不是这个元素，就把i位置的值赋给j，j++，否则j不++

14.  [ 实现 strStr()](https://leetcode-cn.com/problems/implement-strstr/)这个题双指针，但是遇到不匹配的时候，需要把左指针回溯回i = i - j + 1这个位置。主要是为了防止出现iswbib这种情况

15.  外观数列 模拟法 双循环

16.  组合总和 dfs private void dfs(int[] candidates, int target, ArrayList<Integer> list, int sum, int index) { 先排序，保证dfs的for循环时从index开始遍历，不往回遍历

17.  组合 在全排列1的基础上，for循环中的index传i + 1，防止往回遍历。for循环内部递归如果传i就表示不会往回遍历

18.  组合总和2 dfs中要增加两个地方，for循环中，dfs中的index要加1了，因为不能重复挑选，第二个是要剪枝candidates[i] == candidates[i - 1]这种情况[1,1,5,6]，1已经做过了就直接跳过

19.  子集1 不包含重复元素。因为是一直往后，不需要visited数组

20.  子集2 you重复元素。for循环内部多一层剪枝，[1,1,2,4]跳过第二个1 if ((i > index && nums[i] == nums[i - 1]))

dfs总结一下，一个数组，for循环的时候，如果每次都要从第一个开始遍历的，要用visited数组排除当前遍历过的，否则不用visited直接传i+1，往后遍历

全排列和组合的区别，就是全排列是需要往回选的，比方说[1,2,3],选到3的时候，还需要选1，这个时候只能用visited数组控制了

21.  全排列1 DFS 使用visited数组记录访问过的节点

22.  全排列2 [1,1,2,4,5] 要跳过第二个1 DFS 排序+多剪枝 如果前一个元素被访问了，并且当前的元素跟前一个元素一样，剪掉

23.  **第K个排列** 相比较全排列1 再多一个剪枝，就是如果下一层的总数小于k，就不访问了，把k剪掉下一层的总数，然后continue，下一层的总数是阶乘n-index-1。最重要的回溯回来也不用恢复状态了，因为这个方法，只会找到一条通路。

24.  单词搜索 dfs，需要用一个visited数组，定义四个方向

25.  缺失的第一个正数

     ```JAVA
     //三种种情况要跳过
     1. nums[i] <= 0 
     2. nums[i] > nums.length
     3. nums[nums[i] - 1] == nums[i]//[1,1]的情况下，要移动到的地方和当前位置的数字一样
     ```

26.  跳跃游戏1 记录一个max指针，每次更新他，false的条件是nums[i] == 0 && max == i && i < nums.length - 1

27.  跳跃游戏2 记录一个end 和一个max，end是之前的一跳最远的地方，到end的时候更新step，max是不断更新的。

28.  字母异位词分组 hash<String, List<String>> 第一个string是字符排序后的样子

奇数位递增，偶数位递减

29. 最大连续子数组，dp = Math.max(dp[i -  1]+ nums[i],nums[i])
30. **四数之和**  两个for循环 每一层for循环都要跳过两个数相同的。然后找到解的时候，left得一直跳到不等于当前值的点位置。第二层的循环是从i+1开始的
31. 最后一个单词的长度，从后往前遍历，查看每个字符是不是在a-z之间或者A-Z之间
32. 最小路径和   dp  第一行和第一列特殊处理，其他的地方是左边和上面的最小值加上当前格子
33. 加一  从后往前遍历，每一位加一，%10判断一下是不是0，如果不是0，可以直接返回，因为已经成功了。如果是0，继续加下一位
34. **x的平方根**，二分法，0为left，x为right，设一个ans变量，每次（long注意这里要转化为long）mid *mid <x的时候把mid赋值给ans
35. 爬楼梯  dp[i] = dp[i - 1] + dp[i - 2]
36. 矩阵置零  生成两个hashSet，分别存储要被标记的行或者列，然后第二次遍历的时候，如果行标记为0，直接把这一行全设为0，再去看列
37. 二维数组的查找 从右上角开始，查看cur跟target的关系，> j-- < i++
38. **颜色分类** 三指针，P0,P2,cur。while循环时cur<=p2，如果cur==0，交换cur和p0，cur++，cur是2，交换cur和p2，这个时候cur不++，因为交换过来的可能是0，那为什么第一次要++，因为交换过来的不可能是0，已经遍历过了。

上面这题和把技术移到偶数前面以及类似的题

39. 旋转数组的最小数字
40. [搜索旋转数组](https://leetcode-cn.com/problems/search-rotate-array-lcci) 找到有序的一边，然后二分查找（要写一个二分的），判断哪边有序的条件是nums[mid] > num[right]
41. 只出现一次的元素  二进制中1的个数
42. 用两个栈实现队列 栈1只负责push，栈2刚开始是空的，第一次deletehead之后，把栈1的所有元素移动到栈2中，此时栈2的栈顶是头结点，delete掉，就还是头节点，一直delete到栈2为空，这个时候再把栈1的元素全部移动到栈2

斐波那契数列的取模要在计算a+b的时候而不是最后

奇偶链表

43.  树的子结构，写一个help比较以A为根节点的是否一样，然后遍历所有的A
44.  镜像二叉树 记住存储临时左节点
45.  对称二叉树     boolean help(TreeNode left, TreeNode right)  左子树的右左和右子树的左右对比
46.  **栈的压入弹出序列** 模拟栈，最后判断栈是否为空
47.  从上到下打印二叉树 BFS
48.  **二叉树转双向链表**  一个pre 一个head节点，dfs左边，如果pre是空，说明是首节点，如果不为空，pre就是当前双向链表的最后一个节点，把当前的遍历的节点连到pre的后面，当前遍历的节点就是pre了，然后再dfs右边。
49.  **二叉树的序列化与反序列化**，不能用LinkedList，要用Queue，左子树右子树是空也要放进去。反序列化的时候，利用i控制，顺序是根左右，每次取出一个如果不是null，设为根节点，这个时候i应当是指向他的左节点，注意这步的指向问题
50.  数组中出现超过一半的数字 擂台法，定义两个变量count和cur，cur代表现在守擂的数字，count代表数量，遍历数组，如果数字与守擂人相同++，不相同--，如果count变成0了换守擂人，并且count变为1.
51.  **1～n整数中1出现的次数**
52.  **数字序列中某一位的数字**。首先找到n是多少位的，定义一个count 9×start×digit start（注意这里是每次减一次，然后n下一次已经变小了），每次9×start×digit递增10，digit每次递增1，一直到不够减了，这个时候digit就是位数，然后用剩余的n-1/digit+start就是当前数，取余就是位数
53.  把数组排成最小的数 把int数组转化为string数组，然后排序，排序的规则是(o1, o2) -> (o1 + o2).compareTo(o2 + o1)
54.  把数字翻译成字符串 dp  要开一个length+1的数组

```java
if (integer >= 10 && integer <= 25) {
  dp[i + 1] = dp[i] + dp[i - 1];
}else {
  dp[i + 1] = dp[i];
}
```

55.  最长不含重复字符的子字符串 hashset+双指针

重点代码

```JAVA
if (set.contains(s.charAt(j))) {
  while (s.charAt(i) != s.charAt(j)) {
    set.remove(s.charAt(i++));
  }
  if (s.charAt(i) == s.charAt(j)) {
    i++;
  }
}
```

56. 丑数  dp for循环从1开始 三个指针分别指向2，3，5的当前位置。

    ```JAVA
    dp[0] = 1
    int n2 = dp[p2] * 2, n3 = dp[p3] * 3, n5 = dp[p5] * 5;
    dp[i] = Math.min(Math.min(n2, n3), n5);
    ```

57. 第一个只出现一次的字符 开一个count[26]的数组，遍历++，然后再次遍历找到第一个count为1的返回

58. 判定字符是否唯一 建立一个26长度的count数组，然后遍历字符串，如果count++之后为2了说明有重复

59. 判定是否互为字符重排 跟上提差不多  也是开两个26长度的数组，然后遍历字符串，最后看看这俩数组是否相同

60. **数组中的逆序对** 

```JAVA
void divide(int[] nums, int left, int right)
//length是当前的最右届
void merge(int[] nums, int left, int mid, int right)
```

61.  两个链表的第一个公共节点

```JAVA
while (curA != curB) {
  if (curA == null) {
    curA = headB;
    continue;
  }
  if (curB == null) {
    curB = headA;
    continue;
  }
  curA = curA.next;
  curB = curB.next;
}
```

62.  **在排序数组中查找数字I**  二分法
63.  二叉搜索树的第k大节点 注意这个是逆序的，所以应该是右中左，改变一下stack放入的顺序即可
64.  二叉树的深度  递归一行Math.max(maxDepth(root.left) + 1, maxDepth(root.right) + 1);
65.  平衡二叉树 左子树是平衡二叉树 && 右子树是平衡二叉树 && 左子树的深度和右子树的深度相差为1

异或题

任何数和本身异或则为 0

任何数和 0 异或是 本身

 只出现一次的数字 1

66.  数组中数字出现的次数 两个数字出现了一次，其他数字出现了两次，首先全部异或一边，最后留下的这个数肯定不是0，因为异或运算两个数不相等，最后得到的数字肯定有一位不是1，通过这一位1 把数组分成两份，然后分别异或即可
67.  数组中数字出现的次数 II

因为只有所有的数字出现了三次，因为二进制的那一位不是0就是1，所以32位的int全部累加起来，不是0就是3，就是4，如果出现4的那一位，就是唯一出现的那个数的1，其他都是0.所以需要定义一个count[32]的数组

68.  和为s的连续正数序列 双指针 滑动窗口法，i，j，sum=1，i只需要到target/2这个边界（注意这里需要=，因为像9，【4，5】这种答案），如果sum==target 初始化答案，然后左边界向右移动，因为i开始的是答案，下一个答案一定是i+1开始的。
69.  滑动窗口的最大值  定义一个queue，第一次构建窗口，遍历k次，然后add，然后继续从k开始遍历到最后，先去除首个元素超期的，再加上最新的元素（这里要while去掉队列中比他大的），然后再取出队首就是最大的
70.  扑克牌中的顺子 如果除0外无重复数字 && max-min<5 就说明是顺子
71.  **约瑟夫环**的问题  圆圈中最后剩下的数字 最后一个数字的index是0，那么他上一位的数字的index = (index + m)%上次轮没复制前数组的大小。这时因为他每次的对头都是上一个对头偏移m个节点
72.  股票的最大利润/买卖股票的最佳时机 dp[i] = max(dp[i - 1], 当前价格 - min(前i-1天的最小值))
73.  买卖股票的最佳时机II 贪心，只要后一天的股票大于前一天的就卖掉
74.  求1加到n 不能用判断符号和加减乘除，用短路效应实现递归的终止

boolean x = n > 1 && (n = sumNums(n - 1) + n) > 0;

75.   不用加减乘除做加法 a+b，等价于(a^b)+((a&b)<<1)

```JAVA
while (b != 0) {
  //计算进位
  int temp = (a & b) << 1;
  //不算进位的和
  a ^= b;
  //把进位赋值给b 下一次b只要加进位就行了
  b = temp;
}
return a;
```

76.  构建乘积数组 就是分发糖果的思路，构建left和right两个数组，从左往右遍历一遍，然后从右往左遍历一遍，然后再次遍历a[i] = left[i - 1] * right[i + 1];
77.  把字符串转换成整数 todo
78.  二叉搜索树的最近公共祖先 注意这里是二叉搜索树，所以主要看p和q在root的哪边，如果在两边或者root==p||root==q那么就返回root，否则看pq在哪边就递归哪边
79.  二叉树的最近公共祖先，递归找左右，如果左边没有，就返回右边，如果右边没有就返回左边，如果左右都没有，说明是root
80.  二叉树中的最大路径和，不路过根节点。用递归。

```JAVA
Integer max = Integer.MIN_VALUE;
public int maxPathSum(TreeNode root) {
  if (root == null) {
    return 0;
  }
  help(root);
  return max;
}

Integer help(TreeNode root) {
  if (root == null) {
    return 0;
  }
  int left = Math.max(0, help(root.left));
  int right = Math.max(0, help(root.right));
  int cur = root.val + left + right;
  max = Math.max(max, cur);
  //这里为什么不返回cur，因为这里要返回节点的最大贡献值，所以只能返回一边
  return root.val + Math.max(left, right);
}
```

81. 搜索旋转排序数组 判断哪边有序使用mid和right做比较
82. 最小栈 使用一个辅助栈  放最小的元素，每次push和pop都要看min栈要不要加入（<=）或者移除元素
83. 将有序数组转换为二叉搜索树 二分 递归，用数组的索引
84. 二叉树的右视图 DFS 要想DFS的前序遍历的第一个元素就是二叉树的左视图，所以右视图，就是右中左前序遍历的反向。然后每次DFS的深度+1的时候，遍历的第一个元素就是右视图

```java
private void help(TreeNode root, int i) {
  if (root == null) {
    return;
  }
  if (result.size() == i) {
    result.add(root.val);
  }
  i++;
  help(root.right, i);
  help(root.left, i);
}
```

85.  删除排序链表中的重复元素 1,2. 1是保留重复数字，2是删除所有重复数字。所以1里面只需要一直往后找到不一样的，把current.next = current.next.next;
86.  2里面当找到一个重复数字之后，一直往后遍历到不重复，然后把cur和prev.next指向下一个不重复的元素
87.  从前序与中序遍历序列构造二叉树

```JAVA
root.left = buildTree(preorder, preBegin + 1, preBegin + index - inBegin, inorder, inBegin, index - 1);
root.right = buildTree(preorder, preBegin + index - inBegin + 1, preEnd, inorder, index + 1, inEnd);
```

88.  从中序与后序遍历序列构造二叉树

```JAVA
root.left = buildTree(inorder, inBegin, index - 1, postorder, postBegin, postBegin + index - inBegin - 1);
root.right = buildTree(inorder, index + 1, inEnd, postorder, postBegin + index - inBegin, postEnd - 1);
```

89.  两数相加 设置一个进位add变量 注意判断l1或者l2有一个为空的处理最长连续序列 维护一个nums所有数目的set，然后遍历数组，如果当前数字不在set中直接continue，否则遍历这个数的上下界，定义一个temp++，temp--，找到上下界，更新max，并且每次++或者--都需要set.remove这个数字
90.  字符串相加 设一个StringBuilder 

```JAVA
StringBuilder sb = new StringBuilder("");
while (i >= 0 || j >= 0) {
int n1 = i >= 0 ? num1.charAt(i) - '0' : 0;
int n2 = j >= 0 ? num2.charAt(j) - '0' : 0;
add = (n1 + n2 + add) / 10;
int ans = (n1 + n2 + add) % 10;
sb.append(ans);
i--;
j--;
}
if (add == 1) {
sb.append("1");
}
```

91.  路径总和 
92.  路径总和2  这题需要在回溯前判断remain是否符合要求
93.  二叉树的完全性检验 层序遍历，然后用一个prev记录前驱节点，如果出现了当前的node不为空，但是prev为空，说明不是完全二叉树
94.  螺旋矩阵(顺时针打印矩阵) 定义左上角和右下角两个顶点, 注意循环内部的时候遍历不要加等号，后面还需要考虑最后一行和一列的情况，startX==endX（最后一行），startY==endY（最后一列）
95.  前 K 个高频元素 用map+PriorityQueue 搞定
96.  移动零 用一个count统计0的个数，也就是后面的数字需要往前移动的个数swap(nums, i, i - count);
97.  相同的树         return p.val == q.val && isSameTree(p.left, q.left) && isSameTree(p.right, q.right);
98.  重排链表 快慢找中点，反转后半部分，归并链表（用一个flag控制）

8 842 4 215  518 162  328

99.  二叉树剪枝  只有左边右边都是0或者null并且自己也是0才返回true
100.  两数相加2 用栈来反向一下 注意最后add为1的时候需要加一个节点，然后反转链表
101.  二进制求和 跟上面这题差不多
102.  腐烂的橘子  BFS 用一个队列，第一次把所有的腐烂的位置都放进队列，然后在创建一个child，每次queue为空了，把child赋给queue的时候，就count++，如果queue和child同时为空，说明能腐烂到的地方都腐烂了，然后检查一下还没有没有没有腐烂的橘子，如果有说明无法遍历，返回-1
103.  有序数组的平方 找到第一个>=0的数的索引，然后一个right指向他，left是right-1
104.  将每个元素替换为右侧最大元素 定义一个rightMax的变量 rightMax = Math.max(temp, rightMax);
105.  单词拆分 set+dp dp[i]表示当前可以被拆分,遍历到每一个的时候,如果包含在set中直接true,否则从0开始循环到i

```java
if (dp[j] && set.contains(s.substring(j + 1, i + 1))) {
  dp[i] = true;
  break;
}
```

二叉树的直径 实质上就是左右最大的深度

最大正方形 dp  边长

```JAVA
result[i][j] = Math.min(result[i - 1][j - 1], Math.min(result[i][j - 1], result[i - 1][j])) + 1;
```

和为K的子数组 用一个map存储前n项的和：次数。然后遍历找sum-k

奇偶链表 建立一个奇数链表，一个偶数链表，用flag控制，然后最重要的别忘了



SQL 学生表 课程表 学生课程表

Q1 查询学生表中重名的学生，查出id和name 按name排序

```MYSQL
select id, name from student where name in 
(select name from student group by name having( count(*) > 1 )) 
order by name;
```

Q2 在student_course表中查询平均分不及格的同学的id和name

```MYSQL
select id, AVG(score) from student_course group by id having(AVG(score) < 60)
```

Q3 在student_course表中查询每门课成绩都不低于80的学生Id

```MYSQL
select id 
(select id from student_course where score < 80)
```

Q4查询每个学生的总成绩，结果列出name和总成绩

```MYSQL
select name from student where id in 
(select id, SUM(score) all_score from student_course group by id)
```































