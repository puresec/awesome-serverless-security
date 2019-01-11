# :lock: awesome-serverless-security
A curated list of awesome serverless security resources

## AWS Lambda Security

| Title  | Description | Published By | Link
| -------| ------------ | ----------- | ----
|  AWS Lambda Security Best-Practices eBook  | PDF eBook covering all the basics such as: Serverless Top 10, IAM roles & permissions, CloudTrail, AWS Config, API Gateway security, etc. | PureSec | [link](https://www.puresec.io/aws-lambda-security-best-practices) |
|  AWS Lambda Security Quick-Start Guide  | A quick start guide portraying security strategies for AWS Lambda applications | PureSec | [link](https://www.puresec.io/blog/aws-lambda-security-quick-guide]) |
|  AWS Lambda Security - Design for Failure  | Important notes on the importance of IAM permissions for AWS Lambda | PureSec | [link](https://www.puresec.io/blog/aws-security-best-practices-aws-lambda-security-design-for-failure) | 
|  Attacking an AWS Account via a Lambda Function  | An article on DarkReading, describing attackers/defenders side of a real serverless bounty hunt | DarkReading | [link](https://www.darkreading.com/cloud/securing-serverless-attacking-an-aws-account-via-a-lambda-function/a/d-id/1333047?) | 
|  Minimizing the attack surface in Serverless  | Presentation | PureSec | [link](https://www.slideshare.net/avi_shulman/serverless-minimizing-the-attack-surface) |
|  Gone in 60 milliseconds: Offensive security in the serverless age (Rich Jones)  | A must-see | Rich Jones (YouTube) | [link](https://www.youtube.com/watch?v=byJBR16xUnc) | 
|  Security Best Practices for Serverless Applications (AWS tech talk)  | Basic best-practices for AWS Lambda | AWS | [link](https://www.slideshare.net/AmazonWebServices/security-best-practices-for-serverless-applications-july-2017-aws-online-tech-talks) | 
|  AWS IAM best practices (AWS Re:Invent 2014)  | Early AWS materials on IAM best practices | AWS | [link](https://www.slideshare.net/AmazonWebServices/sec305-iam-best-practices-aws-reinvent-2014) |
|  The Many-Faced Threats to the Serverless World  | A classic, covers most of the basic security risks | Yan Cui | [link](https://www.slideshare.net/theburningmonk/security-in-serverless-world-96644428) | 
|  How to Encrypt Serverless Environment Variable Secrets with KMS  | Basic secrets handling with KMS |  Dylan Tack | [link](https://www.metaltoad.com/blog/how-to-encrypt-serverless-environment-variable-secrets-with-kms]) |
|  Sharing Secrets with AWS Lambda Using AWS Systems Manager Parameter Store (AWS)  | How to use parameter store for secrets | AWS | [link](https://aws.amazon.com/blogs/compute/sharing-secrets-with-aws-lambda-using-aws-systems-manager-parameter-store/) | 
|  A Serverless Journey: AWS Lambda under the hood | Great talk on how Lambda works, intro to Firecracker | AWS (Re:Invent 2018 video)  | [link](https://www.youtube.com/watch?v=QdzV04T_kec) | 
|  Security Considerations for AWS Lambda Runtime API and Layers  | Things to keep in mind when developing with Layers & Runtime API | PureSec | [link](https://www.puresec.io/blog/aws-lambda-security-considerations-runtime-api-and-layers) | 
|  The (AWS) FireCracker Virtual Machine Monitor  | An analysis of Firecracker | Azhar Desai | [link](https://lwn.net/Articles/775736/) |
| AWS Lambda Serverless Security Workshop | Learn techniques to secure a serverless application built with AWS Lambda, Amazon API Gateway and RDS Aurora (Re:Invent 2018 workshop)| AWS | [link](https://github.com/aws-samples/aws-serverless-security-workshop)

### Security Tools / Solutions

| Title  | Description | Published By | Link
| -------| ------------ | ----------- | ----
|  PureSec Serverless Security Platform  | The world's first and most advanced end-to-end serverless security platform | PureSec | [link](https://www.puresec.io/product) |
|  PureSec FunctionShield  |  a free AWS Lambda security library for developers | PureSec | [link](https://www.puresec.io/function-shield) | 
|  Automated SQL Injection Testing of Serverless Functions  | An open source proxy for using SQLMap to test AWS Lambda, natively | PureSec | [link](https://www.puresec.io/blog/automated-sql-injection-testing-of-serverless-functions-on-a-shoestring-budget-and-some-good-music) | 
|  Auto-Generate Least Privileged IAM Roles for AWS Lambda  | A Serverless framework plugin for automatically generating least privileged roles using static analysis | PureSec | [link](https://www.puresec.io/blog/generating-least-privileged-iam-roles-for-aws-lambda-functions-the-easy-way) |
|  OWASP ServerlessGoat  | A vulnerable AWS Lambda serverless application | OWASP | [link](https://www.owasp.org/index.php/OWASP_Serverless_Goat) |
|  Secure Serverless CI/CD with Codeship, PureSec, and AWS Lambda  | A step by step guide for secure serverless CI/CD | CodeShip & PureSec | [link](https://blog.codeship.com/secure-serverless-ci-cd-with-codeship-puresec-and-aws-lambda/) | 

## Azure Functions Security

| Title  | Description | Published By | Link
| -------| ------------ | ----------- | ----
|  TechNet Article: Azure Functions & Serverless Platform Security  | Some basics on Azure functions security | Microsoft | [link](https://gallery.technet.microsoft.com/Azure-Functions-and-c6449f8d) | 
|  Run Your Azure Functions from a Package File  | Immutable Azure functions | Microsoft | [link](https://docs.microsoft.com/en-us/azure/azure-functions/run-functions-from-deployment-package) | 
|  Security in Azure App Service & Azure Functions  | More basics | Microsoft | [link](https://docs.microsoft.com/en-us/azure/app-service/app-service-security) | 
|  Identity & Secure Resource Access in App Service & Azure Functions  | Explores features in App Service or Azure Functions which make working with identities simple (Build Conference) | Microsoft (YouTube) | [link](https://www.youtube.com/watch?v=iFDXDQXRJ8Y) | 
|  Secure Azure Functions with JWT access tokens  | Blog post | Boris Wilhelms | [link](https://blog.wille-zone.de/post/secure-azure-functions-with-jwt-token/) | 

## Serverless Risks / General

| Title  | Description | Published By | Link
| -------| ------------ | ----------- | ----
|  The Ten Most Critical Risks for Serverless Applications v1.0 (Guide)  | The most comprehensive list of risks to serverless applications | PureSec/Community | [link](https://github.com/puresec/sas-top-10) |
|  Securing Serverless (Blog Series, by PureSec)  | Blog series covering the main differences between security traditional applications and serverless | PureSec | [link](https://www.puresec.io/blog/tag/securing-serverless-blog-series) |
|  Securing Serverless: A Newbie's Guide (Jeremy Daly)  | A terrific newbie's guide | Jeremy Daly | [link](https://www.jeremydaly.com/securing-serverless-a-newbies-guide/) | 
|  Serverless Security: What are we up against (Talk)  | Conference Talk (ServerlessDays) | Ory Segal | [link](https://www.youtube.com/watch?v=M7wUanfWs1c&t=2s) |
|  Unraveling the truth around serverless security | A discussion between Rupak Ganguly  (Serverless Inc.) and Ory Segal (CTO, PureSec) | (Serverless Inc + PureSec Webinar)  | [link](https://www.youtube.com/watch?v=a5RfAMOrEW0) | 
|  Hacking Serverless Runtimes: Profiling Lambda, Azure and More (BlackHat presentation)  | Good early insights | Andrew Krug, Graham Jones (BlackHat Conf.) | [link](https://www.blackhat.com/docs/us-17/wednesday/us-17-Krug-Hacking-Severless-Runtimes.pdf) |
|  Serverless Security & Things that Go Bump in the Night  | QCon NYC | Erik Peterson / CloudZero | [link](https://qconnewyork.com/ny2017/system/files/presentation-slides/serverless_security_and_things_that_go_bump_in_the_night_-_qcon_nyc_2017.pdf) |
|  Go Serverless: Securing Cloud via Serverless Design Patterns (whitepaper)  | Six serverless design patterns to build security services in the cloud | Sanghyun Hong, Abhinav Srivastava, William Shambrook, Tudor Dumitras | [link]( https://www.usenix.org/system/files/conference/hotcloud18/hotcloud18-paper-hong.pdf) |
| Peeking Behind the Curtains of Serverless Platforms | Provides insights into architectures, resource utilization, and the performance isolation efficiency of AWS Lambda, GCF and Azure Functions (pdf)| Liang Wang, Mengyuan Li, Yinqian Zhang, Thomas Ristenpart, Michael Swift | [link](https://www.usenix.org/system/files/conference/atc18/atc18-wang-liang.pdf)
| Serverless Architectures | THE overview on Serverless Architectures. This article provides an in-depth look at serverless architecture | Mike Roberts (at MartinFowler.com) | [link](https://martinfowler.com/articles/serverless.html)


## Vulnerabilities, Weaknesses & CVEs

| Title  | Description | Published By | Link
| -------| ------------ | ----------- | ----
|  ReDoS in NPM package 'aws-lambda-multipart-parser'  | A ReDoS in an NPM package used to attack AWS Lambda applications | PureSec / CVE | [link](https://www.puresec.io/blog/redos-vulnerability-in-aws-lambda-multipart-parser-node-package) |
|  Apache OpenWhisk Action Mutability Weakness  | 2 vulnerabilities discovered in Apache OpenWhisk (CVEs) | PureSec | [link](https://www.puresec.io/blog/apache_openwhisk_mutability_weakness) | 
|  Serverless Cypto-Mining  | Exploiting app layer vulnerabilities in serverless functions to abuse AWS Lambda for crypto-mining | PureSec | [link](https://www.puresec.io/blog/new-attack-vector-serverless-crypto-mining) | 

## General Application Security Articles & Books

| Title  | Description | Published By | Link
| -------| ------------ | ----------- | ----
|  The Web Application Hacker’s Handbook  | A classic book (Book, Amazon)| Dafydd Stuttard, Marcus Pinto | [link](https://www.amazon.com/Web-Application-Hackers-Handbook-Exploiting/dp/1118026470/) |
|  Web Application Defender’s Cookbook (Book, Amazon)  | Another classic, covering ModSecurity | Ryan Barnett | [link](https://www.amazon.com/Web-Application-Defenders-Cookbook-Protecting/dp/1118362187/) |
|  XSS (Cross Site Scripting) Attacks, Exploits & Defense  | The XSS bible (Book, Amazon)|  Seth Fogie, Jeremiah Grossman, Robert Hansen, Anton Rager, Petko D. Petkov  | [link](https://www.amazon.com/XSS-Attacks-Scripting-Exploits-Defense/dp/1597491543/) |
|  Hacking Exposed - Web Applications  | A Classic (Book, Amazon)| Joel Scambray, Vincent Liu, Caleb Sima | [link](https://www.amazon.com/Hacking-Exposed-Web-Applications-Third/dp/0071740643) | 
|  Securing DevOps  | Tons of real world examples (Book, Manning) | Julien Vehent | [link](https://www.manning.com/books/securing-devops?a_aid=securingdevops&a_bid=1353bcd8) |

## AWS Lambda (General)

| Title  | Description | Published By | Link
| -------| ------------ | ----------- | ----
|  Serverless Architectures on AWS  | Teaches you how to build, secure and manage serverless architectures (Book, Amazon)| Peter Sbarski | [link](https://www.amazon.com/Serverless-Architectures-AWS-examples-Lambda/dp/1617293822/) |
|  Tips & Tricks for logging and monitoring AWS Lambda Functions  | Tips to help you get the most out of your logging and monitoring infrastructure for your functions | Yan Cui | [link](https://hackernoon.com/tips-and-tricks-for-logging-and-monitoring-aws-lambda-functions-885af6da29a5) |

## Other Interesting Articles / Web Pages

| Title  | Description | Published By | Link
| -------| ------------ | ----------- | ----
|  Google gVisor:  | Github repo | Google | [link](https://github.com/google/gvisor) |
|  Google gVisor & Google Cloud Functions  | Blog post | Google | [link](https://cloudplatform.googleblog.com/2018/05/Open-sourcing-gVisor-a-sandboxed-container-runtime.html) |
|  IBM Cloud Functions - Platform Architecture  | OpenWhisk & IBM Cloud Functions overview | IBM | [link](https://console.bluemix.net/docs/openwhisk/openwhisk_about.html#openwhisk_about) |

