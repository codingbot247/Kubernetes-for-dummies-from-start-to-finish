<h1>Index</h1>

<h2>Introduction</h2>
<p>
Kubernetes is the Greek word for Helmsman of a ship. This name was chosen because it oversees a set of servers and decides where to deploy containerized applications, when to scale up or down the number of application replicas and what to do when an application or server stops working. The first thing one would need to understand before learning Kubernetes is, Containers. Containers are virtual environments which are isolated and have no knowledge of your operating system. A container requires a container engine (for example: Docker) to be installed on any Operating system on which it is expected to work. </p>

<h3>Next Steps:</h3>
<ul>
<li>Install <a href= "https://docs.docker.com/engine/install/">Docker</a>: Your docker container runtime should run before your spin up your cluster, you can go with other options like podman too rather than Docker. To check if you have docker installed successfully and running just type "docker" in your CLI and hit enter if not start your docker desktop application. </li>
<li>Install <a href ="https://minikube.sigs.k8s.io/docs/start/">Minikube</a> : It helps your learn Kubernetes but not fit for production, and lacks security and networking abilities by other cloud providers.This will help you to try and test the kubernetes commands on your local machine for free</li>
<li>Start your cluster: Type minicube start to spinup your cluster. Please note that in different cloud providers you would use a different command to start the cluster rather than minicube. Then to interact with the cluster you use kubectl</li>
</ul>

