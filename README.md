<h1 align="center">EWasteNet</h1>
<h3 align="center" >A Two-Stream DeiT Approach for E-Waste Classification</h3>

<h2>Introduction</h2>

<p>This repository contains the E-Waste Vision Dataset and EWasteNet, the classifier made of Two-Stream DeiT for classifying the images. 
    </p>

<p>The project utilizes a deep learning model to analyze images of e-waste items and classify them into specific
    categories, such as smartphones, laptops, printers, etc. The Two-Stream DeiT architecture combines spatial and
    temporal information to improve the accuracy of classification.</p>

<h2>Dataset</h2>

<p>To train and evaluate the EWasteNet model, we have used a carefully curated dataset of 1058 e-waste images. The
    dataset consists of various types of e-waste items, each labeled with the corresponding class/category.</p>


<h2>Model Architecture</h2>

<p>The EWasteNet model is based on the Two-Stream DeiT (Vision Transformer) architecture. It combines two streams. The first steam of EWasteNet passes through a sobel operator that detects the edges while the second steam is directed through an ASPP (Atrous Spatial Pyramid Pooling) and CBAM attention block were multi-scale contextual information is captured.</p>
<img align="center" height="800px" width="500px" src="https://raw.githubusercontent.com/NifulIslam/EWasteNet-A-Two-Stream-DeiT-Approach-for-E-Waste-Classification/main/images/twoDeiT.png" alt="Dataset Image">


<h2>Results</h2>

<p>The performance of the EWasteNet model is evaluated using various metrics, including the Receiver Operating
    Characteristic (ROC) curve and the confusion matrix.</p>

<img align="center" src="https://raw.githubusercontent.com/NifulIslam/EWasteNet-A-Two-Stream-DeiT-Approach-for-E-Waste-Classification/main/images/ROC.png" alt="ROC Curve">

<p>The ROC curve illustrates the trade-off between true positive rate and false positive rate at various
    classification thresholds. A higher area under the curve (AUC) indicates better model performance.</p>

<img align="center" src="https://raw.githubusercontent.com/NifulIslam/EWasteNet-A-Two-Stream-DeiT-Approach-for-E-Waste-Classification/main/images/confusion-matrix.png" alt="Confusion Matrix">

<p>The confusion matrix provides a detailed breakdown of the model's predictions and the ground truth labels. It
    helps us understand the distribution of correct and incorrect predictions across different classes.</p>

<h2>Getting Started</h2>

<p>To get started with the EWasteNet project, follow these steps:</p>

<ol>
    <li>Clone the repository:</li>
</ol>

<pre><code>git clone https://github.com/NifulIslam/EWasteNet-A-Two-Stream-DeiT-Approach-for-E-Waste-Classification
</code></pre>

<ol start="2">
    <li>Install the necessary dependencies:</li>
</ol>

<pre><code>pip install -r requirements.txt</code></pre>

<ol start="3">
    <li>Download or prepare your own dataset of e-waste images. Ensure that the dataset is properly labeled with
        class/category information.</li>
    <li>Preprocess the dataset as per your requirements (e.g., resize images, split into training and testing sets).
    </li>
    <li>Train the EWasteNet model using the provided scripts and configuration files.</li>
    <li>Evaluate the model's performance using the test set and visualize the results.</li>
</ol>

<p>Feel free to explore the codebase and experiment with different configurations to improve the model's
    performance.</p>

<h2>Contributing</h2>

<p>Contributions to the EWasteNet project are welcome! If you find any issues or have ideas for improvements, please
    open an issue or submit a pull request. We appreciate your feedback and contributions.</p>



Note: Some of the images are missing in this repository. We will update this soon
