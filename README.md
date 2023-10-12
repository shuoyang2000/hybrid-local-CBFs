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
These libraries have been bundled with the repository as changes have had to be made to make them compatible.

# Reproduce the Results
Run the two ipynb files in `examples` folder.

# TODO
Refactor dubins car example