
# Work in Progess

# Virtual Private Cloud



# What is a VPC?
If we imagine your AWS Region as a country, a Virtual Private Cloud (VPC) is like your own private city inside that country.
You can design neighborhoods (known as subnets), traffic rules, and security measures to control how resources, like EC2 instances and databases, connect and work together.

# 3 steps
```
☁️ Create an Amazon VPC.
```
```
🥅 Create a public subnet.
```
```
🚪 Create an internet gateway.
```

```
1) Create a VPC
1.1) Access the VPC console in AWS
1.2)  In the AWS Management Console search field, type VPC.
1.3) Select VPC from the drop down menu.
1.4) In the left navigation pane, choose Your VPCs
```
```
2. Create a VPC.
```
# What's the point of having VPCs, why do they matter?
To put it simply - without VPCs, every AWS resource would exist in one giant, open space in the cloud, like a country without cities or districts.

Resources would be randomly scattered with no privacy or personal space, so everyone could see and access everyone else's resources .

![image](https://github.com/user-attachments/assets/13a97bae-8b48-44f6-80fc-6d6c0b6d3ff8)


VPCs are the reason why resources can be made private to you. You also get control over resources in a VPC, so you can organize how they communicate and integrate with each other without the public internet.

p.s. if we're still a little unsure about the difference a VPC makes, here's another analogy that might help. Imagine if every file in Google Drive from any account was put into the same folder with no privacy or subfolders. You'd have to find your files amongst everything uploaded by everyone, which makes managing/securing your files really hard! That's what managing your resources would feel like without VPCs.


