# AWS EC2 Starting/Stopping CloudWatch Events template

## Description

This is a AWS CloudFormation template to start and stop EC2 instances automatically.

## Installation

1. Create AWS CloudFormation Stack with this template and specify the following CloudFormation parameters.
    * Ec2InstanceIds:"i-xxxxx","i-xxxxx"
    * CronStartUtc: 45 20 * * ? *
    * CronStopUtc: 45 21 * * ? *
