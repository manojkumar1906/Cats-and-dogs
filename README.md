#include <iostream>
#include <bits/stdc++.h>
#define ll long long int
using namespace std;

int main() {
	// your code goes here
	
	int t;
	cin >> t;
	while(t--)
	{
	    ll c, d, l;
	    cin >> c >> d >> l;
	    ll cg = (l-4*d)/4;
	    ll dg = (c - cg);
	    
	    if(l%4 || l<4*d || l>4*(c+d) || dg>2*d)
	    cout << "no\n";
	    else cout << "yes\n";
	}
	
	return 0;
}
