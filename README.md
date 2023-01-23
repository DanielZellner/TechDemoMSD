# TechDemoMSD
This Repo is for the Techdemo in CD

## About
This repo includes an Ionic-application that get transfered to the aws cloud after push or pull-request.
To accomplish this action it uses the ```aws-s3-sync-action```

## setup
to run the application:
```npm install```
```ionic serve```

### build
To build the application (these build files get transferred to the s3 bucket):
```npm run build``` or ```ionic build```

## Actions
https://github.com/marketplace/actions/aws-s3-sync-github-action

## Further use
To further use the application and the aws-cloud, you could add the feature of cloudfront to enable web-hosting.
Cloudfront can use the S3-bucket-files and host a public website.
