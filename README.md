# :lock: awesome-serverless-security
A curated list of awesome serverless security resources

## AWS Lambda Security:
* AWS Lambda Security Best-Practices eBook [link](https://www.puresec.io/aws-lambda-security-best-practices)
* AWS Lambda Security Quick-Start Guide [link](https://www.puresec.io/blog/aws-lambda-security-quick-guide])
* AWS Lambda Security - Design for Failure [link](https://www.puresec.io/blog/aws-security-best-practices-aws-lambda-security-design-for-failure) 
* Attacking an AWS Account via a Lambda Function [link](https://www.darkreading.com/cloud/securing-serverless-attacking-an-aws-account-via-a-lambda-function/a/d-id/1333047?) 
* Minimizing the attack surface in Serverless [link](https://www.slideshare.net/avi_shulman/serverless-minimizing-the-attack-surface)
* Gone in 60 milliseconds: Offensive security in the serverless age (Rich Jones) [link](https://www.youtube.com/watch?v=byJBR16xUnc) 
* Security Best Practices for Serverless Applications (AWS tech talk) [link](https://www.slideshare.net/AmazonWebServices/security-best-practices-for-serverless-applications-july-2017-aws-online-tech-talks) 
* AWS IAM best practices (AWS Re:Invent 2014) (link)[https://www.slideshare.net/AmazonWebServices/sec305-iam-best-practices-aws-reinvent-2014] 
* The Many-Faced Threats to the Serverless World (link)[https://www.slideshare.net/theburningmonk/security-in-serverless-world-96644428] 
* How to Encrypt Serverless Environment Variable Secrets with KMS (link)[https://www.metaltoad.com/blog/how-to-encrypt-serverless-environment-variable-secrets-with-kms] 
* Sharing Secrets with AWS Lambda Using AWS Systems Manager Parameter Store (AWS) [link](https://aws.amazon.com/blogs/compute/sharing-secrets-with-aws-lambda-using-aws-systems-manager-parameter-store/) 
* A Serverless Journey: AWS Lambda under the hood (Re:Invent 2018 video) [link](https://www.youtube.com/watch?v=QdzV04T_kec) 
* Security Considerations for AWS Lambda Runtime API and Layers [link](https://www.puresec.io/blog/aws-lambda-security-considerations-runtime-api-and-layers) 
* The (AWS) FireCracker Virtual Machine Monitor [link](https://lwn.net/Articles/775736/)

### Tools / Solutions
* PureSec Serverless Security Platform: https://www.puresec.io/product
* PureSec FunctionShield: a free AWS Lambda security library for developers: https://www.puresec.io/function-shield 
* Automated SQL Injection Testing of Serverless Functions on a Shoestring Budget (and some Good Music): https://www.puresec.io/blog/automated-sql-injection-testing-of-serverless-functions-on-a-shoestring-budget-and-some-good-music 
* Generating Least Privileged IAM Roles for AWS Lambda Functions - The Easy Way: https://www.puresec.io/blog/generating-least-privileged-iam-roles-for-aws-lambda-functions-the-easy-way
* OWASP ServerlessGoat: A vulnerable AWS Lambda serverless application + lessons and cheat sheet: https://www.owasp.org/index.php/OWASP_Serverless_Goat


## Azure Functions Security:
* TechNet Article: Azure Functions & Serverless Platform Security: https://gallery.technet.microsoft.com/Azure-Functions-and-c6449f8d 
* Run Your Azure Functions from a Package File: https://docs.microsoft.com/en-us/azure/azure-functions/run-functions-from-deployment-package 
* Security in Azure App Service & Azure Functions: Functions: https://docs.microsoft.com/en-us/azure/app-service/app-service-security 
* Identity & Secure Resource Access in App Service & Azure Functions: https://www.youtube.com/watch?v=iFDXDQXRJ8Y 
* Secure Azure Functions with JWT access tokens: https://blog.wille-zone.de/post/secure-azure-functions-with-jwt-token/ 

## Serverless / Function as a Service (FaaS) Security and Serverless Risks:
* The Ten Most Critical Risks for Serverless Applications v1.0 (Guide): https://github.com/puresec/sas-top-10
* Securing Serverless (Blog Series): https://www.puresec.io/blog/tag/securing-serverless-blog-series
* Securing Serverless: A Newbie's Guide: https://www.jeremydaly.com/securing-serverless-a-newbies-guide/ 
* Serverless Security: What are we up against? https://www.youtube.com/watch?v=M7wUanfWs1c&t=2s
* Unraveling the truth around serverless security: https://www.youtube.com/watch?v=a5RfAMOrEW0 
* Hacking Serverless Runtimes: Profiling Lambda, Azure and More (presentation): https://www.blackhat.com/docs/us-17/wednesday/us-17-Krug-Hacking-Severless-Runtimes.pdf
* Serverless Security & Things that Go Bump in the Night: https://qconnewyork.com/ny2017/system/files/presentation-slides/serverless_security_and_things_that_go_bump_in_the_night_-_qcon_nyc_2017.pdf 
* Go Serverless: Securing Cloud via Serverless Design Patterns (whitepaper): https://www.usenix.org/system/files/conference/hotcloud18/hotcloud18-paper-hong.pdf
* Secure Serverless CI/CD with Codeship, PureSec, and AWS Lambda: https://blog.codeship.com/secure-serverless-ci-cd-with-codeship-puresec-and-aws-lambda/ 

## General Application Security Articles & Books:
* The Web Application Hacker’s Handbook: https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470/
* Web Application Defender’s Cookbook: https://www.amazon.com/Web-Application-Defenders-Cookbook-Protecting/dp/1118362187/
* XSS (Cross Site Scripting) Attacks, Exploits & Defense: https://www.amazon.com/Attacks-CROSS-SCRIPTING-EXPLOITS-DEFENSE-ebook
* Hacking Exposed - Web Applications (still one of my favorites, oldie but goodie): https://www.amazon.com/Hacking-Exposed-Web-Applications-Third/dp/0071740643 
* Securing DevOps: https://www.manning.com/books/securing-devops?a_aid=securingdevops&a_bid=1353bcd8 

## AWS Lambda (General):
* Serverless Architectures on AWS: https://www.amazon.com/Serverless-Architectures-AWS-examples-Lambda/dp/1617293822/
* Tips & Tricks for logging and monitoring AWS Lambda Functions: https://hackernoon.com/tips-and-tricks-for-logging-and-monitoring-aws-lambda-functions-885af6da29a5

## Other Interesting Articles / Web Pages:
* Google gVisor: https://github.com/google/gvisor
* Google gVisor & Google Cloud Functions: https://cloudplatform.googleblog.com/2018/05/Open-sourcing-gVisor-a-sandboxed-container-runtime.html
* IBM Cloud Functions - Platform Architecture: https://console.bluemix.net/docs/openwhisk/openwhisk_about.html#openwhisk_about

## Vulnerabilities, Weaknesses & CVEs:
* ReDoS in NPM package 'aws-lambda-multipart-parser': https://www.puresec.io/blog/redos-vulnerability-in-aws-lambda-multipart-parser-node-package
* Apache OpenWhisk Action Mutability Weakness: https://www.puresec.io/blog/apache_openwhisk_mutability_weakness 
* Serverless Cypto-Mining: https://www.puresec.io/blog/new-attack-vector-serverless-crypto-mining 


