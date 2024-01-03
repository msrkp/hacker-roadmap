# Becoming a Hacker: My Journey to Become Security Enthusiasts or Hacker and How You Could Become Like One 

The following will be a guide for anyone interested in getting started in hacking or infosec. All the below content is based on the assumption that the reader doesn't know anything about computer/hacking.

"I can only show you the door. You're the one that has to walk through it." - Morpheus, The Matrix. I'm giving you the map, but you've got to steer the journey. Success depends on your effort and choices.

Note: I might be wrong, but I won't be sharing any specific resource for any concept. I believe if doing a specific defined course, and certification will keep someone at the top of the game, then everyone will be successful and the world is full of talented people. You become great at stuff by trying hard on your own, not because someone said you should be.


# Who Am I: 
Never take opinions and advices from a random guy on the internet. Social media is full of fake influencers and content creators, it is always a good idea to research to see if the guy is legit. Here is a summary of my profile.

* **Mohan Sri Rama Krishna Pedhapati** aka *s1r1us*
    * Founder of Electrovolt Infosec
        * Indian-based Pentesting & Security Consulting Firm
        * 10 highly specialized security researchers from all over the world
        * Partner of Cure53, a world class security firm
    * Senior Application Security Auditor at Cure53, Berlin (One of the 20 highly specialized consultants)
    * Blockchain Security Hobbyist at OtterSec, USA
    * Captain of CTF Team Invaders from RGUKTN, and plays with zer0pts
    * Research Topics and Highlights:
        * Browser and Web Security in general
        * Specializes in Client Side Security
        * 2020 – Speaker of BountyCon Facebook on topic Tangled Browsers 
        * 2021 – 4th Place of Top 10 Web Hacking Techniques for Prototype Pollution Research.
            * Presented Research at BSides Ahmedabad Conference
        * 2022 – Research on Electron Applications
            * Found RCE in Most of the Electron Based Application: Discord, VSCode, Teams
            * Published Research in Defcon USA, Blackhat USA, Nullcon Goa Conferences
            * Research featured in vice.com
    * Email: l33tsirius@gmail.com
    * Blog where I publish any interesting research:
        * https://blog.s1r1us.ninja/
        * https://blog.electrovolt.io/
    * Hobbies: Cricket, recently Piano, Guitar, Swimming


# Target Audience and Requirements
0. Anyone who has a knack for solving problems, explore new fields, any student
1. **PERSISTENT Learner**: In my opinion, this is the only quality needed to learn anything. You need to be a continuous learner, however, the learning curve for the first one or two years will be very steep. If you can't ride these initial hard years and be persistent, sadly chances of being successful are very low.
2. **Degree**: You don't need any kind of degree. If you can read that is good enough. I don't think not knowing English very well would be a problem, there are very good online translations that can help.
3. **Resources**: Anyone with a basic configuration laptop and Internet.

# Inspiration

It is important to realize that every one of us has different IQ levels. One might learn or solve problems quickly, while on the other hand, you might take a full day to solve the same problem. In the end, what counts is solving the problem, which is nothing but the quality of a persistent learner. However, it is very important to realize your potential; IQ is not a one-dimensional measure. Some might be good in maths, others in entrepreneurship, and others in coding. Similarly, the infosec field has various areas one can be good at. One who is good at math can choose cryptography, one can choose reverse engineering, and one can choose web exploitation.

Let us consider my case on why to choose web exploitation as the primary field. I used to solve all kinds of CTF challenges like cryptography, PWN, and the web. The basic crypto problems are a no-brainer to me, but when trying to solve problems that involve a lot of math and visualization like elliptical curve cryptography, I used to struggle a lot. You should note that it is not that I can't solve it with persistence; I just take a lot of time to solve it, and my cryptography teammate used to solve it very easily. So, I realized my IQ is not as good as the cryptography and reverse engineering CTF mates, so I explored binary exploitation and web exploitation.

Bottom line: Figure out what you're good at, play to your strengths, and own your game.

# What is hacking?

