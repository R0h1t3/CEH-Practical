# C|EH Practical Certification Writeup
Hello Reader, since you are reading this article on C|EH certification, I hope that you already have a minial knowlegde about the certification exam and want to know more about it. Before going into the article, let me know brief you about the certification.

### C|EH Practical
This is a pratical hacking certification exam conducted by a prestigous organisation **EC Council**. This exam test the knowledge of the candidte in specific cybersecurity areas. This is exam is beginner friendly exam that with good preparation, an ameture cybersecurity could ace it. The main topic that are focused in this certification are - Network scanning, SQL injection, XSS, Banner grabbing, Steganography, Remote code execution, Brute-forcing, & Vulnerability scanning. <br /> 

**Duration of the Exam:** 6 hours<br />
**Number of Question:** 20 <br />
**Qualification Percentage:** 70% - 14 Questions correctly answered<br />
**Mode of Exam:** Proctored Online Exam<br />
**Type of Exam:** Open Book Test<br />
**Question Pattern:** Exhibit Practical Hacking skills <br />

As mentioned above, each candidate is give a set of 20 questions in the span of 6 hours. In between, as per the candidates request and the proctors approval, the candidate can take a break 0f 5 min, 2 times during the duration of the exam. This is an `open book test`. Only hard copy notes and access to internet is allowed during the entirity of the exam. (**Warning:** The use of softycopy notes or talking with anyone during the exam is strictly prohibited, if the proctor sees any form malpractice, they can immediately terminate and reschedule your exam.)<br />

