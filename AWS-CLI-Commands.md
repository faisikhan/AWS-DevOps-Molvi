# Most Frequently used AWS CLI Commands

`aws help` ==> Gives info about various AWS CLI Commands.

`aws configure` ==> Setup AWS Credentials

`aws sts get-caller-identity` ==> AWS STS stands for AWS Security Token Service & used to access AWS resources.

`aws ec2 describe-instances` ==> It will list all AWS EC2 instances

`aws ec2 describe-instances --region ap-south-1` ==> If we want to see EC2 instances in a specific region.

`aws ec2 stop-instances --instance-id i-01cf9c4be69b7a9b3` ==> It will stop the instance with ID i-01cf9c4be69b7a9b3.

`aws ec2 start-instances --instance-id i-01cf9c4be69b7a9b3` ==> It will stop the EC2 instance.

`aws ec2 reboot-instances --instance-id i-01cf9c4be69b7a9b3` ==> It will restart the VM.

`aws ec2 terminate-instances --instance-id i-01cf9c4be69b7a9b3` ==> It will terminate the EC2 instance with the given Instance ID.

`
