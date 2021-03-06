<h1>Greetings from LightOJ</h1>
<h3>Summary</h3>
<p>Sum of two integer.</p>
<h3>Solution</h3>
<p>Input two integer and print sum of two integer.
But still some people can't get Accepted verdict because of not following the proper output format.

* Make sure you have printed newline on each line.
* Make sure you have same output as the sample output on the problem descriptin, take a look at case number.
* Make sure you have added right amount of spaces on the output.
</p>
<h6>C</h6>

```cpp
#include<stdio.h>
int main()
{
    int n,i,a,b;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        scanf("%d %d",&a,&b);
        printf("Case %d: %d\n",i,a+b);
    }
    return 0;
}
```
[Faysal Rahman](https://www.linkedin.com/in/ftowaha/)
