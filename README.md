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

After successfully created a bucket
-> Next we need to upload audio file into the bucket.

![Screenshot (475)](https://user-images.githubusercontent.com/91054688/232242816-ed6e1ace-9d12-4ab6-b30b-66a3c0250e66.png)
![Screenshot (476)](https://user-images.githubusercontent.com/91054688/232242833-5a286a01-5fc4-499f-a024-e62965a4ad3d.png)
![Screenshot (477)](https://user-images.githubusercontent.com/91054688/232242838-6b83ec76-726f-49c1-9144-a64f439c2014.png)

Now we need to create a job in Amazon Transcribe service

![Screenshot (474)](https://user-images.githubusercontent.com/91054688/232242919-a8cae606-0c0b-4fb4-8904-c2063788f83d.png)
![Screenshot (478)](https://user-images.githubusercontent.com/91054688/232242931-e202eabd-fde5-4859-b4b2-26c53f38a4a1.png)
![Screenshot (479)](https://user-images.githubusercontent.com/91054688/232242988-ebcc5e9a-f1a0-42bb-a888-28d8a1513418.png)

successfully created a job .

![Screenshot (480)](https://user-images.githubusercontent.com/91054688/232243033-68388ecf-5ca3-4c1e-8ab7-2a9d3b3b203c.png)

successfully audio file converted into text file.
In conclusion, Amazon Transcribe is a reliable and efficient solution for transcribing your audio to text. It's user-friendly, customizable, and supports a wide range of audio formats and languages. By using AWS services, you can save time and resources and gain valuable insights from your audio content. Try it out and see how it can benefit your business or personal projects.

Thank you...

