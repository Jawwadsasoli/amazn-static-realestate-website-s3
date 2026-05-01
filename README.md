🚀 Built and Deployed a Static Website on AWS using S3 + CloudFront

Today I completed a hands-on AWS cloud project where I hosted a static website using:

✅ Amazon S3
✅ CloudFront CDN
✅ HTTPS Delivery
✅ Static Website Hosting
✅ Bucket Policies & Permissions
✅ CloudFront Distribution Configuration

🔧 What I Learned

* Difference between S3 REST endpoints vs S3 Website endpoints
* Configuring CloudFront with S3 static hosting
* HTTPS delivery using CloudFront
* Cache invalidation concepts
* Troubleshooting real-world cloud deployment issues

🐞 Troubleshooting Challenges I Solved
During deployment, I encountered multiple production-style errors:

❌ AccessDenied errors
❌ 504 Gateway Timeout
❌ NoSuchKey / index.html issues

I debugged and resolved them by:

* Switching from S3 REST endpoint to S3 Website endpoint
* Configuring CloudFront Origin Protocol Policy correctly
* Fixing Origin Path misconfiguration
* Validating bucket permissions and public access settings
* Invalidating CloudFront cache

📚 This project helped me understand how AWS services interact together in real-world deployments and improved my troubleshooting and cloud architecture skills.

Architecture:
User → CloudFront CDN → S3 Static Website

Next Steps:
➡️ Custom Domain with Route 53
➡️ SSL Certificate using ACM
➡️ CI/CD Automation
➡️ Infrastructure as Code using CloudFormation/Terraform

#AWS #CloudComputing #CloudFront #AmazonS3 #DevOps #AWSSolutionsArchitect #AWSProjects #Infrastructure #LearningInPublic #CloudEngineer #TechLearning
