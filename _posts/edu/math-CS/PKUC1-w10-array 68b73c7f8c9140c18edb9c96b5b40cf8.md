# PKUC1-w10-array

Date: December 28, 2023

[array function](https://www.coursera.org/learn/jisuanji-biancheng/lecture/a53He/shu-zu-de-zuo-yong-zhi-er) 

```cpp
#include<iostream>
#include<cmath>
using namespace std;

/* 
looking for prime within 100.
Sieve of Eratosthenes algorithm
*/

int main()
{
    int sum=0, a[100]={0};
    for(int i=2;i<sqrt(100.0);i++) // outer loop for i[2,9]
    {
        sum=i;
        while(sum<100)// inner loop for sum[2,99]
        {
            sum=sum+i;
            if(sum<100)
            a[sum]=1; // why = ?
        }
    }
    for(int i=2;i<100;i++)
    {
        if(a[i]==0)cout<<i<<" "; // why == ?
        
    }

    cout<<""<<endl;

	return 0;
}
```

when `a[i] = {9, 15}` , how could we calculate and remove it from the array a[n]?

the details in the table as below

| **a[i]** | **a[sum]** | **a[sum + i]** |
| --- | --- | --- |
| 2 | 2 | {4, 6, 8, …… 98} |
| 3 | 3 | {6, 9, 12, 15…… 99} |
| …… | …… | …… |
| 7 | 7 | {14, 21, 28, …… 98} |
| 8 | 8 | {16, 24, 32, …… 96} |