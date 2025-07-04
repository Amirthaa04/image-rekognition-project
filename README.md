# 🖼️ Image Recognition on Amazon S3 Using AWS Rekognition

This project demonstrates how to perform object and scene detection on images stored in an Amazon S3 bucket using Amazon Rekognition and `boto3` in Python. Run directly from AWS CloudShell — no EC2 or local setup required!

## 📌 Features
- Connects to AWS Rekognition via `boto3`
- Detects up to 10 object labels per image
- Parses nested instances and parent relationships
- Executed securely in CloudShell with IAM permissions

## 🔧 Tech Stack
- Python 3.9+
- AWS CloudShell
- Amazon S3
- Amazon Rekognition
- IAM (for secure access)

## 🚀 Getting Started

1. **Create/Upload an image** to an S3 bucket:
   - Region: same as your Rekognition client
   - Example: `image1.jpg` in `image-rekognition-project-04072025`

2. **Launch AWS CloudShell**

3. **Clone this repository** or manually create `rekognition.py`:
   ```bash
   git clone https://github.com/your-username/image-rekognition-project.git
   cd image-rekognition-project
4. **Set values in rekognition.py:**
    photo = 'image1.jpg'
    bucket = 'Your_Bucket_Name'
5.**Run the script:**
   python3 rekognition.py

   

🛡️ IAM Permissions Required
Attach these AWS-managed policies to your IAM user or role:

AmazonRekognitionFullAccess
AmazonS3ReadOnlyAccess

📋 Sample Output
![image](https://github.com/user-attachments/assets/a233ac66-9bdb-4ed4-92f2-8f36d317764d)
