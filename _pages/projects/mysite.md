---
title: "AWS Hosted Personal Site"
excerpt: "AWS hosted with CI/CD pipeline integration"
sitemap: true
permalink: /projects/mysite.html
author_profile: false
classes: wide

---

## Project Overview
The goal of this project was to build and host my personal website to showcase my professional interestes and work experience.  While I very easily could have hosted this site using a service like Wix.com, I purposely leveraged my background in Cloud computing to design a solution leveraging high availiablity and automation to host my site.


## The Stack

### ![Jekyll](/assets/images/logo-jekyll.png){:height="100" width="200"} | [https://jekyllrb.com/](https://jekyllrb.com/){:target="_blank"}
Jekyll is a Ruby based static site generator. You give it text written in your favorite markup language and it uses layouts to create a static website. You can tweak how you want the site URLs to look like, what data gets displayed on the site, and more.  

### ![Github](/assets/images/logo-github.png){:height="100" width="200"} | [https://github.com/](https://github.com/){:target="_blank"}
All code and configurations for the Jekyll sites is maintenace in a Github repo.  In the next phase of this project I will be looking into build a full CI/CD pipeline with Travis Ci.  All builds will be tested and automatic deployments following a succesful test.

### ![Terraform](/assets/images/logo-terraform.svg){:height="100" width="200"} |  [https://terraform.io/](https://www.terraform.io/){:target="_blank"}
Terraform is a tool by Hashi Corp, that uses Infrastructure as Code to provision and manage any cloud, infrastructure, or service.  For this project all the Amazon Web Services infrasture was created and deployed custom Terraform code that developed.

### ![AWS](/assets/images/logo-aws.png){:height="100" width="200"} | [https://aws.com/](https://www.aws.com/){:target="_blank"}
All the hosting of this site is being done within the Amazon Web Services environment.  This includes all storage, DNS, Certificate and CDN hosting of the site.  Click below for a datailed view of the platform.

[AWS Setup Details](/projects/awssetup.html)



