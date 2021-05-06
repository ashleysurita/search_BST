# search_BST

### Problem:
Javascript
```
class TreeNode {
    constructor(value = 0, leftChild = null, rightChild = null) {
        this.value = value
        this.left = leftChild
        this.right = rightChild
    }
}

function searchBST(root, target) {
    // Write your code here.
    return false
}

// Test Cases
var tree = new TreeNode(8, new TreeNode(3, new TreeNode(1), new TreeNode(6)), new TreeNode(10, null, new TreeNode(14, new TreeNode(13))))
console.log(searchBST(null, 1)) // false
console.log(searchBST(tree, 1)) // true
console.log(searchBST(tree, 14)) // true
console.log(searchBST(tree, 2)) // false
console.log(searchBST(tree, 13)) // true
console.log(searchBST(new TreeNode(), 0)) // true
```

Python
```
class TreeNode:
    def __init__(self, value = 0, left = None, right = None):
        self.value = value
        self.left = left
        self.right = right

def searchBST(root: TreeNode, target: int) -> bool:
    # Write your code here.
    pass

# Test Cases
tree = TreeNode(8, TreeNode(3, TreeNode(1), TreeNode(6)), TreeNode(10, None, TreeNode(14, TreeNode(13))))
print(searchBST(None, 1)) # False
print(searchBST(tree, 1)) # True
print(searchBST(tree, 14)) # True
print(searchBST(tree, 2)) # False
print(searchBST(tree, 13)) # True
print(searchBST(TreeNode(), 0)) # True
```
