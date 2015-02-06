# EC2 Route53 Presence for Docker

Docker container which registers the local ec2 instance into route53. 

Example of usage:
```
docker run --name route53-presence  \
          -e HOSTNAME_PUBLIC=some.example.com  \
          -e HOSTNAME_LOCAL=local.some.example.com  \
          -e AWS_ACCESS_KEY=XXX \
          -e AWS_SECRET_KEY=XXX  \
          misakai/route53-presence
```
