# How to Install AWS CLI on Ubuntu 24.04?

`curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"`

`unzip awscliv2.zip`

`./aws/install --bin-dir /usr/local/bin --install-dir /usr/local/aws-cli --update`

`aws ecr get-login-password --region us-east-1 | docker login --username AWS --password-stdin 559050236729.dkr.ecr.us-east-1.amazonaws.com`
