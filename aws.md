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

## Launch Templates

1. Launch templates are predefined configurations to create a number of EC2 instances in one go. 
2. You can share the launch tempates with your team to create instances instead of sharing lots of information. 
3. Just share the template and it'd be pretty straightforward to create the instances. 
4. AWS also strongly recommends to use the Launch templates instead of Launch Configurations for creating EC2 instances or Auto-scaling groups.

![image](https://user-images.githubusercontent.com/21220549/236186946-96de6450-8e07-468e-b5b2-d68c3893008e.png)

Let's suppose we want to use Ubuntu 22.04 in our EC2 instances, select as shown in the image:

![image](https://user-images.githubusercontent.com/21220549/236187111-135fd76c-714b-432c-a158-ef4bfdd5c1d0.png)

In the next step, please specify the instance type and the key pair that will be associated with the EC2 instances.

![image](https://user-images.githubusercontent.com/21220549/236187572-486019c2-b7da-4931-b496-43eccab91ceb.png)

If you want to add a public/private subnet automatically to the launch template and a security group, you can do it in the following way:

![image](https://user-images.githubusercontent.com/21220549/236188012-226e5bc3-dcd3-4b1f-8a8e-f9837c2c8153.png)

For storage volumes:

![image](https://user-images.githubusercontent.com/21220549/236188151-3b72fd0b-8e3f-4f49-adf9-931db4ac182e.png)

The launch template has been created successfully:

![image](https://user-images.githubusercontent.com/21220549/236188308-235df6a8-b38c-40ad-b49d-527613b4b484.png)

## Launch Instance from a Launch Template

In this step, we'll see how we can launch an EC2 instance with a launch template.

![image](https://user-images.githubusercontent.com/21220549/236188659-bd643545-6da5-42e0-8c5f-b91650244890.png)

Press the Launch instance button and it will create an EC2 instance with our desired configuration according to the launch template version 1.0

![image](https://user-images.githubusercontent.com/21220549/236189017-60a7d204-8e45-4aa3-9ca5-523fd724a70d.png)

If we delete a launch template, all of its versions will be deleted. Whereas, we can delete a specific version of the launch template as well.

## EC2 Spot Instances

These are cheaper instances as compared to the on-demand instances, you can get a discount upto 90% because those are AWS spare instances.

## Savings Plan

You get discounted compute resources for 1-3 years term agreement.

## Scheduled Instances

These are also reserved instances that start and stop automatically according to the application needs and prior time setting.

## AMIs [Amazong Machine Images]

![image](https://user-images.githubusercontent.com/21220549/236218047-044b1ceb-5ade-4d7a-90dc-fb332d01e6a7.png)

## Elastic Block Store [EBS Volumes]





