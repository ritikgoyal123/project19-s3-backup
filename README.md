Scheduled S3 Backup
Goal
Automate backup upload to Amazon S3.

Tasks Completed
Created S3 Bucket
Created Backup Script
Configured Cron Job
Uploaded Log File
Commands
aws s3 cp app.log s3://bucket-name/

crontab -e

Result
Backup files successfully uploaded to S3 automatically.
