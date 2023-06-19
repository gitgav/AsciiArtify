Plugin installation:
curl -O https://raw.githubusercontent.com/gitgav/AsciiArtify/main/scripts/kubectl-kubeplugin
sudo mv kubectl-kubeplugin /usr/local/bin

Plugin usage:
kubectl kubeplugin [resourse] [namespace]

Example usage:
kubectl kubeplugin node
kubectl kubeplugin pod kube-system
