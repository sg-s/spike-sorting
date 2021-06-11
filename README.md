## Spike sorting packages


| Name | Platform | Notes | 
| ---- | -------- | --------- |
| [kilosort](https://github.com/MouseLand/Kilosort) | MATLAB | + drift correction, GPU | 
| [mountainsort]() | python |  | 
| [wave_clus](https://github.com/csn-le/wave_clus) | MATLAB | wavelets + super-paramagnetic clustering |
| [FAST](https://github.com/Olveczky-Lab/FAST) | F# | super-paramagnetic clustering, long term stabilization | 
| [spikeinterface](https://github.com/SpikeInterface/spikeinterface) | python |  | 
| [spykes](https://github.com/KordingLab/spykes) | python | |
| [klusta](https://github.com/kwikteam/klusta)  | python | automatic spike sorting |
| [nerds](https://github.com/KordingLab/nerds) | MATLAB | blind deconv. |
| [BinaryPursuitSpikeSorting](https://github.com/pillowlab/BinaryPursuitSpikeSorting) | MATLAB |  find synchronous spikes using Binary Pursuit  | 
|  [mksort](https://github.com/ripple-neuro/mksort) | MATLAB | | 
| [crabsort](https://githib.com/sg-s/crabsort) | MATLAB | neural nets + active learning | 
|  [moksm](https://github.com/aecker/moksm) | | Kalman filters + EM| 
| [bpsort](https://github.com/aecker/bpsort)  |  |  binary pursuit |
| [LDA-GMM_SpikeSort](https://github.com/mrezak/LDA-GMM_SpikeSort) | | discrminative subspace learning | 



## Fundamentals

spike sorting is typically a blind source seperation problem


## Historical computational workflows 

### preprocessing

1. High pass filter to remove LFP
2. Spatial filtering/whiteneing to maybe remove extinisic noise 
3. Thresholding to identify putative spikes 
4. Cut out snippets 

### Dim Red

1. PCA/t-SNE

### Clustering

1. Density-based clsutering 

### Template Matching 

This is to solve the problem of mulitple neurons firing at the same time, and their waveforms superimposing. The waveforms typically summate because the extracellular medium is mostly conductive. 

## Datasets to play with

Allen Brain Obs. Neuropixels dataset 


## Talks

1. [Alessio Buccino - spikeinterface](https://www.youtube.com/watch?v=p_dd52IzOGo)
