This is an example project that demonstrates the deployment of a simple 
React app to AWS using GitHub Actions. New features are pushed to the features
branch and then GitHub Actions runs tests on every new pull request to the main
branch. If successfull the app is updated on AWS Elastic Beanstalk. 