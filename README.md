# Static website hosting on AWS☁️ using Terraform

## Prerequisites:
Steps to do before starting the project:
- Installed AWS CLI and configured AWS access and secret key on our local machine
- Installed Terraform on our local machine

## Steps to host static website on S3 using Terraform
### Steps #1: Create an S3 bucket:
- Created an S3 bucket to store the website files. The bucket name should be globally unique across all AWS accounts.
### Steps #2: Configuring a Bucket for a static website hosting:
- In S3 bucket properties, we need to enable static website hosting and need to specify the default index document (index.html) and optional error document(error.html).
### Steps #3: Uploading website files:
- Uploading our static website files(HTML, CSS, JS, images, etc.) to the S3 bucket with appropriate permissions(public-read) for the objects to make them publicly accessible.
### Steps #4: Enabling public access:
- Allow the public access to the S3 bucket and its objects by configuring the bucket policy or Access Control Lists(ACLs).
### Steps #5: Configuring DNS/Website endpoint: 
- We can use the custom domain to load our website online. In this project, the default S3 website endpoint is used.

## Output screenshots:

![1](https://github.com/Jayalakshmi-i/Terraform-Static-website/assets/141424247/dc426bd9-388f-43e7-9f16-f480bbcc9626)

![2](https://github.com/Jayalakshmi-i/Terraform-Static-website/assets/141424247/87c881da-7c84-4c7c-8677-0f84ae21e43e)

![3](https://github.com/Jayalakshmi-i/Terraform-Static-website/assets/141424247/a949c5e0-ce19-4e80-8a94-20369e98ab52)

![4](https://github.com/Jayalakshmi-i/Terraform-Static-website/assets/141424247/417d9844-2273-4d9c-988e-55556b6f22e1)

![image](https://github.com/Jayalakshmi-i/Terraform-Static-website/assets/141424247/f0c6dd8a-30d6-4afa-aaaf-02221583ff59)

