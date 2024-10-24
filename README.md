# onetime-secret
onetime secret - docker-compose file - ideal for AWS Lightsail

Create a AWS Lightsail instance (AWS Linux 2) - IMPORTANT, read below first!

Copy contents from the lightsail script in this repo into the startup scrip when you create the instqance!

Add port 3000 as a custom TCP Port to the instance

Once instance has started, copy public IP address, make sure to add the port 3000 to HTTP address
e.g.: http://1.2.3.4:3000

