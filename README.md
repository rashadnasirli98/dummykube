clone this project 
Minikube requires a hypervisor to create and manage virtual machines.   so Install hyperkit
1: brew install hyperkit  

Minikube  installation 
2: brew install minikube

Start Minikube
3:  minikube start 

Apply the YAML file to create the pod 
4: kubectl apply -f nginx-pod.yaml  

Check running pod
5: kubectl get pods

Port forward 
6: kubectl port-forward nginx-pod 8080:80 

now open localhost
 http://localhost:8080 


![image](https://github.com/rashadnasirli98/dummykube/assets/137173120/ba8f4de0-3969-4042-832d-13af321b554d)
