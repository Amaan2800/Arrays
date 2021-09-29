#include<iostream>
using namespace std;
int main(){
    int n,i,even=0,odd=0;
    cin>>n;
    int a[n];
    for(i=0;i<n;i++){
        cin>>a[i];
    }
    for(i=0;i<n;i++){
        if(a[i]%2==0)
        {
            even++;
        }
    }
    cout<<"even count is "<<even<<endl;
    cout<<"odd count is "<<n-even;
    return 0;
}
