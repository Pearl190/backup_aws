aws s3 sync /backup-folder s3://my-bucket-name/ --exclude "*" --include "*.dmp"
aws s3 sync /backup-folder s3://my-bucket-name/ --storage-class STANDARD
