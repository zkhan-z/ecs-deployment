# ecs-deployment
Provisioning and orchestrating Amazon Elastic Container Service (ECS) deployment and deploying a simple 'hello world' docker container
I will be using CodeComit/CodeDeploy/Codebuild/ and Codepipeline to build and design my pipeline.
imagedefinitions.json, use elastic container registry (ECR) and create your imagedefinitions speciication. Then you would copy it's json template and add it to your imagedefinitions.json file
buildspec.yml, this information will be found on CodeCommit, you will have to click on push and you should see all the steps your docker container needs
Make sure you also have a Dockerfile as well, just import it using DockerHub.
add all these files to a GitHub and connect this to your CodeCommit or you could manually attach these files directly to CodeCommit and then run your CodePipeline.
Benefits: this is a microservice, you do not have to manage these pipeline and will have more time with your applicationa and software production and can integrate AWS cloudwatch as well. The downside is that it comes with cost and if you have a budget then this is not the best solution. Good for large scale operations and multitendency usage.
