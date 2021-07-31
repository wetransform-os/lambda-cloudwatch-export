# lambda-cloudwatch-export
This AWS lambda function creates a CloudWatch export task for the last 24 hours of a log group to a specified S3 bucket. This lambda is intended to be triggered by a CloudWatch rule running every 24 hours.

This repo was forked from https://github.com/gadgetry-io/lambda-cloudwatch-export for use in Ready's AWS infrastructure.

## Authors

This lambda function was originally created by Miles Maddox (https://github.com/justmiles). Ready will be maintaining this fork.

## License

MIT Licensed. See [LICENSE](https://github.com/Ready-Responders/lambda-cloudwatch-export/blob/master/LICENSE) for full details.
