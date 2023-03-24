# 👁 Diabetic-Retinopathy-Detection 
The model employs a deep learning approach to detect Diabetic Retinopathy. It uses the RESNET architecture pre-trained on the ImageNet dataset and fine-tunes the last layers with a custom CNN architecture to achieve high accuracy. Additionally, to address the problem of class imbalance, the model applies class weights and data augmentation techniques to increase the dataset's diversity and size. The model is evaluated over 10 runs, and the resulting metrics indicate its effectiveness in identifying Diabetic Retinopathy cases.
## Problem Statement
Diabetic Retinopathy (DR) is a common complication of diabetes mellitus, which causes lesions on the retina that effect vision. If it is not detected early, it can lead to blindness. Unfortunately, DR is not a reversible process, and treatment only sustains vision. DR early detection and treatment can significantly reduce the risk of vision loss. The manual diagnosis process of DR retina fundus images by ophthalmologists is time-, effort-, and cost-consuming and prone to misdiagnosis unlike computer-aided diagnosis systems. 

| DR Severity Level        | Lesions                                                                                      |
|--------------------------|----------------------------------------------------------------------------------------------|
| No DR                    | Absent of lesions                                                                            |
| Mild non-proliferative DR | MA only                                                                                      |
| Moderate non-proliferative DR | More than just MA but less than severe DR                                              |
| Severe non-proliferative DR | Any of the following: 
                              * more than 20 intraretinal HM in each of 4 quadrants
                              * definite venous beading in 2+quadrants
                              * Prominent intraretinal microvascular abnormalities in 1+ quadrant
                              * no signs of proliferative DR
                           |
| Proliferative DR          | One or more of the following: vitreous/pre-retinal HM, neovascularization                  |

## 📞 Contact
If you have any questions or issues, please feel free to reach out [Aaryak Garg](https://www.linkedin.com/in/aaryak-garg-7b202b184/) at [aaryak.ug20@nsut.ac.in](aaryak.ug20@nsut.ac.in).
