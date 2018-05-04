# AWS Certified Advanced Networking Specialty Exam Experiences

ACG Discussion Forum
https://acloud.guru/forums/aws-certified-advanced-networking-specialty/




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-LAsGGrZy6708Qh9CnXG/passed_advanced_networking_tod

Just passed Advanced Networking Exam

65 questions, 170 mn

Overall Score: 78%

Topic Level Scoring:

1.Design and Implement Hybrid IT Network Architectures at Scale: 66%

2.Design and Implement AWS Networks: 78%

3.Automate AWS Tasks: 75%

4.Configure network integration with application services: 85%
  
5.Design and Implement for Security and Compliance: 83%
  
6.Manage, Optimize, and Troubleshoot the Network: 85%

A little disappointed by my score on 1.0 but as I have no professional experience on deploying hybrid solution or even WAN, I think it is fair.

There was a lot of questions about Direct Connect, VPN and also DNS (hybrid, local, ...). I didn't work enough DNS and it was a small mistake. 1 question about Workspace (linked to DNS), 2 questions on LB sandwich and on billing.

No question about Direct Connect Gateway, NLB, ALB.

Some tips:

*listen and listen and listen ... Ryan. Not a lot missing (LB sandwich)

*Buy the AWS certified Advanced Networking Study guide and read it from start to end and reverse and reverse....

*watch the re:invent videos (300 or 400):

AWS re -Invent 2016 - From One to Many - Evolving VPC Design (ARC302) - Recap different VPC design pattern.

AWS reInvent 2016 Extending Datacenters to the Cloud (NET305)

AWS re:Invent 2015: Deep Dive in AWS Direct Connect and VPNs (NET406)

AWS re:Invent 2017: Deep Dive: AWS Direct Connect and VPNs (NET403)

AWS re:Invent 2016: Deep Dive: AWS Direct Connect and VPNs (NET402)

AWS re:Invent 2015: (ARC402) Double Redundancy With AWS Direct Connect - Info on Active/Passive.

I finished up with about 1 hour to spare, but it is the hardest AWS exam I passed yet (harder than Devops).

Thanks Ryan for your course. It was really useful as a basis of my studies.




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-LACzXw8_pAXhEjxumII/passed_aws_certified_advanced

On April 6, 2018 I cleared the AWS Certified Advanced Networking - Specialty exam on my first attempt. This has been the hardest AWS certification to date for me. I wrote an article about my experience: https://www.linkedin.com/pulse/my-take-aws-certified-advanced-networking-exam-michal-gasek/

Hope you find it informative!




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L9XWxnVmIHd8SrtyChs/passed_advanced_networking_-_s

Passed Advanced Networking - Specialty exam today. This was a tough test. I have a strong infrastructure background and I have been a CCNA for over 16 years. I used A Cloud Guru and went through it twice, Linux Academy mostly for the practice test, WhizLabs for the practice tests and I skimmed through the Official Study guide. Watch the YouTube re:Invent videos on networking. Especially on Direct Connect and VPNs. There are scenarios and examples in those videos which was related to questions I got on the test. I also found this site very helpful and also had a lot of info which I had questions on. https://www.itdiversified.com/aws-certified-advanced-networking-prep-vpc/. There are pages for Direct Connect and VPN on this site also. I had a few questions on CloudFormation and Hybrid DNS. The majority was around Direct Connect and VPNs. A few billing questions related to Direct Connect.




Hi Shawn, The actual exam is much harder than both the final exam in the ACG or WhizLabs. But I found both very useful, you will get questions on the same topics. The questions are a lot longer and more in depth. As I went through each question on WhizLabs and ACG I made sure I research every answer shown to know exactly why it was right or wrong.

Hi Squreshi25, I found this exam much harder than the three Associate exams. I would compare it to Cisco CCNA and maybe a little harder than the CCNA. From my research in reading blogs from other people who have took the exam it is either compared to the most difficult or the second most difficult under SA Pro.

Hi Gabriel, Yes I had probably had 20 questions on Direct Connect. Know how you would control routes (Active, Passive) using AS Path Prepending, MED, Local Pref or weighted. Direct Connect billing, always remember whoever owns the DX pays port hours and whoever owns the VIF pays transfer rates (at DX transfer rates pricing). I had questions on DX requirements to setup the connection and each type of VIF. Know failover options with another DX or VPN. These youtube videos have a lot of great information, some of the examples in these videos I had questions on. https://www.youtube.com/watch?v=SMvom9QjkPk&list=PLlkukGgpsXyvUbJ85RVD7qNJ1mcGKO4_w&index=1 I also read the Direct Connect and VPN whitepapers.

