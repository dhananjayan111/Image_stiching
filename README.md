# Image_stiching
project_submission

In panorama.py
1. Compute the sift-key points and descriptors for left and right images.
2. Compute distances between every descriptor in one image and every descriptor in the other image.
3. Select the top best matches for each descriptor of an image.
4. Run RANSAC to estimate homography.
5. Warp to align for stitching.
6. Finally stitch them together.

In final.ipynb
1. imported video and converted it into frames and stored it in a folder.
2. Imported all the images of truck appearace using length of video.
3.Imported the panorama module created.
4. Finally stitched the image. 
5. Due to lack of key points less than 4 in body of the truck. I have submitted the bst result I got.
