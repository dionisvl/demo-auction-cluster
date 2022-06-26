# Demo Cluster Provisioning


## Install Ansible
- `sudo apt install ansible`
- `sudo apt install sshpass`

## Installation to production
- install the Jenkins to production, for more info go to demo-auction-jenkins project.
- install the Docker Registry to production, for more info go to demo-auction-registry project.
- prepare target servers
    - make site
    - make authorize
    - make generate-deploy-key
    - make authorize-deploy
    - make docker-login
- go to main demo-auction main project and deploy project to target servers by example command:
    - `make deploy`