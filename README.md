# JEÐ116F Forðafræði jarðhitakerfa / Geothermal Reservoir Physics and Engineering

Computational exercises for JEÐ116F at the University of Iceland, autumn 2026.
Everything runs in Google Colab. Nothing needs to be installed on your own computer.

## Notebooks

| # | Topic | Open |
|---|-------|------|
| 01 | The state and motion of water: enthalpy, boiling, pressure with depth, Darcy flow | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/two-phaseflow/JED116F/blob/main/notebooks/01_state_and_motion_of_water.ipynb) |
| 02 | Well tests: injectivity index, the pressure diffusion equation in code, transmissivity and kh from pressure records (K-37, K-38, NJ-15, Ohaaki) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/two-phaseflow/JED116F/blob/main/notebooks/02_well_tests_pressure_transients.ipynb) |
| 03 | Stored heat and Monte Carlo, heat extraction from fractured rock: the Gringarten model in code, recovery factor, a Cape-type EGS doublet | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/two-phaseflow/JED116F/blob/main/notebooks/03_stored_heat_and_fractured_rock.ipynb) |
| 04 | Lumped models and inverse modelling: tank models in code, misfit and least squares, forecasts (Hoffell, Ahuachapán) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/two-phaseflow/JED116F/blob/main/notebooks/04_lumped_models_inverse.ipynb) |

## How to work with these notebooks

1. Click the Colab badge for the notebook you need.
2. In Colab, choose **File > Save a copy in Drive**. You now have your own copy. Work in that copy, not in the read-only view of the repository.
3. Run the first cell. It installs the water property package `iapws` for the session, which takes about 20 seconds. Colab forgets the installation when the session ends, so run that cell again each time.
4. Cells marked **B** contain gaps written as `___`. Replace them with your own code. A test cell after each one checks your answer.
5. To hand in, use **File > Download > Download .ipynb** and upload that file, together with your written report, to Canvas.

You cannot save changes back into this repository. Your copy in Google Drive is yours alone.

## If you prefer to work locally

```
pip install -r requirements.txt
jupyter lab
```

## Rules on using AI tools

You may use AI tools for error messages, coding approaches, plotting and test cases. You must be able to explain every line you hand in, and you may be asked to do so. Think about what a result should look like before you run a calculation, and say so in your report when the result surprised you.

## Structure

```
notebooks/   exercise notebooks, one per lecture block
data/        data files used by the notebooks
```

## Course

Instructors: Samuel Scott (samuels@hi.is) and Gunnar Gunnarsson.
