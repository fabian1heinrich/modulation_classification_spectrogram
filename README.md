# modulation classification spectrogram
this repository contains the code for a modulation classification that is based on the spectrogram of the time series of a signal. therefore we transform our original issue to an cv issues with increased complexity since a spectrogram is handled as an image with much higher dimension

### ideas
- reduce dimensionality of spectrogram by masking out certain areas
- using more advancde rnn archictures compared to lstms
- optimizing spectrogram calculation to speed up the whole pipeline