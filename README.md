[![Paper](https://img.shields.io/badge/paper-arXiv%3A2006.06751-B31B1B.svg)](https://arxiv.org/abs/2006.06751)
[![DOI](https://zenodo.org/badge/157623289.svg)](https://zenodo.org/badge/latestdoi/157623289)

# Dimensional Reduction of Helium-4 Inside Argon Plated MCM-41 Nanopores
Nathan Nichols, Timothy R. Prisk, Garfield Warren, Paul Sokol, and Adrian Del Maestro

<!--FIXME [arXiv:1602.04225](https://arxiv.org/abs/1602.04225)-->

### Abstract
The angstrom-scale coherence length describing the superfluid wavefunction of <sup>4</sup>He at low temperatures has prevented its preparation in a truly one-dimensional geometry.  Mesoporous ordered silica-based structures such as the molecular sieve MCM-41 offer a promising avenue towards physical confinement, but the minimal pore diameters that can be chemically synthesized have proven to be too large to reach the quasi-one-dimensional limit.  We present an active nano-engineering approach to this problem by pre-plating MCM-41 with a single, well controlled layer of Ar gas before filling the resulting pores with helium.  The experimental adsorption isotherms and neutron scattering results are utilized to inform large scale quantum Monte Carlo simulations. The results demonstrate angstrom and kelvin scale tunability of the effective confinement potential experienced by <sup>4</sup>He atoms inside the MCM-41, with the Ar layer reducing the diameter of the confining media into a regime where a number of solid layers surround a one-dimensional quantum liquid.

### Description
This repository includes links, code, scripts, and data to generate the figures in a paper.

### Requirements
The [data](Data/) in this project was generated via path integral quantum Monte Carlo
simulations peformed in the grand canonical ensemble using our
[open source code](https://code.delmaestro.org/) and through experiments carried
out using the [Disc Chopper Spectrometer (DCS)](https://www.nist.gov/ncnr/dcs-disk-chopper-spectrometer)
at the NIST Center for Neutron Research.

[Notebooks](Notebooks/) require [Jupyter](https://jupyter.org/) with at least
[Python 3.7](https://www.python.org/) and [Julia 1.4.1](https://julialang.org/)
with the appropriate [Jupyter kernel](https://github.com/JuliaLang/IJulia.jl) installed.
Additional dependencies may be easily determined on a per notebook basis.

### Support
This research was supported in part by the National Science Foundation (NSF)
under award Nos. DMR-1808440 and DMR-1809027. 
We acknowledge the support of the National Institute of Standards and Technology,
U.S. Department of Commerce, in providing the neutron research facilities
used in this work.
Computations were performed on the Vermont Advanced Computing Core supported in
part by NSF award No. OAC-1827314 and IU Big Red Karst.  This work used the
Extreme Science and Engineering Discovery Environment (XSEDE), which is
supported by National Science Foundation grant number ACI-1548562. XSEDE
resources used include Bridges at Pittsburgh Supercomputing,
Comet at San Diego Supercomputer Center, and Open Science Grid (OSG)
through allocations TG-DMR190045 and TG-DMR190101.  OSG is supported by the
National Science Foundation award 1148698, and the U.S. Department of Energy's
Office of Science.

[<img height="150px" src="https://www.nsf.gov/images/logos/NSF_4-Color_bitmap_Logo.png">](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1808440&HistoricalAwards=false)
[<img height="150px" src="https://delmaestro.org/images/vacc_logo.jpg">](https://www.uvm.edu/vacc)
[<img height="150px" src="https://www.xsede.org/image/image_gallery?uuid=5787b7c0-b9e5-4eaa-8f6c-815ebf39eb08&groupId=10157&t=1369258426992">](https://www.xsede.org/)

### Figures

#### Figure 01: Experimental adsorption isotherms
<img src="Notebooks/plots/He_Ar_MCM41_isotherm.svg" width="400px">

#### Figure 02: Neutron scattering
<img src="Notebooks/plots/scattering.svg" width="400px">

#### Figure 03: Projection of MCM-41 supercell
<img src="Notebooks/plots/mcm41_crystal_structure.svg" width="400px">

#### Figure 04: Effective manybody potential
<img src="Notebooks/plots/manybodyPotential.svg" width="400px">

#### Figure 05a: Helium interacting with argon shell
<img src="Notebooks/plots/effectivePotential.svg" width="400px">

#### Figure 05b: Effect of density on minima location and potential well depth
<img src="Notebooks/plots/effectivePotential_b.svg" width="400px">

#### Figure 06: Relationship between pressure and chemical potential for bulk helium
<img src="Notebooks/plots/pressure_vs_chemical_potential.svg" width="400px">

#### Figure 07: QMC adsorption isotherms
<img src="Notebooks/plots/filling_the_pore.svg" width="400px">

#### Figure 08: Radial density of helium in Ar preplated MCM-41
<img src="Notebooks/plots/radialDensity.svg" width="400px">

#### Figure 09: Linear density of inner core and coverage of layers
<img src="Notebooks/plots/linearDensity.svg" width="400px">

#### Figure 10: Central slice of confinement potential for helium inside MCM-41 
<img src="Notebooks/plots/cylindrical_potential_effective_parameters_z0.svg" width="400px">

#### Figure 11: Comparison of fitting methods to determine effective potential 
<img src="Notebooks/plots/cylindrical_potential_effective_parameters.svg" width="400px">

#### Figure 12: Finite size effects on radial density 
<img src="Notebooks/plots/finite_size_scaling_radial_density.svg" width="400px">

#### Figure 13: Finite size effects on inner core
<img src="Notebooks/plots/finite_size_scaling_inner_core.svg" width="400px">

#### Figure 14: Effects of the finite imaginary time step
<img src="Notebooks/plots/EoN_vs_tau.svg" width="400px">
