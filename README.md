# Unsup2
UnsupAlgs

Species identification is an important part of conservation efforts. This project attempts to use the Birds bones and living habits data set to label species based on skeletal features.The idea is that birds skeletal structure should be varied enough to allow for easy and simple identification. The data labels are:

SW :Swimming
W :Wading
T :Terrestrial
R :Raptors
P :Scansorial_birds
SO :Singing Birds

These will be how the data is clustered. No two bird species are exactly alike, so given enough data points are provided this should work.

Since the data set seemed very distinct (An emu is much larger than say a chicken) K means felt like a very good choice. The basic idea here is: K centroids will be chosen, the model will be fit and when the centroids stop moving is when we are done. Even though K means is supposed to be non-deterministic, more often than not a pidgeon and emu should not be clustered together.
