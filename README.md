CARTA deployment using Kubernetes. The kubernetes objects are in template folder, there are reading values from the values.yaml file, then the version of the chart is in Chart.yaml file.
To run this files make sure minikube is installed with docker engine "containerd",
then the metrics-server for resource allocation
The CARTA image is taken from https://hub.docker.com/r/cartavis/carta/.
We still working on storage.