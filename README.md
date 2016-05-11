# Ambisonic Toolkit Kernels

A set of impulse response files used for convolution-based encoders and decoders.



## Using Kernels with Reaper

The kernels are already included as part of the [ATK for Reaper](http://ambisonictoolkit.github.io/download/reaper/) install, and there is no need to download and install the kernels seperately.



## Using Kernels with SuperCollider


Install [ATK for SuperCollider](http://ambisonictoolkit.github.io/download/supercollider/). Launch SuperCollider3, and run the following code:


```
ATK Kernel Installation
(
// Create ATK support directory
// Place unzipped kernels in the directory opened  

Atk.createUserSupportDir;
Atk.openUserSupportDir;
)
```

If ATK for SuperCollider has been correctly installed, the above code will open the ATK's user support directory. Place the downloaded kernels here.

If you use ATK for Reaper as well as ATK for SuperCollider on Mac OSX, the kernels are shared between the two programs, and they will reside in the same location. We do not expect this to cause any problems.


## Working with this repository

The sound files in this repository are versioned using [Git Large File Storage (LFS)](https://git-lfs.github.com/). You will need to install LFS in order to clone and work on this repository. The repository is set up to use LFS with all WAV files.
