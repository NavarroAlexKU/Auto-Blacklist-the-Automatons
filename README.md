# Auto-Blacklist-the-Automations

![ScreenShot](https://github.com/NavarroAlexKU/Auto-Blacklist-the-Automatons/blob/main/AWS%20Security%20Logo.png)

## Project Objective:
Secure the web application infrastructure by automating the blacklist of IP addresses that are trying to crawl into our infrastructure. 

## Author:
[Alex Navarro]
[https://github.com/NavarroAlexKU]

## 🔗 Social Media Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexnavarro2/)

## Project Walk-Through:

1.) We will start by implementing the AWS WAF and create a web ACL

![ScreenShot](https://github.com/NavarroAlexKU/Auto-Blacklist-the-Automatons/blob/main/AWS%20WAF.jpeg)

### What is AWS WAF?
* AWS WAF is a web application firewall that lets you montior the HTTP & HTTPS requests that are forwarded to an Amazon Cloudfront or application load balancer. This AWS service operates at the Application layer (layer 7) of the OSI model.

    a.) go to the AWS Management Console and Search AWS WAF or go to "Security, Indentity, & Compliance" and you can find the service there.

    ![ScreenShot](https://github.com/NavarroAlexKU/Auto-Blacklist-the-Automatons/blob/main/Screenshot%202022-11-19%20at%2012.07.11%20PM.png)

    You'll then be brought to AWS WAF homepage, click "Create web ACL"

    ![ScreenShot](https://github.com/NavarroAlexKU/Auto-Blacklist-the-Automatons/blob/main/Screenshot%202022-11-19%20at%201.25.47%20PM.png)

* Naming and Configuring the Web ACL
    - Nameing AWS WAF
    - Description "Optional"
    - CloudWatch Metric Name
    for now we're just going to give it a name and click next.

    ![ScreenShot](https://raw.githubusercontent.com/NavarroAlexKU/Auto-Blacklist-the-Automatons/88bce98b653a5f8542b52ace064c1b072d83768e/Screenshot%202022-11-19%20at%201.35.07%20PM.png)