Also know Hybrid DNS, I had a few questions on that.



From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L82JPe4HLta7FDRcdHq/passed_networking_specialty_to

Firstly thanks for the great content from acloud :) A few surprises:

Several 'who pays what' scenarios where resources are in separate accounts, especially in the context of DX
A few automation scenarios, how would alert for..., what tools would you use to...
Several questions about media content delivery.
Other than these points the acloud course content was quite well aligned and certainly my key resource. I also dipped in to the acloud security specialty course for clarification around logging and filtering etc, which helped.




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L4Ewla7_L9Dn6o4Rtbl/pass_aws_certified_advanced_ne

I just passed the AWS Certified Advanced Networking – Specialty exam yesterday. This is my 4th AWS exam, my previous 3 are all the associate exams. I passed with a very low grade - 66% but anyway I finnally passed it!

The exam center had a very pool network connectivity to the server. The connection was down for 20+ times, I had to asked the teacher to help me exit the test and re-enter it for so many times! This was really a diaster and impacted my experience. But this is the only exam center in my city so it makes me no choice.

All in all, this test was really hard..I have been working as a Network Engineer for 6 years or so but I am freaked out when I have finished the first 15 questions..Because I can not 100% confirm the answer for all of them..Totally there were 65 questions and I have marked for 25+ questions that I am not confident with the answer.

I had a good pratise test result on AcloudGuru and also all exams at Whizlab but the actual exam was much harder than I expected. It took me 100 minutes to finish all the questions and 70 minutes for review.

I got a very low grade on Security and Compliance (33%), also the Automate AWS tasks (55%) which I believe is not covered well in all training materials in the market. This should be something we have to focus on.

The content includes:

AWS Direct Connect and VPN Connection (this is the most important and have to know them inside-out)

Public VIF, Private VIF and Hosted VIF

How to control active/passive route by using AS pre-pending, MED, Local Prefernce, etc.

Software VPN, Hardware VPN and 3rd Party VPN difference and use case

Security Group and NACL, stateful and stateless, permit and deny rules. What's the resone for 1 deny and 1 permit in VPC Flow log for the same package?

VPC and Subnet use case

Route table configuration and use case, what's the limitation

Route Propogation and route limitation

DHCP Options Set (enableDnsHostname, enableDnsSupport)

Placement Group, Enhanced Networing, Jumbo Frame (9001 MTU), etc.

DNS feature (.2 address) and DNS configuration on Route53

DNS configuration for Hybrid environment (can refer to 3 articles provided below)

DX Billing

Route priority in VPC

VPC Peering use case

VPC Endpoint, along with how to configure route table

CloudFormation

Workspace and AD service

ELB和AutoScaling Group

and more...

I went over all videos below:

In AcloudGuru

Most videos in LinuxAcademy

AWS re:Invent 2017 Breakout Sessions | Networking (15 Videos) https://www.youtube.com/playlist?list=PLhr1KZpdzukewxjrgeVIGw49tiIbkqt0Z

AWS Speicialty Advanced Networking (10 Videos) https://www.youtube.com/watch?v=SMvom9QjkPk&list=PLlkukGgpsXyvUbJ85RVD7qNJ1mcGKO4_w&index=1

Also some other materials, it's too long so I put it on my blog. **https://www.xiaopeiqing.com/posts/2896.html **(It's in Chinese, you can just pay attention to the links at the bottom)




I also passed last week and I totally concur with what Teague is saying. The exam was really hard and networking is what I have been doing for a very long time, I am a 2xCCIE with a somewhat low number but that didn't help that much!

I have only a year of experience with AWS and invested 20-30 hours studying this exam so I may have been a bit short.

Only 5 questions had an obvious answer from me and I proceeded by elimination for quite a high number of questions. Somewhat I managed to pull a 80%. Many times while I was reading a question, I was telling myself that I knew the answer but that answer was just not one of the possible choices. Well, that was how I felt.

Know your DirectConnect in or out and expect questions on a lot of topics as mentioned by Teague. Lab everything you can, create yourself some challenges. I can stress this one though: Understand how to design solutions to address name resolutions within your VPC but most importantly between your VPC and your on-prem (private DNS, bind on EC2, DNS forwarders, split-dns, DHCP options).

That being said, studying this exam was fun and it was really useful for my day-to-day work.

