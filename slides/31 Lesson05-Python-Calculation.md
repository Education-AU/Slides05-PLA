---
title: Calculating Test in Python
template: two-column
showFooter : false
---
Here we calculate the F-test statistic in Python and evaluate the hypotheses $H_R$ and $H_F$.

With result:
```text
71.51077918303574
2.408189860091998
H_R rejected go with full
```

The full code is located in download `BodyFat.ipynb` 
<!-- column -->

``` python
n=len(df.Density)
pf=5;pr=1;alpha=0.05;y=df.Density
#Design of Restricted
D_R=np.ones(n).reshape(-1,1)
#Design of Full
D_F=np.column_stack((np.ones(n),df.Height,df.Weight,df.Age,df.Height**2))
#Test statistic
RSS_F=np.linalg.norm(D_F@np.linalg.inv(D_F.T@D_F)@D_F.T@y-y)**2
RSS_R=np.linalg.norm(D_R@np.linalg.inv(D_R.T@D_R)@D_R.T@y-y)**2

T=(RSS_R-RSS_F)/(pf-pr)/(RSS_F/(len(y)-pf))
print(T)

# Critical value
F_CRIT=f.ppf(1-alpha,pf-pr,n-pf)
print(F_CRIT)
if T>=F_CRIT:
    print("H_R rejected go with full")
else:
    print("H_R is just as good")
``` 
