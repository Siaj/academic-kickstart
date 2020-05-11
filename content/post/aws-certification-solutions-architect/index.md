---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "PASSING MY AWS CERTIFIED SAA EXAM"
subtitle: ""
summary: "Tools and Materials I used to prepare for and pass my AWS certification exam"
authors: [admin]
tags: []
categories: []
date: 2020-05-09T19:57:26-06:00
lastmod: 2020-05-09T19:57:26-06:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
<hr/>

This is just a short post about the tools and materials I used to prepare for and pass my AWS certifications (Certified Cloud Practitioner and Certified Solutins Architect Associate). My initial preparation was towards the Solutions Architect Examination but then I decided to take the Practitioner exam before that, knowing that if I am able to pass that one, it would give me lots of confidence going into the Solutions Architect exam.

The whole preparation process took roughly 7 weeks for me, and that's one thing about these certification exams, you need to take as much time as possible to prepare for them as they can be really tricky and difficult if you do not have the sufficient preparation.

I made use of materials from the AWS certification prep website ([link below](#aws_links)), where I got the gist of what to know and some recommended material to study in order to pass the exam. Things like the exam guide and a short sample exam is available to give you a general idea as to what to expect. Most importantly, there are links to whitepapers and FAQs of the necessary services you need to know.

Just that alone was not enough to effectively study for the exam, at least for me, so I made use of some video tutorials from udemy ([links below](#vid_train)). The videos really helped me a lot, as it made going through and learning about the various services less painful - because you see someone explain and demonstrate. I went through the video tutorials twice; the first round was just watching to get a general idea about the content (more like watching a TV show), and in the second round, I made lots of notes and got my 'hands dirty' by practicing along with the instructor.

After feeling confident about the knowledge gained so far, you may want to get some practice exams (also from udemy - [link below](#practice)) to validate your knowledge before going in for the main exam. In my opinion, these practice exams are generally difficult than the main exam but excellent in preparing you for the exam - so don't be too hard on yourself should you fail a couple of them. They provide detailed explanations to the solutions and that again helps in clearing some doubts and solidifying your knowledge in the subject matter.

I decided to take the Cloud Practioner exam after my preparation thus far, and it was really good - it helped increase my confidence, so I booked the Solutions Architect Associate (SAA) exam for the following week and passed that one too. Currently preparing to take the Developer Associate exam sometime this month and maybe the SysOps Admin Associate some other time in the near future.

I am hoping this would help those interested in pursuing the AWS Certified Solutions Architect Exam or even the Cloud Practitioner ([video below](#vid)) prepare sufficiently in order to ace these exams. Good Luck!
<hr/>

<h1><u>MATERIALS</u></h1>
<div id="aws_links" style="padding-top: 20px"></div>

__1. AWS Whitepapers & Other Materials:__
  * <a href="https://aws.amazon.com/certification/certification-prep/" target="_balnk">AWS Certification Prep - Website</a>
  * <a href="https://aws.amazon.com/architecture/well-architected/" target="_balnk">AWS Well-Architected Framework - Website</a>
  * <a href="https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf" target="_balnk">AWS Cloud Best Practices - PDF</a>
  * NB: Please read product documentation for the required services (Overview, Features & Faqs)

<div id="vid_train" style="padding-top: 20px"></div>

__2. Videos Tutorials on Udemy:__
  * <a href="https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c02/" target="_blank">Stephane Maarek</a>  
  * <a href="https://www.udemy.com/course/aws-certified-solutions-architect-associate/" target="_blank">A Cloud Guru</a>

<div id="practice" style="padding-top: 20px"></div>

__3. Practice Exams on Udemy:__
  * <a href="https://www.udemy.com/course/aws-certified-solutions-architect-associate-amazon-practice-exams-saa-c02/" target="_balnk">Solutions Architect Practice Exams</a>
  <br/><br/>
  <hr/>


__SOME IMPORTANT NOTES FOR SAA:__
1. Please take some time to watch a couple of AWS re:Invent videos on youtube, they have really excellent talks about their services (what is better than learning about a service from the owners of the service)

2. You should know and understand the concepts around the Amazon VPC inside-out. Be able to design, build and solve VPC problem efficiently without any reference

3. Understand Designing Reliable and Highly Available Architectures (Load Balancing + Target Groups, Auto Scaling Groups + Launch configs, Database Multi-AZ, S3 Cross-Region Replication, S3 Storage tiers, CloudFront CDN, etc.)

4. Architecture Security (IAM, VPC Security [Private Subnets; Security Groups; Network Access Control Lists; using VPC Endpoints and NAT Gateways], Encryption/KMS)

5. Cost-Effective Design (Ex. Use of Reserved Instances rather than On-Demand Instance in certain circumstances to save cost)


<div id="vid" style="padding-top: 50px">
  {{< youtube 3hLmDS179YE >}}
</div>