Opening a beer bottle using your teeth is an unusual or unintended way to solve the problem of opening the beer bottle. In Hindi, there is a word for this *Jugaad*, which means coming up with clever and quick solutions using whatever you have around to solve a problem. Similarly in computer science hacking, someone who has a deep understanding of computer systems and networks can use this knowledge to make software or hardware work in unexpected ways either for problem-solving or achieving specific goals.

For example, increasing likes or views in Instagram posts is a hack. Asking the question needs curiosity, to confirm if it is possible at all needs technical understanding and knowledge of how a web application works. Once you have a technical understanding, exploring various ways to increase likes needs creativity. The curiosity and creativity can be acquired through experience. To acquire technical understanding we need to know about computers and network systems. I will share my thoughts on how to acquire this.

# Computer Science Degree?

You can't be a car mechanic without knowing how the car works. But have you wondered if the mechanics in our towns/villages know the physics of how an internal combustion engine works? I don't think so, they just know enough to fix it. Unlike the medical field, you can go wrong as many times as you want until you fix it by taking help from other mechanics and exploration. A curious mechanic might explore ways to make it more efficient, so he starts learning about the physics and mechanics of a combustion engine. Until this point, he doesn't need to know the science. He can just learn whenever there is a need, this is called learning by doing and I am a very strong believer of it. 

Again I can share my experience of why I believe in learning by doing, during my first year of university I used to complete a lot of courses on artificial intelligence/ML, but I never was able to fully use that knowledge anywhere. I just wasted months completing courses without any results. What I should have done is, I should have participated in competitions at https://www.kaggle.com/ and learn while working on the challenge. Even though I failed in the competition, once it was over I could read the writeup of people who solved it and use it in later competitions. 

And especially the computer science field is so wonderful, anyone can be good at it because every resource you ever need is there online. So here are a few things you should search on Google and read online if you don't know anything about computers. Just search, read, and watch. The first time you watch or read these, you might not understand a bit. But it is fine, you will slowly but surely understand, as I said there is a steep learning curve initially. 

- What is a computer?
- What is an operating system? 
- How does the internet work, and what are common browsers and search engines? 
- What is coding or programming?
- How to run and compile a c program?
- How to configure my IP? This involves searching of lot of sub-questions. What is DNS, IP Address, etc?

If you don't understand or know about a concept you are reading. Search and read about it, it is exhausting recursion(search-read-search-read-search) but after some time the amount of searches you do will reduce.

Ok now assuming, you know how a basic computer and internetwork. Read the following resource, it answers the question "What happens when you type google.com into your browser's address box and press enter?". It is a highly technical attempt to answer the question, you might not understand most of it but I suggest spending a lot of time(a week?) to get a basic overall understanding which involves a lot of Google searches again. 

https://github.com/alex/what-happens-when

## Build a website an app or a game
Now that you have some basic understanding, I highly suggest building an application from scratch. For instance, you can build a web application with backend, and frontend in any programming language of your choosing. I used to build web applications (in Apache, PHP, CSS, JS, and MYSQL) before I dived into hacking. I don't want to share courses on how to build this, just open your favourite editor and start googling(how to x). Moreover, If you like games build a game or an Android application. They don't need to be high-end applications, just basic ones to help you get a sense of programming.


You might be wondering, why I am not sharing any courses or certifications. With experience, I realized I had never been able to excel in the field even after doing a lot of courses and certifications. What worked for me was experimenting and diving into the field directly, and during that journey, if I hit a roadblock about some hard concept, I would read some blogs, and watch YouTube videos, and even if it was still hard(never happened) I might consider doing a course. That is why I am not listing any specific course or certification, just search by yourself and figure out what works well for you.

Based on how good you are, it might take a month, two, or even five months. Take your time to explore and experiment with computers, networks, and programs. And begin the below exploration when you are confident.

You can skip all the above things if you already have experience.

# How to learn about hacking?
There are numerous ways one can choose,
- Online Courses/ Certifications (Not a fan)
- Masters/PhD in Cyber Security (Again not a fan)
- Capture The Flag Competitions (❤️) ( Will discuss what it is in length below)

