TareaEstructuras
================
#include <iostream>

using namespace std;



int main()
{
 int n;

 int c=0;
int i;
int j=0;
int k =1;
int t=1;

 cout<<"ingrese un numero " <<endl;

 cin>>n;





for(int s=1; s<=n;s+=2){
for(int m=n;m>=1;m--){
    cout<<n<<" ";
    c++;

if(c==t){

  cout<<"\n";

   c=0;
   t++;

}

}
}

    return 0;
}
