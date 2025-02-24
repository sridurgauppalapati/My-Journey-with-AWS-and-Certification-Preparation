# My-Journey-with-AWS-and-Certification-Preparation
During my journey with AWS, I had the opportunity to explore and work with a variety of services, which also led me to prepare for the AWS Certified Cloud Practitioner exam. Throughout this process, I created and compiled a collection of helpful resources and materials that played a key role in my understanding and memorization of the content. This post aims to showcase some of the tables and summaries I developed, which significantly assisted me in retaining key concepts and passing the exam.
Monitoring	
Timestamp, cloudwatch dashboards(CPU utilization, status checks, network,disk read/writes, bucketsizeBytes, NumberOfObjects, AllRequests, Total Estimated Charge(only in us-east-1), service API usage, push ur own metrics	Cloud watch metrics
	(every minute)
Autoscaling, EC2 actions(stop, terminate, reboot/recover), SNS notifications, create billing alarm, Alarm status: OK,INSUFFICIENT_	Cloud watch alarms
DATA, ALARM
Elastic Beanstalk, ECS, AWS Lambda, CloudTrail, CloudWatch log agents, Route53, enable real-time monitoring of logs, adjustable cloudwatch logs retention(by default no logs from your EC2 instance will go to cloudwatch, need to run a cloudwatch agent on EC2 to push the log files you want, make sure IAM permissions are correct, cloudwatch log agent can be setup on-premises too	CloudWatch Logs
Schedule: corn jobs(scheduled scripts)	Amazon EventBridge
Event pattern: Event rules to react to a service doing something
Trigger Lambda functions, send SQS/SNS messages.
Scema registry, archive events sent to an event bus, ability to replay archived events.
![image](https://github.com/user-attachments/assets/7e7bc47e-b91a-45b8-8662-9e5a9ec8ceb4)