My thought process is simple, why spend your money when you have better resources and environments online? The advantages of courses and degrees are they push you constantly with exams, assignments, and grades. If you are not at all interested, even the pushing from degrees won't work. If you are interested and persistent, degrees would be good and CTFs would be great. I am not outright saying courses or degrees are a waste of time, they are wonderful if you are fortunate enough to do a solid course, certification, or degree.

# CTF - A place to learn about hacking

To employ the learning-by-doing model, we need an environment to start learning right? Fortunately, we have a wonderful competition and community called CTF which helps us in providing the environment to be a hacker. You don't need courses and certifications. Just participate in CTFs for a year or two, write blogs, do research from the concepts you learned from the CTFs, do bug hunting, and write your findings in a blog. If you do this all perfectly, there is no stopping you from becoming a professional hacker. If you are talented enough, companies don't care much about your degrees or certifications. I know numerous college dropouts and high school dropouts who are pro-hackers.

# What is a CTF?

CTF stands for "Capture The Flag." In the world of computers, a CTF is like a high-tech treasure hunt. Instead of hunting for a physical flag, solve puzzles and challenges on computers to find hidden digital flags(a random string). For example, you will be asked to find a flag in the web application frontend source code. If you know how to look for the front-end code of a web application in a browser, you solved the challenge. This is a very beginner web security CTF challenge, there are levels to it. A highly advanced challenge would ask you to hack the browser itself. Watch the below video from Liveoverflow

