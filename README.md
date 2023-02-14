<p align="center">
  <img src="assets/Julia_for_HPC_ECP.png" alt="Julia for HPC ECP Community Days" width="600" />
</p>

# Julia for HPC Tutorial and BoF at the 2023 ECP Community Days

**Note:** Recordings will be available soon

To engage with the Julia for HPC community, go to: https://julialang.org/community/ -- recommended meetings/calls:
1. Julia HPC working group: Monthly call, Discord, [HPC Pages](https://juliaparallel.org/)
2. Triage meeting

## BoF: Developing end-to-end workflows for Exascale Systems in Julia

Please fill out the [Julia for HPC survey](https://forms.gle/Cbo5778tZySuYiE59)

### Lightning talks

1. Valentin Churavy: Update from the Ecosystem (e.g Preferences, MPI CUDA, TTFX, Weak Dependencies etc)
2. William Godoy: Curated content from the community – eg [Our paper](https://arxiv.org/abs/2211.02740), JuliaCon HPC workshop, SC BoF
3. Michel Schanen: State of Julia on Sunspot and Crusher

### Discussion

1. What versions should we ask for from the sysadmin
2. What effort was needed to get going on each system (e.g. do you need undocumented module/environment invocations?)
3. NERSC user support experiences
4. How julia makes HPC more accessible
5. How are ECP projects going (eg. portability, productivity, regrets etc?)
6. Julia on HPC: Packaging applications into sysimage / PkgCompiler
7. Porting from X to Julia (X=Fortran …)
8. Performance / compiler optimization (eg. `--check-bounds=no`)
9. Julia + MPI experiences (e.g. installing, community support, diagnosing problems) https://juliaparallel.org/tutorials/preferences/ 
10. Julia as a workflow language (FluxRM.jl?)


## Tutorial: Julia programming for Exascale

1. Introduction to Julia (Johannes Blaschke). [Code](https://github.com/JBlaschke/HPC-Julia) and [Presentation](https://jblaschke.github.io/HPC-Julia/presentation_index.html#/)
2. Hands-on example of a MPI+X application (William Godoy, and Pedro Valero) [Code](https://github.com/ornladios/ADIOS2-Examples/tree/master/source/julia/GrayScott.jl)
3. Automatic Differentiation of a 2D Burgers code (Michel Schanen, slides: [DiffDistPDE.pdf](DiffDistPDE.pdf), code: [Burgers.jl](https://github.com/DJ4Earth/Burgers.jl))
4. Combining an HPC application with AI (Youngsung Kim, and Hyun Kang)
5. How to write device portable Code (Valentin Churavy) [Slides](https://github.com/JuliaParallel/julia-ecp-community-days-2023/blob/main/presentations/02_07_23%20--%20How%20to%20write%20device%20portable%20Code.pdf)
