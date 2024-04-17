# Cloud Resume Project

I aim to create a simple static cloud-based resume website by converting a resume from PDF format to HTML, CSS, and JavaScript. I'll be hosting it on AWS cloud leveraging tools like S3 Bucket, Cloudfront, Route53, SSL, Domain, DynamoDB, Terraform and Github Actions for automatic deployment to cloud for CI/CD.

## ToDo

- [x] Convert PDF resume to HTML, CSS, and JavaScript.
- [x] Make it mobile first for easy viewing
- [x] Work on desktop version
- [x] Utilize AWS S3 bucket for hosting the resume.
- [x] Make it available on edge locations using cloudfront distribution
- [x] Get a domain name and route cloudfront distribution through it
- [x] Implement SSL protocol for secure communication.
- [x] Setup Route 53 for dns service and routing
- [x] Setup Github Actions to Automatically deploy to s3 bucket and invalidate cdn cache
- [ ] Setup a view counter in website using js
- [ ] Store the counter data in dynamo db and query it using api.
- [ ] Infrastructure as Code (IaC) using Terraform.
- [ ] Implement CI/CD for front-end and back-end codes.