[![CTF](http://img.youtube.com/vi/8ev9ZX9J45A/0.jpg)](https://www.youtube.com/watch?v=8ev9ZX9J45A "What is CTF? An introduction to security Capture The Flag competitions
")

# CTF - Where to start?

picoCTF is a great place to start in CTFs, it is designed for high school students in the USA by CMU(PPP). Explore and practice all the previous edition challenges in every category, and try to solve the challenge yourself first, if you can't figure out the solution, search for a writeup online. You can find solutions for almost all previous year's challenges in a Google search.

https://picoctf.org/get_started.html
https://primer.picoctf.org/

This would take solid 3-4 months

Initially, Solving basic challenges of every category is very important to increase your breadth in the infosec field. Once you get a good grasp of what each category would look like, it gets easier for you to choose the category that better suits you. 

Talking about categories, There are different areas in information security, these include

- **Hardware Hacking**: Manipulating or exploiting the physical components of hardware for unauthorized access/actions. Ex: Side-channel attacks, RFID hacking, JTAG exploitation

- **Binary Exploitation**: Finding flaws in Binary Files such as OS, Browsers, and Native Applications 

- **Reverse Engineering**: Converting the Machine code / Assembly back to human readable code.

- **Web Exploitation**: Exploiting Web Apps.

- **Cryptography**: Cryptography involves lot of maths; breaking ciphers, algorithms, and much more. 

- **Forensics**: This involves the investigation of computer systems after a hack.

- **Blockchain Security**: Finding flaws in blockchain implementations, dApps. So much money here….  

## Join a CTF team: good environment to trigger impostor syndrome
Once you get a good understanding of easy to medium-level CTF challenges from picoCTF, start writing about them in your blog, explore other CTF competitions, and try to solve them solo. 

It is very important to join an active CTF team, good active CTF teams won't hire an individual unless he has good stuff in his blog. Therefore, it is important to constantly write blogs and show that you will be a good addition to the team. 

Joining a CTF team helps you increase your network and get to know the mindset of how your teammates solve the challenges. They also make you question your skill(impostor syndrome), which is also very important. It will show how noob you are, few people ever realize their skill and be in a delusion that there are very skilled, this is a very bad trait because it will stop your learning. Furthermore, Teams also provide a healthy competitive environment among teammates.

Bottom line
- Learn basics from Pico
- Solve challenges from other CTF competitions and write blogs
- Pick one specific category (I choose web exploitation, after realizing my worth in cryptography and binary exploitation)
- Join an active CTF team, increase your depth in the specific category
- Read and write a lot of blogs

Resources that I used in my journey of learning web exploitation
- https://www.amazon.com/The-Web-Application-Hackers-Handbook/dp/1118026470
- I took other CTFers as an inspiration and duplicated whatever they did, solving all the challenges they previously worked on, and reading all their previous writeups. I read almost all the blogs of the people I listed as inspiration here https://blog.s1r1us.ninja/inspiration
- https://www.oreilly.com/library/view/web-application-obfuscation/9781597496049/
- https://portswigger.net/research

# Research and Bug Hunting( Bug Bounties )


After a solid year of CTFs, you will be in a position to get started in Bug Hunting and Research. Along with the CTFs on the weekend, start exploring bug hunting and security research. 

I have an interesting personal story, I did CTFs for almost a year with the Invaders team. On Twitter I saw people earning tons of money via bug bounties for very easy basic bugs, I was so tempted and with overconfidence, I started doing bug bounties in web applications. I tried this for a few months, but I was not able to make much as other people were doing. I realized that even though the bugs are other people who are finding easy bugs, they have a few advantages like early access to bug bounty programs, experience in where to look, and persistence. At the same time, I also found a few people finding very technical bugs in the application explored by a lot of bug bounty hunters but they never were able to find the same bug. To level up my skills, I again started doing CTFs now by joining zer0pts, a Japanese CTF team and I continued CTF for a year actively in that team. 

During my active CTF participation with Invaders, I found interesting research areas which I explored and applied in the bug bounty field, and interestingly enough I was able to find bugs in the applications which are previously hunted actively

Some research I did with the help of ideas from CTFs
- https://blog.s1r1us.ninja/research/cookie-tossing-to-rce-on-google-cloud-jupyter-notebooks
- https://blog.s1r1us.ninja/research/PP
- https://blog.electrovolt.io/

I made good enough money via this approach instead of trying to find basic bugs.

# Getting a job

At this point, you learned
- Basics of Computers
- Built an application
- Participated in CTFs
- Find some interesting bugs in real-world application
- Wrote blogs and published very good research
- Made connections in meetups, on-site CTFs and conferences

You can either continue earning via bug bounties and research like few people who do full-time bug hunting. Or join a company like I did by using the blogs as leverage. 

Even though I believed, I had a very solid resume I was rejected by a few Indian companies, and my resume was never considered by some. One company that rejected me was Flipkart, I still don't know why they rejected me in the final HR round maybe because of my bad communication skills. or maybe they don't know the value of my research? At that point, I thought I was not good enough for corporate companies. I continued my search and I got an offer from Bugcrowd, which I didn't join due to some complications.

During the CTFs and bug bounties, I made so many friends, that I asked my research mate Masato to refer me to his company(Cure53, a company I always dreamed of joining). He happily did, and the Cure53 didn't even perform a formal interview and hired me and I showed my skill :).

If you think there is so much competition in the information security field, you are wrong. There are very less highly skilled people in my opinion. So, try hard until you reach a level where people don't consider looking at resumes or degrees or certifications. Just by looking at your previous work, they will hire you.

Not any company, just show me your CTF writeups, research, and experience. I will hire you and pay you around 50 - 1 Crore salary. If you don't believe what I say, that there no Indians in our company because I couldn't find one, all of them are top CTF players from other countries. Not saying that there are no pro hackers in India, there are many who are working for all the other high-paying companies. At this moment, I couldn't find one who I think is at the level of people who are currently working for our company.

# Final Thoughts

It is very easy for me to write the roadmap reflecting my experience, my journey, and what worked for me. As I said each and everyone has different IQ levels and dimensions, if you are a very slow learner and need help from courses and certifications, complete them, but use that experience practically in CTFs, bug bounties, or security research. Our end goal is to make a solid profile for ourselves to showcase to the companies to get us hired. 

I can assure you that it will be very hard for an absolute beginner but it is not something unachievable. People waste four years for a garbage degree, you can spend the same time to be very good at information security. I would say I spent 6 years of my college life to be in the place where I am now.





