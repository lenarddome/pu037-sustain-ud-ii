# pu037 SUSTAIN simulation archive

Dome, L., Edmunds, C.E.R, Wills, A.J. (2021) SUSTAIN captures category learning, recognition, and hippocampal activation in a unidimensional vs information-integration task. **In Proceedings of the 43rd Annual Conference of the Cognitive Science Society.**

This repository is the archival copy of the [OSF repository](https://osf.io/jc9xs/).

## R scripts in model/

`pu037train.R` - Generates a matrix, where each row is one trial presented to
the model and each column contains information about that trial.

`pu037optim.R` - This script contains the procedure used to find the best
fitting parameter for SUSTAIN.

`pu037simulation.R` - This script carries out a simulation with SUSTAIN using
`pu037train()`.

`pu037explore.R` - This script was used to analyse the output of `slpSUSTAIN`.

`recognition/pu037optim_recognition.R` - The script used to find the best
fitting threshold parameter for the recognition scores.


# Data files

`pu037.RData` The original data from Edmunds et al. (2006)
`pu037parameters.RData` Data from the parameter search using DEoptim.
`pu037sims.RData` Simulation data from `pu037simulation.R`
`recognition/pu037test.RData` Test phase performance of SUSTAIN
`recognition/pu037threshold.RData` Data from the parameter search for response
threshold using `recognition/pu037test.RData`
