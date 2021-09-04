# Class 14

## AWS basics
Role manager in security
- allows you to set up ACL for users on all AWS services

**USE THE DEFAULT SETTING**
- these are designed to get you going. Then you can update and change.

### SNS
FIFO vs standard
- standard is usually better unless the order of sending matters.

ARN string: used to connect other serives to this one.

Steps:
- install and pull in the aws-sdk
- config to region
- create a messege function:
- create a new AWS.SNS with the apiVersion --> AWS.SNS({ 'date' }).publish(data)
    - we can add .promise() to turn it into a promise structure

You need an access key. 
- deleting these will save you from being billed for use

### Tools
AWS-SDK:




## Questions

AWS Cloud watch vs analytics pros/adswerve, google tag manager

Best corses for learning? -amazon

Where are those methods?

Is each subscription to just one topic?

Is that aws configure with the key for the computer or the folder?

# Assignment Questions

Review, Research, and Discussion

1. What’s the difference between a FIFO and a standard queue?
- they are the same. A standard queue works on the FIFO principle. 
2. How can the server be assured a message was properly received?
- the 3 way handshake is one way. Also, each packet of information has headers applied to it that the lower higher levels of the OSI use to make sure that the packets get compiled in the correct order. 
3. What classic design pattern is best represented by event driven programming?
- distributed asynchronous architecture pattern.
4. How do you test an event driven system?
- youhave to mock up all the event data to test each individual event you want to check. 

Document the following Vocabulary Terms
- FIFO Queue: it follows the First In First Out principle meaning that as data enters the queue it will be processed and output in the order that it came in. 
- Pub/Sub: a way to handle asynchronous processing in event driven programming. 


Skim the following materials in preparation for the upcoming lecture. Note the following as you browse the material, and be prepared to participate in discussions during lecture

1. Which 3 things had you heard about previously and now have better clarity on?
2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- AWS!!!!! I'm most excited for the use of lambda functions. From what I've read these can be very powerful but I need to see some examples of how to use them to better understand.
3. What are you most excited about trying to implement or see how it works?