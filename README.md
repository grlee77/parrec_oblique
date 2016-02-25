Philips MRI test data
=====================

This repository contains several 2D scans acquired on a 3T Philips Ingenia MR
scanner running software version 5.1.9 and exported by the vendor-supplied
tools at the scanner console to .PAR/.REC, NIFTI and NIFTI_FSL formats.  These
are intended to serve as a reference for sorting out the image affines when
developing third-party tools to convert between image formats.

2D slices were acquired in each of the 3 primary image orientations:

- transverse (files named `*trans_0_0_0*`)
- sagittal (files named `*sag_0_0_0*`)
- coronal (files named `*cor_0_0_0*`)

It also contains versions that are triply oblique with angles offset from each
of these image planes.  The angles of rotation are 5, 15, and 30 degrees about
the AP, RL, and FH axes respectively.  The direction of the rotations is
right handed for the thumb pointing toward P, L or H in each case.

- transverse (files named `*trans_5_15_30*`)
- sagittal (files named `*sag_5_15_30*`)
- coronal (files named `*cor_5_15_30*`)

License
=======

The data in this repository is made available in the public domain via
a Creative Commons CCZero 1.0 License/Waiver:
https://creativecommons.org/publicdomain/zero/1.0/
