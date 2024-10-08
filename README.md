# QDL-CMFD: a Quality-independent and Deep Learning-based Copy-Move image Forgery Detection method

One of the prevalent methods of image forgery is copy-move, where one or more regions of an image are duplicated and moved elsewhere in the image. It is usually difficult to detect this type of forgery due to the similarity of the copied and forged areas. Also, forgers perform pre-processing and/or post-processing operations on the manipulated regions to make it even more difficult to detect. In this study, an image quality-independent method based on deep learning approach, termed QDL-CMFD, is presented for detecting this type of forgery. QDL-CMFD utilizes generative adversarial networks for image quality enhancement, and convolutional neural networks (CNN) for forgery detection. A tailored dual-branch CNN architecture is introduced consisting of two subnetworks, namely a manipulation detection subnetwork and a similarity detection subnetwork. Accordingly, unlike most existing methods, QDL-CMFD is able to simultaneous detection of several forged areas, as well as determining the source and target of the forgery. Also, QDL-CMFD is robust against various pre-processing/post-processing attacks. It shows excellent performance for detecting low-quality forged images and small areas. Experiments conducted on the CASIA and CoMoFoD benchmark datasets confirm that QDL-CMFD performs significantly better than the competitors.


## Diagram of the proposed method:

![Method](https://github.com/M-Hashemzadeh/QDL-CMFD/assets/59253242/cfb7fa4a-2574-49ea-a11f-4024d16881cb)

## Train/Inference

You may use QDL-CMFD.ipynb, inference is as simple as:

# Example
pred = QDLCMFD_decoder(model, image)

## Condition and terms to use any sources of this project (Codes, Datasets, etc.):

1) Please cite the following paper:

M. Aria, M. Hashemzadeh, and N. Farajzadeh, "QDL-CMFD: A Quality-independent and deep Learning-based Copy-Move image forgery detection method," Neurocomputing, vol. 511, pp. 213-236, 2022/10/28/ 2022, doi: https://doi.org/10.1016/j.neucom.2022.09.017.

2) Please do not distribute the database or source codes to others without the authorization from authors.

Authors’ Emails: mehrad.aria[at]shirazu.ac.ir (M. Aria) & hashemzadeh[at]azaruniv.ac.ir (M. Hashemzadeh).
