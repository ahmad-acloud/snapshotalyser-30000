# snapshotalyser-30000
Demo project to manage EC2 instance snapshots
# About
This project is a demo, and uses boto3 to mange AWS EC2 instances snapshots.

## Configuration

shotty uses the configuration created by the AWS cli. e.g.

`aws configure --profile shotty`

##Running
`pipenv run python shotty/shotty.py <command> <subcommand>
<--project=PROJECT> `
*Command* is instances,volumes and snapshots
*subcommand* - depends on command
*project* is optional
