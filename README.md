# aws-auto-scaling-group
Highly available and scalable web architecture on AWS using Auto Scaling and Application Load Balancer.

Built a Highly Available Architecture using Auto Scaling & Load Balancer on AWS
Today I implemented a scalable and fault-tolerant web architecture on AWS.
This time, I went beyond just EC2 + Load Balancer and configured Auto Scaling for dynamic traffic handling.
🔹 What I Implemented:
✅ Created a Launch Template (AMI, Instance type, Security Group configuration)
✅ Allowed HTTP (Port 80) in Security Group
✅ Configured multiple Subnets for better availability
✅ Created a Target Group
✅ Launched an Application Load Balancer
✅ Attached Target Group to the Load Balancer
✅ Created an Auto Scaling Group using the Launch Template
✅ Attached Auto Scaling Group to the Load Balancer
✅ Configured scaling policies for automatic instance management
🔥 Result:
• Traffic is distributed across instances
• Instances automatically scale based on load
• High availability across subnets
• Fault tolerance achieved
This project helped me understand:
How Launch Templates standardize deployments
How Auto Scaling ensures elasticity
How Load Balancer works with Target Groups
Real-world cloud architecture fundamentals
Hands-on practice like this is helping me strengthen my Cloud Computing foundation step by step 🚀
Currently exploring more in AWS Architecture & DevOps.
