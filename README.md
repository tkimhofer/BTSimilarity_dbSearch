# Fast spectral similarity clustering

This algorithm calculates the similarity between spectra based on binary trees. The latter are constructed using y-weighted x-values, e.g. using 1D NMR spectra (x: ppm, y: intensity) or chromatograms such as SIC's or TIC's from LC-MS (x: scan time, y: ion counts).

Provided functions for calculating and visualising i) individual binary trees and ii) hierarchical agglomerative clusterings.

Algorithm adopted from DOI: 10.1016/S0003-2670(00)80840-5

The functions works for 1D NMR data as well as for chromatograms, e.g. SIC's or TIC's generated with LC-MS.


![](pseudAlgo.png)
