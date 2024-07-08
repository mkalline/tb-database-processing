# tb-database-processing
## TB Database processing

In this repository we list all the programs used in the paper with DOI: https://doi.org/10.1016/j.compbiomed.2024.108167.

## TB Database request

The image databases used can be requested at https://tbimages.ufam.edu.br. First, users are asked to fill in and send a form to the owners, who authorize access by sending a download link. The use is restrict to academic research.

## File description 
<b>File:</b> SemanticSegmentation_DepthWiseSeparableConvolution.ipynb<br>
<b>Goal:</b> File implemented in Google Colaboratory to train the semantic segmentation model using encoder with depth-wise separable convolution layers and calculate the metrics<br>
<b>Database:</b> DDS3 with mosaic images

<b>File:</b> SemanticSegmentation_ChannelAttentionMechanism.ipynb<br>
<b>Goal:</b> File implemented in Google Colaboratory to train the semantic segmentation model using encoder with channel attention mechanism and calculate the metrics<br>
<b>Database:</b> DDS3 with mosaic images

<b>File:</b> SemanticSegmentation_U-Net.ipynb<br>
<b>Goal:</b> File implemented in Google Colaboratory to train the semantic segmentation model using U-Net architecture and calculate the metrics<br>
<b>Database:</b> DDS3 with mosaic images

<b>File:</b> Predictions_Diagnoses.ipynb<br>
<b>Goal:</b> Count bacilli in all 50 sets of 5 diagnoses. For each diagnosis, a file is created in the “predictions” folder. This file contains a list of the total bacilli found in each set of the corresponding diagnosis. For example, the file 'predictions/predictions_NEGATIVE.txt' will have a list of 50 values corresponding to the total number of bacilli in each set of NEGATIVE diagnosis.<br>
<b>Database:</b> DDS4 with digital fields
