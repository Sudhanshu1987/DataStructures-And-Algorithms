# Trees

1. Traversals- PreOrder/InOrder/PostOrder
     * https://leetcode.com/problems/trim-a-binary-search-tree - PostOrder
2. BFS- 
* https://leetcode.com/problems/binary-tree-right-side-view - 3 interesting things to notice about such problems.
        * You almost always use the Queue for such problems
        * Time Complexity - O(n)... Space complexity - O(Diameter of Tree). At any time the maximum number of nodes in queue will be equal to the nodes at certain level. For leaf node this number is N / 2.
        * Due to statement 2 you can run the loop till the size of queue at every level and pick the last element.
