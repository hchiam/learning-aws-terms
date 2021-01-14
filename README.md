# Learning AWS (Amazon Web Services) terms in plain English

Just one of the things I'm learning. <https://github.com/hchiam/learning>

<https://expeditedsecurity.com/aws-in-plain-english>

## App services

1. EC2 = virtual servers
2. IAM = users/keys/certs "I am" who
3. S3 = FTP server (file/site storage + transfer); "SSS" "Site Storage Server"
4. VPC = virtually show as 1 network
5. Lambda = sounds like [Google Apps Script](https://github.com/hchiam/learning-google-apps-script) but for AWS

## Web app dev services

6. API Gateway = API proxy (can test with?)
7. RDS = "Remote DB Service" (?)
8. Route53 = DNS domains, like GoDaddy
9. SES = simple email service for notifications / email resets
   10 Cloudfront = CDN
10. CloudSearch = text search in files (S3) and DB (RDS)
11. DynamoDB = NoSQL `{k:v}`
12. Elasticache = distributed memory caching
13. Elastic Transcoder = video handler
14. SQS = data queue
15. WAF = firewall (e.g. vs. DDOS)

## Mobile app dev services

17. Cognito = mobile OAuth service (NOT INcognito)
18. Device Farm = mobile test service
19. Mobile Analytics
20. SNS = mobile notifications but also emails & texts (so > SES)

## DevOps + deployment services

21. CodeCommit = version control, like GitHub
22. Code Deploy = like Heroku or Glitch.com or surge.sh
23. CodePipeline = CI, like TravisCI to autotest and trigger GitHub Actions
24. EC2 Container Service = virtual server container service, like Docker service
25. Elastic Beanstalk = PaaS: basically like Heroku, but an upgraded app host on AWS instead

## Business/network services

26. AppStream = rdp/Citrix but only access an app (compare with 30: Workspaces)
27. Direct Connect = dedicated line / connection (?)
28. Directory Service = used for connecting apps that need a MS Active Directory to control them
29. WorkDocs = like Dropbox
30. WorkMail = company email and calendar
31. Workspaces = rdp but access full desktop (compare with 26: AppStream)
32. Service Catalog = preset apps ready for use
33. Storage Gateway = connect FTP Server (S3) with your corporate network

## Big data services

34. Data Pipeline = data ETL: data Extraction, Transform, & Loading (within AWS) (can schedule and get failure alerts)
35. Elastic Map Reduce = for big data S3 FTP text files processing (sounds superficially like [MapReduce](https://en.wikipedia.org/wiki/MapReduce) at [Google](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf))
36. Glacier = long-term archive for S3 (FTP server) (slow read/get?)
37. Kinesis = fast big data processing for other AWS services to use
38. RedShift = data analytics, processing, & output
39. Machine Learning
40. SWF = virtual servers queue of "deciders" + "workers" ("Server WorkForce" - it actually stands for "Simple Workflow") (compare with 15: SQS "data queue" != this)
41. Snowball = hard drive storage connected to network

## AWS management services

42. CloudFormation = AWS services setup
43. CloudTrail = AWS logging of API calls
44. CloudWatch = AWS failure alerts
45. Config = AWS centralized setup changes tracker
46. OpsWorks = ? app run management, like auto-scaling ?
47. Trusted Advisor = AWS setup non-usage identifier
48. Inspector = AWS setup security checker
