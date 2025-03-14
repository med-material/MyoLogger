# MyoLogger
200Hz CSV Logging with the Myoband EMG band

Myo.cs has been patched to emit a C# signal:
https://github.com/med-material/MyoLogger/blob/main/Assets/Thalmic%20Myo/Myo/Scripts/Myo.NET/Myo.cs#L41

SampleLogger3.cs listens to the C# event from Myo.cs.
https://github.com/med-material/MyoLogger/blob/main/Assets/SampleLogger3.cs
