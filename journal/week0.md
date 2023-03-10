# Week 0 — Billing and Architecture
<b> Create a budget </b> <br>
I created my own Budget for $1 because I cannot afford any kind of spend. I did not create a second Budget because I was concerned of budget spending going over the 2 budget free limit.

![image](https://user-images.githubusercontent.com/88491497/224267037-e9f45136-f529-4f60-8987-b050c876447d.png) <br><br>

<b> Logical Architecture Design </b> <br>
Designed a full code pipeline logical architecture incorportating commit, build and deploy steps.

The advanced demo consists of 4 stages :-

STAGE 1 : Configure Security & Create a CodeCommit Repo <br>
STAGE 2 : Configure CodeBuild to clone the repo, create a container image and store on ECR <br>
STAGE 3 : Configure a CodePipeline with commit and build steps to automate build on commit.<br>
STAGE 4 : Create an ECS Cluster, TG's , ALB and configure the code pipeline for deployment to ECS Fargate

<a href="https://lucid.app/lucidchart/9d61629e-4bea-4396-997e-871c32157d6a/edit?viewport_loc=-16%2C-100%2C1365%2C617%2C0_0&invitationId=inv_5c045cab-88fa-4f0e-9989-9c0d4f77feb2"> Logical CI/CD Architecture </a>

![image](https://user-images.githubusercontent.com/88491497/223996386-b9ae2df1-f03f-485e-bc61-984d2bd62170.png)
