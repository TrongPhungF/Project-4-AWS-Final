Here are the secrets store in github Repository secrets :
+ AWS_ACCESS_KEY_ID - aws access key id
+ AWS_SECRET_ACCESS_KEY - aws access key
+ AWS_SESSION_TOKEN - aws session token
Here are the secrets store in github Repository variables: 
+ AWS_REGION
+ CLUSTER_NAME
+ ECR_REPOSITORY_BE
+ ECR_REPOSITORY_FE
+ IMAGES_NAME_BE
+ IMAGES_NAME_FE
+ WORKING_DIRECTORY_BE
+ WORKING_DIRECTORY_FE
+ WORKING_DIRECTORY_EKS_FE
+ WORKING_DIRECTORY_EKS_BE
+ Flow:
1. Create the pull_request then merge in the cicd-backend folder.
2. Get the dns name of the load balancer of backend.
3. Patse that value to the github secret "REACT_APP_MOVIE_API_URL"
4. Create the pull_request then merge in the cicd-frontend folder.