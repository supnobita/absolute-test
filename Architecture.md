#Framework component
1. Jenkins
2. minikube
3. Docker Repo (docker hub)
4. Application
#Build infra process
1. Run ansible with playbook name: test, this will install jenkins server
2. Run ansible with minikube playbook: this will install minikube
3. Setup job run with jenkins file in app folder
