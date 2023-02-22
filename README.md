# TUFLOW Ensemble Tool

The TUFLOW Ensemble Tool bulk processes Plot Output (PO) csv files generated by TUFLOW models run for ARR2016 storm ensembles. This tool will determine the critical duration and temporal pattern for each storm, and will also generate box plots for each PO line and storm event.

**Important - Please read the [user manual](https://github.com/hydroEng/tuflow_ensemble/blob/master/USER_MANUAL.md) for help on usage.**
# Download

[Download the latest version here](https://github.com/hydroEng/tuflow_ensemble/releases/). No need to install, just run the .exe file. 

# Screenshots

#### Tool:

<img src="https://github.com/hydroEng/tuflow_ensemble/blob/master/src/assets/screenshot_1.png" alt="TUFLOW Ensemble Tool" width="35%" height="35%">

#### Sample outputs:

Critical storms:

<img src="https://github.com/hydroEng/tuflow_ensemble/blob/master/src/assets/sample_results.png" alt="Sample Results">

Plot:

<img src="https://raw.githubusercontent.com/hydroEng/tuflow_ensemble/master/src/assets/100.0y-%20Max%20Flow%20Location1.png" alt="Sample plot" width="50%" height="50%">


# Reporting Bugs

Please create a github issue if you encounter any bugs or want to make suggestions.

There are some known limitations with the tool at the moment:

- There cannot be more than one critical storm for single duration. This is not likely to happen anyway, but will be fixed in future releases if there is interest.
- Changing the default colour / layout of generated plots is not yet possible.  
- All durations must have the same number of temporal patterns. 
