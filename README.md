# FINAL-FRT-PROJECT
E-SHOPPER is a E-commerce webite which is created using HTML CSS and JAVASCRIPT languge. ![Screenshot (91)](https://github.com/SOHEL9764/FINAL-FRT-PROJECT/assets/129665439/4fbbc62e-4fbf-4105-96ad-07a480ffcfe4)
Website is running in virtual machine IIS web server.![Screenshot (92)](https://github.com/SOHEL9764/FINAL-FRT-PROJECT/assets/129665439/237b58a2-fac6-4d63-8195-163e47d0ad93)
To provide high availability and scalability I am using second azure service which is virtual machine scale set.![Screenshot (93)](https://github.com/SOHEL9764/FINAL-FRT-PROJECT/assets/129665439/b89111ec-5f9a-4a75-8001-5b1cddd6984c)
This is scaling rule which is defined in VMSS that when the traffic to website is too high during holidays or peak hours of the day and cpu utilization exceeds 75% then virtual machine scale set instance count will increase by 1.![Screenshot (94)](https://github.com/SOHEL9764/FINAL-FRT-PROJECT/assets/129665439/13b5365b-88a0-45df-b2fb-df18a0509052)
Furthermore To provide high availability I am using 3rd AZURE service which is AZURE LOAD BALANCER.![Screenshot (95)](https://github.com/SOHEL9764/FINAL-FRT-PROJECT/assets/129665439/1a58e1f8-ce9e-4901-a067-3c0a9b1aaf53)
As per our scaling policy rule if CPU utilization is below 25% then there will be only one virtual machine instance and that can be verify with this image that there is only one VM's instance running in load balancer backend.![Screenshot (96)](https://github.com/SOHEL9764/FINAL-FRT-PROJECT/assets/129665439/f4f739f1-0461-4977-8602-4fdb491eaa4f)
This load balancer will route incomming traffic across numbers of virtual machine instances based on the scaling policy to provide users high availability during holidays or peak hours of the day when traffic to our website is high.![Screenshot (97)](https://github.com/SOHEL9764/FINAL-FRT-PROJECT/assets/129665439/841c5490-157f-4a8a-8ead-a0387bf6190f)
Hence this project solves our problem to provide high availabity and scalabilty to our application and meet those demands, Thanks for giving your valuable time, Regards SOHEL SHAIKH.
