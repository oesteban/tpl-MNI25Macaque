# MNI Macaque Atlas

## Overview
We present an unbiased standard macaque monkey magnetic resonance imaging template brain volume that offers a common stereotaxic reference frame to localize anatomical and functional information in an organized and reliable way for comparison across individual macaque monkeys and studies.

We have used MRI volumes from a group of 25 normal adult macaque monkeys (18 Macaca fascicularis, 7 Macaca mulatta) to create the individual atlas. Thus, the atlas does not rely on the anatomy of a single subject, but instead depends on nonlinear normalization of numerous macaque brains mapped to an average template image that is faithful to the location of anatomical structures.

## Methods
The macaque average atlas is comprised of 25 T1-weighted MRIs of normal young adult macaque brains (18 Macaca fascicularis, 7 Macaca mulatta). This atlas is not based on a single subject but instead is an average constructed from the averaged position, orientation and scale from all the individual subjects and is representative of both the intensities and spatial positioning of anatomical structures.

Image pre-processing included non-uniform intensity correction and intensity normalization with a range of 0–100. One monkey out of 25 macaques was chosen to serve as the initial target. Registration of the remaining 24 macaque monkeys to the chosen was initialized using manually identified homologous landmarks that included the center of the left and right eyeballs, the anterior commissure (AC), the posterior apex of the 4th ventricle as seen in a midline sagittal image, the most anterior aspect of the genu and the most posterior aspect of the corpus callosum, and the intersection of the central sulcus with the longitudinal fissure.

The ANIMAL algorithm (Collins et al., 1995) was used to estimate the nonlinear deformation field that best aligned local neighbourhoods between each monkey volume and the average target. The nonlinear registration began by estimating a grid with 3mm spacing. Each MRI volume was resampled through the recovered nonlinear transformation, and all resampled volumes were averaged together on a voxel-by-voxel basis to create a mean intensity image. To remove the potential bias of the initial atlas used for registration, all deformation fields were average together and then the average deformation was inverted and then applied to the mean intensity volume to create a spatially unbiased, average intensity atlas volume that is used as the target for the next registration step. This process was repeated twice, using a grid spacing of 2mm, and then 1mm.

## Publications
The following publications should be referenced when using this atlas:

* M. Mallar Chakravarty, Stephen Frey, and D. Louis Collins. ‘Digital atlas of the monkey brain in stereotactic co-ordinates’ in The Rhesus Monkey Brain In Stereotactic Coordinates, G Paxinos, XF Huang, M Petrides, AW Toga. Elsevier, March 2008.
* Stephen Frey, Deepak N. Pandya, M. Mallar Chakravarty, Michael Petrides, D. Louis Collins. ‘MNI monkey space’, Neuroscience Research, Volume 65, Supplement 1, pg S130, 2009.
* Stephen Frey, Deepak N. Pandya, M. Mallar Chakravarty, Lara Bailey, Michael Petrides, D. Louis Collins. ‘An MRI based average macaque monkey stereotaxic atlas and space (MNI monkey space)’, NeuroImage (2011), doi:10.1016/j.neuroimage.2011.01.040
 
