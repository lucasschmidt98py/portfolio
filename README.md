<script type="text/javascript" async
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

<script type="text/javascript" async
    src="mathjax_config.js">
</script>

# Nuclear Engineer

I am a motivated student of Applied Mathematics at Wrocław University of Science and Technology mostly interesd in applications of probability theory and stochastic calculus in particle transport equations.

## Education

- M.S Applied Mathematics | Wrocław University of Science and Technology (Poland) | NAWA scholarship holder

- B.S Nuclear Engineering | Federal University of Rio de Janeiro (Brazil)

## Work Experience

### Software Developer at Brazilian National Agency for Petroleum, Natural Gas and Biofuels (_2022_ - _2023_) (_Python,_ _C/C++_)

Description: Solution of Conservation Equations using Riemann Solvers in C++ using parallel paradigm

$$ 
\frac{\partial U}{\partial t} + \frac{\partial F(U)}{\partial x} = 0 
$$

where 

$$ 
U = \begin{bmatrix} u_1 \\ u_2 \\ \vdots \\ u_m\end{bmatrix}, \quad F = \begin{bmatrix} f_1 \\ f_2 \\ \vdots \\ f_m\end{bmatrix} 
$$

![Shock Wave](/fig/shock_wave.svg)


### Quantitative Research Intern at BOCOM BBM bank (_2021_ - _2022_)

- Modeling of observable variables at Brazilian energy market

- Mathematical Modeling of binary variables

- Creation of scheduled routines in Python and R for data updating and models feeding 


## Projects

### The Generator Project (_C/C++,Python,Julia_)

The Generator Project is a set of Neutron Monte Carlo Branching algorithm for simulation of 

The project today is able to simulate a stochastic process described by the Kolmogorov equation

$$ \frac{\partial g(s,t)}{\partial t} = Q[q(s)-s] \frac{\partial g(s,t)}{\partial s } $$

$$ g(s,0) = s $$

![BranchingTree](/fig/branching_tree.jpeg)

### Algorithm implementations of Feller's Book (*Julia*)

The project is an implementation in Julia of the many stochastic processes presented in the book of [FELLER, William. An introduction to probability theory and its applications, Volume 1. John Wiley & Sons, 1991.]()

$$U_z(s) = psU_{z+1}(s) + qsU_{z-1}(s) \quad 0 < z < a$$

$$ U_0(s) = 1 \quad U_a(s) = 0 $$

![RuinProblem](/fig/RuinProblem.png)

## Awards

 - Finalist at World Nuclear University Olympiad in Vienna
 - Section Best Work for SIR modeling for COVID-19 outbreak
 - Honors at SIAC for the work Simplified Models for Casimir Forces

## Publications

### [Sir model parameters estimation with covid-19 data](https://www.researchgate.net/profile/Nilson-Roberty/publication/351308624_SIR_Model_Parameters_Estimation_with_COVID-19_Data/links/6091396192851c490fb6bb5f/SIR-Model-Parameters-Estimation-with-COVID-19-Data.pdf)

- Authors: Roberty, Nilson C., and Lucas SF de Araujo
- Description: The work  introduces the use of the SIR model, a simple mathematical framework with three compartments (Susceptible, Infected, Removed), to describe the phenomenology associated with COVID-19 infection. The model is based on parameters β and γ, representing fundamental mechanisms of reaction and decay in the context of the disease.

$$ \frac{dS}{dt} = -\beta(t) \frac{S(t)}{N}I(t) $$

$$ \frac{dI}{dt} = \beta(t) \frac{S(t)}{N}I(t) - \gamma(t)I(t) $$

$$ \frac{dR}{dt} = \gamma(t) I(t) $$

![](/fig/SIR.png)

### [Doppler Broadening of Neutron Cross-Sections Using Kaniadakis Entropy](https://www.mdpi.com/1099-4300/24/10/1437)

- Authros: de Abreu, W. V., Maciel, J. M., Martinez, A. S., Gonçalves, A. D. C., & Schmidt, L.

## Languages

 - Portuguese(_Native_)
 - French(_B1_)
 - English(_C1 - 7.0 IELTS_)
