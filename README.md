# 数据结构代码：
## 1. 线性结构
  ### 01 顺序表
```
    待更新
```
  ### 02 单链表
```
    待更新
```
  ### 03 静态链表
``` 
    待更新
```
  ### 04 双向链表
```
* 初始化：
   Head->pre = Head->next = NULL //指向空
* 头插入：
   为空时：//pHead->next->pre = pNewNode; //不需要，因为该指针为NULL
   非空时：pHead->next->pre = pNewNode;   //需要
```
  ### 05 双向循环链表
```
 * 初始化：
     Head->pre = Head->next = Head; //指向自身
 * 为空：
     Head->next = Head;
 * 遍历结束：
     cur->next = Head;
```
  ### 总结
```
  线性表分为顺序存储和链式储存; 链式储存分为: 单链表, 静态链表, 循环链表, 双向链表
```
  ## 栈和队列
```
    待更新
```
  ## 树和二叉树