Now if the Solutions Architect Pro is much harder than this one, I am really getting worried since this is the next one on my radar :-)

Cheers to all and Happy studying!

NB: Special Thanks to Adrian for building this great course for ACG. More demos/labs would have been nice though.




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L0u-1L5PgAy9Ek0ub7Z/failed_the_exam

Failed the Exam (high 50s). I have always thought of myself as certifiable - you prep and pass- multiple choice exam strategies. I know AWS exams are much tougher than the usual Certifications. I thought I was well prepared but as it turned out I was not- the exam was somewhat different than I anticipated.

My background is broad/technical, not much networking. I am AWS Certified Professional- SA and DevOps.

The exam is tough- it does real deep dive into networking. The deep dive is much deeper and more focused than DevOps or SA Professional exam. Of course this depends significantly on your background and what you do on a day-today basis.

The exam is scenarios and troubleshooting, very few definitional stuff type of questions. More than normal share of gotchas. Some questions were total head scratchers – I will post a couple.

Here are the broad areas covered by the exam:

170 minutes, 65 questions (only) – time is not an issue

1.Direct Connect - about 40 – 50% of the exam

DX- all about BGP including all the subtle nuances, some VPN etc thrown in.

AWS docs, WPs, blogs, videos etc are simply not enough to train on this – you need CCNA type stuff (CSR/ASA/…) - B2B (Back-to-Basics) on DNS/TCP/FW...

2.DNS 20 – 25%

Custom DNS servers, Private hosted zones, DHCP, DNS Proxys/Resolvers

AWS Docs/Blogs/Videos simply not enough- I went thru almost all of them. The scenarios in the exam are way more complex. Will have to dig deeper in the bowels of YouTube and Google for additional materials on this.

3.VPC 15 -20%

VPC- End Points, VPC-Peering, Transit VPC, Proxy/Shared VPC

There are some good AWS videos – pay attention to details, questions are subtle/complex

4.Rest

ELB, Rt53, NACL/SG etc, Security, tiny amount of Work Space also.

I found questions in this section somewhat easier (as compared to others)

At this point I see several stumbling blocks on the way to exam:

AWS docs/blogs/WPs/Videos etc itself are not enough to prep for this (I had gone thru them all). Typically AWS docs are great - detailed, and very well organized. Combine them with WPs, blogs, and videos- you will get the complete picture. But not good enough for the purpose of this exam unfortunately.

External trainings etc are yet to mature and catchup (if you all are listening there is work to do)

No AWS practice exam

Exam is both new and not so popular, so there is not enough corpus of chatter yet on the boards that could help (so we have our work cut out for us - I will do my part)

Final take: This exam is meant for Networking Professionals/Practioners- not for ’generalists’ (like me). You need to be Cisco/CCNA type at the heart for this – not only to pass the pass the exam, but more importantly to do this role (Networking Professional)- configure routers etc. The idea at the end of the day is to do this role, not just to get a Cert and feather on your cap/resume.

If you are not into this or don’t plan to get into this – avoid (IMHO)




Steve Seymour' video gets great reviews- it is good, also his accent and presentation style. But I think much better video is "Double Redundancy with AWS Direct Connect" - https://www.youtube.com/watch?v=_JgNnmOfxLE




Hello Sam,

Sorry to hear about that; same for me today.
I am planning to re-write in January; if you want a study-partner to compare notes, feel free to reach out:
bvansteen at gmail.com

Here is how I scored:

Topic Level Scoring:

1.0  Design and Implement Hybrid IT Network Architectures at Scale: 83%

2.0  Design and Implement AWS Networks: 71%

3.0  Automate AWS Tasks: 50%

4.0  Configure network integration with application services: 57%

5.0  Design and Implement for Security and Compliance: 16%

6.0  Manage, Optimize, and Troubleshoot the Network: 57%

Thanks.

Brian.




...
heycasey 32 2
Answered 4 months ago
Sorry to hear about failing the exam. I appreciate the feedback from Brian and Sam since I'll be taking the exam soon. I have a decent amount of network experience and have a bunch of hands-on DX experience. The SSL part as well as CloudFormation does scare me, though!

A couple comments:

"External trainings etc are yet to mature and catchup (if you all are listening there is work to do)"

Adrian is no longer with ACG as evidenced by the fact that his name doesn't exist on this web site at all. I've contacted ACG support who has assured me that they will be updating the course, but who knows when? I hope others contact ACG support so they rightfully support this course since we all paid for this service.

"No AWS practice exam"