During the exam the candidates have to hack into live virtual machine which are hosted online by the exam portal. Here the candidates have to perform different techniques to get the flags for the respective questions(i.e. IP Adresses, numbers that are answers to questions). There will be 2 virtual machines (1 Parrot OS + 1 Windows OS) and IP address range under which the exam questions will be based on. <br />
To know more the C|EH Practical Exam, visit the [link](https://www.eccouncil.org/programs/certified-ethical-hacker-ceh/).<br />

## My Journey :nerd_face:

I have studying about cybersecurity for the past 3 years. I have heard about this certification quite a few times during these years. Later I cam to know of a scholarship program that is being offer by the EC-Council in the end of 2021.<br />
Apperently EC-Council has announced 1M USD for C|EH Practical certification for the enhancment of the hacking skills in the cybersecurity community.  The actual cost of this certification is 550USD, but if the candidate gets selected by this program, they would get the same certification for just 99USD (which is a very generous offer). The scholarship application has a few pre-requisites and the candidate is asked to write a breif answer for why the deserve the scholarship. That is pretty much the scholarship application. <br />To know more about the scholarship visit the [link](https://www.eccouncil.org/ec-council-announces-1m-ceh-practical-scholarship-2021-to-boost-ethical-hacking-skill/).<br /> [Application Link](https://www.eccouncil.org/campaigns/ceh/ceh-practical-scholarship-2021/#Apply_now)<br />

Fortunately, I got selected by the scholarship program in Nov 2021. After the payment of the scholarship amount, they sent a coupoun code to access the certification exam along with the list of instruction to follow. At the end of the procedure, I was able to schedule the exam as per the slot system availabe in the aspen portal, which is where the exam would take place.<br />

**Note:** The coupon code is valid for 365 days to use it in the aspen portal. And after using the coupoun in the portal, the candidate can schedule the exam within 365 days. So they have a total of 2 years to attend the certification exam.<br />

Well, I redemmed the coupoun right after I got it :upside_down_face:. I started the preparation for this exam around May of this year. I research about the resources to prepare and cam to know about the [`iclass`](https://iclass.eccouncil.org/our-courses/certified-ethical-hacker-ceh/?utm_source=ecc-menu&utm_medium=eccreferral&utm_campaign=ceh-course-page#train) training that EC-Council provided exclusively for this certification.<br />

However, because of the cost of the barrier, I didn't purchase it. I studied according to the syllabus of the exam and used online freely available resources. I will share the reources that I used at the end of this article:wink:. I tried few CTF rooms in `TryHackMe`, `Hackthebox`, and `PicoCTF`. Plating around with `DVWA` also help me a lot to understand the foundations of a few concepts. I read a lot of review articles on this certification before taking it. From all this experince, I created a personalised notes that had the information of the all the compiled resources I had used for my preparation<br />

A month went by and I gained enough confidence to show up for the exam. (Confidence on your skills is a neccassity to appear before any exam :sunglasses:). I planned on taking the exam on the first week of July but due to unavailabilty of the slot, I booked a slot on the 3rd week of it. For booking of the exam slot, I was diverted to another website in which the exam actually took place. I created an account and booked my slot there.
Before the exam I had a good night sleep, was fresh, revieved my notes and all was well!<br />

### The Judgement Day
I had my exam slot in the morning 9:30 am. I went into the exam portal and connected with the proctor. Here came the first trouble. I logged in with my laptop in my Kali OS, apparently it doesn't support the application verison of `GoTo Meeting` in which the proctor invigilates our entire exam. I logged in with the Web browser version. The proctor asked me connect with desktop verison, since the browser version doesn't allow me share the screen and give remote control to them. This came by suprise :expressionless:. Good for me, I had dual booted my laptop with a windows version:face_exhaling:. The proctor was kind enough to give some extra time to join again. Then I logged into the exam portal from theat OS and the proctor start the exam after a few procedure.<br />

The 20 question was pretty much in the range from easy to moderate. I juggled between the 2 virtual machines to answer the question. The worst part of the exam is the connectivity speed to the virtual machine, they were too slow (I can't stress enouch on that:sneezing_face:). Make sure you have a good bandwidht before starting the exam. Mine was a bit slow, because of which I had restart my virtual machine during the exam. All the tools were already present in the machines itself, and the question clearly mentioned which virtual machine to use for that specific question. You just have to use approprite tools and solve the challenge.<br />

I complete 19 of them in 4 hours and the remaining one was tricky. By the time I figured it was too late to solve it:dizzy_face:. After clicked the `Submit` button and informing the proctor that I finished my exam, she instructed my how to check my exam status.<br />

**BOOYAH!**:tada::confetti_ball:<br />
I cleared the certification exam, got them all correct. The proctored congragulated me and left the meeting after giving me a few instruction on downloading the certificate, transcript and badge.<br />
[Verify my badge](https://aspen.eccouncil.org/VerifyBadge?type=certification&a=A89SS0SuEu/oPIOQV44sO3WvvKP/T+URnkVMNXxdEH8=).

## Resources & Tips
Anyone appearing for the exam, I would suggest to have strong knowlodge in these areas<br />
- **Demonstrate the understanding of attack vectors**
- **Perform network scanning to identify live and vulnerable machines in a network.**
- **Perform OS banner grabbing, service, and user enumeration.**
- **Perform system hacking, steganography, steganalysis attacks, and cover tracks.**
- **Identify and use viruses, computer worms, and malware to exploit systems.**
- **Perform packet sniffing.**
- **Conduct a variety of web server and web application attacks including directory traversal, parameter tampering, XSS, etc.**
- **Perform SQL injection attacks.**
- **Perform different types of cryptography attacks.**
- **Perform vulnerability analysis to identify security loopholes in the target organization’s network, communication infrastructure, and end systems etc.**<br />

Tools to be familiar with<br />
- Nmap<br />
- Hydra<br />
- Sqlmap<br />
- John / Hashcat<br />
- Metasploit / Netcat<br />
- Wireshark or Tcpdump<br />
- OpenStego<br />
- Snow<br />
- Veracrypt<br />
- HashCalc<br />
- CrypTool<br />
- Burpsuite<br />

There is a great GitHub Repo which sums of most of the resources, that I have used to prepare - [GitHub](https://github.com/CyberSecurityUP/Guide-CEH-Practical-Master)

Other than these the iLabs that are provided by the EC-Council have been recorded and released in youtube, see all of them to get familiarity with the virtual machines - [YouTube](https://www.youtube.com/watch?v=b2YrqpeklFw&list=PLrrgFyE6PtlaCixUxJPM0Y9Peye6iCewH&index=18)

Before registration go through this [article](https://lightkun-yagami.medium.com/passed-ec-councils-certified-ethical-hacker-practical-20634b6f0f2) to know about the slot booking and exam starting process.

## Conclusion
Overall, this was a very delightful and fun experience to take up this certification exam. The process was enjoyable and will be to you too.<br />
**Happy Hacking!**:computer::v:

