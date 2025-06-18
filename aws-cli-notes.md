markdown

# 🕝 AWS CLI Pracrice Notes

This file includes the basic AWS CLI commands I'm learning and using.

## ✅ Setup

'''bash
aws configure

Add your Access Key , Secret Access Key, and region (e.g., eu-west-1 for Ireland).

S3 Bucket Commands
bash

# Create a bucket
aws s3 mb s3://karabo-cloud-bucket

# Upload a file
aws s3 cp hello.txt s3://karabo-cloud-bucket/

# List contents
aws s3 1s s3://karabo-cloud-bucket/

💡 Notes
Buckets must have blobally unique names
Always double check the region when testing!


