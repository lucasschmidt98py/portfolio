<script type="text/javascript" async
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

<script type="text/javascript" async
    src="mathjax_config.js">
</script>

# Nuclear Engineer

I am a motivated student of Applied Mathematics at Wrocław University of Science and Technology mostly interesd in applications of probability theory and stochastic calculus in particle transport equations. You can find my C.V [here](English_CV.pdf)!

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

The Generator Project is a Monte Carlo set of codes that generates neutron data based on branching algorithms. The project makes great use of the [CERN's ROOT framework](https://root.cern.ch/) , both for simulation and processing a high amount of data with high performance in C/C++. Since the project was created in the context of the Branching Processes investigation, the project also has a set of Jupyter-Notebooks in Python/Julia for analysis and data visualization. 

The project today is able to simulate a stochastic process described by the Kolmogorov equations as explained by me [here](https://lucasschmidt98py.github.io/SIAC_2022/Capitulo/intro.html).

$$ \frac{\partial g(z,t)}{\partial t} = -Qg(z,t) + Qq[g(z,t)] $$

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

### [The neutron one-point branching process simulation](https://doi.org/10.1016/j.nucengdes.2024.1129376)

### [The one-point branching process simulation (Undergraduation final work)](http://www.repositorio.poli.ufrj.br/monografias/projpoli10042277.pdf)


- Authors: Roberty, Nilson C., and Lucas S.F. de Araujo
- Description: Describing the neutron population inside a nuclear reactor is a difficult task. The
most common way to do so is to solve the Boltzmann transport equation. Under
many simplifications, kinetics equations can be derived in order to have only a temporal dynamics of the system. Such approach is made under many simplifications
and in many cases can lead to difficult analytical and numerical solutions, especially
in the cases where many groups of precursors and energies are considered. The current work intends to describe the neutron population for a prompt/delayed system
of particles in an infinite medium in a one-point Branching Process approach. The
model dynamics is described in terms of the backward and forward-type Kolmogorov
equations. Population expectation can be computed in terms of derivatives of the
generation function and this way, criticality conditions can be presented. Also, it
will be shown that criticality arguments can also be presented in probabilistic ways
and that the so called extinction probability has an important role in the system
stability. Also, it is presented a Monte-Carlo system’s simulations by making use
of the Generator Project, a C++ set of codes which makes great use of CERN’s
ROOT library.

![Critical Simulation](/fig/critpop.png)

### [Sir model parameters estimation with covid-19 data](https://www.researchgate.net/profile/Nilson-Roberty/publication/351308624_SIR_Model_Parameters_Estimation_with_COVID-19_Data/links/6091396192851c490fb6bb5f/SIR-Model-Parameters-Estimation-with-COVID-19-Data.pdf)

- Authors: Roberty, Nilson C., and Lucas S.F. de Araujo
- Description: Based on the SIR model that divides the population into susceptible, infected and removed
individuals, data about the evolution of the pandemic compiled by the Johns Hopkins University
Center for Systems Science and Engineering (JHUCSSE) are integrated into the numerical system
solution. The system parameters Rate of Contact $\beta$, Basic Reproduction Number R0 and Removal Rate $\gamma$, also named Rate of Decay, are determined according to a ridge regression approach
and a mobile statistical scheme with different averages. Data is automatically downloaded from [here](https://raw.githubusercontent.com/CSSEGISandData/COVID-19). The main Python libraries
used are Numpy, Pandas, Skit-Learn, Requests and Urllib.

$$ \frac{dS}{dt} = -\beta(t) \frac{S(t)}{N}I(t) $$

$$ \frac{dI}{dt} = \beta(t) \frac{S(t)}{N}I(t) - \gamma(t)I(t) $$

$$ \frac{dR}{dt} = \gamma(t) I(t) $$

![](/fig/SIR.png)

### [Doppler Broadening of Neutron Cross-Sections Using Kaniadakis Entropy](https://www.mdpi.com/1099-4300/24/10/1437)

- Authros: de Abreu, W. V., Maciel, J. M., Martinez, A. S., Gonçalves, A. D. C., & Lucas S.F. de Araujo.

## Languages

 - Portuguese(_Native_)
 - French(_B1_)
 - English(_C1 - 7.0 IELTS_)
