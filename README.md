[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/aws/aws-controllers-k8s/issues)
![status is preview](https://img.shields.io/badge/status-preview-brightgreen?style=flat)
![GitHub issues](https://img.shields.io/github/issues-raw/aws/aws-controllers-k8s?style=flat)
![GitHub](https://img.shields.io/github/license/aws/aws-controllers-k8s?style=flat)


![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/aws/aws-controllers-k8s)
[![Go Report Card](https://goreportcard.com/badge/github.com/aws/aws-controllers-k8s)](https://goreportcard.com/report/github.com/aws/aws-controllers-k8s)
![GitHub watchers](https://img.shields.io/github/watchers/aws/aws-controllers-k8s?style=social)
![GitHub stars](https://img.shields.io/github/stars/aws/aws-controllers-k8s?style=social)
![GitHub forks](https://img.shields.io/github/forks/aws/aws-controllers-k8s?style=social)



# AWS Controllers for Kubernetes (ACK)
**AWS Controllers for Kubernetes (ACK)** lets you define and use AWS service resources directly from Kubernetes. With ACK, you can take advantage of AWS managed services for your Kubernetes applications without needing to define resources outside of the cluster or run services that provide supporting capabilities like databases or message queues within the cluster.

This is a new open source project built with ❤️ by AWS and available as a **Developer Preview**. We encourage you to try it out, provide feedback and contribute to development.

*Important: Because this project is a preview, there may be significant and breaking changes introduced in the future. We encourage you to try and experiment with this project. Please do not adopt it for production use.*

### Contents
* [Overview](#background)
* [Getting Started](#getting-started)
* [Help & Feedback](#help--feedback)
* [Contributing](#contributing)
* [License](#license)

## Background
Kubernetes applications often require a number of supporting resources like databases, message queues, and object stores to operate. AWS provides a set of managed services that you can use to provide these resources for your applications, but provisioning and integrating them with Kubernetes was complex and time consuming. ACK lets you define and consume many AWS services and resources directly within a Kubernetes cluster. ACK gives you a unified, operationally seamless way to manage your application and its dependencies.

ACK is a collection of [Kubernetes Custom Resource Definitions](https://kubernetes.io/docs/concepts/extend-kubernetes/api-extension/custom-resources/) (CRDs) and controllers which work together to extend the Kubernetes API and create AWS resources on your cluster’s behalf.

## Getting Started
To get started, [choose and install](https://aws.github.io/aws-controllers-k8s/user-docs/install/) the controllers for the AWS services you want to manage. Then, [configure permissions](https://aws.github.io/aws-controllers-k8s/user-docs/permissions/) and [define your first AWS resource](https://aws.github.io/aws-controllers-k8s/user-docs/usage/).

### Supported Services
[List of supported AWS services](/services)

## Help & Feedback
For help, please consider the following venues (in order):

* [ACK project documentation](https://aws.github.io/aws-controllers-k8s/user-docs/install/)
* [AWS service documentation](https://docs.aws.amazon.com/)
* [Search open issues](https://github.com/aws/aws-controllers-k8s/issues)
* [File a new issue](https://github.com/aws/aws-controllers-k8s/issues/new/choose)
* Search our [mailing list](https://groups.google.com/forum/#!forum/aws-service-operator-user/).
* Slack: Talk to us on the #provider-aws channel on the Kubernetes Slack (https://kubernetes.slack.com/) community.

## Contributing
We welcome community contributions and pull requests. See our [contribution guide](/CONTRIBUTING.md) for more information on how to report issues, set up a development environment, and submit code.

Check the [issues list](https://github.com/aws/aws-controllers-k8s/issues) for descriptions of work items. We invite any and all feedback and contributions, so please don't hesitate to submit an issue, a pull request or comment on an existing issue.

ACK adheres to the [Amazon Open Source Code of Conduct](https://aws.github.io/code-of-conduct). You can also learn more about our [Governance](/GOVERNANCE.md) structure.

## License
This project is licensed under the Apache-2.0 License.
