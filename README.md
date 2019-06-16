Awstoken is a bash wrapper around awscli for easy temporary security credential generation for AWS API.

More about AWS temporary security credential [here](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp.html).

Main purpose is to be able easily to force MFA for all users even for API access.

Forked from [here](https://github.com/vandot/awstoken).

## Changes:

- Added the `awsgovcloudtoken` to generate credentials in a AWS GovCloud account.
