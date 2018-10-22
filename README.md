# kubecli
Docker image with the components needed for kubectl.

# Kube CLI

This is Docker image for the [kubectl](https://kubernetes.io/docs/reference/kubectl/overview/).

The `:latest` tag of this image is Debian-based for kubectl.

## Usage

To pull this image from [Docker Hub](https://hub.docker.com/r/bwoods8/kubecli/), run the following command:

```bash
docker pull bwoods8/kubecli:latest
```
This is pulling the latest version.

Verify pulled image:

```bash
docker pull bwoods8/kubecli:latest kubectl version --client
```
