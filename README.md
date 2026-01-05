# pv~ for PureData

A simple phase vocoder for PureData, providing real-time pitch shifting.

Based on the C++ library [Signalsmith Stretch](https://github.com/Signalsmith-Audio/signalsmith-stretch).

## Usage
```
[adc~]
|
[pv~ cents]  # cents: pitch shift in hundredths of a semitone
|
[dac~]
```
