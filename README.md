# SoftGNSS for My Studies

**UNOFFICIAL! READ BEFORE FORK/CLONE!**

I am studying GNSS topics for my thesis. To get used to the overall GNSS basically, I am studying on it, sometimes making changes on the files.

When I feel completely ready on it with perfect sample data. I will make a basic guide for the usage of anyone.

**The sample signal I use:** GPSdata-DiscreteComponents-fs38_192-if9_55.bin ([Download](https://drive.google.com/file/d/1tqEsyAGX6abRyv4urq49ptkkf_r2MoR9/view?usp=share_link))

## Improvement(s)
1. Solved the error below with a workaround. (*calculatePseudoranges.m* error)
    ```
    Expected one output from a curly brace or dot indexing expression, but there were 8 results.
    Error in calculatePseudoranges (line 67)
            trackResults(channelNr).absoluteSample(msOfTheSignal(channelNr)) / samplesPerCode;
    Error in postNavigation (line 156)
        navSolutions.channel.rawP(:, currMeasNr) = calculatePseudoranges(...
            trackResults(channelNr).absoluteSample(msOfTheSignal(channelNr)) / samplesPerCode;
    ```


## Collaboration
Collaborations are welcome. Please send me a message about it.