To me, this is a critical miss on AWS's part. If they're not fully forthcoming with the exam content, then they shouldn't be charging $300 for each attempt. However, they are coming out with an official study guide which I am sure will have practice questions. Book info can be found here: https://www.amazon.com/Certified-Advanced-Networking-Official-Study/dp/1119439833/ and is out in early March.

I also think a big miss is that AWS does not tell you what new features will or will not be on the exam. There are so many new features to networking that come out so quickly, and I understand it's difficult to constantly be updating the exam with this new information. However, if AWS wants to offer the opportunity of certifications for their product, they need to be current and disclose what information is included on the exam vs. not.




I took the exam last week and passed it. I'll provide my comments here since Sam T seemed to do a good job of summarizing the exam components.

First, my opinion on who should be attempting this exam. If you are using or plan on configuring on-prem networks to interface with AWS on a regular basis and have an intermediate background in networking, this is the exam for you. The reason why this exam is classified as Specialty is that it isn't intended for everyone, nor should it be. I know that some people have a goal of passing all 7 AWS certifications, but unless your profession is one that truly requires knowing every facet of AWS and its components, taking all 7 tests would be a waste of your time. If someone passes this exam and is then asked to configure an on-prem to AWS configuration with private and public vifs utilizing multipath BGP with BFD enabled in a multi-VPC environment and using VPC peering to a shared services VPC, and then cannot do it, then what is truly achieved by passing the exam?

I'll lay out how I prepared for the exam:

1. Lots of on-the-job experience, especially with Direct Connect and VPC configurations. I'm fortunate enough to work in an environment where we have data center presences in DX locations, so it's dark fiber from our routers directly to the AWS DX routers. I've configured private vifs, public vifs, Transit VPCs using routers, Transit VPCs using firewalls, VPC peering, endpoints, NAT gateways, and lots of VPNs. Without question, this was the biggest help in getting me prepared for the exam. There's no substitute for hands-on configuration to be fully comfortable with the exam concepts.

2. The ACG videos. I would say that Adrian does a great job of covering most of the exam topics. There are certainly topics that go above and beyond what's on the exam and there are gaps where more learning material would be nice, but the videos seem to be the best learning resource out there so far. Note that Adrian no longer works for ACG, and I'm assuming that he's been prohibited from participating in ACG and updating his videos since he has started his own cloud education company. It's disheartening to see that ACG is not publicly addressing this fact or more importantly discussing how they plan to support this course going forward. I hope that this gets addressed soon and in a transparent, honest manner.

3. The re:Invent Direct Connect Deep Dive sessions on Youtube. Lots of DX information on the exam can be learned from those videos.

4. The DNS blog posts that are referenced in other posts in this forum. I did not study these closely enough and paid the price since there were a fair number of questions around DNS implementations between on-prem and VPCs, and I don't think I did too well on them.

