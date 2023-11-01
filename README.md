# Stack
class Stack{
public:
const static int SIZE;
Stack();
bool isFull();
bool isEmpty();
bool push(const int n);
bool pop(int &l);
private:
int *arr;
int top;
};
Stack :: Stack(){
int arr= new int[SIZE];
top=-1;
}
bool Stack :: isFull(){
return top==SIZE;
}
bool Stack :: isEmpty(){
return top==-1;
}
bool Stack :: push(const int n){
if(!isFull()){
top++;
arr[top]=n;
else 
return 0
}
bool Stack :: pop( int &l)
{
if(!isEmpty()){
l=arr[top];
top--;
}
