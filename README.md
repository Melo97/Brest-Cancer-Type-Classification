# Brest-Cancer-Type-Classification

This Machine Learning model was build with the objective to better predict if a Brest Cancer is either Benign or Malignant, based on many features. To train and test the model, it was used the 'Breast Cancer Wisconsin (Diagnostic) Database', as a source, containing information for every register of: <br>
        - radius (mean of distances from center to points on the perimeter) <br>
        - texture (standard deviation of gray-scale values) <br>
        - perimeter <br>
        - area <br>
        - smoothness (local variation in radius lengths) <br>
        - compactness (perimeter^2 / area - 1.0) <br>
        - concavity (severity of concave portions of the contour) <br>
        - concave points (number of concave portions of the contour) <br>
        - symmetry <br>
        - fractal dimension ("coastline approximation" - 1) <br>
<br>
To build the model, it was performed the PCA - to reduce the model into 2 componets (so we could see the labels in a 2D scatterplot) - and the SVM classifier - to predict the Cancer class (1: Malignant | 0: Benign)<br><br>

<figure>
    <center><img src = "https://upload.wikimedia.org/wikipedia/commons/7/72/SVM_margin.png"></center>
</figure>
<br>
Image sources: Wikipedia [SVM]
