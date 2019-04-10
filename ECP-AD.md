## ECP Application Development:
 * https://confluence.exascaleproject.org/display/12AD
 * 26 applications (15 uses HDF5, 4 use NetCDF, 3 use ADIOS, 4 use POSIX I/O)
 * 5 co-design centers
 * A Proxy Application project
 * An Applications Assessment project

### 6 Chemistry and Materials applications
 * LatticeQCD (Nuclear, HEP)
   * Chroma (https://github.com/JeffersonLab/chroma)
     * I/O: POSIX, HDF5
   * QDP++ (https://github.com/usqcd-software/qdpxx)
   * QDP-JIT (https://github.com/fwinter/qdp-jit)
   * QMP (https://github.com/usqcd-software/qmp)
   * QPhiX (https://github.com/jeffersonlab/qphix)
   * QUDA (https://github.com/lattice/quda)

   * MILC (https://github.com/milc-qcd/milc_qcd)
     * I/O: MPI-IO, POSIX
   * QLA (https://github.com/usqcd-software/qla)
   * QIO (https://github.com/usqcd-software/qio)
   * QMP (https://github.com/usqcd-software/qmp)
   * QOPQDP (https://github.com/usqcd-software/qopqdp)
   * QUDA (https://github.com/lattice/quda)
   * QPHIX (https://github.com/JeffersonLab/milc-qphix)
   * GRID (https://github.com/paboyle/Grid)

   * CPS (https://github.com/RBC-UKQCD/CPS)
     * I/O: POSIX
   * GRID (https://github.com/paboyle/Grid)
   * QIO (https://github.com/usqcd-software/qio)
   * QMP (https://github.com/usqcd-software/qmp)
   * QUDA (https://github.com/lattice/quda)


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
   * I/O
     * HDF5
     * NetCDF4 (call PnetCDF)

 * Combustion-Pele (NREL)
   * git@code.ornl.gov:Pele/PeleC.git
   * I/O: HDF5

 * ExaSMR (Fluid Dynamics)
   * Shift (https://code-int.ornl.gov/exnihilo/exnihilo)
     * I/O: HDF5, ADIOS (optional)
   * OpenMC (https://github.com/mit-crpg/openmc)
     * I/O: HDF5
   * Nek5000 (github.com/Nek5000)
     * I/O: POSIX

 * MFIX-Exa (Fluid Dynamics)
   * https://mfix.netl.doe.gov/gitlab/users/sign_in
   * Dependency: AMReX

 * WDMApp (Fusion)
   * GENE (gitlab.mpcdf.mpg.de)
     * I/O: ADIOS, HDF5
   * XGC (bitbucket.org/madams/epsi)
     * I/O: ADIOS

 * WarpX (Particle Accelerators)
   * WarpX (https://bitbucket.org/berkeleylab/warpx)
     * Dependency AMReX
     * I/O: HDF5
   * PICSAR (https://bitbucket.org/berkeleylab/picsar)
     * I/O: MPI-IO, text pixr format

### 5 Earth and Space Sciences applications
 * ExaStar (Stellar Explosions, LBNL)
   * Castro (https://github.com/AMReX-Astro/Castro)
     * https://amrex-astro.github.io/Castro/docs/io.html
     * BoxLib, FAB (MultiFAB)
   * FLASH (https://github.com/ECP-Astro/FLASH-subset)
     * Production code (http://flash.uchicago.edu/site/flashcode/download)
     * HSF5, PnetCDF
   * I/O options
     * multi-dimensional AMR checkpoint
     * Tabular data
     * HDF5
     * BoxLib (homegrown format)

 * EaxSky (Cosmology, Habib, ANL)
   * GenericIO Releases: http://trac.alcf.anl.gov/projects/genericio
     * I/O: MPI-IO and POSIX I/O
   * Nyx repository: https://github.com/AMReX-Astro/Nyx
     * C++ I/O, converter utility uses HDF5
   * HACC CORAL benchmark: https://asc.llnl.gov/CORAL-benchmarks/
     * I/O: MPI-IO

 * EQSIM (Earthquake Simulation, LBNL)
   * https://github.com/geodynamics/sw4
   * I/O: C++, POSIX I/O
   * I/O: HDF5 under development [PR #41](https://github.com/geodynamics/sw4/pull/41)

 * Subsurface (Coupled Flow, Transport, Reactions and Mechanics, LBNL)
   * CHOMBO-Crunch (https://anag-repo.lbl.gov)
   * GEO ?
   * I/O: HDF5

 * E3SM-MMF
   * https://github.com/E3SM-Project/E3SM
   * I/O: PIO, NetCDF4, PnetCDF, HDF5, ADIOS

### 5 Data Analytics and Optimization applications
 * Urban (Metropolitan Energy and Economic Dynamics)
   * WRF (https://github.com/NCAR/WRFV3)
     * I/O: NetCDF4/HDF5/PnetCDF
   * Nek5000 (github.com/Nek5000)
     * I/O: POSIX
   * Other applications:
     * EnergyPlus, TUMS, MOVES, chiSIM

 * ExaSGD (Stochastic Grid Dynamics)
   * GridPACK (https://github.com/GridOPTICS/GridPACK)
     * I/O: C++, POSIX
   * PIPS (https://github.com/Argonne-National-Laboratory/PIPS)
     * I/O: C++, POSIX
   * StructJuMP (https://github.com/StructJuMP/StructJuMP.jl)
     * Julia
   * GOSS

 * CANDLE (Machine Learning)
   * https://github.com/ECP-Candle/
   * I/O: python (HDF5 python)

 * ExaBiome (Microorganisms)
   * MetaHipMer (https://bitbucket.org/berkeleylab/hipmeraculous)
     * private repo
   * HipMCL (https://bitbucket.org/azadcse/hipmcl/)
     * I/O: POSIX, text
   * GOTTCHA (https://github.com/LANL-Bioinformatics/GOTTCHA)
     * Perl

 * ExaFEL (Electron Laser)
   * PSANA (https://github.com/lcls-psana)
     * Python (C++ ?)
   * CCTBX (http://cctbx.github.io)
     * I/O: Python, HDF5
   * LUNUS (https://github.com/mewall/lunus)
     * Python
   * M-TIP

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
