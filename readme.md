leetcode 两数相加 2 445

- 数字太大，相加，
  溢出
  字符串 大数字
  相加的算法
  最后一位相加
  carry + 加的结果， 放入数组， 反序

- 数据结构处理 
  如果不用字符串表达，有没有表达方案？
  链表 LinkedList
  推荐算法 

- 链表
  有点像数组，可以存一堆数据
  数组是连续空间
  链表是不连续的。更优 通过指针连起来
  每个节点，LinkedNode => LinkedList
  {val: 1, next: null} 

  1. 初始化链表   new LinkedNode(2);
    val, next
  2. 遍历链表
    while(node) {
        node = node.next;
    }
  3. 数组转变成链表
    - 第一次循环 val
    - 第二次循环 next - 1

- 大数相加 可以选择字符串 但链表更自然
  最后返回的也是相应的数据结构
  算法  每位相加， 存储， 进位 