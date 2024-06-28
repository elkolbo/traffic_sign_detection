## This repository provides the architecture to detect red round traffic signs in images and classify them
Developers: Lorenz Kolb, Moritz Huhle

The procedure and all the steps can be closely examined in the notebook complete.ipynb.

Roughly the pipeline is made from 2 parts: <br>
Part 1:<br>
  preprocess the images and find red circles using the Hough Transform<br>
Part 2: <br>
  feed the subimages of the found circles into a trained classifier to determine the traffic sign visible in the given picture

