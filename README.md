# knd(1) 
# NAME
    knd

# SYNOPSIS
    knd [--replicas=replicas OR -r] [--nginx-version=version] [deployment-name] [-D OR --delete-deployment]

# DESCRIPTION
    knd (Kubernetes NGINX deployer) deploys NGINX on a Kubernetes cluster, and verifies that it has come up healthy.A CLI progress bar is provided to indicate the deployment/scaling progress.The application can be deployed with a configurable number of replicas. Type knd --help for more detailed information.