[rapport_Numerics of GANs.pdf](https://github.com/OrsonTyphanel93/Hacker-/files/8283059/rapport_Numerics.of.GANs.pdf)
# project (Reviewer)


# Project The Numerics of GANs

MIla , University of Montreal 


## FAQ

#### Explore new tools to optimize GANs 



#### At the empirical and theoretical level, based on tools for processing symmetric and asymmetric matrices 




## Authors

- [@OrsonTyphanelMengara](https://sway.office.com/DXfaOXg0DKNLKyJx?ref=Link)


## limit of the article and research furtur

[Documentation](https://linktodocumentation)

Linearization is a useful tool for understanding the learning dynamics of GANs. Simple examples of GAN learning have been designed and analyzed analytically.For the local convergence of general GANs, these theoretical results are useful for designing new regularizers that also work very well in practice.Despite these successes, their theory has a number of limitations that I hope will be addressed in future research.
First, their theory is only local. This means that, although we can make statements about the
convergence of GAN learning in some local neighborhood of the equilibrium point, their
theorems make no statements about global convergence or the size of the convergence region.


 Of course, one can argue that local convergence is a minimum requirement.
and thus understanding local convergence is a necessary first step before deriving a global theory.
 However, statements about the size of the convergence region are necessary to get a complete picture and I believe that a better understanding of convergence is needed.I believe that a better theory in this area will provide new insights into the formation of GANs.Promising research shows that a variant of consensus optimization is globally convergent for a simple GAN, called the linear-quadratic GAN. Second, their theory requires the realizability assumption, which is valid for simple toy examples for the formation of GANs, but not necessarily for more complex systems. Again, it is important to understand that understanding convergence under the assumption of realizability is a minimum requirement. Furthermore, realizability may be at least approximately valid for highly expressive deep neural networks.However, additional work is needed to understand
what happens when the realizability assumption does not hold. 


Finally, for simplicity, they derived their theory for the deterministic system without noise. they deliberately focused on this case which it leads to a much cleaner theory that emphasizes structural ideas. rather than technical details and (i) the noise can be reduced arbitrarily by increasing the number of users. (ii) noise can be arbitrarily reduced by increasing the batch size. Theoretical framework for analyzing the noisy case The noisy case is given by the theory of stochastic approximation.
Typical theorems of stochastic approximation theory require assumptions similar to their local convergence theory.
 However, deriving the technical details in a reasoned manner is beyond the scope of this work.


 Further analysis of the noisy case could also lead to additional results, for example on local convergence issues.
Properties of stationary distributions of SimGA and AltGA near equilibrium.



## Usage/Examples

```javascript
import Component from 'my-project'

function App() {
  return <Component />
}
```


