## ECP Application Development:
 * https://confluence.exascaleproject.org/display/12AD
 * 26 applications (15 uses HDF5, 4 use NetCDF, 3 use ADIOS, 4 use POSIX I/O)
 * 5 co-design centers
 * A Proxy Application project
 * An Applications Assessment project

### 6 Chemistry and Materials applications
 * LatticeQCD (Nuclear, HEP)
   * Chroma: https://github.com/JeffersonLab/chroma
   * MILC: https://github.com/milc-qcd/milc_qcd
   * Others see https://confluence.exascaleproject.org/display/ADSE03/LaticeQCD+Software+Specs
   * I/O: HDF5

 * NWChemEx (Chemistry, Materials, PNNL)
   * https://github.com/NWChemEx-Project
   * http://www.nwchem-sw.org/index.php/Main_Page
   * I/O: POSIX, text format

 * GAMESS (Chemistry, Materials)
   * Development: https://github.com/gms-bbg/gamess
   * Release: http://www.msg.ameslab.gov/gamess/download.html
   * I/O: HDF5

 * EXAALT (Molecular dynamics)
   * https://gitlab.com/exaalt/exaalt/wikis/home
   * ParSplice
   * I/O: ?

 * ExaAM (Manufacture Simulation)
   * 13 components, each in different repo
   * Component AMPE, Diablo, and Tusas: NetCDF/HDF5
   * Component ExaCA, Truchas-PBF: AMReX

 * QMCPACK (Quantum Mechanics)
   * https://github.com/QMCPACK/qmcpack
   * I/O: HDF5

### 6 Energy applications
 * ExaWind (Fluid Dynamics)
   * https://github.com/Exawind/nalu-wind
   * I/O: NetCDF4/HDF5/PnetCDF

 * Combustion-Pele
   * git@code.ornl.gov:Pele/PeleC.git
   * I/O: HDF5

 * ExaSMR (Fluid Dynamics)
   * component Shift: https://code-int.ornl.gov/exnihilo/exnihilo
   * component OpenMC: https://github.com/mit-crpg/openmc
   * component Nek5000: github.com/Nek5000
   * I/O: HDF5 (Shift, OpenMC)
   * I/O: ADIOS (optional for Shift)

 * MFIX-Exa (Fluid Dynamics)
   * https://mfix.netl.doe.gov/gitlab/users/sign_in
   * AMReX

 * WDMApp (Fusion)
   * GENE: gitlab.mpcdf.mpg.de
   * XGC: bitbucket.org/madams/epsi
   * I/O: ADIOS, HDF5

 * WarpX (Particle Accelerators)
   * WarpX: https://bitbucket.org/berkeleylab/warpx
   * PICSAR: https://bitbucket.org/berkeleylab/picsar
   * I/O: HDF5

### 5 Earth and Space Sciences applications
 * ExaStar (LBNL)
   * https://github.com/AMReX-Astro/Castro
   * New development repo https://github.com/ECP-Astro/FLASH-subset
   * Production code downloaded as tarball from
   * http://flash.uchicago.edu/site/flashcode/download/
   * I/O: multi-dimensional AMR checkpoint
   * I/O: Tabular data
   * I/O: HDF5
   * I/O: BoxLib (homegrown format)

 * EaxSky (Habib, ANL)
   * GenericIO Releases: http://trac.alcf.anl.gov/projects/genericio
   * Nyx repository: https://github.com/AMReX-Astro/Nyx
   * HACC CORAL benchmark: https://asc.llnl.gov/CORAL-benchmarks/
   * I/O: MPI-IO

 * EQSIM (LBNL) 
   * https://github.com/geodynamics/sw4
   * I/O: C++, POSIX I/O

 * Subsurface (LBNL)
   * anag-repo.lbl.gov
   * CHOMBO
   * I/O: HDF5

 * E3SM-MMF
   * https://github.com/E3SM-Project/E3SM
   * I/O: PIO, NetCDF4, PnetCDF, HDF5, ADIOS

• 5 Data Analytics and Optimization applications
 * Urban (Metropolitan Energy and Economic Dynamics)
   * https://github.com/NCAR/WRFV3
   * WRF: NetCDF4/HDF5/PnetCDF
   * Nek500: none

 * ExaSGD (Grid Dynamics)
   * https://github.com/Argonne-National-Laboratory/PIPS
   * I/O: C++, POSIX

 * CANDLE (Machine Learning)
   * https://github.com/ECP-Candle/
   * I/O: python ?

 * ExaBiome (Microorganisms)
   * https://bitbucket.org/berkeleylab/hipmeraculous
   * https://bitbucket.org/azadcse/hipmcl/
   * I/O: POSIX, text

 * ExaFEL (Electron Laser)
   * PSANA: https://github.com/lcls-psana	
   * CCTBX: http://cctbx.github.io
   * LUNUS: https://github.com/mewall/lunus
   * I/O: Python, HDF5

### 3 National Security applications
 *  ATDM-LANL
 * ATDM-LLNL
 * ATDM-SNL

### 6 Co-design projects aimed at developing crosscutting capabilities
 * CODAR (Data Analysis and Reduction)
		https://CODARcode/cheetah (Python)
		https://github.com/CODARcode/PerformanceVisualization (Database)
		https://github.com/CODARcode/savanna (ADIOS)
		https://github.com/CODARcode/Z-checker (HDF5/NetCDF)
		https://sdrbench.github.io

 * COPA (Particle Applications)
   * ?
		
 * AMREX (Block-structured AMR)
   * https://github.com/AMReX-Codes/amrex
   * I/O: C++, text, POSIX

 * CEED (Unstructured Mesh)
   * https://github.com/CEED
   * https://ceed.exascaleproject.org
   * 5 applications: Nek5000, MFEM, MAGMA, OCCA, PUMI

 * ExaGraph (graph problem)
   * Kokkos https://github.com/kokkos/kokkos-kernels
   * Trilinos https://github.com/trilinos/Trilinos
   * HIPMCL https://bitbucket.org/azadcse/hipmcl/

	ExaLearn (Machine Learning)
   * ?

## Proxy Applications

## Application Assessment
