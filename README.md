  ## Hi there 👋

  - 🎓 **MPhil in Scientific Computing** @ University of Cambridge
  - 🎓 **BEng Chemical Engineering** @ University College London (UCL)

  ---

  ### 🔭 Current Project

  **[BHInference.jl](https://github.com/ju1s04/BHInference.jl)**: Bayesian inference of black hole parameters using
  general-relativistic ray tracing ([Krang.jl](https://github.com/dominic-chang/Krang.jl)) and probabilistic modelling
  ([Turing.jl](https://turinglang.org/)).

  ---

  ### 🛠️ Open Source Contributions

**[AMReX](https://github.com/AMReX-Codes/amrex)**, a framework for massively parallel, block-structured adaptive mesh refinement (AMR) applications on CPUs and GPUs (CUDA, HIP, SYCL)
- Added `GPU_MIN_BLOCKS` setting to cap register usage via `__launch_bounds__` ([#5980](https://github.com/AMReX-Codes/amrex/pull/5980), ✅ merged)

**[Castro](https://github.com/AMReX-Astro/Castro)**, an AMReX-based code for compressible (radiation and magneto) hydrodynamics in astrophysics. GPU optimisations of the MHD solver, benchmarked on an NVIDIA A100.
- **HLLD Riemann solver:** templated on direction so array indices are compile-time constants, keeping thread-local state in registers instead of local memory. ([#3407](https://github.com/AMReX-Astro/Castro/pull/3407), 🔍 under review)
- **PPM characteristic projection:** computed wave integrals at point of use and merged the left/right projections into one sweep, cutting per-thread temporary storage ([#3406](https://github.com/AMReX-Astro/Castro/pull/3406), 🔍 under review)
- **Eigenvector sparsity:** skipped structural zeros in the MHD eigenvector projection, removing unnecessary products per interface state ([#3408](https://github.com/AMReX-Astro/Castro/pull/3408), 🔍 under review)


 ---

  ### 📚 Previous Work

  - **MPhil Dissertation**: Optimising large systems of equations using GPUs *(74.25%)*, University of Cambridge
  - **Multi-material simulations** using the Ghost Fluid Method *(92%)*, University of Cambridge
  - **Acceleration of CFD using CUDA** *(71%)*, University of Cambridge

  ---

  ### 📖 Key Modules

  - Programming GPUs
  - Parallelisation for HPC (OpenMP, MPI, CUDA)
  - Robotic Systems (COMP00037) *(90%)*

  ---

  ### 📊 GitHub Stats

  ![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ju1s04&layout=compact)

 
<!--
**ju1s04/ju1s04** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
