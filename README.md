# aws-sso-profile

A small script to set up your shell environment for an AWS SSO profile.

## Usage

```sh
eval $(aws-sso-profile <profile-name>)
```

This will run `aws sso login` if needed, then export `AWS_PROFILE` and `AWS_DEFAULT_REGION`.

## Requirements

- Ruby
- AWS CLI v2
