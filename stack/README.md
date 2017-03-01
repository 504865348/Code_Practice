【题目一】 实现一个特殊的栈,在实现栈的基本功能的基础上,再实现返回栈中最小元素的操作。		
> 栈的常用操作为pop, peek, push, isEmpty. 完成这个题目的时候可以考虑使用两个站结构存储。其中一个栈结构存储最小的元素，另一个栈存储所有元素。
	
> add        增加一个元索		
> remove   	移除并返回队列头部的元素	
> element  	返回队列头部的元素	
> offer     	添加一个元素并返回true	
> poll      	移除并返问队列头部的元素	
> peek      	返回队列头部的元素	
> 无put     	添加一个元素	
> 无take   	移除并返回队列头部的元素	

> 用一个push栈 + 一个pop栈	组成队列
> 用一个队列 + 一个help队列 	组成栈

【题目四】 一个栈依次压入1、2、3、4、5,那么从栈顶到栈底分别为5、4、3、2、1。将这个栈 转置后,从栈顶到栈底为1、2、3、4、5,也就是实现栈中元素的逆序,但是只能用 递归函数来实现,不能用其他数据结构。
> 递归其实相当于一个栈结构。
> 思路为，取出栈底元素(递归实现)，将余下部分翻转(递归调用), 将栈底元素放回。

【题目五】
> to be continue


【题目六】 给定一个整型数组arr和整数w,表示一个大小为w的窗口从数组 的最左边滑到最右边。求每次窗口内的最大值,并返回结果数组
> 用一个LinkedList存储最大值，每次新的元素进来，判断是否从last加入，并且判断是否有过期元素从first弹出。	
> 
> **重要** 这是一个重要的最大值最小值的更新结构，有的题目可能需要用stack完成，根据题目的要求。例如找到数组中下一个比当前元素大的数。但是都是利用一个子结构完成最大值最小值的更新。

【题目七】

2.MaxTree是一棵二叉树,数组的每一个值对应一个二叉树节点	
3.包括MaxTree树在内且在其中的每一棵子树上,值最大的节点 都是树的头。

> 可以用堆排序！
> **重要** 可以用*最俗栈结构*, 该栈结构中始终保持由大到小的排序。

【题目八】 给定String类型的数组strArr,再给定整数k,请严格按照排名顺序 打印出现次数前k名的字符串。		
> to be continue

【题目九】 有N个长度不一样的数组,所有数组中的元素都是从小到大有序 排列的,请从大到小打印这N个数组整体的前K个数。

【题目十】
> 创建大根堆和小根堆分别存储前一半和后一半。**实际上优先队列，heap可以看错stack结构**，这里用到了优先队列存储最大最小值，并放在顶部，思想可以看做是stack。

【题目十一】 给定一个整型矩阵map,其中的值只有0和1两种,求其中全是1的 所有矩形区域中,最大的矩形区域为1的数量。	

【题目十二】
	 Max{arr[i..j]} – Min{arr[i..j]} <= num		



