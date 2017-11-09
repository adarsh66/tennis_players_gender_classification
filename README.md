# Tennis Players Gender Classification

This notebook will aim to take the Inception V3 network and train it to discriminate between Male and Female tennis players' images. These images will be taken from Google image search results and only images more than 180x180 are considered.
Discriminating genders in sports players is a difficult problem due to the different image styles, camera angles and sporting movements. We would hope that the network is able to learn the textural changes in the clothing between the male and female players to make its decisions.

#TODO : place a link for the data source

Results:
 - With a dataset of only 500 images, able to achieve 80% accuracy on the test set
 - More data will undoubtedly improve performance.
 - Visualized the way the network is making decisions by employing some crude image masking techniques and observing the resulting output.
 - There is discussion in place to see if cropping images to just the face portion will help boost recognition further. Although identifying face location within the image is a separate challenge on its own.

 
