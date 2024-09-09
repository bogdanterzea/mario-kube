# mario-kube
This is a Helm chart for deploying a containerized version of the Super Mario game on Kubernetes using Minikube.

### Prerequisites
- Docker
- Minikube
- Helm
- Kubectl

### Setup Steps
- Clone the repository
- Ensure Minikube is running
- You can use directly the helm package - `helm install mario-game ./mario-chart-0.1.0.tgz`
- Access the game - `minikube service mario-game`

##### Mention: Image used from: [pengbai/docker-supermario](https://hub.docker.com/r/pengbai/docker-supermario)
