# Medical-Waste-4.0-Dataset
This dataset was acquired in the framework of the Medical Waste Treating 4.0 funded by the Tuscany Region.

The dataset aims to be a valuable resource for devising and testing computer vision methods for the primary sorting of medical waste.

Acquisition device: OAK-D camera with tech specs available here https://docs.luxonis.com/projects/hardware/en/latest/pages/BW1098OAK.html

Each sample consists of three images, namely an RGB image and a stereo pair:

RGB: 1920 x 1080
Grayscale: 640 x 400 

Example:
timestamp.jpg = RGB Image
timestamp_r.png = Right image in the stereo pair
timestamp_l.png = Left image in the stereo pair

The full dataset is divided into two sub-datasets, named Dataset $\mathcal{A}$ and Dataset $\mathcal{B}$.
- Dataset $\mathcal{A}$ is the main dataset that can be used to train, validate and test machine learning algorithms for medical waste classification. It was originally released in zenodo: https://doi.org/10.5281/zenodo.7643416
- Dataset $\mathcal{B}$ was acquired  on different days from the dataset $\mathcal{A}$, in order to avoid any possible duplicated images between datasets $\mathcal{A}$ and $\mathcal{B}$. It can be used for additional final test.

Categories:
- gauze
- glove pair latex
- glove pair nitrile
- glove pair surgery
- glove single latex
- glove single nitrile
- glove single surgery
- medical cap
- medical glasses
- shoe cover pair
- shoe cover single
- test tube
- urine bag

 Citation
If you use this dataset in your research, please cite:

```
@inproceedings{bruno2023medical,
  title={Medical Waste Sorting: a computer vision approach for assisted primary sorting},
  author={Bruno, Antonio and Caudai, Claudia and Leone, Giuseppe Riccardo and Martinelli, Massimo and Moroni, Davide and Crotti, F},
  booktitle={2023 IEEE International Conference on Acoustics, Speech, and Signal Processing Workshops (ICASSPW)},
  pages={1--5},
  year={2023},
  organization={IEEE}
  doi = {10.1109/ICASSPW59220.2023.10193520}
}
```
