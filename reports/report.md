The top 3 detector and descriptor combinations I personally would prefer are:

1. Detector: FAST, Decsriptor: BRISK
2. Detector: FAST, Decsriptor: BRIEF
3. Detector: FAST, Decsriptor: ORB

FAST had been observed to give more keypoints and thus on applying the subsequent descriptors as mentioned above, more matched keypoints could also be obtained. Along with this, it also took less time to process as compared to others.

Whereas if we are just comparing the processing time, then HARRIS also performed well but gave least number of keypoints and thus I didn't find it reliable approach.


