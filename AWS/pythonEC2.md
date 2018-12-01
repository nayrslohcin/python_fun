# AWS
Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

python-testing uses the config file created by the AWS cli. e.g.

`aws configure --profile python-testing`

## Running

`pipenv run python AWS\python-ec2.py <command> <subcommand>
 <--project=PROJECT>`

*command* is instances, volumes, or snapshtos list, start, or stop
*subcommand* - depends on command
*project" is optional

