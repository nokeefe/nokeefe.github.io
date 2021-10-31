---
author: toomanyadmins
comments: false
date: 2021-01-12 00:26:57+00:00
layout: page
link: https://nokeefe.com/
slug: create-your-website-with-blocks
title: Projects
wordpress_id: 5
---




## Projects







## [Simple Button App](https://simple-button-app.herokuapp.com/)







Wanting to have fun with a tech challenge... I put together a quick web app that displays something cool when you click the button. Tested and deployed via CircleCI, onto Heroku.










https://vimeo.com/499862084


Wingmates in action














## [Terraform & AWS](https://github.com/nokeefe/terraform-aws)







A personal project to become familiar with industry best practices and the how-to of initializing AWS resources with Terraform. The project initializes an EC2 instance, creates VPCs and subnets, and configures and attaches a security group to specified hardware. Auto-scaling group configured to scale depending on traffic and/or EC2 availability.






















## [AWS Image Build](https://github.com/nokeefe/aws-image-build)







Puppet and Bash were used to manage Hashicorp Packer to create a custom AWS ami image based on modules specified in my Terraform-AWS project. When used as the ami in a Terraform project, it can be further modified as the user sees fit._ _







_Suprising (to me), the ami costs money to host on AWS :(_









































![“Roses Tremieres” by Berthe Morisot](https://nokeefe.com/wp-content/themes/twentytwentyone/assets/images/roses-tremieres-hollyhocks-1884.jpg)









![“In the Bois de Boulogne” by Berthe Morisot](https://nokeefe.com/wp-content/themes/twentytwentyone/assets/images/in-the-bois-de-boulogne.jpg)















![“Young Woman in Mauve” by Berthe Morisot](https://nokeefe.com/wp-content/themes/twentytwentyone/assets/images/young-woman-in-mauve.jpg)





























## Wondering how this site is live?
















### App Server







This WordPress site in running on a t2.micro EC2 instance via Amazon Web Services (AWS); chosen to be cost-efficient while still providing enough oomph for a personal website.







### Further instance details







To get the server up and running quickly with the dependencies I needed, I created and used Terraform in conjunction with a Puppet manifest for certain installations.







A LEMP stack was used mostly due to prior familiarization with Nginx and its configurations in my Terraform plan. 













### Authoritative Name Servers







I chose two additional t2.nano instances for the name servers for the same reason they were chosen for the app server - namely, cost-efficiency. Bind9 was a natural choice.







_Originally I utilized two t2.micro instances but switched to t2.nano after reviewing my usage with rightsizing recommendations._







### Not sure what a Name Server is?







When you type in a web address like [this one](http://nokeefe.com) and hit enter, your browser will look in its cache, or history, to see if it knows the page. If it doesn't, it will contact other servers to see if they know the corresponding IP address to the web site. 







A name server in particular can receive a query for the domain in question's IP address and attempts to send the information back to the browser or other server that made the query. This is a very high level overview of the Domain Name System.































Have a question?







[Message me on LinkedIn](https://www.linkedin.com/in/nbokeefe/)


















