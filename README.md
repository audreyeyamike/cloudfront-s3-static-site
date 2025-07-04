# 🌐 Secure Static Website Hosting on AWS (S3 + CloudFront)

This project demonstrates how to host a *static website securely* using a *private Amazon S3 bucket* and deliver it globally through *Amazon CloudFront*.

## 📁 Files Included
- index.html: Homepage of the website

## 🔒 Setup Overview
- S3 bucket with *block public access enabled*
- CloudFront distribution using *Origin Access Control (OAC)*
- No public bucket policy required

## ✅ Steps Taken
1. Created a private S3 bucket (your-bucket-name)
2. Uploaded a simple HTML file (index.html)
3. Set up a CloudFront distribution pointing to the S3 bucket
4. Enabled OAC to allow CloudFront to access private content
5. Configured index.html as the default root object

## 🌍 Live Demo
Access the website here:  
🔗 https://your-cloudfront-url.cloudfront.net

## 🛠 Skills Demonstrated
- AWS S3 (secure bucket)
- AWS CloudFront with OAC
- Static site hosting
- IAM permissions and policies
- CDN configuration

## 🧠 What I Learned
- Best practices for secure cloud hosting
- How to avoid public S3 access and use CloudFront instead
- How to configure OAC and test deployment

---

## 👤 Author

*Eyamike Audrey*  
📧 eyamikeaudrey652@gmail.com 
