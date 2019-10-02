# Gaseous Detectors


1. How does a Geiger-Muller tube work?
    <span style="color:blue">   </span>    

2. The sources have a strength on order 100 μC; does this correspond to what  you measured with the Geiger counter?
    <span style="color:blue">   </span>    
    
2. Difference between avalanche mode and streamer mode?

    <span style="color:blue">
        
    </span>    

2. Why efficiency curve shift to right/left by adding different gas composition?

    <span style="color:blue">
        
    </span>   
    
1. **Ramsauer-Townsend Effect**

    The reduction of cross-section when low energy (about 1 eV) electrons collides with atom of inert gases is known as **_Ramsauer-Townsend effect_**. This reduction of cross-section requires quantum mechanical explanation (1-dimensional model) as it is connected with the wave nature of the electrons[^2]. 
    [^2]: D. E. Golden and H. W. Bandel, _Low-Energy $e^-Ar$ Total Scattering Cross Sections: The Ramsauer-Townsend Effect_, Phys. Rev. 149, 58 (1966)
    
    This effect was discovered independently by Ramsauer[^3]  and Townsend and Bailey[^4].
    [^3]: C. Ramsauer, Ann. Physik 64, 513 (1921)
    [^4]: J. S. Townsend and V. A. Bailey, Phil. Mag. 43, 593 (1922)

2. **Townsend Coefficient**

    The average distance travelled by electron in an ionizing collision is called its mean free path.

    The average distance an electron travels between ionizing collisions is called mean free path and its inverse is the number of ionizing collision per unit length is known as the first Townsend coefficient ($\alpha$).
    
    This parameter determines the gas gain of the gas. 
    
    If $n_0$ is the number of primary electron without amplification in uniform electric field, and $n$ is the number of electrons after distance $x$ under avalanche condition. So $n$ is given by $n = n_0 e^{\alpha . x}$ and the gas gain $G$ is given by $G = n_0/n = e^{\alpha}x$. 
    
    The first Townsend Coefficient depends on the nature of the gas, the electric field and pressure.

3. **Transparancy**

    <span style="color:blue">
    The fraction of ionization electrons transferred through the GEM foil is known as its *transparancy*. 
    </span>   
    
    $$\color{red}{Transparancy}~=~\frac{Ionized~electron~transfered~through~GEM~foil}{Total~number~of~ionized~electrons}$$
    
    <span style="color:blue">
    This is important while finding out the energy resolution and directly effects the gain/efficiency of detection.
    </span>   


4. **Gain**

    The gain of a detector can be calculated using the ratio of output to the input value of current, like:
    $$Gain~=~\frac{I_{out}}{q~\times~f}$$
    where $q$ is the charge collected at the first layer of GEM foil and is calculated as:
    $$q~= n~\times~e$$
    where $e$ is the electron charge, $n$ is the average number of electrons produced in the drift region by the incident particles and $f$ is the interaction rate of the incident particles in the gas. For the given X-ray source with a specific energy and the known ionization potential of the used gas mixture $n$ can be calculated and in our case it is found to be $n \sim 290$.
    
5. **Charge-up effect**

    The effect caused by the the electrons or ions coming from the primary or secondary ionization from the amplification region sticks to the insulator surface inside the GEM holes, which lead to the modification of electric field in the holes and is known as the ***charge-up effect***.

    It has direct effect on the electron transparancy and the effective gain of the GEM detector.

    Also, the charge-up effect depends on the geometry of the holes.
    
    For the conical hole gain increases about 60\% than the cylindrical hole. There is no effect of the charge-up for the cylindrical hole.

6. **Collection Efficiency**

    Collection efficiency is the ratio of the total electrons released from the bottom of GEM foil (last GEM foil in case of multiple foil used) to the number of electrons reached the readout board. 
	$$\text{Collection efficiency}~=~\frac{\text{Number of electrons reached readout board}}{\text{Total number of released electron from bottom of GEM foil}}$$
    Also, it depends on the ratio of the conversion electric field to the collection electric field. Higher the conversion field lesser the collection efficiency. In general the conversion field should never be greater than the collection field. 

## GEM

1. **Why we don't observe any signal in GEM detector with $CO_2$ gas?**
2. **What is (are) the highly-ionising particle(s) that can lead to destructive discharge? What is the physical reason for GEMs improved radiation hardness?**
3. **Is there a stereo angle between the strips in a superchamber? If not, what is the ghost hit rate as a result?**
4. **It is not clear how the bending of GEM foils affects the transparency of the GEM detectors. Can this be explained?**
5. **Define real and effective gain of the GEM detectors.**
6. **Why GEM detectors are better compared to other gaseous detectors, e.g. RPC?**
7. **What causes ageing in the gaseous detectors?**
8. **Are currents same in RPC and GEM? what is the order of current?**

    GEM: ~nA
    RPC: ~$\mu$A
    
9. **Why those particular conical shapes of holes in GEM foils? How these shapes affect the performance and electric field.**
10. **If there are any defect in holes in GEM foil, do you reject the foil or not?**
11. **Do you reject foil if the defected holes are concentrated in one place or if they are evenly distributed?**
12. **Why the total number of defected holes are different in the front and back side of GEM foil?**
13. **The ratio of gas mixture $(Ar:CO_2:CF_4)=(45:15:30)$ and the $(Ar:CO_2)=(70:30)$. How did you decide ratio of Ar and $CO_2$ after removing the $CF_4$? Also, what is the role of $CF_4$ in the gas mixture?**
