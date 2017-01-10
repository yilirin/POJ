#Notes on [CS97 SI](http://web.stanford.edu/class/cs97si/)

##Mathematics
####1. prime number
	bool isprime(int n)
	{
	    int flag = 1;
	    for (int i = 2; i <= sqrt(n); ++i)  
	    {
	        if (n % i == 0)
	        {
	            flag = 0;
	            break;
	        }
	    }
	    return flag;
	}
	
####2. Fast Exponentiation
- recursive algorithms:

```
double pow(double a, int n) {
```
- non-recursive:

```
double pow(double a, int n) {
```

####3. GCD
```
int gcd(int a, int b) {
```

####4. Line-Line intersection
- $ax+by+c=0$
- $dx+ey+f=0$
- $x = (fb-ce)/(ae-bd)$
- $y = (cd-fa)/(ae-bd)$

####5. Circumcircle of a Triangle
- Find the (equations of the) bisectors of AB and BC 
- Compute their intersection

####6. Area of a Triangle
- Use cross product: 2S=|(B−A)×(C−A)| 
- Area of a Simple Polygon: If P is convex, we can **decompose** P into triangles: