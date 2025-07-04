# 🖼️ Image Recognition on Amazon S3 Using AWS Rekognition

This project demonstrates how to perform object and scene detection on images stored in an Amazon S3 bucket using **Amazon Rekognition** and **boto3** in Python. It runs entirely from **AWS CloudShell** — no EC2 or local setup required!

---

## 📌 Features

- Connects to Amazon Rekognition via `boto3`
- Detects up to 10 object labels per image
- Parses bounding boxes, confidence scores, and parent labels
- Executed securely in CloudShell with IAM-based access

---

## 🔧 Tech Stack

| Component         | Description                          |
|------------------|--------------------------------------|
| Python 3.9+       | Scripting language                   |
| AWS CloudShell    | Terminal-based development environment |
| Amazon S3         | Image storage                        |
| Amazon Rekognition | Image analysis and labeling         |
| IAM               | Secure access control                |

---

## 🏗️ Architecture Diagram

![image](https://github.com/user-attachments/assets/db28c2aa-a624-494c-a8a7-c8a0720c4a60)




---

## 🚀 Getting Started

1. **Upload your image** to an S3 bucket  
   Example: `image1.jpg` in `image-rekognition-project-04072025`

2. **Launch CloudShell** from the AWS Console

3. **Clone this repository or create manually**
   ```bash
   git clone https://github.com/your-username/image-rekognition-project.git
   cd image-rekognition-project

4. **Update rekognition.py**
   photo = 'image1.jpg'
   bucket = 'image-rekognition-project-04072025'
   
5.**Run the script**
   python3 rekognition.py


## 🛡️ IAM Permissions Required
Attach these policies to your IAM user or role:
- AmazonRekognitionFullAccess
- AmazonS3ReadOnlyAccess

## 📋 Sample Output
![image](https://github.com/user-attachments/assets/a7130165-8623-4004-ba28-a0ed6af30f3d)

  
