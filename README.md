# edgeDeployment
CISCO associated project to deploy code on IOT edge nodes.

### Below are requirements
  Update code on each edge node with the latest code.

### Steps

  1. Set up three Linux(ubuntu) machines because we need at least 3 nodes to create kubernetes cluster.
  2. Installed Kubernetes, kubeadm and all other required dependencies over all 3 systems.
  3. Set up docker container running on each node.
  4. Created jenkins job that watch git repo changes, creates docker image and deploy container on each node.
