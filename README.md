# GoGo-Audio: Text to Audio Converter
It is a cloud-based serverless application that converts text to speech using a natural-sounding speech synthesizer. 
The application offers a simple user interface that receives text in a variety of languages and converts it to audio files that can be played on a web browser.

### Deployed URL (using AWS) :
http://www-audiopost01.s3-website.us-east-2.amazonaws.com/

### AWS Services used: 
API Gateway, Dynamo DB, Lambda, SNS, S3 Bucket, Amazon Polly, IAM Roles

## Application architecture

1. Register and Login Functionality: <br/> <br/>
   <img src="https://github.com/JANVI062/GoGo-Audio/blob/master/images/Register-login.png" width="60%" height="70%">


2. New Post(creating new audio files) and Get Post(retrieving past audio files from database) functionality:

   ![alt text](https://github.com/JANVI062/GoGo-Audio/blob/master/images/Posts.png)
