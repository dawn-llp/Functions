# Functions

## [1.MultiChi](https://github.com/ShayleeLi/Functions/blob/master/MultiChi.R)
<p>This function script is designed to conduct chi-square test between multiple categorical variables.</p>
#### 1.1 chiMatrix(dt)
<p>dt refers to data that used to conduct chi-Square tests. dt needs to be data frame or matrix.
<p>Return to p-value matrix of all variables. <p>
><p>source(".../MultiChi.R")
><p>train=data.frame(a)
><p>chiMatrix(train)

#
#### 1.2 pickChi(dt,p=0.01)
<p>dt refers to data that used to conduct chi-Square tests. dt needs to be data frame or matrix.
<p>p refters to p-value threshold to print out variable pair message.
<p>Return to p-value matrix of all variables. <p>
><p>source(".../MultiChi.R")
><p>train=data.frame(a)
><p>chiPick(train,p=1e-10)

