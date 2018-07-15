# algorithm
学习过程当中遇到的一些算法题。
有笔试面试的算法题（目前只写了笔试遇见过的算法题）。和《剑指offer》上相关的算法题。
不积跬步无以至千里，加油。 
一、数据结构
    1、链表
       链表是物理存储单元上非连续的、非顺序的存储结构，数据元素的逻辑顺序是通过链表的指针地址实现，有一系列结点（地址）组成，结点可动态的生成。一个结点包含两个部分：存储数据元素的数据域和存储指向下一个结点地址的指针
      相关例子：Linkedlist实现了定义一个链表，和链表的一些方法
   2、队列
       队列是一种特殊的线性表，特殊之处在于它只允许在表的前端（front）进行删除操作，而在表的后端（rear）进行插入操作，和栈一样，队列是一种操作受限制的线性表。进行插入操作的端称为队尾，进行删除操作的端称为队头。
   3、栈
       栈（stack）又名堆栈，它是一种运算受限的线性表。其限制是仅允许在表的一端进行插入和删除运算。这一端被称为栈顶，相对地，把另一端称为栈底。向一个栈插入新元素又称作进栈、入栈或压栈，它是把新元素放到栈顶元素的上面，使之成为新的栈顶元素；从一个栈删除元素又称作出栈或退栈，它是把栈顶元素删除掉，使其相邻的元素成为新的栈顶元素。
   4、二叉树
       树：除了根结点之外每个结点只有一个父结点，根结点没有父结点，除了叶结点之外所有结点都有一个或者多个子节点，叶结点没有子结点，父结点和子结点之间用指针相连接
      二叉树：树的一种特殊结构，在二叉树中每个结点最多只有两个子结点。
      二叉树的遍历：前序遍历：先根结点，再访问左子结点，最后访问右子结点；中序遍历：先访问左子结点，再访问根结点，最后访问右子结点；后序遍历：先访问左子结点，再访问右子结点，最后访问根结点。
二、算法
   1、二分查找
	概念：也叫折半查找，找到数组中的中间值与两边数组中的端点值作比较，从而移动指向数组中间值的指针。如此迭代找到所要查找的数。
	条件：所要查找的数存在的结构必须是顺序存储的结构。（排过序的）。
	时间复杂度：二分查找查找的速度较快。时间复杂度为O（logn）
   2、快速排序
	思路:先在数组中选取一个数字，接下来把数组中的数字分为两部分，比所选的数字大的放在数组的右边，比所选的数字小的放在数组的左边。再对两边的数组进行递归的快速排序
	平均时间复杂度：O（nlogn）、最差情况下的时间复杂度：O(n2)
	

