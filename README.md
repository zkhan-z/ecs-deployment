# ecs-deployment
Provisioning and orchestrating Amazon Elastic Container Service (ECS) deploymentand deploying a simple 'hello world' docker container
I will be using CodeComit/CodeDeploy/Codebuild/ and Codepipeline to build and design my pipeline.
to create a taskdefinition.json file, use elastic container registry (ECR) and create your taskdefinition speciication. Then you would copy teh json template and add it to your task definition file
create a buildspec, this information will be found on CodeCommit, you will have to click on push and you should see all the steps your docker container needs to push to a ecs for orchestration.
Make sure you also have a Dockerfile as well, just import it using DockerHub
add all these files to a GitHub and connect this to your CodeCommit or you could manually attach these files directely to CodeCommit and then run your CodePipeline.
Benefits: this is a microservice, you do not have to manage these pipeline and will have more time with your applicationa and software production.
