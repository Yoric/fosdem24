[comment]: # (CODE_THEME = base16/zenburn)

# Qadence

A framework for experimenting with analog/digital quantum computing

David 'Yoric' Teller

![](../img/pasqal.png)

[comment]: # (!!! data-auto-animate)

# Qadence

A framework for experimenting with analog/digital quantum computing

David 'Yoric' Teller

![](../img/pasqal.png)

(not my work)

[comment]: # (!!! data-auto-animate)

# About Pasqal

- We build qubits!

[comment]: # (!!! data-auto-animate)

# About Pasqal

- We build qubits!
    - Quantum computers
    - Quantum algorithms
    - Quantum tools
    - Quantum teaching materials
    - ...

[comment]: # (!!!)

![photo of Pasqal's quantum computer showing lasers and lenses](../img/qpu.jpg)

[comment]: # (!!!)

# Quantum computing?

- Compute with qubits, not bits.
- Still very much open research.

[comment]: # (!!! data-auto-animate)

# Quantum computing?

- Compute with qubits, not bits.
- Still very much open research.
    - Hardware
    - Algorithms
    - Compilers & tools
    

[comment]: # (!!! data-auto-animate)

# Quantum computing?

- Compute with qubits, not bits.
- Still very much open research.
    - Hardware
    - Algorithms
    - Compilers & tools
    - Hype

[comment]: # (!!! data-auto-animate)

# Why quantum?

- Today's processors fight quantum physics.
- Aiming for the next generation(s) of hardware.

[comment]: # (!!! data-auto-animate)

# Why quantum?

- Today's processors fight quantum physics.
    - Embrace it!
- Aiming for the next generation(s) of hardware.

[comment]: # (!!! data-auto-animate)

# Why quantum?

- Today's processors fight quantum physics.
- Aiming for the next generation(s) of hardware.
    - Faster?
    - Much more energy-efficient?

[comment]: # (!!! data-auto-animate)

# Why quantum?

- Today's processors fight quantum physics.
- Aiming for the next generation(s) of hardware.
    - Also, get out of the current hardware dead end.

[comment]: # (!!! data-auto-animate)

# Why quantum?

- Today's processors fight quantum physics.
- Aiming for the next generation(s) of hardware.
- Also, hype.

[comment]: # (!!! data-auto-animate)

# Bits

![a bit (represented as a square signal)](../img/signal.png)

[comment]: # (!!!)

# Qubits

![a qubit (represented as a unitary sphere)](../img/sphere.png)

[comment]: # (!!! data-auto-animate)

# Two flavours

- Digital
- Analog

[comment]: # (!!! data-auto-animate)

# Digital

![example of a digital circuit](../img/digital.svg)

[comment]: # (!!! data-auto-animate)

# Digital

- A program is a _circuit_.
- Programming languages exist.

[comment]: # (!!! data-auto-animate)

# Digital

- A program is a _circuit_.
- Programming languages exist.
    - ... for model hardware.

[comment]: # (!!! data-auto-animate)

# Analog

![the pasqal logo made from individual atoms](../img/register.png)

[comment]: # (!!! data-auto-animate)

# Analog 

- A program is geometry + pulses.
- Maps naturally to hardware constraints.

[comment]: # (!!! data-auto-animate)

# Analog 

- A program is geometry + pulses.
- Maps naturally to hardware constraints.
    - ...and to some classes of problems.

[comment]: # (!!! data-auto-animate)

# Analog 

- A program is geometry + pulses.
- Maps naturally to hardware constraints.
- ... how do you program _that_?

[comment]: # (!!! data-auto-animate)

# Analog

![\hat{H}(\Omega, \delta, \phi; t) = \sum_{\text{atom } i}\left(
    \overbrace{
      \frac{\Omega}{2}\left[\cos(\phi) \hat \sigma^x_i - \sin(\phi) \hat \sigma^y_i \right] 
    - \delta \hat n_i
    }^\text{Programmable laser pulse, global interaction}
    + \underbrace{\sum_{j<i}\frac{C_6}{|\mathbf r_{ij}|^6} \hat n_i \hat n_{j}}_\text{Programmable register, atom-atom interaction}\right)
](../img/hamiltonian.png)

[comment]: # (!!! data-auto-animate)

# Analog 

- A program is geometry + pulses.
- Maps naturally to hardware constraints.
- ... how do you program _that_?
    - no, really?

[comment]: # (!!! data-auto-animate)

# Qadence

[comment]: # (!!!)

# Qadence

A toolkit designed to:

- experiment with Digital + Analog circuits;
- simulate or execute circuits;

[comment]: # (!!! data-auto-animate)

# Qadence

A toolkit designed to:

- experiment with Digital + Analog circuits;
    - learn how to design a hardware-friendly language;
    - without dealing with laser pulses.
- simulate or execute circuits;

[comment]: # (!!! data-auto-animate)

# Qadence

A toolkit designed to:

- experiment with Digital + Analog circuits;
- simulate or execute circuits;
    - _optimize_ circuits wrt constraints.

[comment]: # (!!! data-auto-animate)

# Qadence

A toolkit designed to:

- experiment with Digital + Analog circuits;
- simulate or execute circuits;
- still not my work 😅.

[comment]: # (!!! data-auto-animate)

# Demo time!

- [Digital](http://localhost:8888/notebooks/Qadence%20digital.ipynb)
    - [Solving a problem](http://localhost:8888/notebooks/Qadence%20MaxCut.ipynb)
- [Analog](http://localhost:8888/notebooks/Qadence%20analog.ipynb)
    - [Solving a problem](http://localhost:8888/notebooks/Qadence%20curve%20fitting.ipynb)

[comment]: # (!!!)

# Conclusions

[comment]: # (!!!)

# Summary

- A toolkit for exploring quantum circuit design.
    - On current hardware.
    - On hypothetical hardware.
- Circuit optimization.
- Not a programming language.

[comment]: # (!!! data-auto-animate)

# Summary

- A toolkit for exploring quantum circuit design.
    - On current hardware.
    - On hypothetical hardware.
- Circuit optimization.
- Not a programming language
    - ...yet

[comment]: # (!!! data-auto-animate)

# Future works

- Libraries
    - Domain/algorithm enrichments
- Compilation
    - Reconfigurable registers.
    - Arbitrary Hamiltonians.
- Towards easier programming

[comment]: # (!!!)

# Thanks

Actual work by Aleksander Wennersteen, Dominik Seitz, Niklas Heim, João P. Moutinho, Roland Guichard, Vytautas Abramavicius, Gert-Jan Both, Gergana V. Velikova, Anton Quelle, Caroline de Groot, Mario Dagrada, Vincent E. Elfving
<first.last>@pasqal.com

- https://pasqal-io.github.io/qadence
- https://browse.arxiv.org/abs/2401.09915
