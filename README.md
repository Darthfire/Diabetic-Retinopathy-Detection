# 👁 Diabetic-Retinopathy-Detection

![DR](https://media.discordapp.net/attachments/891317274936483871/1088950357062844606/WADER_diagrams-Page-8.drawio.png?width=2688&height=934)

## ⚙️ Model
The model employs a deep learning approach to detect Diabetic Retinopathy. It uses the RESNET architecture pre-trained on the ImageNet dataset and fine-tunes the last layers with a custom CNN architecture to achieve high accuracy. Additionally, to address the problem of class imbalance, the model applies class weights and data augmentation techniques to increase the dataset's diversity and size. The model is evaluated over 10 runs, and the resulting metrics indicate its effectiveness in identifying Diabetic Retinopathy cases.
## 🏥 Problem Statement
Diabetic Retinopathy (DR) is a common complication of diabetes mellitus, which causes lesions on the retina that effect vision. If it is not detected early, it can lead to blindness. Unfortunately, DR is not a reversible process, and treatment only sustains vision. DR early detection and treatment can significantly reduce the risk of vision loss. The manual diagnosis process of DR retina fundus images by ophthalmologists is time-, effort-, and cost-consuming and prone to misdiagnosis unlike computer-aided diagnosis systems. 

![TYPES](https://media.discordapp.net/attachments/891317274936483871/1088952522275827782/1-s2.png?width=1160&height=626)

Fig. The DR stages: (a) normal retinal (b) Mild DR, (c) Moderate DR, (d) Severe DR, (e) Proliferative DR,(f) Macular edema

| DR Severity Level              | Lesions                                                                                     |
|--------------------------------|---------------------------------------------------------------------------------------------|
| No DR                          | Absent of lesions                                                                           |
| Mild non-proliferative DR      | MA only                                                                                     |
| Moderate non-proliferative DR  | More than just MA but less than severe DR                                                 |
| Severe non-proliferative DR    | Any of the following: <br> &nbsp;&nbsp;&nbsp;&nbsp;• more than 20 intraretinal HM in each of 4 quadrants <br> &nbsp;&nbsp;&nbsp;&nbsp;• definite venous beading in 2+ quadrants <br> &nbsp;&nbsp;&nbsp;&nbsp;• prominent intraretinal microvascular abnormalities in 1+ quadrant <br> &nbsp;&nbsp;&nbsp;&nbsp;• no signs of proliferative DR |
| Proliferative DR               | One or more of the following: vitreous/pre-retinal HM, neovascularization                 |


## 📞 Contact
If you have any questions or issues, please feel free to reach out [Aaryak Garg](https://www.linkedin.com/in/aaryak-garg-7b202b184/) at [aaryak.ug20@nsut.ac.in](aaryak.ug20@nsut.ac.in).
