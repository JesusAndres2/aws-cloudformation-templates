# aws-cloudformation-templates
Repository with useful cloudformation templates that i have been used.

# List of resources in folders
* __cloudfront__:
1. CDN for static web content with S3 buckets to store code and logs. Allocated with Waf ACL and Lambda Edge
* __cognito__:
1. Simple cognito with AAD as identity provider
2. Simple cognito with OICD as identity provider
3. Create a simple cognito User Pool. Create Identity Provider. Grant logged User pool users Assume Role of Identity pool to use a Lex bot from WebApp 
* __dynamo__:
1. Simple tables with distinct Provisioned Throughput
* __lambda__:
1. Base lambda template
* __s3__:
1. Basic S3 privte bucket capable to invoke lambda after PutObject Event
* __secrets-manager__:
1. Simple secret with multiple values to store as params in a JSON file