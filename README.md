## Deploy Static Website on AWS
1- Create s3 bucket.
![create s3 bucket](create%20s3%20bucket.png)
2- Upload the project files to the bucket.
![project files screenshot](project%20files.png)
3- Secure Bucket via IAM.
![IAM policy](BucketPolicy.png)
4- Configure S3 Bucket.
![Bucket Configuration](BucketHostingSettings.png)
5- Distribute Website via CloudFront.
![Cloudfront](CloudFront.png)
![Cloudfront settings](CloudFrontSetttings.png)
![Cloudfront URL](CloudFrontURL.png)

6- Access Website in Web Browser
- copied CloudFront domain name![Cloudfront URL](CloudFrontURL.png)
- website-endpoint ![website endpoint URL](website-endpoint.png)
- S3 object URL. 
![S3 object URL](S3opbjectURL.png)