## Open Source Contest- Student Code-In

### About 

**[Student Code-In](https://scodein.tech) is a global program that helps students grow with Open Source. It is a 2 months long Open-Source initiative which provides you the best platform to improve your skills and abilities by contributing to vast variety of Open Source Projects. In this, all the registered participants would get an exquisite opportunity to interact with the mentors and the Organizing Team.**

<p align="center">
  <kbd><img src="https://github.com/StudentCode-in/Image-Recognition-and-Classification-Device-for-Blind-People/blob/master/images/Student%20Code-In%20logo.jpg" ></kbd>
  </p>

---

## **Project:**

# Image Recognition and Classification Device for Blind People

**Project idea is to implement an image recognition and classification device in their pocket with a camera in spectacles of blind people, so that it can recognize and classify the things(visuals) in front of them. It also helps to identify the people in front of them with the help of face recognition. The classified or recognized image will be converted into speech so that the Blinds can listen and understand what is in front of them with the help of a headset.**

<p align="center">
<kbd><img src=https://github.com/akhilaku/Image-Recognition-and-Classification-Device-for-Blind-People/blob/master/images/Project-Theme.jpg width=800 height=369 /></kbd>
  </p>


**This device will help to identify and classify the things in front of them using Intel Movidius Neural Compute Stick(NCS) with Raspberry Pi-3 and a Pi-Camera.**

<p align="center">
<kbd><img src=https://github.com/akhilaku/Image-Recognition-and-Classification-Device-for-Blind-People/blob/master/images/IMNCS.png width=800 height=369 /></kbd>
  </p>
  
  
**The project is developed till its image recognition and classification process, and I'm under developing its classified image text to  speech process so that Blind people can know what is in front of them through their earphones connected to the device.**
With the help of Intel Movidius NCS we can run any complex pre-trainet Networks in the processors with low processing capability.
This NCS functions as an efficient external processor for performing any complex neural architectures.

**Intel Movidius Neural Compute Stick(NCS)** can be used as an **external GPU** for the systems which cannot support for artificial intelligence based projects.
They are less-cost comparing other GPU's and can be used efficiently for most of the Deep Learning, Machine Learning and Artificial Intelligence Based Projects. 

---

## 🚩  Vision
### Goals of this project:
- **To reduce the difficulties faced by the blind people in their daily life** by creating a device which will tell them what is in front of them(includes identifying the people in front of them using Face recognition)
- **To make the blind people forget about their disabilities.**

---

### Hardware component required for this projects:

- [**Intel Movidius Neural Compute Stick(NCS) 2**](https://software.intel.com/content/www/us/en/develop/hardware/neural-compute-stick.html)
- [**Raspberry pi-3** ](https://www.raspberrypi.org/documentation/)
- [**Raspberry pi-camera**](https://projects.raspberrypi.org/en/projects/getting-started-with-picamera/8)
- **Headset-** Click [here](https://www.hackster.io/youness/connect-bluetooth-headset-to-raspberry-pi-3-a2dp-and-hsp-56ec2f) to see how to connect your headset with Raspberry Pi-3.

### Softwares Requirements:

- **Python**- Click [here](https://www.python.org/downloads/) to download
- **OpenVino Tool Kit**- Click [here](https://software.seek.intel.com/openvino-toolkit?cid=diad&source=hackster&campid=WW_Q2_2020_IoTG-DE_OpenVI%20NO-DA&content=dev-challenge) to download

---

### Getting Started

**1.** Fork [this](https://github.com/StudentCode-in/Image-Recognition-and-Classification-Device-for-Blind-People) repository.
Click on the <a href="https://github.com/StudentCode-in/Image-Recognition-and-Classification-Device-for-Blind-People/"><img src="https://img.icons8.com/ios/24/000000/code-fork.png"></a> symbol at the top right corner.

**2.** Clone the forked repository.

```bash
git clone https://github.com/<your-github-username>/Image-Recognition-and-Classification-Device-for-Blind-People
```

**3.** Navigate to the project directory.

```bash
cd Image-Recognition-and-Classification-Device-for-Blind-People
```

**4.** Create a new branch.

```bash
git checkout -b <your_branch_name>
```

**5.** Make changes in source code.

**6.** Add your changes and commit

```bash
#Add changes to Index
git add .

#Commit to the local repo
git commit -m "<your_commit_message>"
```
**7.** Push your local commits to your repository.

```bash
git push -u origin <your_branch_name>
```
#### Create a Pull-Request(PR) to merge your changes into the original repository(write a simple description about the changes you made)

---

### :bulb: **View the steps below for a quick application:**

**STEPS:**

1. **Step 01:** For using the property of the NCSDK API add (import) the mvnc library.

1. **Step 02:** You can access the Movidius NCS using an API like any other USB device. Also you can use parallel Movidius devices at once if you need more capacity to compute your model. For now, one kit is enough for this application. Select and open process.

1. **Step 03:** We will use a pre-trained GoogleNet model for using a compiled graph file.

1. **Step 04:** We also need to do some pre-processing before loading the image into our Movidius NCS.

1. **Step 05:** Use LoadTensor() to load the image into the Movidius.

1. **Step 06:** Give the input image to the pre-trained model and get the output by using GetResult().

1. **Step 07:** Print the prediction of the model's output and corresponding labels. Here we also display the input image at the same time.

1. **Step 08:** For the last step, we clear and shutdown the Movidius NCS device for using it again.

#### These above steps are for image recognition and classification. After this we have to convert the identified image's text into speech.

---

### The below image shows the simple hardware connection of Intel Movidius NCS-2 and pi-camera with Raspberry Pi-3.

<p align="center">
<kbd><img src=https://github.com/akhilaku/Image-Recognition-and-Classification-Device-for-Blind-People/blob/master/images/hardware%20setting.jpg width=500 height=375 /></kbd>
  </p>
 
---

### :warning:  Issues

Always feel free to **file a new issue** with a respective title and description on the [Image-Recognition-and-Classification-Device-for-Blind-People](https://github.com/StudentCode-in/Image-Recognition-and-Classification-Device-for-Blind-People/issues) repository.

### :handshake:  Contribution

If you have any great ideas which can make this project more better, you can make changes and send me a Pull Request(PR) with a respective title and description on the [Image-Recognition-and-Classification-Device-for-Blind-People](https://github.com/StudentCode-in/Image-Recognition-and-Classification-Device-for-Blind-People) repository, I will definitely review your pull request.

---
  
### Project Admin

| ![](https://github.com/akhilaku/Image-Classifier-using-Intel-Movidius-NCS-2/blob/master/akhildasKs%20(2).jpg) |
| :------------------------: |
| **AKHILDAS KS**  |

[![GitHub followers](https://img.shields.io/github/followers/akhilaku.svg?label=Follow%20@akhilaku&style=social)](https://github.com/akhilaku/) [![Twitter Follow](https://img.shields.io/twitter/follow/KsAkhildas?style=social)](https://twitter.com/KsAkhildas)

[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/akhilaku/)

![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)

---
