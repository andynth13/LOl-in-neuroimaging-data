# LOl-in-neuroimaging-data

# Project Goal
* Apply and understanding another method to reduce dimension of the data which is Linear Optimal Low-Rank (LOL) projection method [1].
* Process images data that can compatible and be able to run well with our current computer configuration.
* Compare LOL with other dimensionality reduction methods.


# Result summary
* Computational resource optimization is crucial. Due to our limit computing resources, project involved resizing (from 193x256x256 to 64x64x64) and flattening high-dimensional neuroimaging data. The whole workflow being test by different hardware set up among team members and the best efficiency was chosen:
    * CPU 12th Gen i7 12800H 2.40Ghz
    * RAM 32GB
* Without any tuning, PCA proven to be the best option to reduce the dimension but still maintain good accuracy of the models (both LDA and RandomForest classifiers).
* LOL method showed competitive performance with PCA, but the results suggested that LOL might be better suited for different data configurations or when computational resources allow for more extensive processing.
* 3D CNN demonstrated poorer performance compared to traditional classification techniques, likely due to the limited training data available.


# Reference
[1] Paper source: Vogelstein, J. T., Bridgeford, E. W., Tang, M., Zheng, D., Douville, C., Burns, R., & Maggioni, M. (2021). Supervised dimensionality reduction for big data. Nature communications, 12(1), 2872.

Special thanks to Eric W.B. and Joshua V. for your recommendation to help us achieve the completion of this project.

[2] Data source: https://neurodata.io/mri/ (brain image)

# Contributors (by alphabetical order)

* An Nguyen
* Andy Nguyen
* Dawn Dang
* Huan Le van


