# PE-3-project


CREATE AN AUDIO TRANSCRIPT TO CONVERT AUDIO FILE TO TEST FILE WITH AMAZON TRANSCRIBE AND AMAZON S3

Hello Everyone!!..I am so excited to share a new article regarding a simple project which was done using Amazon Web Services. This project will explain about how to convert audio file to text by using amazon s3 and amazon transcribe.

Prerequisits:

1.creating a s3 bucket
2.creating a job in amazon Transcribe

Amazon Transcribe:
Amazon Transcribe is a cloud-based automatic speech recognition (ASR) service provided by Amazon Web Services (AWS). It enables developers to add speech-to-text capabilities to their applications, allowing them to transcribe audio recordings into text in real-time or in batch mode.
With Amazon Transcribe, users can transcribe audio files in a variety of formats, including MP3, WAV, and FLAC, among others. The service also supports multiple languages, including English, Spanish, French, German, Japanese, and Mandarin Chinese, among others.

Amazon S3:
Amazon S3 (Simple Storage Service) is a cloud-based object storage service provided by Amazon Web Services (AWS). S3 is designed to store and retrieve any amount of data from anywhere on the web, making it an ideal storage solution for a wide range of applications and use cases.
S3 provides durable, scalable, and secure storage for objects, which can range in size from a few kilobytes to terabytes. The service provides a simple web services interface that can be used to store and retrieve data, and it can be integrated with a variety of other AWS services, such as EC2, Lambda, and CloudFront.
S3 also provides several features such as versioning, lifecycle policies, access controls, encryption, and cross-region replication, which allow users to manage their data effectively and securely. Additionally, S3 can be used to host static websites, and it can be integrated with Amazon Glacier, which is a low-cost archival storage service.

Steps:

->First we need to create a bucket in Amazon s3 Service.

![Screenshot (471)](https://user-images.githubusercontent.com/91054688/232242538-e105eb81-255f-46df-9f36-18b5a52deaf4.png)
![Screenshot (472)](https://user-images.githubusercontent.com/91054688/232242540-4cf1857f-c5f0-4166-956f-7e31e90b2fa7.png)
![Screenshot (473)](https://user-images.githubusercontent.com/91054688/232242542-ad095ba4-0912-415a-a42b-589cc8a88920.png)
![Screenshot (474)](https://user-images.githubusercontent.com/91054688/232242544-801b46b1-65a1-4d2a-9710-d2b6604730d0.png)
![Screenshot (478)](https://user-images.githubusercontent.com/91054688/232242547-c7ff3e16-7f0f-4127-a017-9e7229125d6e.png)
![Screenshot (479)](https://user-images.githubusercontent.com/91054688/232242550-1b5a0451-e1a5-4568-a6da-f067bea390a2.png)
![Screenshot (480)](https://user-images.githubusercontent.com/91054688/232242551-aca2ea54-ee21-419d-abd1-66f9b61ef98f.png)

