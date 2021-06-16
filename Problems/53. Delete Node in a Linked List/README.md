# 53. Delete Node in a Linked List
### Difficulty: Easy
Write a function to delete a node in a singly-linked list. You will not be given access to the head of the list, instead you will be given access to the node to be deleted directly. <br/> It is guaranteed that the node to be deleted is not a tail node in the list. <br/>   <br/><b>- Example</b> 1: <br/> Input: head = [4,5,1,9], node = 5 <br/> Output: [4,1,9] <br/> Explanation: You are given the second node with value 5, the linked list should become 4 -> 1 -> 9 after calling your function. <br/> <br/><b>- Example</b> 2: <br/> Input: head = [4,5,1,9], node = 1 <br/> Output: [4,5,9] <br/> Explanation: You are given the third node with value 1, the linked list should become 4 -> 5 -> 9 after calling your function. <br/> <br/><b>- Example</b> 3: <br/> Input: head = [1,2,3,4], node = 3 <br/> Output: [1,2,4] <br/> <br/><b>- Example</b> 4: <br/> Input: head = [0,1], node = 0 <br/> Output: [1] <br/> <br/><b>- Example</b> 5: <br/> Input: head = [-3,5,-99], node = -3 <br/> Output: [5,-99] <br/>   Constraints: <br/> The number of the nodes in the given list is in the range [2, 1000]. <br/> -1000 <= Node.val <= 1000 <br/> The value of each node in the list is unique. <br/> The node to be deleted is in the list and is not a tail node