## AI Ops - EKS

This is part of the [Modernizing ITOps with AI/ML on AWS](https://catalog.workshops.aws/aiops/en-US) Workshop.

In order to deploy all the components required for this workshop, we will need to download the code and required packages by following the steps below:

### Clone the repository
In your [Cloud9 environment](https://console.aws.amazon.com/cloud9/) or [CloudShell](https://console.aws.amazon.com/cloudshell/home), enter the following command into the terminal to clone the repository into your environment:

```
git clone https://github.com/aws-samples/aiops-eks.git
```


### Deploy CloudFormation stack for CloudWatch Anomaly


```
aws cloudformation create-stack --stack-name cloudwatchanomaly --template-body file://aiops-eks/deploy_workshop_cloudwatchanomaly.yml --capabilities CAPABILITY_IAM CAPABILITY_NAMED_IAM CAPABILITY_AUTO_EXPAND
```



See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License Summary

The documentation is made available under the Creative Commons Attribution-ShareAlike 4.0 International License. See the LICENSE file.

The sample code within this documentation is made available under the MIT-0 license. See the LICENSE-SAMPLECODE file.
