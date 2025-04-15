# AWS-storage-services

AWS command to manage S3 buckets and objects

The mentee i collected the HTML file from is named Dominion

## The Commands used and response gotten include:

~ $ aws s3 mb s3://t-e-s-t-bucket

make_bucket: t-e-s-t-bucket

~ $ aws s3 cp index.html s3://t-e-s-t-bucket

upload: ./index.html to s3://t-e-s-t-bucket/index.html         

~ $ aws s3 cp s3://t-e-s-t-bucket/index.html index.html

download: s3://t-e-s-t-bucket/index.html to ./index.html       

~ $ aws s3 rm s3://t-e-s-t-bucket/index.html 

delete: s3://t-e-s-t-bucket/index.html

~ $ aws s3 rm s3://t-e-s-t-bucket/index.html

delete: s3://t-e-s-t-bucket/index.html

~ $ aws s3 rm s3://t-e-s-t-bucket/index.html

delete: s3://t-e-s-t-bucket/index.html

~ $ aws s3 rb s3://t-e-s-t-bucket --force

remove_bucket: t-e-s-t-bucket

