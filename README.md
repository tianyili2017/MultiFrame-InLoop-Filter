# MultiFrame-InLoop-Filter
Source codes for training and evaluating the multi-frame in-loop filter (MIF) approach. [1]

## 1. Training codes

## 2. Test codes

The aforementioned folder <font color="#0040c0">*HM-16.5_MIF-Net*</font> contains both encoder and decoder for the proposed MIF approach. All source codes are stored in its sub-folder <font color="#0040c0">*HM-16.5_MIF-Net/source*</font>, and the compiled executable files are in <font color="#0040c0">*HM-16.5_MIF-Net/bin*</font>. 

In total, eight C++ files have been modified, as below.

 - source/App/TAppDecoder/TAppDecTop.cpp
 - source/App/TAppEncoder/TAppEncTop.cpp
 - source/Lib/TLibDecoder/TDecSlice.cpp
 - source/Lib/TLibDecoder/TDecGop.cpp
 - source/Lib/TLibDecoder/TDecGop.h
 - source/Lib/TLibEncoder/TEncSlice.cpp
 - source/Lib/TLibEncoder/TEncGOP.cpp
 - source/Lib/TLibEncoder/TEncGOP.h

To run the codec, please refer to file <font color="#0040c0">*HM-16.5_MIF-Net/bin/README.md*</font>.

Below is an example when the encoder is running.

![](example_encoder.png)

## References

[1] Tianyi Li, Mai Xu, Ce Zhu, Ren Yang, Zulin Wang and Zhenyu Guan, “A Deep Learning Approach for Multi-Frame In-Loop Filter of HEVC,” IEEE TIP, vol. 28, no. 11, pp. 5663-5678, Nov. 2019.
