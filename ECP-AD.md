## ECP Application Development:
 * https://confluence.exascaleproject.org/display/12AD
 * 26 applications (15 uses HDF5, 4 use NetCDF, 3 use ADIOS, 4 use POSIX I/O)
 * 5 co-design centers
 * A Proxy Application project
 * An Applications Assessment project

### 6 Chemistry and Materials applications
 * 2.2.1.01 ADSE03-LatticeQCD (Nuclear, HEP)
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


 * 2.2.1.02 ADSE11-NWChemEx (Chemistry, Materials, PNNL)
   * https://github.com/NWChemEx-Project
   * http://www.nwchem-sw.org/index.php/Main_Page
   * I/O: POSIX, text format

 * 2.2.1.03 ADSE16-GAMESS (Chemistry, Materials)
   * Development: https://github.com/gms-bbg/gamess
   * Release: http://www.msg.ameslab.gov/gamess/download.html
   * I/O: HDF5

 * 2.2.1.04 ADSE04-EXAALT (Molecular dynamics)
   * https://gitlab.com/exaalt/exaalt/wikis/home
   * ParSplice
   * I/O: ?

 * 2.2.1.05 ADSE10-ExaAM (Manufacture Simulation)
   * 13 components, each in different repo
   * Component AMPE, Diablo, and Tusas: NetCDF/HDF5
   * Component ExaCA, Truchas-PBF: AMReX

 * 2.2.1.06 ADSE09-QMCPACK (Quantum Mechanics)
   * https://github.com/QMCPACK/qmcpack
   * I/O: HDF5