I'll agree mostly with Sam's percentage breakouts of the exam topics. DX plays a big role in the questions. DNS architecture questions are there too. But there were also a fair amount of questions on ELB (now called Classic Load Balancer) that the ACG videos do a great job of covering. SSL questions with ELB are definitely there too. I also had a good number of questions on using Cloudformation vs OpsWorks/Chef which I pretty much disregarded since I use Terraform for VPC automation. Of course, everyone's exam is going to vary, and there will always be a number of questions that won't count (but you won't know which ones will or will not count).

I went into the exam with not feeling fully studied up, and that's mostly to do with the fact that I used a free exam voucher that I obtained by attending a particular session at re:Invent. (BTW, I doubt this will be a regular occurrence, and no, I do not know where other free vouchers can be found.) With that, I felt that the pressure was off and fully expected to fail and re-take the exam at a future time.

I buzzed through all 65 questions and put my best guess answer down on the first pass. Next, I took the exam again and spent more time on the questions that were difficult for me. After all that, I still had about 20 minutes left, so I feel that 3 hours was more than enough time for me to complete the exam. I'm not suggesting that this is the best strategy for everyone but am simply giving my experience. One upside to this method is that it took me about 20 questions in to get comfortable with how the questions are being asked. Yes, the questions are asked in indirect ways that sometimes feel intentionally tricky. After a number of questions, you see the methodology and get more comfortable with it as you progress in the test. So when I answered the questions on the second pass, my nervousness was gone and I felt that I could understand the questions more clearly.

I was pleasantly surprised to see my "pass" message at the end of the exam and breathed a sigh of relief. I will say this: If I didn't pass the first time, there is absolutely no way that I would have taken the exam again before reading the official study guide that is due out in March. Spending US$300 on each exam attempt is too much to risk given the scarcity of information that is available for this exam. I'm really curious to see how the study guide covers the exam topics and look forward to providing feedback on the book when it comes out.

Last thing: If AWS Advanced Networking is of interest to you, then your education will definitely not stop after passing this exam. I see new AWS offerings like the NLB and especially PrivateLink that are really exciting concepts and will make my life as a Cloud Network Engineer a lot easier. I look forward to seeing how AWS and networking concepts evolve in the future!




I agree 100% with everything that you just stated. I just passed the exam myself a couple of hours ago, and while difficult, it seems to be fair. I would have never thought to go looking for additional cloud formation videos if not for one of these posts and I think it helped. Also, the blog posts on R53 and DNS forwarders should definitely be read. I would highly suggest knowing DX, BGP, VPN, Vif creation backwards and forwards. The questions that got me the most confused were ELB/Cloudformation/SSL related.




@heycasey, very insightful. Thanks for sharing. I'd like to second your point about this exam not being for everyone. If you have never configured a non-consumer router, you should download EVE NG and start experimenting with static routing and BGP. VyOS is a great open source router with advanced functionality. Hold off on risking the $300 exam fee until you understand the basics of networking in addition to everything Adrian covers in the course.





I took the exam last week and passed it. I have 5+ years of AWS experience with minimal networking experience(But I am passionate about networking). My problem with this exam before taking it was, there was no material other an ACG(I would rate ACG course better than LA for this course) and Linux Academy. And there was no real world practice exams. All practice exams doesn't match even 30% of real exam complexity. One thing I noticed during the exam was "if we are not good at concepts for this exam, time will not be sufficient". Questions are lengthy and subtly twisted to force us to select wrong choice. So my advice is understand concepts for this exam in detail. As expected most of the questions are related to DX. So even though we can't practice DX, logically think how DX works. These concepts must be on finger tips. Below are material I had followed. Also please follow experiences of SAM.T and all others users, they are really valuable.

1) ACG and LA course. ACG course is very good. Might not have covered all the details, but covered as much as possible.

2) White Papers on Networking.

3) AWS youtube videos on "Advanced Networking". I had stuck to 2016,2015 videos because 2017 had lot of new concepts included which currently are not in exam.

Over all even though the exam is challenging, I loved it. It was one of the best exams I had taken. I wish all the best, it really worth taking this exam.



From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L1sARZMnZRPp-duzKR9/passed_aws_advanced_networking

So I passed the AWS Networking Specialty exam today. It was hard. I don't think it was that difficult due to the breadth of content, rather the style of questioning is what made it difficult. The test is only 65 questions, but it took me over two hours to finish. Why is that? It is because Amazon likes to throw in certain adjectives or other seemingly innocuous descriptors that completely change what they are looking for in an answer. Need an example? Just do the 10 practice questions, they do a decent job illustrating what I have just described. I thought the questions asked on my test were constantly trying to lead me down a path only to throw in a tiny wrinkle and completely change the answer. This is especially true of questions that have multiple answers. Frankly, some of the questions were BS. AWS is too clever by half....especially when they try to get into testing the test taker's networking acumen. I believe AWS did not give me enough information to completely rule out possible answers. I probably over thought the questions a little too much.

Most of the feedback about this test has been from folks that are more systems and application based engineers. I am a network engineer. 20 years of this stuff. I have taken a ton of certification exams in that time. I would like to know the questions I missed, I suspect I would have some decent complaints on a couple of them.

Adding to what other people have written about the test material. I had several questions about billing. The ones that got me had to do with DX billing and when a different account (not on the same billing account) is utilizing the the DX of another account and the various scenarios involved.

Oh my score was a 74. Usually I know if I passed a test after completing the last question. In this case, I had no idea.




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L2AZrSRYWDDF17y4CrI/passed_the_advanced_networking

Well, with almost no specific prep (really!) I managed to pass the exam. I am a CCIE and I have passed all the associate, professional, and the Big Data specialty exams, so that is how I managed it.

All that said, I definitely wouldn't advise winging it! I thought it would be much easier than it was. In fact, as others have observed, it is pretty tricky - the questions have layers of trickiness and while having a Cisco/Juniper/other networking background will help in some respects, most of the material would never be seen on those vendors' exams (eg. Route53, ELB, SSL, nuances around DX, etc, etc, etc).

So, all-in-all I am very relieved to have passed.

