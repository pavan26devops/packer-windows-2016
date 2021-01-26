# Packer-AWS-windows-2016-AMI
Packer configuartion to build AWS Windows 2016 Base AMI

### To validate the configuration.
packer validate win2016-jenkins-slave.json

### To build the AMI
AWS_PROFILE=pavan-aws packer build win2016-jenkins-slave.json

### To add verbose to build
PACKER_LOG=1 AWS_PROFILE=pavan-aws packer build win2016-jenkins-slave.json

### To build in debug mode
AWS_PROFILE=pavan-aws packer build -debug win2016-jenkins-slave.json

# References

* https://www.rderewianko.com/jenkins-ec2-windows-ondemand/
* https://cloud-right.com/2016/12/packer-and-aws-windows-server-2016/
