#include <iostream>

using namespace std;

  int cnt=1;
   bool prime(int x){
      if(x==1)
        return true;
      else{
        if((cnt%x)==0)
        return false ;
        else
          return prime(x-1);
      }
   }
    int rec(int n){

        if(n==1){
            return 0;
        }
        else{
            cnt++;
            if(prime(cnt-1)){
                cout<<cnt<<" ";
                return rec(n-1);
            }
            else
            return rec(n-1);
        }
    }
int main()
{
    int n;
    cin>>n;
    rec(n);
    return 0;
}
