
# image-lambda
repo for AWS S3 bucket and Lamda function event trigger practice

## How to use my lambda

When an image is uploaded to the bucket a lambda function is triggered to update my images.json file with the new image information.

## Issues encountered

Took a bit of fiddling to get permissions setup for the bucket and the lambda. My main blocker was that when I was testing my lambda it kept saying that arr.push() is not a function. So im sure im missing something but I couldnt update the images.json array when pulled from the bucket. Currently the task is incomplete. To be continued.....

## Link to my images.json file

[URL](https://kd-401-image-bucket.s3.us-west-2.amazonaws.com/images.json)