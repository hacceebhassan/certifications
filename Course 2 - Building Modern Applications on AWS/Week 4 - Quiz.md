# Building Modern Python Applications on AWS - Coursera

## Week 4 - Quiz

### Question 1

You can directly integrate other AWS Services with your State Machine using Tasks. Which of the following actions is not supported by Service Integrations in AWS Step Functions without using an Activity state?

- [ ] Run an Amazon Elastic Container Service task

- [x] Execute a program running on an external server

- [ ] Send a message in Amazon Simple Queue Service

- [ ] Invoking a Lambda Function


### Question 2

When defining a Step Function state machine, what language can be used?

- [ ] Python

- [ ] NodeJS

- [ ] Java

- [x] JSON


### Question 3

What state type can be used to execute a set of steps for each element of an input array in parallel?

- [ ] Array

- [ ] Parallel

- [ ] Choice

- [x] Map


### Question 4

A state machine in AWS Step Function is used for doing continuous deployment as part of a pipeline. One of the steps is to use Lambda to send an email asking for a manager to approve or not the deployment in production. 

Which of the following service integration pattern should be used?

- [ ] Activity task

- [ ] Request Response

- [ ] Run a Job

- [x] Wait for Callback


### Question 5

A state machine in AWS Step Function makes use of the AWS Batch service to run a batch job on many EC2 instances. The state machine doesn’t need to see the output of the batch job, but only that it started. 

Which of the following service integration pattern should be used?

- [x] Request Response

- [ ] Wait for Callback

- [ ] Activity task

- [ ] Run a Job


### Question 6

Existing EC2 instances are used to do batch processing on data hosted in an S3 bucket. A state machine in AWS Step Functions must be used to send the location where that data is to that group of instances. 

Which of the following would be appropriate steps in the right order for this scenario to work? 

- [ ] Change the code in the EC2 instances to pull from the state machine for work to do using the Wait for Callback integration pattern of a Task type state.

- [ ] Create an activity, add the activity to the state machine, and Step Function will now call the code in the EC2 instance to do the work.

- [ ] Use the Run a Job integration pattern of a Task type state that will call the EC2 instances to do the work.

- [x] Create an activity, add the activity to the state machine, and change the code in the EC2 instances to pull from the activity for work to do.


### Question 7

Which setting of a Step Function activity task type definition is used to make sure that the worker is still working on activity task it was asked to do?

- [ ] TimeoutSeconds

- [x] HeartbeatSeconds

- [ ] RetrySeconds

- [ ] CallbackSeconds


### Question 8

Which of the following service integration pattern is supported by an AWS Step Function Express workflow?

- [x] Request Response

- [ ] Run a Job

- [ ] Wait for Callback

- [ ] Activity task


### Question 9

For orchestrating a few Lambda functions that run for a very short duration at volumes as high as 5,000 concurrent execution, which type of workflow should be used?

- [ ] Concurrent workflow

- [ ] Standard workflow

- [ ] Dedicated workflow

- [x] Express workflow


### Question 10

Which of the following has the right associations between the service and its function?

- [ ] Step Function orchestrates and SQS is a service bus

- [ ] SQS is a queue service and SNS is a service bus

- [ ] EventBridge is a service bus and Step Function is a pub/sub

- [x] SNS is a pub/sub and EventBridge is a service bus