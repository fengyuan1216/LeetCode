###086.Partition-List
设立两个新的链表头，在遍历原链接时将h->val大于x和小于x的节点分别串接上去。
特别要注意最后的新链表一定要将尾节点之后置为NULL，标志链表的结束，否则程序在测评时会继续追踪下去。