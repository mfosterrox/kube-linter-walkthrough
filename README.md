# kube-linter-walkthrough

This repo contains the [sockshop application](https://microservices-demo.github.io/), KubeLinter config files, GitHub CI pipeline and some defaults to help you get started with KubeLinter.
## What is KubeLinter?

[KubeLinter](https://github.com/stackrox/kube-linter) analyzes Kubernetes YAML files and Helm charts, and checks them against a variety of best practices, with a focus on production readiness and security.

[KubeLinter](https://github.com/stackrox/kube-linter) runs sensible default checks, designed to give you useful information about your Kubernetes YAML files and Helm charts. This is to help teams check early and often for security misconfigurations and DevOps best practices. Some common examples of these include running containers as a non-root user, enforcing least privilege, and storing sensitive information only in secrets.

[KubeLinter](https://github.com/stackrox/kube-linter) is configurable, so you can enable and disable checks, as well as create your own custom checks, depending on the policies you want to follow within your organization.

When a lint check fails, [KubeLinter](https://github.com/stackrox/kube-linter) reports recommendations for how to resolve any potential issues and returns a non-zero exit code.

## Documentation

Visit https://docs.kubelinter.io for detailed documentation on installing, using and configuring KubeLinter.

