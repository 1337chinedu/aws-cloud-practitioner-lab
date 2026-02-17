Today, I got hands-on with Elastic Load Balancer (ELB) and Auto Scaling Group (ASG) in my AWS Cloud Practitioner course.

I launched 2 EC2 instances and used an Application Load Balancer to route traffic through one URL. After that, I terminated both instances and created an Auto Scaling Group with a desired capacity of 2, attached to the same target group.

AWS automatically recreated the instances when terminated and kept everything accessible through the same single link.

What I learned:
◾ Load balancers distribute traffic across multiple instances
◾ Auto Scaling Groups automatically create and manage EC2 instances
◾ Target groups connect ELB and ASG seamlessly
◾ Scalability and fault tolerance are built into cloud design

Still learning and documenting the journey one module at a time.
