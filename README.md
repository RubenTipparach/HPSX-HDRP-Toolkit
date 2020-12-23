# HPSX-HDRP-Toolkit
The haunted psx HDRP volume shader.

This shader is based on: https://github.com/o-l-l-i/OrderedDitheringMonoChannel

It adds a few extra features such as limiting number of steps in each RGB channel and seperation amount.

<img src="https://raw.githubusercontent.com/RubenTipparach/HPSX-HDRP-Toolkit/main/images/hallway.jpg" alt="Your image title" width="500"/>

<img src="https://raw.githubusercontent.com/RubenTipparach/HPSX-HDRP-Toolkit/main/images/plant.jpg" alt="Your image title" width="500"/>



# Migration
Migration to newer or older versions of HDRP (at least 2019 LTS should work) is a little wierd since the feature was somewhat removed from the pipeline(I think). However, it is as simple as adding to the `afterPostProcessCustomPostProcesses:` line with the custom volume pass.

![migration](images/migration.png)


