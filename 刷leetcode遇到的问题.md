#### 1. leetcode206

单链表反转问题

C++中不能在'ListNode'类型的空指针中访问成员，也就是不能用

```c++
if(head==nullptr||head->next==nullptr)
if(!head->next||!head)
```

必须是

```c++
if(!head||!head->next)
```

