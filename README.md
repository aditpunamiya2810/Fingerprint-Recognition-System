This a group project for signal and image processing class in college. 
We have made a basic fingerprint recognition system using image processing techniques.

Step 1:
Enhance the image using 
Contrast Limited Adaptive Histogram Equalization (CLAHE)
Thresholding
Skeletonization
Noise Removal

Step 2:
Feature extraction

Keypoint Detection: We employ Harris corner detection.

Descriptor Generation: The ORB (Oriented FAST and Rotated BRIEF) algorithm.

Step 3:
Matching the fingerprints

Matching fingerprints involves comparing the extracted features of a given fingerprint against a database of known fingerprints to identify potential matches:-

Descriptor Matching: We employ the Brute-Force Matcher (BFMatcher) with the Hamming distance metric.

Matching Criteria


