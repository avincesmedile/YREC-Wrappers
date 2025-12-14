# Additional YREC Tools (`alternate_tools/`)
## Overview

This repository contains the more advanced Python tools for preparing, updating, and managing YREC (Yale Rotating Stellar Evolution Code) model grids. These scripts help you:

- Update YREC namelist files with custom parameters.
- Generate grids of stellar models over mass and metallicity ([Fe/H]).
- Load and manipulate YREC model tracks for analysis.
- Run YREC in batch mode for multiple models efficiently.

These tools are ideal for research-level stellar modeling, especially when creating large grids or testing multiple physical assumptions.

---

## Directory Structure

alternate_tools/
- `yrec_parallel.py`          : Run YREC batches in parallel (one mass per node).
- `read_output_files.py`     : Load YREC model tracks, store, and last into Python. Alternative to load_yrec_tracks
- `change_nml.py`           : Update YREC namelist files, does not require a command prompt. Updates all filepaths in a directory to native user filepaths when downloading YREC.
- `README.md`               : This documentation.


