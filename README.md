# Brest-Cancer-Type-Classification

This Machine Learning model was build with the objective to better predict if a Brest Cancer is either Benign or Malignant, based on many features. To train and test the model, it was used the 'Breast Cancer Wisconsin (Diagnostic) Database', as a source, containing information for every register of:
        - radius (mean of distances from center to points on the perimeter)
        - texture (standard deviation of gray-scale values)
        - perimeter
        - area
        - smoothness (local variation in radius lengths)
        - compactness (perimeter^2 / area - 1.0)
        - concavity (severity of concave portions of the contour)
        - concave points (number of concave portions of the contour)
        - symmetry
        - fractal dimension ("coastline approximation" - 1)
        
To build the model, it was performed the PCA - to reduce the model into 2 componets (so we could see the labels in a 2D scatterplot) - and the SVM classifier - to predict the Cancer class (1: Malignant | 0: Benign)

<figure>
    <center><img src = "https://upload.wikimedia.org/wikipedia/commons/7/72/SVM_margin.png", height="125" width="250"></center>
</figure>

<figure>
    <center><img src="https://i.stack.imgur.com/O740D.png", height="250" width="500"></center>
</figure>

Image sources: Wikipedia [SVM] and i.stack [PCA]
