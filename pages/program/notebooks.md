---
layout: page
title: Notebooks
description:
menubar: program
permalink: program/notebooks/
menubar_toc: true
set_last_modified: true
---

Authors of notebooks are expected to upload their notebook to the Zenodo site for 
[USRSE'25 Conference Proceedings](https://zenodo.org/communities/usrse25/records?q=&l=list&p=1&s=10&sort=newest) 
**before** the conference begins.

<a name="n-energy"></a>
## Open Free Energy: An Open Source Ecosystem for Calculating Free Energies

_Alyssa Travitz, Irfan Alibay, Hannah Baumann, David Dotson, James Eastwood, Mike Henry, Josh Horton, Ian Kenney, Iván Pulido, Benjamin Ries, and David Mobley_

Alchemical free energy calculations are integral to state-of-the-art drug discovery pipelines, 
yet the need for domain expertise and reliance on closed-source software remain major barriers 
to their widespread use. The Open Free Energy (OpenFE) project is a pre-competitive 
collaboration between academic and industry partners to develop an ecosystem of extensible 
open-source tools for accessible and reproducible free energy calculations. OpenFE’s ecosystem 
includes Python-based tools for network planning, atom mapping, defining protocols for 
relative and absolute alchemical transformations, simulation execution, and data analysis. We 
will demonstrate how these tools can be used out of the box, adapted, or extended to create 
end-to-end workflows enabling robust free energy calculations at scale.

[Colab notebook](https://colab.research.google.com/github/OpenFreeEnergy/openfe-usrse-demo/blob/main/src/openfe_demo.ipynb)

GitHub repository: [https://github.com/OpenFreeEnergy/openfe-usrse-demo/](https://github.com/OpenFreeEnergy/openfe-usrse-demo/)

Open Free Energy: [https://openfree.energy/](https://openfree.energy/)

------

<a name="n-undate"></a>
## Undate: computing with uncertain and partially-unknown dates

_Rebecca S. Koeser_

This notebook provides a demonstration of the functionality
of the Python library undate (<https://github.com/dh-tech/undate-python/>).

Undate is an ambitious, in-progress effort to develop a
pragmatic Python library for computation and analysis of
temporal information in humanistic and cultural data, with
a particular emphasis on uncertain, incomplete, or
imprecise dates and with support for multiple calendars.

Researchers in the humanities often work with historical or
cultural data, and knowing when particular materials were
created or events happened is important for understanding
the context, interpreting correctly, and determining
relationships and sequencing. However, these kind of
materials rarely have full precision dates with known year,
month, and day. In some contexts, scholars may be happy if
they can determine even just a century based on handwriting
or mentions of historic coins.

Humanistic and cultural data also often includes dates in
different calendars, or even a mix of calendars within the
same project or system. It's important to preserve the
original date and calendar information, but it's also
valuable to convert dates to a standard calendar so they
can be compared and sorted together. `Undate` objects are
calendar aware and calendar explicit, with a default of the
Gregorian calendar. Currently, we support parsing and
calendar conversion for dates in the Hebrew Anno Mundi
calendar and Islamic Hijri calendar.

This notebook demonstrates current use and functionality of
the core Undate and UndateInterval objects, along with some
examples showing use-cases from two projects that fed into
development on undate: Shakespeare and Company Project
(<https://shakespeareandco.princeton.edu/>), and Princeton
Geniza Project (<https://geniza.princeton.edu/>).

Repository URL:
[https://github.com/rlskoeser/undate-notebook-usrse25](https://github.com/rlskoeser/undate-notebook-usrse25)
Git ref: 1.0

------
<a name="n-image"></a>
## Combining TIFF, HDF5, and Zarr into a Single Image File Format

_Mark Kittisopikul_

"Situation: There are 3 competing standards" the last card
of a popular XKCD cartoon ([#927](https://xkcd.com/927/)) might read if applied to
recent microscopy bioimaging formats. TIFF, HDF5, and Zarr
have all been used to store images as part of popular
standards and formats (OME-TIFF, BDV-HDF5, OME-Zarr). The
cartoon humorously points out the tendency to create new
standards while discounting prior efforts. To combat the
proliferation of formats I examine similarities between
TIFF, HDF5, and Zarr shard containers. I then exploit them
to create a combined data container that is simultaneously
a TIFF file, a HDF5 file, and a Zarr version 3 shard
without duplicating the image pixel or volumetric voxel
data. This combined format is compatible with multiple
viewers and image analysis pipelines. Additionally, the
techniques involved provide a path to convert between the
formats with minimal processing or overhead. In practice,
the combined format avoids redundant copies of data while
providing great utility to the microscope user. The
combined format is a great candidate for a microscope
acquisition format as it satisfies both short term needs to
view microscope output in traditional viewers while
integrating into next generation image analysis pipelines.

[https://github.com/mkitti/simple_image_formats/blob/main/header_formats.ipynb](https://github.com/mkitti/simple_image_formats/blob/main/header_formats.ipynb)

------
