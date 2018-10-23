# getsec
get AWS Secrets Manager secrets by command line
Drop it in your PATH somewhere for easy access.
You'll have to have Ruby and AWS CLI installed and configured before it'll work.

Usage:

`getsec list`
- returns list of secrets in your AWS Secrets Manager

`getsec secret-name`
- returns secret values for `secret-name`
