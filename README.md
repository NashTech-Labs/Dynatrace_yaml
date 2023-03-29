# Dynatrace_yaml

Replace "your-environment-id" and "your-api-token" with your Dynatrace environment ID and API token respectively.

This configuration file creates a Kubernetes DaemonSet that runs the Dynatrace OneAgent container on every node in the cluster. The OneAgent container is responsible for monitoring the applications running in the other containers on the same node.

Once the OneAgent container is running, you can see the monitored Kubernetes nodes and containers in the Dynatrace console.
