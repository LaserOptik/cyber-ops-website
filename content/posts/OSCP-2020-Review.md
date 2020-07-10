+++
title = "OSCP 2020 Review - Passed in the #1 attemp being a newbie"
date = "2020-07-10"
author = ""
authorTwitter = "" #do not include @
cover = ""
tags = ["oscp"]
keywords = ["oscp", "2020", "review"]
description = "My OSCP review, from the beginning of my preparation to the exam."
showFullContent = false
+++

# Background
I will start this review saying that, before my preparation process, my background as pentester was null. I centered my professional career in software and web developing and the few things that I knew about hacking and pentesting were learned by myself but barely got me reach the level of a very noob script kiddie.

# Starting off my way
I decided to leave my job as web developer after 6+ years experience to switch to cybersecurity (since it had been always my loved field) and start preparing for that in a full-time basis. At this point I had already obtained my Security+ certification which I got while I was working as web developer a couple years ago as entry-point and also to get some blue-team skills which I consider also crucial once working in any cybersecurity role. Then, without experience about pentesting at all I got the [TJNull HackTheBox OSCP-like machines excel](https://docs.google.com/spreadsheets/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/edit#gid=0) and I purchased the VIP of HackTheBox the very first days. 

# Getting prepared in HackTheBox
Once with my VIP membership in HTB, the first 2 weeks I was doing retired machines following the provided walkthough by HTB, since I didn't even what tools to use in many situations. Then I started to do some of them without the walkthrough and even some easy active boxes (no walkthrough provided on these) to starting to forge a hacker-like thinking. So after the first month and with a minimum skills and mindset about hacking I planned the following work flow in order to keep growing:
- **Do at least 1 active machine per week** (or 2 whenever possible), although they aren't in the TJNull OSCP-like excel, **to improve my hacking mindset** (as we know there is no walkthrough available in the active machines). The amount of knowledge and skills you get in active machines exposing your mind to constant stucks and always trying to get alternative ways to achieve something is amazing and that was what really helped me to build a hacker/pentester mindset. I always tried to do the most real-life machine available in that moment and avoid the CTFy ones since I knew that that would be the most proficient to get prepared to OSCP and also to real life :).
- Also **do at least 2-3 retired machines per week of TJNulls OSCP-like excel** (without looking at the walkthrough whenever possible or looking at it when a stuck was already taking me out some time) **to keep expanding my skillset about more kind of technologies**.

I was following this workflow during about 10 months only doing boxes on HackTheBox. I didn't consider to practice with VulnHub machines since it has not Windows machines and HTB actually has more than enough to be prepared to OSCP. Furthemore, I have to say that the rank system on HTB helped me to keep motivated and growing in order to achieve new ranks and achivements. In fact, at the final stage of my preparation in HTB I got carried away too much by doing some hard boxes with the purpose of getting the 'Elite Hacker' rank (what was absolutely unnecessary to get ready for OSCP).
So, I ended doing all the Linux and Windows columns of the excel list, and about the 30% of the "More challenging than OSCP, but good practice" column.

I can confirm that HackTheBox is absolutely a proper platform to get more than well prepared to get into OSCP and I'd like to thanks to TJNull for elaborating that useful OSCP-like machines list since it was very helpful for me. Anyway, I will make two groups of the boxes that I most encourage to do of this list if you are planning to do only some of them, since there are some that may not be very OSCP-like but are a must because of the amount of knowledge you can get. I'll elaborate this list in a separated post.

# Getting into OSCP
After more than 10 months getting prepared on HTB I decided to take the plunge and get into OSCP. Recently Offensive Security had updated the OSCP course to the new 2020 version with new contents. I purchased the 90 days plan and I received my PWK course resources (PDF of 850 pages and videos) and connectivity pack to labs. I only followed the PDF from the contents, and I faced the big question whose decision will totally drive our PWK and lab journeys and learning experiences for different ways, "**Do I do the exercises, or not?**". If you are reading this and haven't get into OSCP yet, you must think this very well since each decision has its pros and cons. I was told that the PDF of the previous version of OSCP had around 450 pages (which also means considerably fewer amount of exercises). The new OSCP 2020 version comes with 850 pages with a huge amount of exercises, some of them require simply to reproduce what was explained in the previous lesson but other require further researching and, in a nutshell, some time to get them done. Here the advantages I found of doing the exercises:

## Advantages of doing exercises:
- You are putting on practice all what you are learning in the lessons so you would acquire the PDF knowledge better.
- You will get 5 extra points for the exam that may be only actually useful when you score 65 points on the exam. As far as I know these are the only 2 scenarios in the exam where you could be exposed to a situation of scoring 65 points and those 5 points would save your ass:
	- Rooting a single 25 points machine and the two 20 points machine (25 + 20 + 20 = 65)
	- Rooting a single 25 points machine, a single 20 points machine, the 10 points machine, and get the user on the 25 points machine left (25 + 20 + 10 + 10 = 65). I read a case where exactly this happened.

## Disadvantages of doing exercises:
- You will spend **A LOT** of time doing them, time that you could use in the labs hacking machines.
- Plus you will have to make the report of at least 10 machines of the labs to send it along with the exercises, so more time you will spend (but in this case not that much)

Well, I decided to do them. And here is where I faced the truly saying of "Try Harder". I spent 45 days reading the PDF, doing the exercises and reporting them, that's too much time and I know many people got that in less time but I'm not unhappy about that if I take into consideration that I have some difficulties with English language since it isn't my primary language (as you surely already realized), so reading and reporting in English supposed a little extra effort to me. I ended making a report of 155 pages (only for the exercises, 207 with the lab report). After all, my advice is that if you have prepared yourself previously hacking boxes on HTB lab I do recommend to do them because you already should have some background practice at your back and you will learn a lot of new tools and techniques (specifically about privilege escalation) doing them (and you also will have 5 fresh points to your exam :) ). If you come without any or short pentesting practice I do recommend to don't do the exercises and try to spend as much time as possible on the labs to build a hacker mindset and get as much practice as you can.

# OSCP lab
The most fun part of the entire course. I did 44 of 66 machines available in my 45 days left and unlocked all networks (IT, Dev and Admin). But if you come with a solid practice from HTB you don't need to do such amount to get prepared. I've heard people doing 8 machines and passing the exam and some doing the entire lab and failing it, so actually it's a matter of how prepared do you feel. 

The thing I most enjoyed was to keep in mind the pivoting concept constantly. That's something that I had not practiced in HTB where each machine is independent. In the OSCP labs you may have to pivot to another machine first to be able to hack others, and that puts you in the obligation of doing post-exploitation when breaking into a machine in order to get valuable information that could be helpful to get into another box. This made the course very real-world-like as it seems a real corporate network.

# Exam
The most important day. About 1 week after I've finished my lab time I scheduled my exam to the next 10 days. I chose to start the exam at 14:00h since I think its the most advantageous time to start for me for various reasons.
- That's my time of having lunch so in the first exam day I could have lunch previously (at 13:00) in order to don't have to spend the lunch time while the exam time.
- In the second day I would be able to not spend lunch time neither during exam time since I could have it after the exam had finished.
- Furthemore this schedule will give me the possibility of having some fresh morning hours to keep trying with a clear mind after sleeping.

In the meanwhile days until the exam date I was doing some VulnHub machines from the TJnull list. 
And then the exam date arrived, and I had a plan. I would do first the BOF since they should be the easiest (25) points. Then, as my mind should be still fresh I would go for the second 25 machine. Then I would take a little rest of 10 minutes and go to some of the 20 points machines and try to hack it also the first day if possible to be able to go sleep relaxed with my pass assured. That would be my first day plan and I would get really happy if I accomplish it.
And the plan went as follows:

1. BOF 25 points - I got it in 1h:30m (first 25 points achieved)
2. Second 25 points machine - I got the user in 2h:15m (now I have 35 points)
3. I took a 10-min rest
4. Second 25 points machine - I got the privesc in 3h:15m (then 50 points)
5. I took 5-min rest
6. First 20 points machine - I got user in 1h (Now I'm getting happier, almost a pass! Don't know if I reached 60 points here, it should if user is scored with 10 points but I'm not sure)
7. I took 30-min time to have dinner
8. First 20 points machine - I got the privesc in 3h (I remember a deep sigh of satisfaction, I GOT THE PASSING SCORE - 70 points)

At this point, was 3:30am and I got the tranquility of going sleep with a passing score. So I left my computer and went to sleep. I got up at 9:15am with the motivation of complete the 2 machines left. Well, my joy in a well. It turns out that I wasn't able to break into any of those 2 machines, one of them was supposed to be easy (10 points) :(. So my final exam score should be 70 points + the 5 points of lab and exercises report = **75 points**.

I received my results after 6 days:
![da09625c116b955b1992e60350fffda3.png](/posts/_resources/ff95f8ab81d14c469d46f2a0cda947ba.png)

# Tips and Recommendations
## For the preparation starters:
- Buy the HackTheBox VIP membership and do at least the 50% of Linux and Windows machines of TJnull list (you can do also some of the "More challenging" column). There are a lot of machines right now since the list keeps growing as HTB launches new boxes, that's why I'm recommending to do at least 50%.
- Take notes about your hacking procedures on each machine. You'll need them to review in the future, trust me.
- Build a preparation plan with a weekly minimum achivements and follow it.
- Don't be afraid about looking walkthroughs on retired machines when needed. Sometimes you simply can't get something done if you don't have the enough knowledge about it. But keep challenging your mind occassionally doing some active box (or a retired one without walkthrough at all) to build a hacker mindset.
- Avoid CTFy and insane boxes on HackTheBox since they won't help you to OSCP. Remember that OSCP boxes are generally easy to medium boxes of HTB and real-world-like!

## For those planning to get into OSCP soon
- Decide whether you'll do the exercise or not and build a plan based on your decision.
- If you decide to not do the exercises, I strongly recommend you to do at least the 1 and 2 Extra Mile BOF exercises since there is very few BOF boxes to practice in the labs.
- In the labs you'll encounter 5 difficult machines (4 in the previous OSCP versions), they are Pain, Sufferance, gh0st, Humble and 1ns1der (this is the new one). I do recommend to not spend too much time with gh0st and 1ns1der since they are very CTFy and quite more difficult from what you will be required to exam.

## For those taking the Exam soon
- Build a strategy and follow it. I do recommend to follow the shortest path to a passing score.
- Choose a proper exam time to you. Take benefit of your most fresh hours with the most difficult boxes.
- As everybody says, take rests often, specifically when you were stuck on something. 
- Dont't waste too much time in a machine where you are totally stuck. You have more passing paths! So many people regret about this. If you are very stuck move to another machine and give it a try.
- Don't go down, even if after 12 hours you only got 25 points, don't give up. You know very well that sometimes breaking into a machine is no more than typing a single command (you only have to find out where).
- And the most important, bear in mind that **this is an easy certification** and that **the boxes are meant to be easy** and according to OSCP, hackable in 12 hours. You have 24! So believe that you can, furthemore think that if so many other people could, so can you.


Thanks for reading my OSCP 2020 experience, I wish the best for you on the course!

