# Salt Dome Interpretation Tool

At the Center for Energy and Geo Processing (CeGP), we are conducting research on the automation of seismic interpretation for post-migrated seismic volumes using advanced pattern recognition, machine learning, and human vision system models. The Graphical User Interface (GUI) for visualizing, testing, and benchmarking various algorithms for salt dome delineation is now available to download. This version (v1.0) of the GUI compares different salt dome delineation algorithms.

We seek your feedback and suggestions. You are also welcome to send your salt dome delineation algorithms to include in the GUI for benchmarking, and comparison with other algorithms.

![](https://github.com/olivesgatech/salt_interpretation_tool/blob/master/figures/snapshot.png)

## Dataset
We have used the real seismic dataset acquired from the Netherland’s offshore, F3 block in the North Sea, whose size is 24 x 16 km^2 [1]. The seismic volume that contains the salt dome structure has an inline number ranging from #151 to #501, a crossline number ranging from #401 to #701, and a time direction ranging from 1,300ms to 1,848ms sampled every 4ms.

Salient Features of the GUI:
* Comparison of different salt dome delineation algorithms, which include
  * 2D GoT by Wang et al. [2]
  * 3D GoT by Shafiq et al. [3]
  * 3D Sobel filter by Aqrawi et al. [4]
  * Texture attributes by Berthelot et al. [5]
  * Codebook by Amin et al. [6]
  * Active Contour by Shafiq et al. [7]
* Visualizing 3D Salt dome
* Objective evaluation of the results of different salt dome delineation algorithms
* Interactive salt dome boundary correction

### References 
[1] https://opendtect.org/osr/pmwiki.php/Main/NetherlandsOffshoreF3BlockComplete4GB

[2] Z. Wang, T. Hegazy, Z. Long, and G. AlRegib, “Noise-robust Detection and Tracking of Salt Domes in Post-migrated Volumes Using Texture, Tensors, and Subspace Learning,” Geophysics, 80(6), WD101-WD116 "2"

[3]: M. Shafiq, Z. Wang, A. Amin, T. Hegazy, M. Deriche, and G. AlRegib, “Detection of salt-dome boundary surfaces in migrated seismic volumes using gradient of textures,” Expanded Abstracts of the SEG 85th Annual Meeting, pp. 1811-1815, New Orleans, Louisiana, Oct. 18-23, 2015.

[4]: A. A. Aqrawi, T. H. Boe, and S. Barros, “Detecting salt domes using a dip guided 3D Sobel seismic attribute,” in Expanded Abstracts of the SEG 81st Annual Meeting, 2011.

[5]: A. Berthelot, A. HS Solberg, and L. J. Gelius, “Texture attributes for detection of salt,” Journal of Applied Geophysics, vol. 88, pp. 52–69, 2013

[6] Amin, Asjad, and Mohamed Deriche. "Salt-dome detection using a codebook-based learning model." IEEE Geoscience and Remote Sensing Letters 13.11 (2016): 1636-1640.

[7]: M. Shafiq, Z. Wang, and G. AlRegib, “Seismic interpretation of migrated data Using edge-based geodesic active contours,” in Proc. IEEE Global Conf. on Signal and Information Processing (GlobalSIP), Orlando, Florida, Dec. 14-16, 2015.
Request

## Downlaod
In order to receive the download link, please fill out this [FORM](https://goo.gl/forms/Ggzu3JqPeLTvOiLr2) to submit your information and agree the conditions of use. These information will be kept confidential and will not be released to anybody outside the CeGP administration team.
