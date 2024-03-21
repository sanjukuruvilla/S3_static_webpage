---

# Host Static Webpage on Amazon S3

This guide provides step-by-step instructions for hosting a static webpage on Amazon S3.

## Overview

This repository contains instructions for hosting a static webpage on Amazon S3. By following these steps, you'll be able to create an S3 bucket, upload your webpage files, configure static website hosting, and access your webpage via a public URL.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Setup Instructions](#setup-instructions)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Prerequisites

Before you begin, ensure you have:

- An AWS account with access to the Amazon S3 service.
- Access to the AWS Management Console.

## Setup Instructions

1. **Navigate to AWS Console**:
   - Go to [https://aws.amazon.com/](https://aws.amazon.com/).
   - Click "Sign In to the Console".

2. **Sign In to AWS Console**:
   - Enter your email address and click "Next".
   - Enter your password and click "Sign in".

3. **Create S3 Bucket**:
   - Click the "Search" field and type "s3".
   - Click "S3".
   - Click "Create bucket".
   - Choose "US East (N. Virginia) us-east-1".
   - Enter your bucket name and uncheck the option to make the bucket publicly accessible.
   - Acknowledge the warning and click "Create bucket".

4. **Upload Webpage Files**:
   - Click your bucket name.
   - Click "Upload" and add your webpage files.
   - Optionally, click "Add folder" to upload folders.
   - Click "Upload" and then "Close".

5. **Configure Bucket Policy**:
   - Click "Permissions" and then "Edit".
   - Copy your bucket ARN and update the bucket policy.
   - Click "Save changes".

6. **Enable Static Website Hosting**:
   - Click "Properties" and then "Static website hosting".
   - Click "Edit" and enable static website hosting.
   - Set the index document to "index.html" and click "Save changes".

7. **Access Your Webpage**:
   - Click the URL provided to access your webpage.
   - [URL](http://skkportfolio.s3-website-us-east-1.amazonaws.com/)

## Usage

Follow the provided instructions to host your static webpage on Amazon S3. Share the generated URL with others to access your webpage.

## Contributing

Contributions to this repository are welcome! If you find issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---
