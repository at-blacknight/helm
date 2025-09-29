Helm Chart
This tutorial shows how to deploy using Helm. To use helm you need to install it first, see the instructions here

In order to use compreface helm chart you need to configure your own Helm client.

$ helm repo add at-blacknight https://at-blacknight.github.io/helm/
“at-blacknight” has been added to your repositories
You can check compreface chart version by command:

helm search repo at-blacknight

NAME                                    CHART VERSION   APP VERSION     DESCRIPTION
at-blacknight/alloy        0.1.0           1.16.0          A Helm chart of alloy for Kubernetes

