# Digital Signal Processing Applications

Digital Signal Processing Projects involving Dual-Tone Multi-Frequency (DTMF) Signal Decoding, Binary Communication Transceiver Design with Alphabet Analysis, Linear Prediction of Stock Market Averages and Adaptive Equalization from 

## Introduction

1. This Project is originally from ECE 4271 in Georgia Tech
2. This Project involves topics like Dual-Tone Multi-Frequency (DTMF) Signal Decoding, Binary Communication Transceiver Design with Alphabet Analysis, Linear Prediction of Stock Market Averages and Adaptive Equalization

## Dual-Tone Multi-Frequency (DTMF) Signal Decoding
1. Use Highpass Filter to filter out low frequency dial and telephone tones
2. Use Goertzel's algorithm in both low band and high band signal
3. Experiment and Explore Input size and DFT size in Goertzel's algorithm
4. Evaluate the performance with different SNR level

## Binary Communication Transceiver Design with Alphabet Analysis
#### Part A
1. Generate data for binary communication system
2. Add zero-mean unit variance gaussian noise based on different SNR level
3. Use Matched Filter to estimate data
4. Evaluate the performance and plot BER vs SNR

#### Part B
1. Generate QPSK symbols for encoding and decoding from text files
2. Statistical analysis of QPSK communication

## Linear Prediction of Stock Market Averages
1. Use Dow Jones Industrial Average data
2. Train the model with linear predictor and experiment different orders of linear predictor
3. Evaluate the performance with MSE error and Gain compared with interest-only and omnipotent mode
4. Optimize linear predictor model with different training data and evaluate the results

## Adaptive Equalization
1. Generate QPSK symbols for encoding and decoding from text files
2. Use white-noise only, time-invariant noise and time variant QPSK signals
3. Use LMS adaptive filter to filter noisy QPSK signal
4. Evaluate the performance based on the correctness of output messages

## Contributing

1. Fork
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Source
James H. McClellen, Alan V. Oppenheim, and Ronald W. Schafer. 1997. Computer-Based Exercises for Signal Processing Using MATLAB 5 (1st ed.). Prentice Hall PTR, Upper Saddle River, NJ, USA.

## Credits

*Enmao Diao*

## License
The MIT License (MIT)

Copyright (c) [2015] [Enmao Diao]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
