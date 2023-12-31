# ICSE-2024-FSE
The artifacts for this paper are placed into two main folders:
-  `Theme 1: Retrospective Analysis`: The data and code used for the retrospective analysis is within the `Theme1` folder, please examine the `README` for that.
-  `Theme 2: Prospective Analysis`: The data and code used for the Prospective analysis is within the `Theme1` folder, please examine the `README` for that.


The following tables repeated in the `Theme1` and `Theme2` folders for your convience.

We use the external [HFTorrent dataset](https://zenodo.org/record/7556031) version 1.0.0. 

## Theme 1 - Index
|Data|Data Description|
|----|-----------------|
|[`/issue-downloader`](/Theme1/issue-downloader/)| This folder contains the scripts that we used to download and filter GitHub issues|
|[`/issue-data`](/Theme1/issue-data/)| This folder contains the GitHub issues that we downloaded and filtered for this analysis. We study a subset of the filtered issues for our failure analysis.|
|[`/pilot-study`](/Theme1/pilot-study/)| This folder contains the results of the pilot study we conduct. (§4.2.2)|
|[`onnx_opset_diff.json`](/Theme1/onnx_opset_diff.json)| This json file contains the raw data used to create Figure 6a.|
|[`FWs and DL compilers data.xlsx`](/Theme1/FWs%20and%20DL%20compilers%20data.xlsx)| This excel file contains the data we collect for frameworks and deep learning compilers. (§2.1.2)|
|[`FailureAnalysis.xlsx`](/Theme1/FailureAnalysis.xlsx)| This excel file contains our failure analysis data.|
|[`data_analysis.ipynb`](/Theme1/data_analysis.ipynb)| This jupyter notebook contains our analysis of our data. It generates Tables 4, 5, 6, and 7. Additionally it generates Figures 6a and 6b.|

## Theme 2 - Index

### Theme 2 Data - Real Models
|File/Folder|Data Description|
|----|-----------------|
|[`pytorch_conv_results.json`](/Theme2/real-models/pytorch_conv_results.json)| This JSON file the PyTorch testing data.|
|[`tf2onnx_conv_results.json`](/Theme2/real-models/tf2onnx_conv_results.json)| This JSON file the TensorFlow testing data.|
|[`analyze.ipynb`](/Theme2/real-models/analyze.ipynb)| This is the notebook used to analyse the data mentioned above. Results from this contribute to Table 8.|
|[`convert.py`](/Theme2/real-models/convert.py)| This is the script we used to convert the PyTorch and TensorFlow models.|
|[`/download`](/Theme2/real-models/download/)| This folder contains the scripts to download the HuggingFace models from the git-bare clones in [HFTorrent dataset](https://zenodo.org/record/7556031).|

###  Theme 2 Data - Synthetic Models
|File/Folder|Data Description|
|----|-----------------|
|[`random_tf.json`](/Theme2/synthetic-models/random_tf.json)| This JSON file contains the processed data for the TensorFlow synthetic model test.|
|[`random_tf_con.json`](/Theme2/synthetic-models/random_tf_con.json)| This JSON file contains the processed data for the TensorFlow constrained synthetic model test.|
|[`random_pt.json`](/Theme2/synthetic-models/random_pt.json)| This JSON file contains the processed data for the PyTorch synthetic model test.|
|[`random_pt_con.json`](/Theme2/synthetic-models/random_pt_con.json)| This JSON file contains the processed data for the PyTorch constrained synthetic model test.|
|[`data_analysis.ipynb`](/Theme2/synthetic-models/data_analysis.ipynb)| This is the notebook used to analyse the data mentioned above. Results from this contribute to Table 8.|
|[`test.ipynb`](/Theme2/synthetic-models/test.ipynb)| This is the notebook used to test the synthetically generated models.|
|[`/nnsmith`](/Theme2/synthetic-models/nnsmith/)| This folder the modified NNSmith used to generate models.|
