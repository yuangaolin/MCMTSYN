# MCMTSYN
MCMTSYN: Predicting anticancer drugs synergy via cross-modal feature fusion and multi-task learning.
The MCMTSYN method mainly involves three key points. The first point is to integrate and utilize multi-omics data to effectively characterize cell lines. The second point is that MCMTSYN, through its cross-modal cross-fusion module, captures the potential mutual information that may exist between two heterogeneous modalities, cell lines and drugs. The third point is to integrate the two tasks of anticancer drug synergy prediction and anticancer drug sensitivity prediction, improve the expressiveness of the model by sharing parameters and optimizing loss, and promote the prediction ability of anticancer drug synergy.

## Requirements

* python=3.7 or higher 
*  pytorch=1.8.1 or higher
*  numpy
*  sklearn
*  pandas

## Running the Code
*Create a "data" folder and store the data downloaded from the "Tag" of this repository in the "data" folder.

* Run the AEtrain.py first to pre-train a drug encoder and a cell line encoder.

* MCMTSYNtrain.py used to train the model.



