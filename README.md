# Time-of-day
This code uses an SVM model to detect time of day from image

This codde classifies into an image into three classes: Day-time, Night-time and Dusk-time.

To run the code, extract the rar file and type in:
python timeofday_implement.py <image_name>
python timeofday_implement.py “image3.png”

Running of this code is based on a pre-learned classifier that is loaded from the folder
“timeofday_pickle”. To relearn the classifier, run timeofday.py

I have used Support Vector Machines to implement this solution, due to limited images
available. However, if a larger dataset is available, deep CNN’s are likely to have a better
performance.
