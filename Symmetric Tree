int ans=true;
void fun(BinaryTreeNode<int>* root1,BinaryTreeNode<int>* root2)
{
    if(root1==NULL and root2==NULL)
    return;
    if(root1==NULL or root2==NULL or root1->data!=root2->data)
    {
        ans=false;
        return;
    }
    fun(root1->left,root2->right);
}


bool isSymmetric(BinaryTreeNode<int>* root)
{
    // Write your code here.    
    fun(root,root);
    return ans;
}
