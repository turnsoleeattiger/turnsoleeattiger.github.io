## this is my new page!
It's happy to see you!
Please feel free to communicate with me!

## how to find me?
* You can find my github page **[here](https://turnsoleeattiger.github.io/Jelly.github.io/)** to view my latast post!
* you can also find my instergram **[here](https://www.instagram.com/turnsoleeattiger/)** to get more information.

## here are some of my information:
- [x] I love eating!
- [x] I am pretty!

## you can see my post *here*:sparkles:
![Image](http://fishmay.myweb.hinet.net/photoall/Images/bubbles-2.jpg)

## here are some of my codes:
```c++script
#include<iostream>
#include<string>
#include<vector>
using namespace std;

void swap(int &a,int &b)
{int t;
t=a;a=b;b=t;}

int main()
{
	int i,j,n;
	cout<<"please input n:"<<endl;
	cin>>n;
	vector<int>p(n*n); 
	cout<<"please input "<<n*n<<" datas"<<endl;
		for(i=0;i<n;i++)
			for(j=0;j<n;j++)
				cin>>p[i*n+j];
	cout<<"the original datas"<<endl;
     for(i=0;i<n;i++)
	 {cout<<endl;
		 for(j=0;j<n;j++)
	 cout<<p[i*n+j]<<" ";}
	 cout<<endl;
	 for(i=0;i<n;i++)
        for(j=0;j<n;j++)
          swap(p[i*n+j],p[j*n+i]);
cout<<"change to:"<<endl;
 for(i=0;i<n;i++)
	{ cout<<endl;
	 for(j=0;j<n;j++)
	cout<<p[j*n+i]<<" ";}
 cout<<endl;
return 0;
}

```




 

 
 
