---
post: Cloud Resume Challenge
---

I am excited to explain the topic! I enjoyed my work about the challenge. It is very worth trying and great learning. I love to share my experience from <a href="https://cloudresumechallenge.dev/">Forrest Brazeal Cloud Resume Challenge</a>. It took me one month around.

<h3>Certification</h3>
I passed AWS Certified Cloud Practitioner then AWS Certified Solutions Architect Associate in August 2020. My senior class taught me about AWS that is based on AWS Certified Cloud Practitioner and I finished the AWS project with the team in senior design class for fall semester 2019 and spring semester 2020. After I graduated on May 2020 with a Bachelor of Science degree in Computer Information Technology, I continue to study cloud computing because it became my passion, then I restudied AWS Certified Cloud Practioner from any online sources like Udemy, Digital Cloud Training, and others. I didn't know that Cloud Resume Challenge helps me to earn good hands-on experience.

<h3>HTML, CSS, and JavaScript</h3>
It is the easiest step ever. I already have a resume website that I found a good website template from GitHub. I modified the resume website. I have HTML, CSS, and JavaScript knowledge for more than four years. I choose to React as a web framework because it is more challenging!

<h3>Host Static Website on S3</h3>
I created a bucket named my domain name that is needed to meet the requirement. I read the AWS documentation and research something on google searching. It is easier to understand. But make sure you edit package.json and add "s3 sync build..." to package.json for deployment in CLI. Check google and AWS documentations about S3 CLI how to upload the website to the S3 bucket.

<h3>CloudFront and Route 53</h3>
Create CloudFront Distribution that makes S3 website as HTTPS like https://www.example.com. I had more errors and learned a lot from my mistake in creating a CloudFront Distribution URL that is reachable successfully. I bought bryantconti.com from Route 53 and added the record as CNAME from ACM. Oh cool! I added blog.bryantconti.com too. I have a blog website that is a static host website from GitHub. I use blog.bryantconti.com for that. 

<h3>DynamoDB, Lambda, and API Gateway for view counter.</h3>
It is the most challenging part ever. After I googled a lot of something while I fought errors, I understood that Lambda tells API Gateway about the number of views from DynamoDB. API Gateway URL tells JavaScript. Running code will display how many visitors access the resume website. I learned the lesson about DynamoDB. One Partition key is needed that all.

<h3>Python tests, Unit Test</h3>
I never write any testing script before. I googled something about how to test the Lambda handler function. I copied something in the Lambda handler function to the testing script, so I struggled with the python script utilizing unit test. I needed to write one or two testing scripts. Test script talks to the function script about view count that is passed or failed. Keep googling, trying, and learning from errors until the script is successful. 

<h3>Serverless Application Model, Infrastructure as Code</h3>
I love Serverless Application Model (SAM)! It creates any AWS services for me instead of manually, and I clicked around in the AWS console to make my point finger tired. Serverless CLI is impressive and easy to use for build and deploy. SAM guide is easy to google. Always learn mistakes and fix errors in the YAML file. I kept trying until the YAML script works, but I checked the API gateway setting and DynamoDB are not correct. I can't make API Gateway endpoint as Regional, but I found a source from google that I solved endpoint configuration that makes it as Regional. I deleted the stack in CloudFormation to destroy what the YAML script did to make AWS services and recreate the stack. Now the script made all AWS setting is correct what I want.

<h3>CI/CD for frontend and backend</h3>
I set up GitHub Actions for the frontend and backend to automate code and AWS resources to set them up. It saves my time a lot! GitHub Action is easy to use because many tools as AWS in <a href="https://github.com/marketplace?type=actions">GitHub Marketplace</a>, can improve workflows and save time. My mistake is to make too many commit along with GitHub workflows and push them to the repository for checking CI/CD works or not. I kept fixing workflows and getting errors until they are successful, so I didn't know GitHub repo has the option called secrets for AWS credentials. It is safe and provides security. Never put AWS credentials in any code! Otherwise, you will get hacked. I should test GitHub workflows locally instead. I learned the lesson. Good to know there is an <a href="https://github.com/nektos/act">act CLI package</a> you can use for testing GitHub workflows locally.

<h3>Conclusion</h3>
The Cloud Resume Challenge improved my skills and knowledge so much. I am more confident with my improved skills for the future. I enjoyed working on the project and learning new technology and software tools. I will keep learning more hands-on projects and the latest software tools. If you need cloud experience, you should try Cloud Resume Challenge that is best helpful. I am sure your skills and knowledge will be a significant improvement.