# patter-question-using-while-loop
#include<iostream>
using namespace std;

int main(){

    int n;
    cin>>n;
    int i,j,k,l;
    i=1;
    while(i<=n){
        j=1;
while(j<=n-i){
    cout<<" ";
    j++;
}
        k=1;
    while(k<=i){
cout<<"*";
    k++;}
    l=1;
        while(l<=i-1){
cout<<"*";
        l++;}
        cout<<endl;
        i++;
    }
}


