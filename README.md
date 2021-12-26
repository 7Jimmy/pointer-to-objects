#include<iostream>
using namespace std;
class test{
	private:
		char name;
		public:
			void in(){
				cout<<"Enter the integer"<<endl;
				cin>>n;
			}
				void out(){
				cout<<"the integer"<<n<<endl;
				
			}
};
int main(){
test *ptr;
ptr=new test;

	ptr->in();
	


	ptr->out();

	return 0;
}