Anyway, good luck everyone.

Mark




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L2WcIduXRZ1yaWZC1i-/passed_with_an_88%25_-_some_thou

Very happy with the grade on what is definitely a difficult exam with complicated questions. I do however see it as a fair exam and possibly even fun if you're into networking. There were some posts about this one being for those long-time network engineers that live and breath networking, or work at ISP engineering departments, etc'. some posts even recommended to avoid if you're not one of those people.

I do not agree with those statements. I believe this a well-made exam for AWS professionals that come in to the exam with wide & deep knowledge of networking with a focus on AWS, doesn't really matter if they gained it throughout many years of a professional career or specifically for the exam. I am a generalist that studied the CCNA material (but never sat an exam and still suck at subnetting) over 10 years ago, and have since did support, production engineering, SaaS, etc'. If you have the strong technical background and the ability to dive deep (and the interest, I guess) then you'll enjoy studying for this exam and enjoy passing it, I know I did.

So yeah, I knew almost nothing about BGP a month ago, certainly never heard of LocPrefs, communities and MEDs, but I dove deep and luckily had the option to do some limited hands-on with DX. hands-on with IPSec VPN (static/dynamic) is EASY to get your hands on and is absolutely recommended. I agree that it's difficult to know the ins and outs of dxconn & vifs if you never configured them. Cisco learning materials have simulators, this stuff doesn't.

Other than that I would like to refrain from talking about specifics. I do believe that Adrian's blog post covers everything. take every word from that list and know everything about it. use the blog post and the course as your SCOPE of material that you need to know and drill down into every single thing from all possible angles. Steve's re:Invent videos are an absolute must and so are the three hybrid DNS blog posts. I do not recommend to diversify with other platforms' courses for this exam, I do not want to get personal but they are just terrible and not worth the time/money.

https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L0u-1L5PgAy9Ek0ub7Z/failed_the_exam




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L0uWJuCjxdDy5254Wxo/failed:_62%25

Below are the results.
Thanks to other advice, I tagged questions for follow-up, got through the 65 questions with ~40 minutes left, and had ~20 questions tagged to review.
Overall, I felt that probably 40% of the questions related to VPN and DX, as others have noted.
But most of my tagged questions related to Hybrid DNS and SSL, so I would highlight these topics as important. And I obviously did not do enough preparation on SSL... :-)
I feel that this course does not sufficiently or clearly cover SSL / security; did anyone else find the exam questions on security hard, and any suggestions on where to learn more (other than AWS documentation)?
Also, as @jady's post highlighted, there are three AWS blogs on Hybrid DNS that are much clearer and more direct than the video in this course.
I think someone else mentioned this; the Automate section is all about CloudFormation, which this course did not cover.

Topic Level Scoring:

1.0  Design and Implement Hybrid IT Network Architectures at Scale: 83%

2.0  Design and Implement AWS Networks: 71%

3.0  Automate AWS Tasks: 50%

4.0  Configure network integration with application services: 57%

5.0  Design and Implement for Security and Compliance: 16%

6.0  Manage, Optimize, and Troubleshoot the Network: 57%



https://aws.amazon.com/blogs/security/how-to-set-up-dns-resolution-between-on-premises-networks-and-aws-using-aws-directory-service-and-amazon-route-53/ https://aws.amazon.com/blogs/security/how-to-set-up-dns-resolution-between-on-premises-networks-and-aws-using-aws-directory-service-and-microsoft-active-directory/ https://aws.amazon.com/blogs/security/how-to-set-up-dns-resolution-between-on-premises-networks-and-aws-by-using-unbound/



https://aws.amazon.com/blogs/security/how-to-set-up-dns-resolution-between-on-premises-networks-and-aws-using-aws-directory-service-and-amazon-route-53/

https://aws.amazon.com/blogs/security/how-to-set-up-dns-resolution-between-on-premises-networks-and-aws-using-aws-directory-service-and-microsoft-active-directory/

https://aws.amazon.com/blogs/security/how-to-set-up-dns-resolution-between-on-premises-networks-and-aws-by-using-unbound/




My opinion is that this is an advanced level exam. I agree that the course could be better but to pass the exam you have to have a strong networking background before and the course objective should be to apply that knowledge to the AWS-way of doing networking. A course to teach you how DNS works, how BGP works, how SSL/TLS works from scratch would be 10 times longer.

Perhaps the course is wrong not stating that from the beginning. I had all that previous knowledge so it felt good to me, but if not stated clearly it can be misleading.




