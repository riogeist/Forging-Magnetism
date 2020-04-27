### Introduction
----------------
     This project is an exploration of how ferromagnetic materials magnetic properties are influenced by high temperatures. The fundamental physics necessary to investigate this question is an understanding of ferromagnetism, phase transitions, and magnetism, specifically magnetic moments. This introduction will consist of 3 topics: explaining magnetic moments; the Ising model; and introducing the properties of ferromagnetic materials.
    The magnetic moment, denoted by the Greek letter µ (mu), is a vector quantity that represents the measure of an object’s tendency to interact with an external magnetic field. Examples of vector quantities include displacement, velocity, acceleration, force, and momentum. When working with magnetic moments, the body being described is usually a particle of quantum sizes, such as a molecule, atom, nucleus, or other subatomic particles.
    The intrinsic magnetic properties of the body are usually represented by an arrow originating from a tiny bar magnet with north and south poles. These north and south poles can be likened to opposite electrical charges (for example, north as positive and south as negative) so that we can call these dipoles, as a dipole is a separation of opposite electrical charges. Due to this, the magnetic moment is also called the magnetic dipole moment [1]. 
    A quantitative definition of µ is to create a model where µ is generated from an electrical current, represented by the letter i, traveling on the edge of a loop of cross-sectional area, A. The magnetic dipole moment µ is a vector defined as the cross product of the current, i, and the cross-sectional area, A, such that µ = i x A . 
    The magnetic moment was defined as a vector quantity that represents the measure of an object’s tendency to interact with an external magnetic field, B0. When an object with some µ is put inside an external magnetic field, Bo, µ will seek to align with Bo, just as a compass aligns with the external magnetic field of the Earth. When µ and Bo are parallel, the object does not move in the magnetic field. However, when µ and Bo are not aligned, the object will swing to align with Bo, as we just discussed. This swing is called torque, represented by the greek letter τ (tau). 
    The torque is a vector defined as the cross product of the magnetic moment and the external magnetic field, such that τ = µ x Bo. From this equation, we can see that in the case above, where µ and Bo are parallel, τ = 0, therefore the object will experience no torque, and µ will be in its lowest energy state as no energy is required to maintain the orientation of the object in the magnetic field. In the case where µ and Bo are antiparallel, µ will be in the highest energy state available as energy would be required for the object’s orientation to be maintained. This energy, E, can be expressed as the dot product of the magnetic moment and the external magnetic field, such that E = - µ * Bo, where the negative term arises as in our parallel case, we want E to be a low value to represent that µ is in its lowest energy state [2].
    The understanding of magnetic moments is crucial for understanding the magnetic properties of ferromagnetic materials. Below we will discuss how to model these magnetic moments in a simple case to show phase transitions due to temperature using the Ising model. 
The Ising model is a mathematical model of ferromagnetism in statistical mechanics (statistical mechanics is defined by the Oxford dictionary as “the description of physical phenomena in terms of a statistical treatment of the behavior of large numbers of atoms or molecules, especially with regard to the distribution of energy among them.” Statistical mechanics is necessary for the fundamental study of any physical system that has many degrees of freedom [6]). Created by the German physicist Ernst Ising, the Ising model doesn't correspond to an actual physical system. The model is a lattice of sites, where a site can exist in one of two states: -1 or +1 [3]. For this project, I will be using a square lattice in two dimensions. In principle, the model can be defined for any lattice in any number of dimensions. Each site in the lattice is labeled with index i,j. If we want to say that the i’th,j’th site is in the state +1, this is denoted by i,j= +1. 
    The Ising model can represent many physical systems: magnets, alloys, and gases are three examples of possible physical systems. 
