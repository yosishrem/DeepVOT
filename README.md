# DeepVOT - Automatic Measurement of Voice Onset Time (VOT) using Deep Recurrent Neural Networks
Voice onset time (VOT) is defined as the time difference between the onset of the burst and the onset of voicing. 
When voicing begins preceding the burst, the stop is called prevoiced, and the VOT is negative. 
When voicing begins following the burst the VOT is positive. 
While most of the work on automatic measurement of VOT has focused on positive VOT mostly evident in American English, in many languages the VOT can be negative. 
We propose an algorithm that estimates if the stop is prevoiced, and measures either positive or negative VOT, respectively.  More specifically, the input to the algorithm is a speech segment of an arbitrary length containing a single stop consonant, and the output is the time of the burst onset, the duration of the burst, and the time of the prevoicing onset with a confidence. Manually labeled data is used to train a recurrent neural network that can model the dynamic temporal behavior of the input signal, and outputs the events' onset and duration. Results suggest that the proposed algorithm is superior to the current state-of-the-art both in terms of the VOT measurement and in terms of prevoicing detection.
