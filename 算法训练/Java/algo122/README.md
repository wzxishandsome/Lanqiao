<article>
    如果有m个人来还鞋，n个人来借鞋，一旦还鞋的人比借鞋的人少，那么无论如何也无法构成排序的
    如果没有人来还鞋，那么就只剩下一种情况了
    否则，我们假定第一个是借鞋的人或是还鞋的人
        对于第一个是借鞋的人，剩下了m个还鞋的人，和n-1个借鞋的人
        对于第一个是还鞋的人，剩下了m-1个还鞋的人和n个借鞋的人
        以此类推
</article>