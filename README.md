# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty users the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

`pipenv run shotty/shotty.py <command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes, or list_snapshots
*subcommand" - depends on Command
*project* is optional
