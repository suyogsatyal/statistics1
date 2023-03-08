# Chapter 2: Measures of Central Tendency

## 2.1) Central Tendency
## Mean
### A. For individual series
$$\bar{x} = \frac{\sum X}{n}$$
 ### B. For Discrete series
$$\bar{x} = \frac{\sum fX}{n}$$
 ### C. For Continuous series
$$\bar{x} = \frac{\sum fm}{n}$$

## Median
### A. For individual series
$$M_d =(\frac{ N+1}{2} )item$$

 ### B. For Discrete series

$$M_d = L + \left(\frac{\frac{N+1}{2}-F}{cf}\right)h$$


 ### C. For Continuous series
$$M_d = L + \left(\frac{\frac{N}{2}-F}{cf}\right)h$$



## Mode
### A. For Individual & Discrete data
Data with the highest frequency.

 ### B. For Continuous series
$$\text{Mode} = L + \frac{(f_1 - f_{0})}{(f_1 - f_{0})+(f_1 - f_{2})} \times C$$

where $\text{Mode}$ is the mode value, $L$ is the lower boundary of the modal class, $f_1$ is the frequency of the modal class, $f_{0}$ is the frequency of the class before the modal class, $f_2$ is the frequency of the class after the modal class, and $C$ is the class interval.

## 2.2) Measures of Dispersion

## Range
$$Range = X_l - X_s$$
$$Coeff.\:of\:Range = \frac{X_l - X_s}{X_l + X_s}$$

## Quartile Deviation
$$Quartile\:Range = Q_3 - Q_1$$
$$Quartile\:Deviation = \frac{Q_3 - Q_1}{2}$$
$$Coeff.\:of\:-Quartile\:Deviation = \frac{Q_3 - Q_1}{Q_3 + Q_1}$$

## Mean Deviation
### A. For Individual Series
$$\text{M.D. from Median} = \frac{1}{n}\sum_{i=1}^{n} |x_i - M_d|$$
$$\text{M.D. from Mean} = \frac{1}{n}\sum_{i=1}^{n} |x_i - \bar{x}|$$
$$\text{M.D. from Mode} = \frac{1}{n}\sum_{i=1}^{n} |x_i - M_o|$$

### B. For Discrete Series
$$\text{M.D. from Mean} = \frac{1}{n}\sum_{i=1}^{N} f_i |X_i - \bar{x}|$$
$$\text{Mean Deviation from Median} = \frac{1}{n}\sum_{i=1}^{N} f_i |M - L_i|$$
$$\text{Mean Deviation from Mode} = \frac{1}{n}\sum_{i=1}^{N} f_i \left|C + \frac{f_m-f_1}{2f_m-f_1-f_2} \times h - M\right|$$

## Standard Deviation[$\sigma$]
### A. For individual series
$$\sigma = \sqrt{\frac{1}{n}\sum(x - \bar{x})^2}$$
$$\sigma = \sqrt{\frac{\sum x^2}{n} - (\frac{\sum x}{n})^2}$$
$$\sigma = \sqrt{\frac{\sum x^2 }{n} - (\bar{X})}$$

### B. For Discrete & Continuous Series
$$\sigma = \sqrt{\frac{1}{n}\sum f(x - \bar{X})^2}$$
$$\sigma = \sqrt{\frac{\sum fx^2}{n} - (\frac{\sum fx}{n})^2}$$

### C. Combined Standard Deviation
$$\sigma_{12} = \sqrt{\frac{\sum(n_i-1)\sigma_i^2 + \sum_{i=1}^{n}n_i(\bar{x_i} - \bar{x})^2}{N-1}}$$

## Coeffifient of Variation [C.V]

$$\text{C.V} =\frac{\sigma}{\bar{X}}\times100\%$$

## Skewness

### A. Karl Pearson's Coefficient of Skewness [$S_k(P)$]
$$S_k(P)_1 = \frac{(\bar{x}-M_0)}{\sigma}$$
$$S_k(P)_2 = \frac{3(\bar{x}-M_d)}{\sigma}$$
If $S_k(P) = 0$, it means the data is not skewed at all.<br/>
If $S_k(P) < 0$, it means the data is negatively skewed. <br/>
If $S_k(P) > 0$, it means the data is positively skewed. 

### B. Bowley's Coefficient of Skewness
$$S_k(B) = \frac{Q_1 + Q_3 - 2M_d}{Q_3 - Q_1}$$


## 2.3) Kurtosis

Percentile Coefficient of Kurtosis:
$$k = \frac{Q_3-Q_1}{2(P_{90}-P_{10})}$$

If $k = 0.263$ then Mesokurtic.<br/>
If $k > 0.263$ then Leptokurtic.<br/>
If $k < 0.263$ then Platokurtic.<br/>

## 2.4) Moments
## Central Moments[$\mu_r$]
### A. For Individual Series
$$\text{General Formula: } \mu_r = \frac{\sum(x-\bar x)^r}{n}$$
$$\mu_1 = 0$$
$$\mu_2 = \frac{\sum(x-\bar x)^2}{n} = \sigma^2 = Variance$$
$$\mu_3 = \frac{\sum(x-\bar x)^3}{n}$$
$$\mu_4 = \frac{\sum(x-\bar x)^4}{n}$$

### B. For Discrete Series
$$\text{General Formula: } \mu_r = \frac{\sum f(x-\bar x)^r}{N}$$
$$\mu_1 = 0$$
$$\mu_2 = \frac{\sum f(x-\bar x)^2}{N} = \sigma^2 = Variance$$
$$\mu_3 = \frac{\sum f(x-\bar x)^3}{N}$$
$$\mu_4 = \frac{\sum f(x-\bar x)^4}{N}$$

## Relation between Raw & Central Moments

$$\mu_1 = 0$$
$$\mu_2 = \bar\mu_2 - (\bar\mu_1)^2$$
$$\mu_3 = \bar\mu_3 - 3\bar\mu_2\bar\mu_1 +2(\bar\mu_1)^3$$
$$\mu_4 = \bar\mu_4 - 4\bar\mu_3\bar\mu_1 + 6\bar\mu_2(\bar\mu_1)^2 - 3(\bar\mu_1)^4$$
