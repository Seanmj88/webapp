DEPLOYING A STATIC WEB APPLICATION WITH SERVERLESS, CODEBUILD CODEPIPELINE and CLOUDFRONT
This example uses a ReactJS website found here https://github.com/themesberg/volt-react-dashboard#quick-start. 

Required resources and templates can be found in ./serverless.yml. It's not using a custom domain for cloudfront.

CodeBuild build steps and configurations are in ./buildspec folder and split between test.yml and deploy.yml

How to deploy.

Run sls deploy in the root folder