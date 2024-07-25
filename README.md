## Dual-Branch CNN Incorporating Multiscale SVD Profile for PolSAR Image Classification

[Nabajyoti Das](https://scholar.google.com/citations?user=SbFjohMAAAAJ&hl=en), [Amos Bortiew](https://www.researchgate.net/profile/Amos-Bortiew), [Swarnajyoti Patra](https://agnigarh.tezu.ernet.in/~swpatra/index.html), and [Lorenzo Bruzzone](https://webapps.unitn.it/du/en/Persona/PER0004714/Curriculum#:~:text=Bruzzone%20is%20the%20founder%20and,machine%20learning%20and%20pattern%20recognition.)

### Datasets

The model was tested with three real PolSAR datasets:

* **Flevoland AIRSAR dataset:** Fully Polarimetric SAR, image size: $750\times1024$ pixels, ground truth: 15 land cover classes
* **San Francisco AIRSAR dataset:** Fully Polarimetric SAR, image size: $900\times1024$ pixels, ground truth: 5 land cover classes
* **San Francisco RADARSAT-2 dataset:** Fully Polarimetric SAR, image size: $1380\times1800$ pixels, ground truth: 5 land cover classes

### Model Architecture

The dual-branch CNN architecture consists of two parallel branches:

* **Branch 1:** Processes the multiscale SVD profile(MSVDP).
* **Branch 2:** Processes the polarimetric features.


### Additional Notes

* Refer to the code comments for detailed function descriptions.