SSL/TLS is not considered networking in the minds of people who work on networks. SSL/TLS is not on the CCIE exam. If the course does not provide enough information on SSL/TLS that should be called out





Thank you, Adrian Cantrill and the A Cloud Guru team! https://www.linkedin.com/pulse/passed-aws-certified-advanced-networking-specialty-exam-minnis




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L07Vs_GnBATiaq8uB2O/done_with_all_the_aws_certific

hey guys,

Before taking my first attempt I have done the below.

1. Finished the cloud guru videos twice.

2. Finished all the linux academy videos once and revised all the slides as they let us download the pdf version. The linux academy trail version could help as its good for a week if you could put in the time.

3. I had a few white papers. You can google them with the below names:

    ddos white paper on aws

    aws vpc connectivity options(very very important)

     best practices for deploying aws workspaces

     aws multiple data centers ha network connectivity

      integrating aws with multi protocol label switching
During the exam, I was baffled with the complexity of the questions especially hybrid cloud and hybrid dos and left insufficient time for the last 10 questions. I felt that was the killer as I messed up time management.

For the second time,

1. Revised all the acloudguru and linuxacademy

2. Watched as many re-invent videos for hybrid cloud as I can. Hopefully this link works for you all.

https://www.youtube.com/playlist?list=PLchh7UF9nyfSkz-1ulITe6uMrGWhQ2m__

3. When I took my exam this time, I was more time aware and made sure I flagged questions and moved on. I feel this greatly allowed me to give my best to all the questions and not just a few.

Some additional suggestions,

1. Read the manuals for direct connect, VPN setups, private VIFs and public VIFs

2. Skimmed through "Practical guide to advanced networking" by Jeffrey Beasley. Very good book.

3. Try to watch as many 400 level videos as you can from re-invent.

3. This is without doubt the most difficult aws exam there is. May be this is because I am not from a networking background but was intrigued by the concepts.

Good luck to everyone attempting the exam. I'm sure you shall do just fine.




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L-2iD7g6JpBdd1JjJ-E/i_passed_the_networking_specia

Well, first Thanks to Adrian and Ryan for the course, I got to say the Adrian's course is great. The questions (in Adrian's exam) are really far from the real exam, the exam is based on scenarios situations and you need to be very cautious with the time, I basically ran out of time (4 minutes left) for 10 questions left. I should have been more careful with that. My first 10 questions were way too long and they took almost 40 minutes when I saw that I was very disappointed, but I think I adapted my speed during the test because I was able to recover some of that time. I really recommend to get practice reading fast and do not think on drawing a diagram of the situation to analyze the question, you will need that time to finish the test. Anyway, I finally got my 7 out of 7 AWS certification and I am very pleased with AcloudGuru courses :)




