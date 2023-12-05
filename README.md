# kubeplugin
Plugins for Kubernetes

## How to use kubeplugin
1. Clone repository with **git clone**.
2. Make sure you have installed kubectl.
3. Go to ***scripts*** folder.
4. Start script locally by typing **bash kubeplugin pod top kube-system**, where ***pod*** is a resource, ***top*** - subcommand and ***kube-system*** - namespace.
5. Result is equivalent as **kubectl top pod kube-system**.
6. To add this script as a ***kubectl plugin***, use **sudo cp ./kubeplugin /usr/local/bin/kubectl-kubeplugin**.
7. Then use **kubectl kubeplugin top pod kube-system** with same result.
