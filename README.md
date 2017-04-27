# Continuous Integration for a Node JS application with upload of artifacts to s3

[![Run Status](https://api.shippable.com/projects/5900943a28b7f006008d355d/badge?branch=master)](https://app.shippable.com/github/himanshu0503/ci-push-to-s3) [![Coverage Badge](https://api.shippable.com/projects/5900943a28b7f006008d355d/coverageBadge?branch=master)](https://app.shippable.com/github/himanshu0503/ci-push-to-s3)

![AyeAye](https://github.com/devops-recipes/ci-push-to-s3/blob/master/public/resources/images/captain.png)

A simple Node JS application with unit tests and coverage reports using mocha
and istanbul. After completing CI it pushes the artifacts to s3.

## Run CI for this repo on Shippable
* Fork this repo into your local repo
* Login into the [Continuous Integration Service](https://app.shippable.com)
* Create a secure env in your subscriptions settings having your **AWS_ACCESS_KEY_ID** and **AWS_SECRET_ACCESS_KEY**. The format is `AWS_ACCESS_KEY_ID="aws-access-key" AWS_SECRET_ACCESS_KEY="aws-secret-key"`
* All CI configuration is in `shippable.yml`
* Follow these [CI Setup Instructions](http://docs.shippable.com/ci/runFirstBuild/) if you have never used Shippable CI Service
* Change the AWS_S3_BUCKET and AWS_S3_REGION to point to your AWS S3 Bucket and AWS S3 Region.
* Update the value of the secure env.
* You should be able to run a manual build or webhook build on commit

## CI Reports on Shippable

### CI Console Output
![CI Console Output](https://github.com/devops-recipes/ci-push-to-s3/blob/master/public/resources/images/console.png)
