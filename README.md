Package the service as a Docker image. Deploy the container to an AWS EC2 instance.You may use any technology stack you are comfortable with.


Steps involved -  
1.Push code to the `main` branch on GitHub.
2.AWS CodePipeline detects the change. 
3.AWS CodeBuild installs dependencies 
4.The build output is deployed to the S3 bucket. 
5.S3 serves the app as a public static website.
