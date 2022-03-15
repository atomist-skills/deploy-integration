# What it's useful for

The Image Policy Deploy Integration supports the configuration of image
deployment policies for environments and the ingestion of lifecycle events from
workloads, such as pods coming and going in Kubernetes.

Together these can be used by a Kubernetes Admission Controller to decide if an
image is good, or for other upstream delivery activities, such as updating
Kubernetes spec files in a Git repository.
