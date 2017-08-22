# quickstart-magento

This Quick Start automatically deploys Magento Community Edition on the AWS Cloud.

Magento is an open-source content management system for e-commerce websites. This automated deployment builds a cluster that runs Magento along with optional sample data, which lets you experiment with custom themes and view the web store.
This Quick Start deploys Magento using AWS CloudFormation templates and offers two options: you can build a new AWS infrastructure for your Magento stack, or deploy Magento into your existing AWS infrastructure. The deployment uses MySQL on Amazon RDS for database operations, Amazon EFS for shared storage between EC2 instances, and an Amazon ElastiCache cluster with the Redis cache engine to improve application load times.

You can use the AWS CloudFormation templates included withe Quick Start to deploy a fully configured Magento infrastructure in your AWS account. The Quick Start automates the following:
  * Deploying Magento Community Edition into a new VPC
  * Deploying Magento Community Edition into an existing VPC
  
You can also use the AWS CloudFormation templates as a starting point for your own implementation.

![Quick Start Magento Design Architecture](http://docs.aws.amazon.com/quickstart/latest/magento/images/magento-architecture.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the [deployment guide](http://docs.aws.amazon.com/quickstart/latest/magento/welcome.html)
