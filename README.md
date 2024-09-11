![unet_multiclass drawio](https://github.com/user-attachments/assets/39ef20a8-2250-4275-83b9-c8c0d0b6f6fb)
# MRI-Brain-Region-Segmentation
U-Net for brain region Segmentation Task 

Segmenting brain regions from MRI images is a complex yet crucial task in many areas of medical research, including neurology, neuroscience, and medical imaging. This segmentation aims to identify and measure various cerebral structures, which is of fundamental importance for applications such as clinical research, surgical planning, monitoring neurological diseases, and many others.

In our work, our focus is on extracting meaningful features from lesions associated with multiple sclerosis (MS). To achieve this, it is imperative to undertake a preliminary step of segmenting the cerebral regions responsible for specific functions. Among these regions, we can mention the frontal lobe, occipital lobe, parietal lobe, temporal lobe, cerebellum, and others.

However, this task can be challenging due to anatomical variations among individuals, image artifacts, noise, image resolution, and other factors. It is often necessary to perform correction for magnetic field intensity inhomogeneities to improve image quality. Additionally, obtaining high-quality MRI data can be a challenge, especially for 3D data. While there are many public MRI databases available, they may not always cover all segmentation needs.

In this context, several software tools are available for MRI image segmentation, such as FreeSurfer, FSL (FMRIB Software Library), and SPM (Statistical Parametric Mapping). However, these tools also have limitations and drawbacks, including complexity for beginners, sensitivity to configuration parameters, high computational power requirements for processing high-resolution 3D MRI images, and difficulties in segmenting 2D data with a limited number of slices.

Moreover, segmenting 2D MRI images can be problematic when the number of MRI slices is limited, as is the case with our patients with MS. Therefore, we have chosen to use the U-Net architecture for brain region segmentation. This architecture is specifically designed for image segmentation, particularly medical images, and has demonstrated exceptional performance in many fields, making it an essential reference for our work.
