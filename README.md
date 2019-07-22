# Salt Dome Interpretation Tool

At the [Center for Energy and Geo Processing (CeGP)](https://cegp.ece.gatech.edu/) and at the [OLIVES lab](https://ghassanalregib.com/), we are conducting research on the automation of seismic interpretation for post-migrated seismic volumes using advanced pattern recognition, machine learning, and human vision system models. The Graphical User Interface (GUI) for visualizing, testing, and benchmarking various algorithms for salt dome delineation is now available to download. This version (v1.0) of the GUI compares different salt dome delineation algorithms.

We seek your feedback and suggestions. You are also welcome to send your salt dome delineation algorithms to include in the GUI for benchmarking, and comparison with other algorithms.

![](https://github.com/olivesgatech/salt_interpretation_tool/blob/master/figures/snapshot.png)

## Dataset
We have used the real seismic dataset acquired from the [Netherland’s offshore, F3 block in the North Sea], whose size is 24 x 16 km^2. The seismic volume that contains the salt dome structure has an inline number ranging from #151 to #501, a crossline number ranging from #401 to #701, and a time direction ranging from 1,300ms to 1,848ms sampled every 4ms.

Salient Features of the GUI:
* Comparison of different salt dome delineation algorithms, which include
  * [2D GoT by Wang et al.]
  * [3D GoT by Shafiq et al.]
  * [3D Sobel filter by Aqrawi et al.]
  * [Texture attributes by Berthelot et al.]
  * [Codebook by Amin et al.]
  * [Active Contour by Shafiq et al.]
  
* Visualizing 3D Salt dome
* Objective evaluation of the results of different salt dome delineation algorithms
* Interactive salt dome boundary correction



[Netherland’s offshore, F3 block in the North Sea]: https://opendtect.org/osr/pmwiki.php/Main/NetherlandsOffshoreF3BlockComplete4GB

[2D GoT by Wang et al.]: https://library.seg.org/doi/abs/10.1190/geo2015-0116.1 "Z. Wang, T. Hegazy, Z. Long, and G. AlRegib, “Noise-robust Detection and Tracking of Salt Domes in Post-migrated Volumes Using Texture, Tensors, and Subspace Learning,” Geophysics, 80(6), WD101-WD116"

[3D GoT by Shafiq et al.]: https://library.seg.org/doi/abs/10.1190/segam2015-5927230.1 "M. Shafiq, Z. Wang, A. Amin, T. Hegazy, M. Deriche, and G. AlRegib, “Detection of salt-dome boundary surfaces in migrated seismic volumes using gradient of textures,” Expanded Abstracts of the SEG 85th Annual Meeting, pp. 1811-1815, New Orleans, Louisiana, Oct. 18-23, 2015."

[3D Sobel filter by Aqrawi et al.]: https://library.seg.org/doi/abs/10.1190/1.3627377 "A. A. Aqrawi, T. H. Boe, and S. Barros, “Detecting salt domes using a dip guided 3D Sobel seismic attribute,” in Expanded Abstracts of the SEG 81st Annual Meeting, 2011."

[Texture attributes by Berthelot et al.]: https://www.sciencedirect.com/science/article/pii/S0926985112001632 "A. Berthelot, A. HS Solberg, and L. J. Gelius, “Texture attributes for detection of salt,” Journal of Applied Geophysics, vol. 88, pp. 52–69, 2013"

[Codebook by Amin et al.]: https://ieeexplore.ieee.org/abstract/document/7552570/ "A. Amin and Mohamed Deriche, “Salt-dome detection using a codebook-based learning model,” IEEE Geoscience and Remote Sensing Letters, vol. 13, no. 11, pp. 1636–1640, 2016"

[Active Contour by Shafiq et al.]: https://ieeexplore.ieee.org/abstract/document/7418265/ "M. Shafiq, Z. Wang, and G. AlRegib, “Seismic interpretation of migrated data Using edge-based geodesic active contours,” in Proc. IEEE Global Conf. on Signal and Information Processing (GlobalSIP), Orlando, Florida, Dec. 14-16, 2015."

## Downlaod
In order to receive the download link, please fill out this [FORM](https://goo.gl/forms/Ggzu3JqPeLTvOiLr2) to submit your information and agree the conditions of use. These information will be kept confidential and will not be released to anybody outside the CeGP administration team.
