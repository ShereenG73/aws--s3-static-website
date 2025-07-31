\# AWS S3 Static Website



This project demonstrates how to create a simple static website hosted on AWS S3 using Terraform.



\## Project Details



\- \*\*S3 Bucket Name:\*\* shereen-giesecke-s3-bucket

\- \*\*Website:\*\* A basic static HTML page served from an S3 bucket

\- \*\*Infrastructure as Code:\*\* Managed with Terraform



\## How to Use



1\. Clone this repository.

2\. Run `terraform init` to initialize Terraform.

3\. Run `terraform apply` to create the S3 bucket and website configuration.

4\. Upload your `index.html` file to the S3 bucket.

5\. Access your website at:  

&nbsp;  `http://shereen-giesecke-s3-bucket.s3-website-us-east-1.amazonaws.com`



\## Notes



\- Make sure the bucket name is globally unique in AWS.

\- The bucket is configured to host a static website.

\- Public access settings must allow website access.



\## Author



Shereen Giesecke



\## License



This project is licensed under the MIT License.



