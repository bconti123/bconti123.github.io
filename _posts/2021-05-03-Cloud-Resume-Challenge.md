---
post: Cloud Resume Challenge
---

I am excited to explain about topic! I enjoyed my work about the challenge. It is very worth to try and great learning. I love sharing my fun work experience from <a href="https://cloudresumechallenge.dev/">Forrest Brazeal Cloud Resume Challenge</a>. It took me one month around.

<h3>Certification</h3>
I passed AWS Certified Cloud Practitioner then AWS Certified Solutions Architect Associate on August 2020. My senior class taught me about AWS that is based on AWS Certified Cloud Practitioner and I finished AWS project with team in senior design class for fall semester 2019 and spring semester 2020. After I gradaute on May 2020 with Bachelor of Science degree in Computer Information Technology, I continue study cloud computing because it became my passion, then I restudied AWS Certified Cloud Practioner from any online sources like Udemy, Digital Cloud Training, and other. I didn't know that Cloud Resume Challenge help me to earn good hands-on experience.

<h3>HTML, CSS, and JavaScript</h3>
I already have resume website that what I found good website template from GitHub. This is easy part. I modified resume website. I have HTML, CSS, and JavaScript knowledges for more than 4 years. I choose React as a web framework because it is more challenge!

<h3>Host Static Website on S3</h3>
I created an bucket named my domain name that is needed to meet the requirement. I read the AWS documentations and research something on google searching. It is easy to understandable. But make sure you edit package.json and add s3 sync build... to package.json for deploy in CLI. Check google and AWS documentations about S3 CLI how to upload website to S3 bucket.

<h3>CloudFront and Route 53</h3>
Create CloudFront Distribution that makes S3 website as HTTPS like https://www.example.com. I had more errors and learned lot from my mistake to created CloudFront Distribution URL that is reachable successfully. I bought bryantconti.com from Route 53 and added record as CNAME from ACM. Oh cool! I added blog.bryantconti.com too. I have a blog website that is deployed as host static website from GitHub. I use blog.bryantconti.com for that. 

<h3>DynamoDB, Lambda, and API Gateway for view counter.</h3>
This is hardest part ever. Took me 2 weeks around and many mistake. I tried to google a lot of things. Reading the AWS documentations and other online sources about Lambda and API Gateway. I fought many errors. I used Python for handler function. Lambda tells API Gateway about the number of views from DynamoDB. API Gateway URL tells JavaScript. Running code will display how many view in resume website. I learned lesson about DynamoDB. One Partition key is needed. That all.

<h3>Python tests, Unit Test</h3>
I never write any testing script before. I googled something about how to test lambda handler function. I copied something in lambda handler function to other script. I was struggling with python script utlizing unit test. I needed one or two scripts. Test script talks to the function script about view count that is passed or failed. Keep googling, trying, and learning from errors until script is successful. 

<h3>Serverless Application Model, Infrastructure as Code</h3>
I love SAM! It creates any AWS services for me instead manually, I clicked around in the AWS console to make my point finger tired. Serverless CLI is amazing and easy to use for build and deploy. SAM guide is easy to google. Always learn mistake and fix errors in YAML file. I kept trying until YAML script works but I checked API gateway setting and DynamoDB are not correct setting. I can't make API Gateway endpoint as Regional but I found source from google that I solved endpoint configuration that make it as Regional. I deleted stack in CloudFormation to destroy what YAML script did make AWS services and recreate stack. Now the script made all AWS setting is correct what I want.  

<h3>CI/CD for frontend and backend</h3>
I set up GitHub Actions for frontend and backend to automate code and AWS resources to set up them. It saves my time lot! GitHub Action is easy to use because there are many tools as AWS in <a href="https://github.com/marketplace?type=actions">GitHub Marketplace</a> can improve workflows and to save time. My mistake is to make too many commit along GitHub workflows and push them to repository for checking CI/CD works or not. I kept fixing workflows and getting errors until sucessful. I didn't know GitHub repo has a secrets option for AWS credential. It is safe and provides security. Never put AWS credentials in any code! Otherwise, you will get hacked. I should test github workflows locally instead. I learned lesson. Good to know there is an <a href="https://github.com/nektos/act">act CLI package</a> you can use for testing github workflows locally.

<h3>Conclusion</h3>
Cloud Resume Challenge improved my skills and knowledges so much. I am more confident with my improved skills for future. I really enjoyed working on the project and learning new technology and software tools. I will keep learning more hands-on projects and new software tools. If you need cloud experience, you should try Cloud Resume Challenge that is best helpful. I am sure your skills and knowledges will be big improvement.