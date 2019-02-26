# :lock: awesome-serverless-security [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of awesome serverless security resources such as (e)books, articles, whitepapers, blogs and research papers.

## Contents
- [AWS Lambda Security](#aws-lambda-security)
- [Security Tools / Solutions](#security-tools--solutions)
- [Azure Functions Security](#azure-functions-security)
- [Google Cloud Functions Security](#google-cloud-functions-security)
- [Serverless Risks / General](#serverless-risks--general)
- [Vulnerabilities, Weaknesses, CVEs](#vulnerabilities-weaknesses-cves)
- [General Application Security Articles, Books](#general-application-security-articles-books)
- [AWS Lambda (General)](#aws-lambda-general)
- [Other Interesting Articles / Web Pages](#other-interesting-articles--web-pages)
## AWS Lambda Security
- [AWS Lambda Security Best-Practices eBook](https://www.puresec.io/aws-lambda-security-best-practices) - PDF eBook covering all the basics such as: Serverless Top 10, IAM roles & permissions, CloudTrail, AWS Config, API Gateway security. 
- [Foundations of AWS Lambda Security](https://www.puresec.io/on-demand-foundations-of-aws-lambda-security) - Webinar recording covering AWS Lambda security basics, IAM permissions, Scalability, Governance. 
- [AWS Lambda Security Quick-Start Guide](https://www.puresec.io/blog/aws-lambda-security-quick-guide) - A quick start guide portraying security strategies for AWS Lambda applications. 
- [AWS Lambda Security - Design for Failure](https://www.puresec.io/blog/aws-security-best-practices-aws-lambda-security-design-for-failure) - Notes on the importance of IAM permissions for AWS Lambda. 
- [Attacking an AWS Account via a Lambda Function](https://www.darkreading.com/cloud/securing-serverless-attacking-an-aws-account-via-a-lambda-function/a/d-id/1333047) - An article from DarkReading, describing attackers and defenders side of a real serverless bounty hunt. 
- [Minimizing the attack surface in Serverless](https://www.slideshare.net/avi_shulman/serverless-minimizing-the-attack-surface) - Presentation covering the basics of serverless attack surfaces. 
- [Gone in 60 milliseconds: Offensive security in the serverless age](https://www.youtube.com/watch?v=byJBR16xUnc) - A presentation video showing attack vectors using cloud event sources, exploitabilities in common serverless patterns and frameworks. 
- [Security Best Practices for Serverless Applications](https://www.slideshare.net/AmazonWebServices/security-best-practices-for-serverless-applications-july-2017-aws-online-tech-talks) -  Basic best-practices for AWS Lambda. 
- [AWS IAM best practices](https://www.slideshare.net/AmazonWebServices/sec305-iam-best-practices-aws-reinvent-2014) - Early AWS materials on IAM best practices. 
- [The Many-Faced Threats to the Serverless World](https://www.slideshare.net/theburningmonk/security-in-serverless-world-96644428) - An article covering most of the basic security risks.
- [How to Encrypt Serverless Environment Variable Secrets with KMS](https://www.metaltoad.com/blog/how-to-encrypt-serverless-environment-variable-secrets-with-kms) - Fundamentals of secrets handling with AWS KMS. 
- [Sharing Secrets with AWS Lambda Using AWS Systems Manager Parameter Store](https://aws.amazon.com/blogs/compute/sharing-secrets-with-aws-lambda-using-aws-systems-manager-parameter-store/) - How to use parameter store for secrets. 
- [A Serverless Journey: AWS Lambda under the hood](https://www.youtube.com/watch?v=QdzV04T_kec) - Great talk on how Lambda works, introduction to Firecracker. 
- [Security Considerations for AWS Lambda Runtime API and Layers](https://www.puresec.io/blog/aws-lambda-security-considerations-runtime-api-and-layers) - A blog post on what to keep in mind when developing with Layers & Runtime API. 
- [The FireCracker Virtual Machine Monitor](https://lwn.net/Articles/775736/) - An analysis of AWS Firecracker. 
- [AWS Lambda Serverless Security Workshop](https://github.com/aws-samples/aws-serverless-security-workshop) - Learn techniques to secure a serverless application built with AWS Lambda, Amazon API Gateway and RDS Aurora (Re:Invent 2018 workshop).
## Security Tools / Solutions
- [PureSec Serverless Security Platform](https://www.puresec.io/product) - The world's first and most advanced end-to-end serverless security platform. 
- [PureSec FunctionShield](https://www.puresec.io/function-shield) - A free AWS Lambda security and Google Cloud Functions library for developers.
- [Automated SQL Injection Testing of Serverless Functions](https://www.puresec.io/blog/automated-sql-injection-testing-of-serverless-functions-on-a-shoestring-budget-and-some-good-music) -  An open source proxy for using SQLMap to test AWS Lambda, natively.
- [Auto-Generate Least Privileged IAM Roles for AWS Lambda](https://www.puresec.io/blog/generating-least-privileged-iam-roles-for-aws-lambda-functions-the-easy-way) - A Serverless framework plugin for automatically generating least privileged roles using static analysis. 
- [OWASP ServerlessGoat](https://www.owasp.org/index.php/OWASP_Serverless_Goat) -  A vulnerable AWS Lambda serverless application. 
- [Secure Serverless CI/CD with Codeship, PureSec, and AWS Lambda](https://blog.codeship.com/secure-serverless-ci-cd-with-codeship-puresec-and-aws-lambda/) - A step by step guide for secure serverless CI/CD.
## Azure Functions Security
- [Azure Functions & Serverless Platform Security](https://gallery.technet.microsoft.com/Azure-Functions-and-c6449f8d) - Some basics on Azure functions security. 
- [Run Your Azure Functions from a Package File](https://docs.microsoft.com/en-us/azure/azure-functions/run-functions-from-deployment-package) - Deploying immutable Azure functions. 
- [Security in Azure App Service & Azure Functions](https://docs.microsoft.com/en-us/azure/app-service/app-service-security) -  More basic concepts for Azure functions. 
- [Identity & Secure Resource Access in App Service & Azure Functions](https://www.youtube.com/watch?v=iFDXDQXRJ8Y) - Explores features in App Service or Azure functions which make working with identities simple (Build Conference). 
- [Secure Azure Functions with JWT access tokens](https://blog.wille-zone.de/post/secure-azure-functions-with-jwt-token/) - A blog post on how to use JWT access tokens with Azure functions.
## Google Cloud Functions Security
- [Function Identity](https://cloud.google.com/functions/docs/securing/function-identity) -  Documentation for Google Cloud Functions IAM and per-function identity.
## Serverless Risks / General
- [CSA: The 12 Most Critical Risks for Serverless Applications 2019](https://www.puresec.io/serverless-security-top-12-csa-puresec) - The most extensive guide on the top risks for serverless applications (Cloud Security Alliance & PureSec).
- [Securing serverless blog series](https://www.puresec.io/blog/tag/securing-serverless-blog-series) - Blog series covering the main differences between security traditional applications and serverless. 
- [Securing Serverless: A Newbie's Guide](https://www.jeremydaly.com/securing-serverless-a-newbies-guide/) - A terrific newbie's guide by Jeremy Daly. 
- [Serverless Security: What are we up against](https://www.youtube.com/watch?v=M7wUanfWs1c&t=2s) - A conference talk from ServerlessDays covering serverless security basics. 
- [Hacking Serverless Runtimes](https://www.blackhat.com/docs/us-17/wednesday/us-17-Krug-Hacking-Severless-Runtimes.pdf) - Good early insights presentation from BlackHat conference 2017.
- [Serverless Security and Things that Go Bump in the Night](https://qconnewyork.com/ny2017/system/files/presentation-slides/serverless_security_and_things_that_go_bump_in_the_night_-_qcon_nyc_2017.pdf) -  QCon NYC presentation by Silvexis covering security basics for serverless.
- [Securing Cloud via Serverless Design Patterns](https://www.usenix.org/system/files/conference/hotcloud18/hotcloud18-paper-hong.pdf) - Six serverless design patterns to build security services in the cloud. 
- [Peeking Behind the Curtains of Serverless Platforms](https://www.usenix.org/system/files/conference/atc18/atc18-wang-liang.pdf) -  Provides insights into architectures, resource utilization, and the performance isolation efficiency of AWS Lambda, GCF and Azure Functions.
- [Serverless Architectures](https://martinfowler.com/articles/serverless.html) - The best overview on serverless architectures. This article provides an in-depth look at serverless architectures. 
## Vulnerabilities, Weaknesses, CVEs
- [ReDoS in NPM package aws-lambda-multipart-parser](https://www.puresec.io/blog/redos-vulnerability-in-aws-lambda-multipart-parser-node-package) - A ReDoS in an NPM package for AWS Lambda functions. 
- [Apache OpenWhisk Action Mutability Weakness](https://www.puresec.io/blog/apache_openwhisk_mutability_weakness) - Two vulnerabilities discovered in Apache OpenWhisk.
- [Serverless Cypto-Mining](https://www.puresec.io/blog/new-attack-vector-serverless-crypto-mining) - Exploiting app layer vulnerabilities in serverless functions to abuse AWS Lambda for crypto-mining.
## General Application Security Articles, Books
- [The Web Application Hacker’s Handbook](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470/) - A classic book on web application security.
- [Web Application Defender’s Cookbook](https://www.amazon.com/Web-Application-Defenders-Cookbook-Protecting/dp/1118362187/) - Another classic, covering ModSecurity protections. 
- [XSS (Cross Site Scripting) Attacks, Exploits & Defense](https://www.amazon.com/XSS-Attacks-Scripting-Exploits-Defense/dp/1597491543/) - The XSS bible covering all aspects of XSS attacks and protections.
- [Hacking Exposed - Web Applications](https://www.amazon.com/Hacking-Exposed-Web-Applications-Third/dp/0071740643) - Another classic book on web application security.
- [Securing DevOps](https://www.manning.com/books/securing-devops?a_aid=securingdevops&a_bid=1353bcd8) -  Tons of real world examples on DevOps and security.
## AWS Lambda (General)
- [Serverless Architectures on AWS](https://www.amazon.com/Serverless-Architectures-AWS-examples-Lambda/dp/1617293822/) - This book teaches you how to build, secure and manage serverless architectures.
- [Tips & Tricks for logging and monitoring AWS Lambda Functions](https://hackernoon.com/tips-and-tricks-for-logging-and-monitoring-aws-lambda-functions-885af6da29a5) - Tips to help you get the most out of your logging and monitoring infrastructure for your functions .
## Other Interesting Articles / Web Pages
- [Google gVisor](https://github.com/google/gvisor) -  GitHub repo for Google gVisor project. 
- [Google gVisor & Google Cloud Functions](https://cloudplatform.googleblog.com/2018/05/Open-sourcing-gVisor-a-sandboxed-container-runtime.html) - A blog post covering Google gVisor and how it is used with Google Cloud Functions.
- [IBM Cloud Functions - Platform Architecture](https://console.bluemix.net/docs/openwhisk/openwhisk_about.html#openwhisk_about) - OpenWhisk & IBM Cloud Functions overview. 
## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
To the extent possible under law, [PureSec](https://www.puresec.io) has waived all copyright and related or neighboring rights to this work.
