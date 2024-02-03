# aws-cloudwatch-log-backup

An AWS Serverless-based solution that helps maintain backups of Cloudwatch Log data.

## Background & Motivation

AWS provides a centralized service, called AWS Backup, to help centrally manage and maintain backup artifacts of archivable resources.  This includes things like S3 buckets, DynamoDB tables and RDS clusters.

However, in AWS Backup's list of [supported services](https://docs.aws.amazon.com/aws-backup/latest/devguide/working-with-supported-services.html) Cloudwatch Log resources are not included.  In compliance-heavy industries like Healthcare and Finance, long-term retention of this is a necessity.  This solution is intended to help bridge this gap.

## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

## Authors

- [@cdschneider](https://www.github.com/cdschneider)
