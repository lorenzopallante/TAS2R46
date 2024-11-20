[![Virtuous button][Virtuous_image]][Virtuous link]

[Virtuous_image]: https://virtuoush2020.com/wp-content/uploads/2021/02/V_logo_h.png
[Virtuous link]: https://virtuoush2020.com/

Repository containing the files regarding the study: 

## Exploring TAS2R46 Biomechanics through Molecular Dynamics and Network Analysis

<i>Marco Cannariato<sup>1</sup>, Riccardo Fanunza<sup>1</sup>, Eric A. Zizzi<sup>1</sup>, Marcello Miceli<sup>1</sup>, Giacomo Di Benedetto<sup>2</sup>, Marco A. Deriu<sup>1</sup> and Lorenzo Pallante<sup>1*</sup>  </i>

<font size=2> <sup>1</sup>Polito<sup>BIO</sup>Med Lab, Department of Mechanical and Aerospace Engineering, Politecnico di Torino, 10129, Turin, Italy\
<sup>2</sup>7HC S.r.l., 00198, Rome, Italy
</font>

The preprint of the article can be accessed at this [link](https://www.biorxiv.org/content/10.1101/2023.11.21.568072v2)

--------


### Repo Structure

The repository is organized in the following folders:

 * `MDP/`

  This folder contains the MD simulation parameters in GROMACS MDP format used for minimization, stepwise equilibration and production MD simulation.

 * `Topologies/`

  This folder contains the molecular topologies for the of Holo, Trans, and Apo states (as obtained from CHARMM-GUI).

 * `SimulationInput/`

  This folder contains the input files for the production of MD simulations (after NVT+NPT equilibration; one tpr per replica).
  
 * `Notebooks/`
  
1. **Conformational_analysis.ipynb**\
  Notebook containing the python codes used to perform the conformational analysis of TAS2R46
2. **DYNET_analysis.ipynb**\
  Notebook containing the python codes used to perform the dynamic network analysis of TAS2R46

------

### Acknowledgements:

The present work has been developed as part of the VIRTUOUS project, funded by the European Union’s Horizon 2020 research and innovation program under the Marie Sklodowska-Curie-RISE Grant Agreement No. 872181 (https://www.virtuoush2020.com/).

This work has been conducted as part of the GALATEA project, which is funded by the European Union’s Horizon Europe research and innovation program under the Marie Skłodowska-Curie Actions (HORIZON-MSCA-2023-SE-01-01, Grant Agreement No. 101183057).
