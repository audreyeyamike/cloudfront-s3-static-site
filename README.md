#  Secure Static Website Hosting on AWS (S3 + CloudFront)

This project demonstrates how to host a *static website securely* using a *private Amazon S3 bucket* and deliver it globally through *Amazon CloudFront*.

##  Files Included

- index.html: Homepage of the website

##  Setup Overview

- S3 bucket with *block public access enabled*
- CloudFront distribution using *Origin Access Control (OAC)*
- No public bucket policy required

### Why I Did This
- *Private S3 Bucket:* Keeps website files secure, preventing direct public access.
- *CloudFront with Origin Access Control (OAC):* Provides global content delivery with low latency while ensuring secure access to the S3 bucket.
- *Static Website Deployment:* Shows practical cloud deployment skills, ideal for client websites and portfolios.

### Where This is Useful
- Hosting company landing pages or personal portfolios.
- Delivering static web content globally with secure access.
- Learning the foundations of AWS cloud deployment and security practices.  

##  Steps I Took

1. Created a private S3 bucket named audrey-s3-website
2. Uploaded a simple index.html file with custom HTML content
3. Set up a CloudFront distribution with *Origin Access Control (OAC)*
4. Automatically updated the S3 bucket policy via CloudFront to allow secure content delivery
5. Configured index.html as the default root object

## Live Demo

You can view the website here:  
🔗 *[https://d10vebhx19efw0.cloudfront.net](https://d10vebhx19efw0.cloudfront.net/index.html)*

##  Skills Demonstrated

- AWS S3 (secure bucket setup)
- Amazon CloudFront (content delivery network)
- Static website hosting
- IAM permissions and bucket access control
- Using Origin Access Control (OAC)

##  What I Learned

- How to securely host static sites on AWS using best practices
- The importance of keeping S3 buckets private
- How to use CloudFront and OAC for content delivery
- Real-world application of cloud infrastructure setup
## Screenshot

Here’s a screenshot of the hosted static website before AWS resources were deleted:

![Static Website Screenshot](./cloudfront.png)
---

## 👤 Author

*Eyamike Audrey*  
📧 eyamikeaudrey652@gmail.com
