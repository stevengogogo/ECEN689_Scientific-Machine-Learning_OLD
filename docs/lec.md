# Lecture Note


# Lecture 1: Introduction to Scientific Machine Learning

> Slides: [PDF](https://drive.google.com/file/d/1sxHYq47--ovp4GnFYLEHYGq5iLhAI_at/view)



---

# Lecture 2: Introduction to Machine Learning

> Slides:  [PDF](https://ntucc365-my.sharepoint.com/:b:/g/personal/r07945001_ntu_edu_tw/EY2uJWOrj4lIoSUFT7Xr1T4BOZEpeHjcdyMCDPYDV1rawQ?e=44BITh)

## Representation Theorem

?> If $E[|Y|] < \inf$, there is a function $f: R^d \rightarrow R$ and a random variable $\epsilon$ such that 
     $$Y = f(X) + \epsilon$$
where $E[\epsilon|X] = 0$


- if $\epsilon$ is independent of $(\textbf{X},Y)$: *homoskedastic*
  - otherwise: heteroskedastic.



## Regression Error

### Quadratic loss

$$L(y, f(x)) = (y-f(x))^{2}$$