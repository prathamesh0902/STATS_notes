# STATS Notes

[Probability Distribution](https://www.geeksforgeeks.org/maths/probability-distribution/)

| Distribution       | Type       | When It Occurs                                   | Real-World Example               | Probability Equation                                                                          | Plot Shape                         |
| ------------------ | ---------- | ------------------------------------------------ | -------------------------------- | --------------------------------------------------------------------------------------------- | ---------------------------------- |
| **Uniform**        | Continuous | All outcomes equally likely in a range           | Random number between 0 and 1    | ( f(x)=\frac{1}{b-a},\ a\le x\le b )                                                          | Flat, constant                     |
| **Binomial**       | Discrete   | Fixed trials, two outcomes, constant probability | Number of heads in 10 tosses     | ( P(X=k)=\binom{n}{k}p^k(1-p)^{n-k} )                                                         | Discrete bars, symmetric or skewed |
| **Poisson**        | Discrete   | Counts of events per time/space                  | Calls per hour at a call center  | ( P(X=k)=\frac{e^{-\lambda}\lambda^k}{k!} )                                                   | Right-skewed, discrete             |
| **Exponential**    | Continuous | Time until first event                           | Time until next customer arrives | ( f(x)=\lambda e^{-\lambda x},\ x\ge0 )                                                       | Rapidly decreasing                 |
| **Geometric**      | Discrete   | Trials until first success                       | Coin tosses until first head     | ( P(X=k)=(1-p)^{k-1}p )                                                                       | Discrete, right-skewed             |
| **Normal**         | Continuous | Natural variation around mean                    | Heights, test scores             | ( f(x)=\frac{1}{\sqrt{2\pi\sigma^2}}e^{-\frac{(x-\mu)^2}{2\sigma^2}} )                        | Symmetric bell curve               |
| **t-Distribution** | Continuous | Small sample, unknown variance                   | Small-sample CI testing          | ( f(x)=\frac{\Gamma((\nu+1)/2)}{\sqrt{\nu\pi}\Gamma(\nu/2)}(1+\frac{x^2}{\nu})^{-(\nu+1)/2} ) | Bell-shaped, heavy tails           |
| **Chi-Square**     | Continuous | Variance testing, goodness-of-fit                | Feature independence tests       | ( f(x)=\frac{1}{2^{k/2}\Gamma(k/2)}x^{k/2-1}e^{-x/2} )                                        | Right-skewed                       |
