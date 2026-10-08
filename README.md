hello
class Solution {
public:
    int strStr(string haystack, string needle) {
        if (needle.empty()) {
            return 0;in
()) {
needle) {
        if (needle.empty()) {class Solution {
public:
    void rotate(vector<vector<int>>& matrix) {
        int n = matrix.size();
      
        // Step 1: Flip the matrix horizontally (reverse rows)
        // Swap the first row with the last row, second with second-to-last, etc.
        for (int i = 0; i < n / 2; ++i) {
            for (int j = 0; j < n; ++j) {
                swap(matrix[i][j], matrix[n - 1 - i][j]);
            }
        }
      
        // Step 2: Transpose the matrix (swap along the diagonal)
        // Swap element at position (i, j) with element at position (j, i)
        for (int i = 0; i < n; ++i) {
            for (int j = 0; j < i; ++j) {
                swap(matrix[i][j], matrix[j][i]);
            }
        }
    }
};

 *     TreeNode() : val(0), left(nullptr), right(nullptr) {}
 *     TreeNode(int x) : val(x), left(nullptr), right(nullptr) {}
 *     TreeNode(int x, TreeNode *left, TreeNode *right) : val(x), left(left), right(right) {}
 * };
 *//**
 * Definition for a binary tree node.
 * struct TreeNode {
 *     int val;
 *     TreeNode *left;
 *     TreeNode *right;
 *     TreeNode() : val(0), left(nullptr), right(nullptr) {}
 *     TreeNode(int x) : val(x), left(nullptr), right(nullptr) {}
 *     TreeNode(int x, TreeNode *left, TreeNode *right) : val(x), left(left), right(right) {}
 * };
 */
class Solution {
public:
    bool isValidBST(TreeNode* root) {
        // Keep track of the previous node in in-order traversal
        TreeNode* previousNode = nullptr;
      
        // Lambda function for in-order traversal validation
        // In a valid BST, in-order traversal yields values in strictly ascending order
        function<bool(TreeNode*)> inOrderValidate = [&](TreeNode* currentNode) -> bool {
            // Base case: empty node is valid
            if (!currentNode) {
                return true;
            }
          
            // Recursively validate left subtree
            if (!inOrderValidate(currentNode->left)) {
                return false;
            }
          
            // Check BST property: current node value must be greater than previous node value
            if (previousNode && previousNode->val >= currentNode->val) {
                return false;
            }
          
            // Update previous node for next comparison
            previousNode = currentNode;
          
            // Recursively validate right subtree
            return inOrderValidate(currentNode->right);
        };
      
        // Start validation from root
        return inOrderValidate(root);
    }
};

        // Lambda function for in-order traversal validation
        // In a valid BST, in-order traversal yields values in strictly ascending order
        function<bool(TreeNode*)> inOrderValidate = [&](TreeNode* currentNode) -> bool {
            // Base case: empty node is valid
            if (!currentNode) {
                return true;
            }
          
            // Recursively validate left subtree
            if (!inOrderValidate(currentNode->left)) {
                return false;
            }
          
            // Check BST property: current node value must be greater than previous node value
            if (previousNode && previousNode->val >= currentNode->val) {
                return false;
            }
          
            // Update previous node for next comparison
            previousNode = currentNode;
          
            // Recursively validate right subtree
            return inOrderValidate(currentNode->right);
        };
      /**
 * Definition for a binary tree node.
 * struct TreeNode {
 *     int val;
 *     TreeNode *left;
 *     TreeNode *right;
 *     TreeNode() : val(0), left(nullptr), right(nullptr) {}
 *     TreeNode(int x) : val(x), left(nullptr), right(nullptr) {}
 *     TreeNode(int x, TreeNode *left, TreeNode *right) : val(x), left(left), right(right) {}
 * };
 */
class Solution {
public:
    bool isValidBST(TreeNode* root) {
        // Keep track of the previous node in in-order traversal
        TreeNode* previousNode = nullptr;
      
        // Lambda function for in-order traversal validation
        // In a valid BST, in-order traversal yields values in strictly ascending order
        function<bool(TreeNode*)> inOrderValidate = [&](TreeNode* currentNode) -> bool {
            // Base case: empty node is valid
            if (!currentNode) {
                return true;
            }
          
            // Recursively validate left subtree
            if (!inOrderValidate(currentNode->left)) {
                return false;
            }
          
            // Check BST property: current node value must be greater than previous node value
            if (previousNode && previousNode->val >= currentNode->val) {
                return false;
            }
          
            // Update previous node for next comparison
            previousNode = currentNode;
          
            // Recursively validate right subtree
            return inOrderValidate(curTFTYrentNode->right);
        };
      GJUUG
        // Start validation from root
        return inOrderValidate(root);
    }
};

        // Start validation from root
        return inOrderValidate(root);
    }
};
