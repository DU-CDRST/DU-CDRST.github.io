# Accelerator and Its Detectors

1. What is an LHC fill?

    <span style="color:blue">   </span>    
    Ref: [https://physics.stackexchange.com/q/340595](https://physics.stackexchange.com/q/340595)

2. Large Hadron Collider momentum calibration and accuracy

    <span style="color:blue">   </span>    
    Ref: [https://journals.aps.org/prab/pdf/10.1103/PhysRevAccelBeams.20.081003](https://journals.aps.org/prab/pdf/10.1103/PhysRevAccelBeams.20.081003)

## LHC

1. Why we prefer $p-p$ collider over $p-\bar{p}$ collider?

   <span style="color:blue">
    a) Storage of anti-proton is difficult.
   </span>

1. **Write the equation of motion for the LHC beam.**

8. **If the equation of motion is $$\frac{d^2x}{dt^2}+kx=0,$$ then what is k? and on what factors it depends?**

9. **Why magnetic field does not increase energy of beam?**

    <span style="color:blue">
    The magnetic force on beam/charge particle is always perpendicular to the direction of motion.
   </span>


11. **What is $\beta^*$?**


10. **Why is there * on $\beta$?**

    <span style="color:blue">
    Here, * is just a notation for the "*interaction point*".
   </span>


11. **What is instantaneous luminosity?**

22. **Why can the LHC not accelerate protons to several TeV in one go? What is the limitation?**

    <span style="color:blue">
    
    * If there is only one accelerator to accelerate particle from rest to 6.5 TeV then to bend particles, one need to increase magnetic field from zero to 8 Tesla. The energy loss in going from 0 to 8 Tesla is too much large as compared to going into several different steps.
    * Another reason is to minimize the cost of LHC accelerator construction by utilizing the previous accelerators.
    * Also, it servers several other experiments at each stage as shown below. ![Experiments at CERN accelrator complex](https://home.cern/sites/home.web.cern.ch/files/2018-06/distribution_of_protons_en.jpg)
    * Apart from this, the circular accelerator uses RF cavities for the acceleration. Each cavity has a certain frequency range as per the design. So, one need different cavity for different energy range.
    * https://physics.stackexchange.com/questions/504126/why-there-is-accelerator-chain-at-lhc

   </span>

1. How the protons bunches are formed?

1. **Explain why the protons are in bunches?**

    <span style="color:blue">
    At LHC, the protons accelerates in bunches instead of continous stream of particles. *The bunch structure is the consequence of the Radio Frequency (RF) acceleration scheme.* Since RF cavity is placed at one place, protons can only be accelerated if RF field has correct orientation while protons pass through the RF cavity.
    
    The bunch size is not constant around the ring. Each bunch gets squeezed and expanded as it circulates around the LHC ring. All the particles are clumped around the synchronous particle (whose energy is completely synchronized with the RF). The particles whose energy is less then the synchronous gets higher engery and particles whose energy energy is higher gets deaccelerated.
    
    The field in an RF cavity is made to oscillate (switch direction) at a given frequency, so timing the arrival of particles is important. In the LHC, each RF cavity is tuned to oscillate at 400 MHz. When the beam has reached the required energy, an ideally timed proton with exactly the right energy will not be accelerated. By contrast, protons with slightly different energies arriving earlier or later will be accelerated or decelerated so that they stay close to the desired energy. In this way, the particle beam is sorted into packs of protons called "bunches".
    
    **Reference**:
    
    1. https://home.cern/science/engineering/accelerating-radiofrequency-cavities
   </span>

    
1. **How much time proton beam takes to reach LHC from Hydrogen cylinder?**

    <span style="color:blue">
    In LHC it takes ~20 mintutes to reach to 6.5 TeV from 450 GeV.
   </span>


## CMS
    
1. **List the neutral hadrons that are detected by ECAL and HCAL?**

    <span style="color:blue">

    ECAL: $\pi^0 \rightarrow \gamma \gamma$
    
    HCAL: all other hadrons
   </span>


13. **How we measure the momentum of muons?**

    

16. **Can you explain why the momentum resolution is related to B and L in this way ($\frac{\Delta p_t}{p_t} \propto \frac{1}{BL^2}$)?**

    <span style="color:blue">

    If we have long curvature and enough magnetic field to bend the particles then the momentum resoultion is better.
   </span>

    
14. **Compare the resolution of electrons and muons?**

15. **If we use the muon system information apart from the tracker and calorimeter information for calculating the muon momentum resoution then will it increase the momentum resolution or decrease?**

    <span style="color:blue">

    It will definitely imporve the momentum resolution.
   </span>

1. What is the tracker resolution?
11. Explain various object identification and isolation variables?

    | Electrons |   |
    |---           |---   |
    |           |   |
    |           |   |

    | Muons     |   |
    |---           |---   |
    |           |   |
    |           |   |

    | Photons   |   |
    |---           |---   |
    |           |   |
    |           |   |

    | Jets      |   |
    |---           |---   |
    |           |   |
    |           |   |

    | MET       |   |
    |---           |---   |
    |           |   |
    |           |   |

14. Why |$\eta$| < 1.4442?
    
    <span style="color:blue">
        Because of crack in the ECAL barrel and endcap.
    </span>    

13. Why b-tagging efficiency goes down at higher pseudo-rapidity?

    <span style="color:blue">
        As the tracker is only till pseudo-rapidity of 2.4.
    </span>    


