Package the service as a Docker image. Deploy the container to an AWS EC2 instance.You may use any technology stack you are comfortable with.


Steps involved -
Push code to the `main` branch on GitHub.
AWS CodePipeline detects the change. 
AWS CodeBuild installs dependencies 
The build output is deployed to the S3 bucket. 
S3 serves the app as a public static website.
