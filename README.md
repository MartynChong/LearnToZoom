-- ABSTRACT -- 
Within the field of computer vision, countless optimisations have been made to
improve the accuracy of image classifiers. One relatively unexplored area is the role
that zooming can play in helping classifiers identify objects. This project explores
the potential of automated zooming as a preprocessing technique to optimise the
performance of image classification models.
In a small-scale experiment centred around identifying cat images, a preprocessing
pipeline is created to find the optimal crop of images before they are fed into the
ResNet image classifier. Using 100,000 training samples labelled by ResNet itself,
a CNN is trained to determine which crops of an image are optimal to be sent for
classification. The result of the experiment saw that images fed through the pipeline
were classified with a 2% greater Top-1 and 3.3% greater Top-3 accuracy, compared
to ResNet’s performance on the original dataset.
Using a basic pipeline, this project demonstrated that automated selective zooming
can improve performance for image classification problems. This showcases a more
sophisticated zooming technique compared to basic or manual zooming methods,
which has the potential to optimise image classification without requiring significant
manpower and time. With further research and development, automated zooming
could play an important role in advancing the capabilities of image classification
models.
