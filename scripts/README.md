Plugin installation: \
curl -O https://raw.githubusercontent.com/gitgav/AsciiArtify/main/scripts/kubectl-kubeplugin \
sudo mv kubectl-kubeplugin /usr/local/bin \
\
Plugin usage: \
kubectl kubeplugin [resourse] [namespace] \
\
Example usage: \
kubectl kubeplugin node \
kubectl kubeplugin pod kube-system \


$ k kubeplugin pod kube-system\
pod     kube-system     coredns-787d4945fb-czwfx                        2m                      12Mi\
pod     kube-system     etcd-minikube                                   19m                     39Mi\
pod     kube-system     kube-apiserver-minikube                         42m                     243Mi\
pod     kube-system     kube-controller-manager-minikube                15m                     39Mi\
pod     kube-system     kube-proxy-jgwnb                                1m                      10Mi\
pod     kube-system     kube-scheduler-minikube                         3m                      15Mi\
pod     kube-system     metrics-server-6b6f9ccc7-v6qdr                  4m                      17Mi\
pod     kube-system     storage-provisioner                             2m                      8Mi
