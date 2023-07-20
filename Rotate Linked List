Node *rotate(Node *head, int k) {
    if(head==NULL || head->next==NULL || k==0){
         return head;
    }

    Node* curr= head;
    int len= 1;

    while(curr->next!=NULL){
         curr= curr->next;
         len++;
    }
    curr->next= head;
    k= k%len;
    k= len-k;

    while(k--){
         curr= curr->next;

    }
    head= curr->next;
    curr->next= NULL;
    return head;
}
