#include<bits/stdc++.h>
using namespace std;
void substr(int ind,vector<int>vec1);
vector<int>vec;
int n;
int main(){
  cout<<"sizeofvector"<<endl;
  cin>>n;
  for(int i=0;i<n;i++){
   int x;
   cin>>x;
   vec.push_back(x);
  }
  vector<int>vec1;
  substr(0,vec1);
}
void substr(int ind,vector<int>vec1){
  if(ind>=n){
    for(int i=0;i<vec1.size();i++){
      cout<<vec1[i];
    }
    cout<<endl;
    return;
  }
  //there will be 2 options for every i whether to take or not take
  //this is for taking condition
  vec1.push_back(vec[ind]);
  substr(ind+1,vec1);
  vec1.pop_back();
  //this is for not taking condition
  substr(ind+1,vec1);
}