### 6 Energy applications
 * 2.2.2.01 ADSE07-ExaWind (Fluid Dynamics)
   * https://github.com/Exawind/nalu-wind
   * I/O
     * HDF5
     * NetCDF4 (call PnetCDF)

 * 2.2.2.02 ADSE14-Combustion-Pele (NREL)
   * git@code.ornl.gov:Pele/PeleC.git
   * I/O: HDF5

 * 2.2.2.03 ADSE08-ExaSMR (Fluid Dynamics)
   * Shift (https://code-int.ornl.gov/exnihilo/exnihilo)
     * I/O: HDF5, ADIOS (optional)
   * OpenMC (https://github.com/mit-crpg/openmc)
     * I/O: HDF5
   * Nek5000 (github.com/Nek5000)
     * I/O: POSIX

 * 2.2.2.04 ADSE21-MFIX-Exa (Fluid Dynamics)
   * https://mfix.netl.doe.gov/gitlab/users/sign_in
   * Dependency: AMReX

 * 2.2.2.05 ADSEcw1207-WDMApp (Fusion)
   * GENE (gitlab.mpcdf.mpg.de)
     * I/O: ADIOS, HDF5
   * XGC (bitbucket.org/madams/epsi)
     * I/O: ADIOS

 * 2.2.2.06 ADSE06-WarpX (Particle Accelerators)
   * WarpX (https://bitbucket.org/berkeleylab/warpx)
     * Dependency AMReX
     * I/O: HDF5
   * PICSAR (https://bitbucket.org/berkeleylab/picsar)
     * I/O: MPI-IO, text pixr format

### 5 Earth and Space Sciences applications
 * 2.2.3.01 ADSE18-ExaStar (Stellar Explosions, LBNL)
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

 * 2.2.3.02 ADSE01-EaxSky (Cosmology, Habib, ANL)
   * GenericIO Releases: http://trac.alcf.anl.gov/projects/genericio
     * I/O: MPI-IO and POSIX I/O
   * Nyx repository: https://github.com/AMReX-Astro/Nyx
     * C++ I/O, converter utility uses HDF5
   * HACC CORAL benchmark: https://asc.llnl.gov/CORAL-benchmarks/
     * I/O: MPI-IO

 * 2.2.3.03 ADSE19-EQSIM (Earthquake Simulation, LBNL)
   * https://github.com/geodynamics/sw4
   * I/O: C++, POSIX I/O
   * I/O: HDF5 under development [PR #41](https://github.com/geodynamics/sw4/pull/41)

 * 2.2.3.04 ADSE05-Subsurface (Coupled Flow, Transport, Reactions and Mechanics, LBNL)
   * CHOMBO-Crunch (https://anag-repo.lbl.gov)
   * GEO ?
   * I/O: HDF5

 * 2.2.3.05 ADSE15-E3SM-MMF
   * https://github.com/E3SM-Project/E3SM
   * I/O: PIO, NetCDF4, PnetCDF, HDF5, ADIOS

### 5 Data Analytics and Optimization applications
 * 2.2.4.01 ADSE17-Urban (Metropolitan Energy and Economic Dynamics)
   * WRF (https://github.com/NCAR/WRFV3)
     * I/O: NetCDF4/HDF5/PnetCDF
   * Nek5000 (github.com/Nek5000)
     * I/O: POSIX
   * Other applications:
     * EnergyPlus, TUMS, MOVES, chiSIM

 * 2.2.4.02 ADSE22-ExaSGD (Stochastic Grid Dynamics)
   * GridPACK (https://github.com/GridOPTICS/GridPACK)
     * I/O: C++, POSIX
   * PIPS (https://github.com/Argonne-National-Laboratory/PIPS)
     * I/O: C++, POSIX
   * StructJuMP (https://github.com/StructJuMP/StructJuMP.jl)
     * Julia
   * GOSS

 * 2.2.4.03 ADSE01-CANDLE (Machine Learning)
   * https://github.com/ECP-Candle/
   * I/O: python (HDF5 python)

 * 2.2.4.04 ADSE20-ExaBiome (Microorganisms)
   * MetaHipMer (https://bitbucket.org/berkeleylab/hipmeraculous)
     * private repo
   * HipMCL (https://bitbucket.org/azadcse/hipmcl/)
     * I/O: POSIX, text
   * GOTTCHA (https://github.com/LANL-Bioinformatics/GOTTCHA)
     * Perl

 * 2.2.4.05 ADSE13-ExaFEL (Electron Laser)
   * PSANA (https://github.com/lcls-psana)
     * Python (C++ ?)
   * CCTBX (http://cctbx.github.io)
     * I/O: Python, HDF5
   * LUNUS (https://github.com/mewall/lunus)
     * Python
   * M-TIP

### 3 National Security applications
 * 2.2.5.01 ADNN01-ASC ATDM-LANL
 * 2.2.5.02 ADNN02-ASC ATDM-LLNL
 * 2.2.5.03 ADNN03-ASC ATDM-SNL

### 6 Co-design projects aimed at developing crosscutting capabilities
 * 2.2.6.01 ADCD504-Proxy Applications
 * 2.2.6.02 ADCD502-Applications Assessment

 * 2.2.6.03 ADCD01-CODAR (Data Analysis and Reduction)
		https://CODARcode/cheetah (Python)
		https://github.com/CODARcode/PerformanceVisualization (Database)
		https://github.com/CODARcode/savanna (ADIOS)
		https://github.com/CODARcode/Z-checker (HDF5/NetCDF)
		https://sdrbench.github.io

 * 2.2.6.04 ADCD02-COPA (Particle Applications)
   * ?
		
 * 2.2.6.05 ADCD03-AMREX (Block-structured AMR)
   * https://github.com/AMReX-Codes/amrex
   * I/O: C++, text, POSIX

 * 2.2.6.06 ADCD04-CEED (Unstructured Mesh)
   * https://github.com/CEED
   * https://ceed.exascaleproject.org
   * 5 applications: Nek5000, MFEM, MAGMA, OCCA, PUMI

 * 2.2.6.07 ADCD05-ExaGraph (graph problem)
   * Kokkos https://github.com/kokkos/kokkos-kernels
   * Trilinos https://github.com/trilinos/Trilinos
   * HIPMCL https://bitbucket.org/azadcse/hipmcl/

 * 2.2.6.08 ADCD08-ExaLearn (Machine Learning)
   * ?

