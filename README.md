In this paper, we investigate the performance of the visionbased American Sign Language (ASL) recognition system employing the
Long Short-Term Memory (LSTM) classifier. MediaPipe introduced by
Google [15] is used to obtain posture landmarks where a custom dataset
has been created and used for the experimental study. Ten sign words
were considered from the ASL: hello, iloveyou, thanks, google, internet,
jogging, house, book, drink and drive. The proposed system is benchmarked with the classifier employing the k Nearest Neighbor (kNN) with
Dynamic Time Warping (DTW). The proposed system yields 92% accuracy comparable to those obtained from the classifier using the kNN
with DTW whose accuracy is equal to 75%. In addition, we evaluated
the robustness of the proposed system by corrupting the landmarks with
zero-mean additive white Gaussian noise whose standard deviation (SD)
ranges from 0.001 to 1. The proposed system maintains accuracy beyond
90% when noise SD is less than or equal to 0.15 but exhibits significant
performance drop when the noise SD is beyond this value.
