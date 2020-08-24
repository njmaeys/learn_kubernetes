# Learn Kubernetes

## Goals
- Have this all run on my Pi
  - [Single node cluster](https://opensource.com/article/20/3/kubernetes-raspberry-pi-k3s)
  - [Multi node cluster](https://opensource.com/article/20/6/kubernetes-raspberry-pi)
- Deploy kubernetes 
  - [Getting Started](https://kubernetes.io/docs/setup/)
- Deploy prometheus to kube cluster
- Deploy graphana to kube cluster
- Deploy webapp to kube cluster
- Use helm to be able to deploy all of those
  - Potential custom chart configs
- Be able to interact with webapp
  - Simple [Golang](https://www.callicoder.com/deploy-containerized-go-app-kubernetes/) application
- See metrics in prometheus
- Create graphs in graphana

## Stretch
- Deploy CI/CD (jenkins to kube cluster)
  - Trying out [Jenkins](https://appfleet.com/blog/how-to-set-up-jenkins-on-kubernetes/) on local machine.
- Git repo to use semantic commits and release
  - [Guidelines For Semantic Commits](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
  - [Guidelines For Semantic Release](https://github.com/semantic-release/semantic-release)