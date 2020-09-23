# Real-time-human-eye-detection
Main python library used is OpenCV. It uses machine learning algorithms to search for faces within a picture. Because faces are so complicated, there isn’t one simple test that will tell you if it found a face or not. This approach uses Cascade classifier. A Haar Cascade is essentially a classifier which is used to detect the object for which it has been trained for, from the source (here for face and eyes). A Haar-like feature considers adjacent rectangular regions at a specific location in a detection window, sums up the pixel intensities in each region and calculates the difference between these sums. This difference is used to categorize the subsections of an image. For example, in human face images, the region of eyes is darker than cheeks. So, when detecting an object in an image, the window of target size is moved over the input image and for each subsection of the image the Haar-like feature is calculated. This difference is then compared to the learned threshold that separates the object from non-objects. For detecting eyes more accurately, blob detection algorithm is used. In computer vision, blob detection method is aimed at detecting regions in a digital image that differ in properties, like brightness or color, compared to surrounding regions. Informally, a blob is a region of an image in which some properties are constant or approximately constant, all the points in a blob are often considered in some sense to be similar to be almost like one another.
