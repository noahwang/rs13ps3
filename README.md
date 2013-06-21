rs13ps3
=======

Recognition System class assignment - Problem Set 3

The removal of a noise signal from a waveform will be the subject of this problem set. You will write software to open and process comma-separated value (CSV) encoded signal data. 

Problem 3.1)

Download a ZIP file that contains three CSV files from the following location:

http://www.k2.t.u-tokyo.ac.jp/members/carson/rs13/ps3.zip

Check that the waveforms are usable by plotting all three waveforms in one figure.

Problem 3.2)

The CSV files provide an original waveform (original.csv), an approximately Gaussian noise waveform (pseudo-gaussian-noise.csv), and a waveform with arbitrary noise (arbitrary-noise.csv). Compare the waveforms and compute their similarity (using, for instance, covariance), providing results in table form.

Problem 3.3)

Determine with what accuracy you can reconstruct the original waveform from the noisy CSV data. You may use a procedure of your choice and are free to use existing libraries. This procedure could be an algorithm like Kalman Filtering, Particle Filtering, or Compressive Sensing.
