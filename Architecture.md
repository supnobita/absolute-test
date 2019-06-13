# Framework component
1. Jenkins. 
2. minikube. 
3. Docker Repo. 
4. Application. 
# Build infra process
1. Run ansible with playbook name: test, this will install jenkins server and docker. 
2. Run ansible with minikube playbook: this will install minikube. 
3. Put app folder as a application code repo. 
4. Install Jenkins Continous Deployment Plugin (Azue team). 
5. add k8s credential to jenkin credential. 
6. Create repo jenkins-shared-lib and setup shared lib on jenkins with that repo. 
7. Create Jenkins job. 
# Flow CICD
1. Code commit. 
2. build code, build docker image, push to repo. 
3. deploy k8s deployment. 
