#include <bits/stdc++.h> 
/*
    ----------------- Binary Tree node class for reference -----------------

    template <typename T>
    class BinaryTreeNode {
        public : 
            T data;
            BinaryTreeNode<T> *left;
            BinaryTreeNode<T> *right;
            BinaryTreeNode<T> *next;

            BinaryTreeNode(T data) {
                this -> data = data;
                left = NULL;
                right = NULL;
                next = NULL;
            }
    };
*/

void connectNodes(BinaryTreeNode< int > *root) {
    // Write your code here.+
    vector<vector<BinaryTreeNode<int>*>> v;
    queue<BinaryTreeNode<int>*> q;
    q.push(root);
    BinaryTreeNode<int> * temp = root;

    while(!q.empty()){
        int size = q.size();
        vector<BinaryTreeNode<int>*> r;
        BinaryTreeNode<int>* temp = NULL;
        for(int i=0; i<size; i++){
            BinaryTreeNode<int>* n = q.front();
            q.pop();
            n->next = temp;
            temp = n;
            r.push_back(n);
            if(n->right){
                q.push(n->right);
            }
            if(n->left){
                q.push(n->left);
            }
            

        }
        //v.push_back(r);
    }

    

    // for(int i=0;i<v.size(); i++){
    
    //     for(int j=0; j<v[i].size(); j++){
            
    //     }
    // }
}
