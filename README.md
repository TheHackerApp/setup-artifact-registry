# setup-artifact-registry

A composite action to configure and authenticate with [Google Cloud Artifact Registry][artifact-registry].

[Google Cloud Workload Identity Federation][workload-identity-federation] is used to authenticate
with Google Cloud using GitHub Actions. The [docker-credential-gcr][] credential helper is used to
authenticate Docker with Artifact Registry using the credentials obtained earlier.

[artifact-registry]: https://cloud.google.com/artifact-registry
[workload-identity-federation]: https://cloud.google.com/iam/docs/workload-identity-federation
[docker-credential-gcr]: https://github.com/GoogleCloudPlatform/docker-credential-gcr
