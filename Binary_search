#include<bits/stdc++.h>
#define ll long long
#define mx max_element
#define mn min_element
#define all(x) (x).begin(), (x).end()
#define rall(x) (x).rbegin(), (x).rend()
#define lb lower_bound
#define ub upper_bound
 
using namespace std;

int main()
{
    int n,x;
    cin>>n;
    cin>>x;//Searchable variable
    vector<int>v(n);
    sort(v.begin(),v.end());
    for(int i=0;i<n;i++){
        cin>>v[i];
    }
    int low=0,high=n-1;//Range is defined
    while(low<=high){
        int mid=(low+high)/2;
        if(v[mid]==x){
            cout<<"found\n";
            return 0;
        }
        else if(v[mid]>x)low=mid;
        else high=mid;
    }
    return 0;
}
//As well as String. just we have to creat the string or array is sorted
