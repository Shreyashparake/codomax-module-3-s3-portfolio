
# Codomax Internship — Module 3: Amazon S3 & Cloud Storage

## Project Overview
A static portfolio website hosted using Amazon S3 static website hosting.

## Objectives
- Create and configure an S3 bucket.
- Upload and manage website objects.
- Understand S3 access control and bucket policies.
- Enable static website hosting.
- Deploy and test a portfolio website.

## AWS Services
- Amazon S3
- S3 Bucket Policies
- S3 Static Website Hosting

## Website Files
- `index.html` — portfolio homepage
- `error.html` — custom error page

## Deployment Steps
1. Created an S3 general-purpose bucket in `ap-south-1`.
2. Uploaded the website files.
3. Enabled static website hosting.
4. Configured public read access for the website objects.
5. Tested the website using the S3 website endpoint.

## Live Website
S3 website endpoint:

`http://codomax-m3-portfolio-shreyash-2026.s3-website-ap-southeast-2.amazonaws.com/`

## Security Considerations
- Public read access is intended only for this public portfolio.
- No public write or delete permissions are granted.
- No AWS credentials or private keys are stored in the repository.
- S3 static website endpoints use HTTP. HTTPS requires an additional service such as Amazon CloudFront.

## Internship
Codomax — Module 3: Amazon S3 & Cloud Storage
