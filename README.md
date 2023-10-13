# Hybrid Local CBFs
Code for "Safe Control Synthesis for Hybrid Systems through  Local Control Barrier Functions"

# Installation
The implementation has been tested with `Python 3.10` under `Ubuntu 22.04`.

Linux, Mac or WSL is recommended to run this repository since [hj_reachability](https://github.com/StanfordASL/hj_reachability) is required and it is built on [jax](https://github.com/google/jax).

1. Clone this repo.
2. Install requirements:
   ```
   pip install -r requirements.txt
   ```

Note that some supplementary libraries are included locally (note the `lib` folder).
These libraries have been bundled with the repository as changes have had to be made to make them adaptded to our problem.

# Reproduce the Results
Run the two ipynb files in `examples` folder.

# Dataset
The computed dataset can be found [here](https://drive.google.com/drive/folders/1ZGvMqZVJg_lxspZMIe7sEDrZ-tsU6R60?usp=sharing)

# Related projects
This project is inspired by a number of related projects, including:
- [refineCBF: Control Barrier Function refinement with HJ Reachability](https://github.com/UCSD-SASLab/refineCBF)
- [cbf_opt: Control Barrier Function toolbox](https://github.com/stonkens/cbf_opt)
- [hj_reachability: Hamilton-Jacobi reachability analysis in JAX](https://github.com/StanfordASL/hj_reachability)

# TODO
- Implement a `hybrid_local_cbf` package and make it generalizable enough