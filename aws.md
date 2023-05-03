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
