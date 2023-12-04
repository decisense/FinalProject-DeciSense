# Optimizing Sustainability through Corrosion Detection in Construction (OSC)

## Project Description
Project ini merupkan salah satu inovasi dalam mendeteksi korosi pada alat & bahan konstruksi. Kebermanfaatan dari teknologi ini jika diterapkan adalah dapat melindungi dan memperpanjang umur pakai alat dan bahan konstruksi dengan memberikan solusi deteksi yang akurat dan dapat diandalkan. Project <b>Instance Segmentation</b> ini dibangun dengan menggunakan <a href="https://github.com/ultralytics/yolov5">YOLOv5</a> sebagai arsitektur dasar dengan modifikasi menggunakan trasnformer. 

Please describe your Startup Campus final project here. You may should your <b>model architecture</b> in JPEG or GIF.

## Contributor
| Full Name | Affiliation | Email | LinkedIn | Role |
| --- | --- | --- | --- | --- |
| Aditya Rizki W | Institut Teknologi Telkom Purwokerto | arizkiwidyanto@gmail.com | [link](https://linkedin.com/in/aditya-rizki-widyanto-393233237) | Team Lead |
| Teuku Muharam.R | Universitas Sebelas Maret | tmr.irzi1533@gmail.com | [link](https://linkedin.com/in/teukumuharamr) | Team Member |
| M. Fadhil Akmal B. P. | Universitas Tadulako | fadhilpaloloang10@gmail.com | [link](https://linkedin.com/in/fadhil-akmal) |Team Member |
| Dina Lestari | Universitas Siliwangi | lestaridina096@gmail.com | [link](https://linkedin.com/in/dina-lestari-a983b9218) | Team Member |
| Katleya Aishya Z | Universitas Airlangga | katleya.aishyaa@gmail.com | [link](https://linkedin.com/in/katleya-aishya-zaldi) | Team Member |
| Nur Indah Y | Universitas Lambung Mangkurat | nurindahyunianti750@gmail.com | [link](https://linkedin.com/in/nur-indah-yunianti) | Team Member |
| Rika Sahriana | Startup Campus, AI Track | rikasahriana28@gmail.com | [link](https://linkedin.com/in/rikasahriana) | Supervisor |

## Setup
### Prerequisite Packages (Dependencies)
- numpy == 1.23.5
- matplotlib == 3.7.1
- torch == 2.1.0+cu118

### Environment
| Colab | Spec |
| --- | --- |
| CPU | Tesla V100-SXM2-16GB |
| GPU | AMD Radeon Graphics |
| ROM | 512 GB SSD |
| RAM | 8 GB |
| OS | Windows 10 |

## Dataset
Dataset yang digunakan dalam project merupakan data gambar korosi yang diambil dari roboflow. Dataset ini hanya terdiri dari 1 class (Corrosion) dengan pembagian sebagai berikut:
- Train: 2506 image
- Valid: 202 image
- Test: 98 image

- Link: [Dataset](https://universe.roboflow.com/cawilcorrosionsegmentation/instance-corrosion/dataset/2)

## Results
### Model Performance

#### 1. Metrics

| model | epoch | learning_rate | batch_size | optimizer | Precision | Recall | mAP50 | mAP90 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| YOLOv5m-seg | 300 |  0.01 | 8 | SGD | 79.2% | 62.8% | 68.3% | 0.453 |
| YOLOv5m-seg + Tr + LayerNormalization | 300 | 0.01 | 8 | SGD | 82.1% | 62.4% | 70.6% | 0.459 |

#### 2. Training/Validation Curve
Insert an image regarding your training and evaluation performances (especially their losses). The aim is to assess whether your model is fit, overfit, or underfit.
 
### Testing
Show some implementations (demos) of this model. Show **at least 10 images** of how your model performs on the testing data.

## Supporting Documents
### Presentation Deck
- Link: [DeckPresentation](https://www.canva.com/design/DAF1YB7t8Q8/6fdAcb7snmG49KSVpEWHig/edit)

### Business Model Canvas
Provide a screenshot of your Business Model Canvas (BMC). Give some explanations, if necessary.

### Short Video
Provide a link to your short video, that should includes the project background and how it works.
- Link: [Drive](https://drive.google.com/file/d/16cCMMrxlAwGHLqBxjvRePQ5L6SpDYAiK/view?usp=drivesdk)

## References
Papers and GitHub repositories that support this final project.
- Link: https://arxiv.org/abs/2010.11929
- Link: https://ieeexplore.ieee.org/document/9874020

## License
For academic and non-commercial use only.

## Acknowledgement
This project entitled <b>"Optimizing Sustainability through Corrosion Detection in Construction (OSC)"</b> is supported and funded by Startup Campus Indonesia and Indonesian Ministry of Education and Culture through the "**Kampus Merdeka: Magang dan Studi Independen Bersertifikasi (MSIB)**" program.
