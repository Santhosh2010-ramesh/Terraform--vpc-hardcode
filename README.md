# Terraform--vpc-hardcode
# Terraform VPC Setup (Hardcoded)

This repository contains a basic Terraform configuration file that sets up an AWS Virtual Private Cloud (VPC) with hardcoded values. It is intended for educational and testing purposes.

## Features

The Terraform script provisions the following AWS resources:

- A Virtual Private Cloud (VPC)
- Public and private subnets
- An Internet Gateway
- Route tables and associations
- (Optional) NAT Gateway and Elastic IP

## Prerequisites

Before you begin, ensure you have the following installed:

- [Terraform](https://www.terraform.io/downloads.html) (v1.0 or higher)
- [AWS CLI](https://aws.amazon.com/cli/)
- An AWS account and IAM user with sufficient permissions
- AWS credentials configured via `~/.aws/credentials` or environment variables

## File Structure

