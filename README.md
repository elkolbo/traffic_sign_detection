## This repository provides the architecture to detect red round traffic signs in images and classify them
Developers: Lorenz Kolb, Moritz Huhle

The procedure and all the steps can be closely examined in the notebook complete.ipynb.
Roughly the pipeloine is made from 2 parts: 
Part 1:
  preprocess the images and find red circled using the Hough Transform
Part 2: 
  feed the subimages of the found circles into a trained classifier to determine the traffig sign visible in the picture

