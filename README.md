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

If you use ATK for Reaper as well as ATK for SuperCollider on Mac OSX, the Kernels are shared between the two programs, and they will reside in the same location. We do not expect this to cause any problems.


## Working with this repository

The sound files in this repository are versioned using [Git Large File Storage (LFS)](https://git-lfs.github.com/). You will need to install LFS in order to clone and work on this repository. The repository is set up to use LFS with all WAV files.

---

## Third Party Notices


### CIPIC HRTF Database (University of California)

V. R. Algazi, R. O. Duda, D. M. Thompson, and C. Avendano, "The CIPIC
HRTF Database," in Proceedings of the 2001 IEEE ASSP Workshop on
Applications of Signal Processing to Audio and Acoustics, New Paltz, NY,
2001.

"The CIPIC HRTF Database - CIPIC International Laboratory." [Online].
Available: http://interface.cipic.ucdavis.edu/sound/hrtf.html.
[Accessed: 07-Jul-2011].

#### CIPIC Notices:

Copyright (c) 2001 The Regents of the University of California.
All Rights Reserved

Disclaimer

THE REGENTS OF THE UNIVERSITY OF CALIFORNIA MAKE NO REPRESENTATION OR
WARRANTIES WITH RESPECT TO THE CONTENTS HEREOF AND SPECIFICALLY DISCLAIM
ANY IMPLIED WARRANTIES OR MERCHANTABILITY OR FITNESS FOR ANY PARTICULAR
PURPOSE.

Further, the Regents of the University of California reserve the right
to revise this software and/or documentation and to make changes from
time to time in the content hereof without obligation of the Regents of
the University of California to notify any person of such revision or
change.

Use of Materials

The Regents of the University of California hereby grant users permission
to reproduce and/or use materials available therein for any purpose-
educational, research or commercial. However, each reproduction of any
part of the materials must include the copyright notice, if it is present.
In addition, as a courtesy, if these materials are used in published
research, this use should be acknowledged in the publication. If these
materials are used in the development of commercial products, the Regents
of the University of California request that written acknowledgment of
such use be sent to:

CIPIC- Center for Image Processing and Integrated Computing University of
California
1 Shields Avenue
Davis, CA 95616-8553

### Listen HRTF Database (IRCAM)

"LISTEN HRTF DATABASE." [Online].
Available: http://recherche.ircam.fr/equipes/salles/listen/.
[Accessed: 07-Jul-2011].

#### IRCAM Notices:

Copyright (c) 2002 IRCAM (Institut de Recherche et Coordination
Acoustique/Musique). All Rights Reserved


Use of Materials

The Listen database is public and available for any use. We would however
appreciate an acknowledgment of the database somewhere in the description
of your work (e.g. paper) or in your development.

Contacts:

Olivier Warusfel, 
Room Acoustics Team, IRCAM
1, place Igor Stravinsky
75004 PARIS, France
