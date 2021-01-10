# Pupil-Detection-and-Tracking
Detection of eye pupil live on webcam using opencv

# Different methods are discussed in this project to effectively track the pupil of the eye
Face and eye regions are detected using OpenCV haarcascades.
Blob detectors are being used to track the pupil live.

# Method-1
Detecting Face and eyes on each frame using Haarcascades and using blob detectors within the eye regions to track the pupil.
*Manual threshold setting to adapt for the lighting conditions
*Not effective for Low resolution webcams

# Method-2
Manually selecting the eye regions using OpenCV ROI and tracking the region throughout the frames using opencv object trackers.
Blob datectors are used within the selected regions to detect the pupil
*Manual threshold setting to adapt for the lighting conditions
*Faster than method-1

# Method-3
Detecting face and eyes using Haar cascades in the first few frames.
Track the detected regions using OpenCV object trackers in the next live frames.
*Manual threshold setting to adapt for the lighting conditions
*Faster and accurate method
*Intermediate face and eye detection if the lighting conditions are changed

# Method-4
Detecting face and eyes using Haar cascades in the first few frames.
Track the detected regions using OpenCV object trackers in the next live frames.
*Auto-calcution of threshold to adapt for different lighting conditions
*Faster and accurate method and works satisfaactorily for low resolution webcams
*Intermediate face and eye detection if the lighting conditions are changed

# Method -- xx
To be updated soon
