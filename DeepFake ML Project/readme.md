# AI/ML Engineer - Digital Forensics and Deepfake Detection

## About the Project

We are excited to share our groundbreaking work in the field of digital forensics, particularly in the automatic detection of face tampering in videos. Our research, which was presented at the WIFS 2018 conference, introduces innovative methodologies to identify hyper-realistic forged videos created using deepfake and Face2Face technologies. Our deep learning approach, encapsulated in two specialized networks, targets the mesoscopic properties of images for high-accuracy detection, achieving more than 98% success in identifying deepfake videos and 95% for Face2Face tampering.

## Responsibilities

- Implement and refine the network architecture outlined in our paper, "MesoNet: a Compact Facial Video Forgery Detection Network."
- Work with both existing datasets and a unique dataset we've compiled from online videos to train and test the networks.
- Enhance the capability of our models to detect face tampering in videos with high accuracy.
- Contribute to the development and optimization of our deep learning models, focusing on ethical AI practices and digital integrity.

## Technical Requirements

- **Python 3.5**
- **Numpy 1.14.2**
- **Keras 2.1.5**

To use the complete pipeline with the face extraction from the videos, you will also need the following libraries:

- **Imageio**
- **FFMPEG**
- **face_recognition**

### Dataset

Aligned face datasets:

| Set        | Size of the forged image class | Size of real image class |
|------------|-------------------------------|--------------------------|
| Training   | 5111                          | 7250                     |
| Validation | 2889                          | 4259                     |

- Training set (~150Mo)
- Validation set (~50Mo)

## Preferred Qualifications

- Experience in digital forensics or a keen interest in exploring this field.
- A background in implementing efficient neural networks that focus on the mesoscopic properties of images.
- Previous work with aligned face datasets and an understanding of the challenges in detecting AI-generated fake videos.

## Project Outcomes

- You will be a key contributor to a project that is at the forefront of addressing the challenges posed by deepfake technology.
- Your work will directly impact the development of tools and methodologies that ensure digital content integrity and authenticity.
- Participation in a project recognized by the prestigious IEEE Workshop on Information Forensics and Security (WIFS 2018).

## Pretrained Models

You can find the pretrained weight in the weights folder. The _DF extension corresponds to a model trained to classify deepfake-generated images and the _F2F to Face2Face-generated images.

## Contributors
- Lakshmi Priya Armugan
- Narendran Asokan
- Karthikeyan Baskaran

## References

Afchar, D., Nozick, V., Yamagishi, J., & Echizen, I. (2018, September). MesoNet: a Compact Facial Video Forgery Detection Network. In IEEE Workshop on Information Forensics and Security, WIFS 2018.

## Credits and Acknowledgments

This project wouldn’t have been possible without the significant contributions of [Darius Afchar](#). Darius, a researcher from École des Ponts Paristech and École Normale Supérieure in France, played a pivotal role in the development of the innovative methodologies that form the core of our digital forensics work. His expertise in deep learning and digital image processing has been invaluable in pushing the boundaries of detecting face tampering in videos.

We extend our deepest gratitude to Darius for his dedication, insight, and pioneering research that have significantly advanced the field of digital forensics and set a new benchmark for the detection of deepfake and Face2Face tampering technologies.

