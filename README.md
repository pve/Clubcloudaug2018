Place for the static version of this website.

Editing through c9.io

Publishing through codeship.io using aws/codeship credentials  Codeship Status for pve/diginfra-website

Delivery: S3 and CloudFront http://staging-digitalinfra.nl.s3-website-us-east-1.amazonaws.com/publicaties/index.html

How to do this:

wget -mk --adjust-extension --no-host-directories http://www.digitalinfrastructures.nl 
git add *
git commit -m "initial upload" 
git push