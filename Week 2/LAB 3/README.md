Task :  Create a dual Stack VPC and subnets using AWS CLI

Step:
1. Launch a non-default VPC
2. Create two subnets 
3. Create an internet gateway to one of the subnets with route table 
4. Configure an egress-only private subnet
5. Modify the IPv6 addressing behavior of the subnets
6. Lauch an instance into your public subnet
7. Launch an instance into your private subnet
8. Perform clean up operations. 


https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnets-commands-example.html

https://docs.aws.amazon.com/vpc/latest/userguide/vpc-subnets-commands-example-ipv6.html

https://docs.aws.amazon.com/vpc/index.html

I created a non-default VPC
I then created two subnets
I created an internet gateway to one of the two subents with route table
I configured an egress-only private subnet
I modified the IPv6 addressing behavior of the two subnets I created
I launched an instance into the two subnets I created
I cleaned up by deleting everything I created
