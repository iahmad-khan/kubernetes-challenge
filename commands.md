   33  ls 
   34  docker build -t test:v1 .
   35  docker images
   36  cat Dockerfile 
   37  nano Deployment.yaml
   38  nano Service.yaml
   39  nano Ingress.yaml
   40  ls
   41  mv Ingress.yaml ingress.yaml 
   42  mv Deployment.yaml deployment.yaml 
   43  mv Service.yaml service.yaml 
   44  ls
   45  k apply -f deployment.yaml 
   46  k get po
   47  k apply -f service.yaml 
   48  k get svc
   49  k apply -f ingress.yaml 
   50  k get ingress
   51  curl $(minikube ip)
   52  nano ingress.yaml 
   53  k apply -f ingress.yaml 
   54  nano ingress.yaml 
   55  k apply -f ingress.yaml 
   56  nano ingress.yaml 
   57  k apply -f ingress.yaml 
   58  cat ingress.yaml 
   59  nano ingress.yaml 
   60  k apply -f ingress.yaml 
   61  curl $(minikube ip)
   62  curl $(minikube ip):4000
   63  echo $(minikube ip)
   64  ping 192.168.49.2
   65  curl $(minikube ip)
   66  k get svc
   67  k get ingress
   68  cat ingress.yaml 
   69  minikube addons list | grep ingress
   70  minikube addons enable ingress
   71  k get ingress
   72  curl 127.0.0.1
   73  curl $(minikube ip)
   74  k get ingress
   75  k get ingress
   76  curl $(minikube ip)
   77  curl 192.168.49.2
   78  k get svc 
   79  minikube service nodejs-service
   80  minikube tunnel

