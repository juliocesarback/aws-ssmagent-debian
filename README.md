# aws-ssmagent-debian
This image have [AWS SSM Agent](https://docs.aws.amazon.com/systems-manager/latest/userguide/ssm-agent.html) installed in a debian image base.

# How to use

## Locally
```
docker build -t aws-ssm-agent
```

## Remote
```
docker pull julioback/ssm-agent:0.1

docker run julioback/ssm-agent
```

## Last stable version
0.1
