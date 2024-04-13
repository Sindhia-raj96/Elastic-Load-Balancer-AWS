To demonstrate how the Elastic Load Balancer in AWS works

Step 1: Lanuched two EC2 instances

![image](https://github.com/Sindhia-raj96/Elastic-Load-Balancer-AWS/assets/161922154/013257a7-6882-4b7f-95b2-a577e4414e42)

Step 2: once the EC2 instances are up and running, now create a Load Balancer

![image](https://github.com/Sindhia-raj96/Elastic-Load-Balancer-AWS/assets/161922154/f05d1d34-2c86-40fe-9140-8aabb403160f)

Step 3: While creating Load balance, make sure to create a security group which only allows the HTTP request and add those two EC2 instances to the target group. After that, click create 

![image](https://github.com/Sindhia-raj96/Elastic-Load-Balancer-AWS/assets/161922154/cb4ce59e-7876-46f4-b4be-801478613589)

![image](https://github.com/Sindhia-raj96/Elastic-Load-Balancer-AWS/assets/161922154/b6803ee0-5ccb-47d1-8c94-828e86b969eb)

Step 4: Copy the DNS name from the created Load Balancer and paste it. The ELB automatically balances the load between those instances.

Instance 1:

![image](https://github.com/Sindhia-raj96/Elastic-Load-Balancer-AWS/assets/161922154/8cb04600-fc41-4958-aca0-a4bdce509100)

Instance 2:

![image](https://github.com/Sindhia-raj96/Elastic-Load-Balancer-AWS/assets/161922154/b0c34f27-108e-4569-a9bd-78ce80c0d503)


