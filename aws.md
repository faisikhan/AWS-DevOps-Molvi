# AWS

It is not necessary that every region is enabled for a certain account. You can see in the following image, a couple of regions are disabled and we have to enable them in IAM. 

![image](https://user-images.githubusercontent.com/21220549/235868422-30bd7dd0-3754-4a51-9f77-862826d2e555.png)

By the way, we'd not be able to create resources in the disabled regions.

You'll see the **"not-opted-in"** as their state for the disabled regions as shown in the following snap.

![image](https://user-images.githubusercontent.com/21220549/235870190-f35a5510-2c54-4787-9d14-822861662390.png)

## AWS Global Dashboard

The Global dashboard gives us a detailed overview of our EC2 resources like subnets, VPCs, instances in specific regions. Its one-stop-shop for our EC2 resources.

![image](https://user-images.githubusercontent.com/21220549/235869113-70ca225e-975d-4f9a-9745-99381e6d3210.png)

We can use the global search option to see the instances, VPCs and security groups on a single page with their respective details. 

### How to search resources?

We can search our resources in the following way. Just keep in mind, we'll get a full detailed page for EC2 instances regardless of their state either stopped or running.

![image](https://user-images.githubusercontent.com/21220549/235871233-2c8f50da-598d-4f35-9ba6-653d36475b0a.png)

### What are AWS Events?

Any scheduled activities regarding EC2 or any other resources in a specific region are known as events. Like for instance, server reboots, node/hardware migration etc.

![image](https://user-images.githubusercontent.com/21220549/235906091-9a6fd0c2-9ab1-473a-9d74-d6b369312be8.png)

### What are AWS Limits?

Limits are imposed to protect your account from malicious activities. It also protects your account from getting over-billed. You can see all the limits for your compute resources in the Limits section as shown below:

![image](https://user-images.githubusercontent.com/21220549/235908119-da0fcc4e-58f2-4ef2-ad38-dc86d433f06a.png)

### How many instances we can launch in a single region?

Answer: 20

![image](https://user-images.githubusercontent.com/21220549/235907906-9154be75-ecbe-40d1-9976-b2bd88c21875.png)

## AWS EC2 Instance Types
There are hundreds of EC2 instance types with different processors, memory, vCPUs, cores, GPUs and hourly pricing.

![image](https://user-images.githubusercontent.com/21220549/235932121-f7e8fd98-8615-4412-a393-76289adfc875.png)

The EC2 instances can be general purpose, Memory optimized, CPU optimized and storage optimized etc.

![image](https://user-images.githubusercontent.com/21220549/235931475-f20fac73-1bd3-4d60-9803-c4d56e922259.png)