From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-L--ZdOy-QPiU1onPQ1f/did_not_make_it_with_62%25_:(

Hey guys,

I'm satisfied to report that I have passed all the below certifications thanks to acloud.guru,

1\. associate aws solution architect

2\. associate sysops admin

3\. associate developer

4\. aws devops professional

5\. aws certified big data specialty
I wrote my aws network speciality and unfortunately did not make with 62%. I would appreciate if anyone can help with the below

1. In your experience what is the pass for this course?

2. Not sure if anyone else noticed this, but time is a concern for this exam like never before. I felt I could have crossed the finish line if I was more time aware throughout the exam.

3. Each and every question is scenario based. Not a single one out of step.

4. Below is my score card. Please let me know if anyone has any tips for me to prepare and crack this again. Since I came close, I'm willing to give it another shot.

  1.0  Design and Implement Hybrid IT Network Architectures at Scale: 66%

  2.0  Design and Implement AWS Networks: 42%

  3.0  Automate AWS Tasks: 100%

  4.0  Configure network integration with application services: 85%

  5.0  Design and Implement for Security and Compliance: 66%

  6.0  Manage, Optimize, and Troubleshoot the Network: 42%
  
  

Specifically I am talking about this post https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-Kri4imXe4eBsSu6c36U/pass_certified_advanced_networ




Vishal,

These are the key point in your exam

1.0  Design and Implement Hybrid IT Network Architectures at Scale: 66%

2.0  Design and Implement AWS Networks: 42%

Those 2 domain worth a lot in the exam the second one worth 29%, the issue with the exam is very based scenarios as you mentioned, and I think it is the hardest one of all the AWS exams. I got my networking specialty last Sunday and I got the same feeling, the main difference between your score and mine were on those 2 domain. You will need to work more in that, do dynamic VPN labs using vyos AMI. You are very close, keep going




I recommend reading about CloudFormation and AWS Config. I've started ACG's introductory CloudFormation course but haven't gotten far enough to comment on its relevance to this exam. I've yet to find a good tutorial on the web that covers CloudFormation in a way that is easily consumable for people just getting started with the tool.





From https://acloud.guru/forums/aws-certified-advanced-networking-specialty/discussion/-Kz73jtOxm-_oABzL9mE/advanced_networking_speciality

I passed the exam on 11/12/17. @jady and @bxcpro have done a thorough job in hightlighting critical exam areas. I don't have much to add in this respect.

Here's some quick background on me so that you know where I'm coming from. I've spent 20 years operating, designing, and engineering IP/MPLS networks primarily for Tier 1 ISPs. I know many aspects of networking inside and out. I haven't taken any of the professional-level AWS exams, so I am not accustomed to the level of detail in the scenario-based questions. I asked PSI for ten sheets of blank paper. I needed almost all of them. I had to draw my own diagram for almost every question, even when diagrams were provided. Answering all the questions took all the allotted time for me.

I feel as though my knowledge of networking helped my a lot with the BGP questions; however, it probably hurt me because I over-analyzed some of the scenarios that are extremely vague to someone with a network engineering background. Let me provide an example from the sample questions. If you are a network engineer, you know that the major ISPs will never accept a /32--referred to as a host route in the sample question--from a customer. Almost all will accept a /24 but you'll have to check their policies to see what smaller blocks they will accept. Also, it matters whether your CIDR block is provider-independent or not. This affects multihoming. Does the test writer know these facts? There's no way for me to know.

I found several areas in the AWS documentation that are confusing or incorrect. I posted previously about this. I am glad to see AWS being responsive to my feedback, although it's unfortunate to have this happen in the first place.

You'll improve your chances of passing this test if you take the ACG course and watch all re:Invent videos on youtube that are related to VPC. Steve Seymour's presentations are the best. I probably watched his presentations five or more times to make sure I understood the concepts. I found other paid training to be so riddled with errors that they are not worth taking. Save your money. The instructors seemed to have no clue about networking.

The instructor's failure to complete the demos/labs remains a sore spot for me. While the ACG course is well worth the money, I feel that the lack of demos/labs that were promised reflects poorly on ACG. I have yet to get a response from ACG on how the company justifies the decision to leave the course incomplete. My emails and tweets have been ignored. The missing labs/demos did force me to do these myself in the console, which I highly recommend whether or not they are eventually added to the course. I remain a huge proponent of ACG and will continue to purchase training for me and the engineers who do AWS work for my company.

I've been monitoring this forum closely for almost all of 2017. I've seen a lot of very basic questions about networking that are not specific to AWS. If you don't have a entry-level understanding of networking, I recommend taking the introductory Cisco or Juniper certifications or reading books such as TCP/IP Illustrated Volume I by Richard Stevens. Gaining this certification through advanced memorization techniques will not serve you well in the work place.

I compiled 40+ pages of notes for this test. Having these notes with me during the test would not have helped one iota. Spend your time in the console rather than memorizing trivial things such as many of the VPC limits. My recollection is that this course covers the VPC limits you need to know.

I don't intend for this post to discourage students. It is a hard test. You can pass this test with a basic knowledge of networking and a significant investment in studying the ins and outs of AWS VPC. Good luck to everyone.




Thank you for the feedback. I agree with all of it. I enjoyed Adrian's lectures and way of teaching. I missed more labs. While I understand that DX labs are almost impossible to do I managed to do hardware VPN labs with BGP myself with just a VPN gateway and a Linux instance in other region. That kind of things should be included in the course.




Have to agree with everything said here. I sat this exam this morning as my last certification of the 7, and I failed it. The lack of labs, exams tips, demos and so forth hurt a lot.

The extreme focus on detail bored the shit out of me so badly that I missed the forest for the trees. I have never been bored with ACG material, and I utterly bored shitless through at least half of the course, which probably lead to things not sticking well in my head.

I'm a huge fan of Adrian's, but this course just feels incomplete and unrefined. I don't come to ACG to get deep, nuanced knowledge in an area, I come here to pass an exam, and the course isn't giving me what I need to do that. I don't need specifics (unless they're in the exam), which few were in mine. I don't need to understand at a low level how something works. I need to understand the high level functioning to make design, troubleshooting and optimization decisions in the exam.