For this project, the Ising model will be used as a theoretical model of a magnet. The magnetization of a magnetic material is made up of the combination of many small magnetic dipoles spread throughout the material. If these dipoles point in random directions then the overall magnetization of the system will be close to zero, but if they line up so that all or most of them point in the same direction then the system can acquire a macroscopic magnetic moment-it becomes magnetized [4]. 
    The magnetic moments are arranged in the lattice, allowing each µ to interact with neighboring sites in the lattice. Neighboring magnetic moments that point in the same direction (+1 and +1, -1 and -1) have lower energy than those that disagree (+1 and -1), due to parallel magnetic moments not requiring any energy to remain oriented in their original direction, while magnetic moments which have opposite orientations will experience a torque, as the neighboring µ will exert a magnetic force upon the other µ. The system will tend towards the lowest energy states, as it requires an inputted energy to keep magnetic moments unaligned, and without this energy, the magnetic moments will align.
    The tendency towards the lowest energy state can be disrupted by thermal energy added to the system. This disruption creates the possibility of different structural phases. The Ising model allows the identification of phase transitions as the amount of thermal energy in the system changes. These phase transitions only occur in Ising models which are higher than 1 dimensional. When the thermal energy in the system is high, the system is disordered. For lower thermal energies, the system becomes ordered and is said to exhibit ferromagnetic order (a discussion of ferromagnetism follows this paragraph). The transition from ordered to disordered is what the Ising model will be used to analyze [5].
	  Above, we read that for a system with low thermal energies, the system is said to exhibit ferromagnetic order. Ferromagnetic order is a description of the magnetic moments in a lattice, where the magnetic moments are aligned parallel to other magnetic moments in neighboring sites. This behavior of magnetic moments aligning is what distinguishes ferromagnetic materials from other materials which exhibit different forms of magnetism, such as paramagnetism, diamagnetism, and antiferromagnetism. 
	  For a material to be ferromagnetic, the material is defined to have “a high susceptibility to magnetization, the strength of which depends on that of the applied magnetizing field, and which may persist after removal of the applied field [6].” Ferromagnetism is displayed by iron and is characterized by the atoms comprising the iron to be magnetically aligned. 
    At the atomic level of iron, or any ferromagnetic material, there are multiple regions in the material which have differing alignments. Each one of these regions is comprised of atoms, but the atoms’ magnetic moments only display ferromagnetic order within their respective regions. These regions are called domains. 
    Within the domain, the net magnetic field of the domain points in some direction such that each individual domain has a net µ which is comprised of each residential atoms magnetic moments. A bulk sample of ferromagnetic material will usually be unmagnetized as the net magnetic moments of the domains comprising the sample will be randomly oriented with respect to one another. However, if the sample is exposed to an externally imposed magnetic field, this can cause the magnetic moments of the sample’s domains to aline with the external magnetic field, resulting in the net µ of each domain pointing in the same direction. This creates an overall net magnetic moment for the sample of ferromagnetic material and results in the sample being magnetized, even after the removal of the external magnetic field [7]. 
    Using the Ising model to represent a sample of ferromagnetic material, we can explore how changing the amount of thermal energy in the system (the ferromagnetic material sample) affects the order of the system. 

### Model
---------
    This project will be using two models. The first model is the equation M = µ*tanh(JM/kB*T), which will be used to plot the strength of the magnetization of the ferromagnetic material as the temperature changes. The second model is the Ising model, which will be simulated using the foundational formula H(σ)=-JΣi*j. 
Model 1: This model has five variables:
- M is the strength of magnetization (A/m)
- µ is the magnetic moment (A*m^2 or J/Tesla)
- J is a coupling constant (Hz)
- kB = 1.38064852 × 10-23 m2 kg s-2 K-1 is Boltzmann’s constant
- T is the temperature (K)
Model 2: This model has 4 variables:
- J is a constant specifying the strength of interaction
- σ is a spin configuration
- i is a row site in a lattice
- j is a column site in a lattice
H(σ) is the function that gives the energy of a configuration σ [8].

### Numerical Methods
---------------------
    In this project, I will be using two numerical methods for my models above. For model 1, I will be using the relaxation method to solve the equation for different solutions (where a solution for the equation is always at m = o) [4]. The relaxation method requires the equation to be iterated until a specified tolerance is reached. This will be done for all values of T over some range to find corresponding values of M. One problem with this method to be careful of is that the method will only find one solution, even if two exist. Boundary conditions for this model are when M is maximized for the ferromagnetic solution, and when M is equal to 0, such that 0<M<max . Another condition for the equation is T != 0K, as we would receive an error for dividing by zero. For this reason, T will be initialized as T = 0.01K.
    For model 2, I will be using a Monte Carlo simulation to simulate the Ising model. A Monet Carlo simulation is the name given to any computer simulation that uses random numbers to simulate a random physical process in order to estimate something about the outcome of that process [4]. The simulation conditions are that there are only two possible states for a site in the simulation to have: +1 or -1. To test for accuracy of this model, the simulation should show ferromagnetic order at low temperatures and display a phase transition to disorder at higher temperatures. 
    
    
### Code
--------
#### Model 1
def magnetizationDueToTemp(m0,f,tol,u,J,kB):
    '''
    Description: function that reads in constants specific to a ferromagnetic material. Function then uses the relaxation method to find                  solutions of the magnetism for a range of temperatures, returning the array of magnetization solutions and the                          corresponding temperature array.
    Paramaters: m0  - initial magnetization strength of ferromagnetic material
                f   - inputted function to describe strength of magnetization due to temperature
                tol - desired tolerance of solutions
                u   - magnetic moment of ferromagnetic material
                J   - coupling constant of the ferromagnetic material
                kB  - Boltzmann's constant
                
   Returns: magArray - array of magnetizations values
            magTemp  - array of temperature values which correlate to magArray solutions
   '''

#### Model 2
in creation
    
### References
--------------
[1] - http://hyperphysics.phy-astr.gsu.edu/hbase/magnetic/magmom.html
[2] - http://mriquestions.com/magnetic-dipole-moment.html
[3] - http://stanford.edu/~jeffjar/statmech2/intro4.html
[4] - Newman’s Computational Physics
[5] - https://web.stanford.edu/~peastman/statmech/phasetransitions.html
[6] - Oxford dictionary
[7] - http://hyperphysics.phy-astr.gsu.edu/hbase/Solids/ferro.html
[8] - http://micro.stanford.edu/~caiwei/me334/Chap12_Ising_Model_v04.pdf
