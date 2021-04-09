# Quark-Gluon-classification
A deep learning model (CNN) build to classify Quark and Gluon using particle images.

# Dataset Description
The dataset was provided by the CERN (2 https://cernbox.cern.ch/index.php/s/hqz8zE7oxyPjvsL). The file name used here is: 'QCDToGGQQ_IMGjet_RH1all_jet0_run0_n36272.test.snappy.parquet' where the 'X_jet' was the input image and 'y' was the target.

- For training:
    - Input: 10,000 images of size 125x125 and 3 channels
    - Target: 10,000 values of 0 or 1

- For validation:
    - Input: 5390 images for size 125x125 and 3 channels
    - Target: 5390 values of 0 or 1

# Model Description
The model and code description is mentioned in the table below:
<table>
    <tr>
        <td>DL Framework</td>
        <td>Keras</td>
    </tr>
        <tr>
        <td>Keras version</td>
        <td>2.4.3</td>
    </tr>    
    <tr>
        <td>Libraries</td>
        <td>Numpy, pandas, pyarrow</td>
    </tr>    
    <tr>
        <td>Pre-trained weights</td>
        <td>Imagenet</td>
    </tr>    
    <tr>
        <td>Activation functions</td>
        <td>ReLU, sigmoid</td>
    </tr>    
    <tr>
        <td>Optimizer</td>
        <td>RMSprop</td>
    </tr>    
    <tr>
        <td>Learning Rate</td>
        <td>0.0001</td>
    </tr>    
    <tr>
        <td>Batch size</td>
        <td>32</td>
    </tr>    
    <tr>
        <td>Epochs</td>
        <td>100</td>
    </tr>    
    <tr>
        <td>Loss function</td>
        <td>Binary Crossentropy</td>
    </tr>  
  <tr>
        <td>Regularizer</td>
        <td>Dropout</td>
    </tr>
    <tr>
        <td>Metrics</td>
        <td>Accuracy</td>
    </tr>    
      
</table>
