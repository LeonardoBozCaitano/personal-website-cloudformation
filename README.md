# My Personal Website infrastructure as code.

Building the infrastructure to my static website hosted in http://www.leonardobozcaitano.com

To lower the costs and increase the availability, my website will be deployed to a S3 hosting a static website. however, to enable the HTTPS protocol and increase performance, this cloudfront template creates a SSL certificate deploy a cloudfront distribuition.

### The infrastructure will be build in 6 steps:

- Creating a public certificate to my domain.
- Creating a OAI user.
- Creating the bucket.
- Assing S3 bucket policy to allow OAL user access.
- Create CloudFront deployment

- Manually Update Route53 to point to CloudFront deployment.
