---
title: "From Unemployed to Full-Time Bug Bounty Hunter"
collection: stories
permalink: /stories/from-unemployed-to-full-time-bug-bounty-hunter/
date: 2025-12-28
excerpt: "“Can a man still be brave if he's afraid?” “That is the only time a man can be brave.”"

---

> “Can a man still be brave if he's afraid?” “That is the only time a man can be brave.”
>
> — **George R.R. Martin,** *A Game of Thrones.*

---

### Graduation and the big "Now What?”

**June 10, 2024.** I walked across the stage, grabbed my Computer Science degree, and immediately hit a wall. One question was stuck on a loop in my head: *Now what?*

For the two years leading up to that day, I had been a sponge for everything security. I spent every spare hour in the weeds of web vulnerabilities, networking, Active Directory, and the non-stop rush of CTFs. 

![Story illustration](/images/image1.png)

![Story illustration](/images/image2.png)

I was jumping from one topic to the next, hoarding knowledge like it was a mission.

But the moment I graduated, the mission changed.

Hacking for fun wasn't enough anymore. It was about survival. I needed to work. I needed to make money. I needed to move to the next level of my life, but that shift left me feeling completely lost.

I fell into a trap that many of us know: I kept telling myself I wasn’t ready. Even though my skills were solid, I felt like I needed one more certification or one more deep dive. Every day that passed without a "plan" felt heavier. The stress of being lost started to outweigh the excitement of the craft.

I was paralyzed by the "Now what?" until the pressure of reality finally forced an answer. I realized I couldn't keep preparing forever. I had the foundation. I had the hunger.

It was time to stop being a student and start being a practitioner. It was time to turn the hobby into a career. It was time to make money.

I spent the next few weeks reviewing everything I had learned. Web attacks, network hacking, scripting, automation, Android security: I went through it all.

During that time, I built what I call my Red Team Second Brain. It’s a massive Notion database containing every note and technique I’ve picked up over the 2 years of learning hacking stuff. You can check it out here:

[Red Team Second Brain](https://www.notion.so/Red-Team-Second-Brain-d10f6ea9f80b4737b0d93569491ac60a?pvs=21) 

The skills were there. The review was done. But the question remained: *Now what?*

### The job hunt reality check

I started applying for jobs. I sent out resume after resume, only to be met with rejection after rejection. Most jobs wanted years of experience I didn't have. I looked into internships, but I wasn't in a position to work for free, and entry-level pay wouldn't be enough to survive.

In my last year of the university, I had tried my hand at bug hunting on VDP targets via Intigriti. The process felt natural. I’d run my subdomain enumeration, find a target, and the bugs would start appearing. I found multiple SQL injections, escalated them to RCE, grabbed account takeovers, and caught plenty of low-hanging fruit.

![Story illustration](/images/image3.png)

![Story illustration](/images/image4.png)

But back then, it was just a VDP. They didn't pay. I eventually stopped because I wanted to focus on mobile app security.

Now, looking at the job market, I realized bug bounty was my best path forward. I knew it wouldn't be easy. But did I have another choice? The short answer was no.

I remembered a saying: **the water will never get warm if you jumped late.**

So, here we go again.

### Drowning in Bugcrowd

I went to Bugcrowd and started jumping from one program to another. I had no idea what I was actually supposed to do. I would run recon, create accounts, and explore, but I was completely lost. I would open Burp Suite, look at the traffic, and just stare at the screen.

It felt so different from CTFs. In a CTF, you have a clear goal and a small environment. But here, everything was huge. One click generated dozens of requests, and I didn't know where to look. I could exploit bugs in a lab, but the real world felt like a mess of noise.

### Meeting Lolamero

I used to be a lone wolf, and I loved that. I liked the idea of solving everything on my own. But as the saying goes *“When the snow falls and the white wind blows the lone wolf dies but the pack survives”*

After wandering around for a few days, I saw a profile for a hunter named Lolamero on a program. For some reason, I decided to look him up on LinkedIn. I reached out to ask for advice or see if he wanted to collaborate.

That changed everything.

We started sharing ideas on how to actually work. I had the technical skills, but Lolamero had the experience. He helped me understand how to approach a real target. Day after day, we worked together. We stopped obsessing over massive recon data and started focusing on manual hunting. We realized that collecting thousands of subdomains was useless if we didn't know what to do with them.

> On a related note, I really like how **zhero** breaks down the different types of bug bounty hunters in one of his articles. Definitely worth a read.
> 
> 
> https://zhero-web-sec.github.io/thoughts/bugbounty-feedback-strategy-and-alchemy
> 

### The Turning Point

We were working on a program on Bugcrowd when we spotted an IDOR bug. We reported it and kept grinding. Then, on the 10th day of our collaboration, it happened.

We got our first bounty. It was a four-digit payout.

![Story illustration](/images/image5.png)

Everything changed that day.

That first payout was pure fuel. It was the proof we needed: if we could do it once, we could do it again. We had the momentum, and for a moment, it felt like we had finally figured it out.

But the honeymoon phase didn’t last forever.

### Chasing the next win

After that big success, we moved on to other targets, but things didn't go as planned. We jumped from program to program, searching for the next big hit, but it wasn't coming. Eventually, we landed on a target where we found three bugs. They were valid, but the payouts weren’t that big.

![Story illustration](/images/image6.png)

The high from that first four-digit bounty started to fade. The motivation disappeared, and we realized we had to start building our momentum all over again from scratch. It was a reality check: bug bounty hunting isn't always about big wins; it is a slow, quiet grind.

### The pack splits up

Just as we were starting to find our rhythm again, life got in the way. After a month of hunting, Lolamero had to make a hard decision. Between university exams and projects, he was completely overloaded. He decided to pause bug hunting and focus on his studies.

Suddenly, I was back to being a lone wolf. I was right back where I started standing alone, staring at the screen, and trying to figure out how to keep the fire burning by myself.

But this time, it was different. Thanks to the time spent with Lolamero, I had a one month experience on hunting and some money in the bank. I wasn't that stressed anymore. I didn't feel like the lost graduate I was back in June. I just knew I had to keep working.

### Back on the solo grind

It took me about seven days of digging to find a new target I could actually stick with. I found a program with a massive application. The payouts for Privilege Escalation weren't great, but the scope was good.

Instead of jumping around, I decided to live in this app. I learned it inside and out. I studied every function, every use case, and every button. I tested everything I could get my hands on, The main web apps, the APIs, and the mobile versions.

![Story illustration](/images/image7.png)

The bounties were small, but they were consistent. By the time I was done, I had 40 accepted bugs in 40 days.

### Crafting the methodology

This was the most important period of my journey so far. This wasn't just about the money; it was about the growth. During those 40 days, I finally stopped guessing and started building a real methodology. I crafted my own work style and, more importantly, I built the right mindset. I wasn't just looking for bugs anymore; I was analyzing systems.

By mid-December 2024 and after 75 days of consistent work, I felt like a completely different hunter. I had the rhythm, I had the skills, and I had the confidence.

Then, my phone lit up. It was a message from Lolamero.

He was back.

This time, we were ready to put in some real work. The university distractions were over for Lolamero, and I had my 40 days of experience to back us up. We weren't just testing the waters anymore; we were hunting for real.

### The pack returns

It wasn't perfect right away. We started hitting a wall of duplicates and "Not Applicable" (NA) reports for some really strange reasons. It was frustrating, but we didn't let the momentum die.

Then, we hit the jackpot.

We spotted two good valid bugs. Each one paid out a four-digit bounty. Not long after, we found another one. 

![Story illustration](/images/image8.png)

We were finally in the zone, enjoying the work, and the money was better than anything we had seen before.

### The move to HackerOne

By mid-January 2025, we felt like we had outgrown our old routine. We were confident, our methodology was sharp, and we were ready for a new stage.

We made the decision to pack up and move our efforts over to HackerOne. It was time to see what we could do against the biggest targets in the world.

We made the jump to HackerOne, and it felt like stepping into a new playground. We picked a famous target with a solid bounty table. We weren’t just looking for any program anymore; we wanted one that actually respected the work we were putting in.

### A fast start on HackerOne

The preparation from the last few months paid off almost immediately. On our first or second day working the program, we hit our first bounty on the platform. It was the confirmation we needed: our methodology worked, even on the bigger stages.

![Story illustration](/images/image9.png)

We stuck with that target for a while, really digging into the corners of the app. Once we felt we had seen enough, we shifted our focus to another program. The success followed us there, too, we landed three more good bounties in a short amount of time.

Everything was finally going well. We had the rhythm, the partnership was solid, and the results were showing up in our dashboard.

But in bug bounty, the highs are often followed by some lows.

### The wall of duplicates

After that initial success,by mid-February after a month on HackerOne we went straight into a dry spell that lasted over a month. It was the hardest stretch we had faced so far. No matter what we found, every report we sent came back as a duplicate. We didn't receive a single bounty for weeks.

It was a massive test of our discipline. It is easy to work when the money is flowing, but it’s a different story when you’re hitting dead ends every day. We kept showing up anyway. We jumped from program to program, grinding through the "dups" until we finally landed on a new target.

### The Critical breakthrough

At first, this new program felt like the others. We submitted some bugs and got hit with more duplicates. Slowly, the "Dups" turned into "Triaged" reports. After a full month of work on this one program, we finally got the notification we had been waiting for. It was a Critical bug. It was our biggest bounty to date, and it completely changed our perspective on what we could achieve.

![Story illustration](/images/image10.png)

### The power of going deep

For the next two months, we didn't look anywhere else. We lived in that one program, trying to go deeper every single day. We kept submitting bugs and the bounties kept coming.

It wasn't about finding the easy, low-hanging fruit anymore. It was about persistence. We realized that the real rewards come when you stay on a target long after everyone else has given up and moved on. In the end, the month of silence and the wall of duplicates all paid off.

As time went on, our methodology improved day by day. We weren't just guessing anymore; we were becoming clinical in our approach. After two months of solid results on the last program, we decided it was time to find something new.

We brought the same "deep dive" style of work to the next target. It started the same way it always does, a few duplicates at first while we learned the ropes, but then the real bugs started to surface. We spent another two months living inside that application, finding complex vulnerabilities and landing good bounties.

### The hunt for a new home

After those two months, we entered a phase of exploration. We started playing around with different programs and receiving bounties from diffrent programs, trying to find the next target we could truly stick with. We were bouncing from one app to another, testing the waters and waiting for that one target that clicked.

At the start of the year, we had set a challenging goal for our total bounty earnings. It was an ambitious number, the kind that feels a little bit out of reach when you first write it down.

### Hitting the target

While we were still searching for our next long-term program, we stumbled onto a vulnerability that changed everything.

We found an authentication bypass that led to a full Account Takeover (ATO). It was a high-impact, sophisticated bug, and the bounty reflected that. With that one report, we didn't just get a win; with it we was able to complete our yearly target.

![Story illustration](/images/image11.png)

It was like mid-November 2025 and it was a surreal moment. Looking back at where I was in June 2024, lost, stressed, and paralyzed by the "Now what?", it was hard to believe how far the journey had taken me.

Everything we went through, from the months of silence and the wall of duplicates to the long nights of manual testing, had led to this.

After hitting that major milestone, we finally took some well-earned rest. We stepped back from the screens to recharge, but our minds didn't stop. We spent that time developing our own tools, turning our ideas into code that would help us work faster and smarter.

### Back to the hunt

When we got back to work, we found the target we had been looking for. We have been stuck to this program for over a month now, digging deeper than ever. We’ve already submitted several high-quality reports, and our triage inbox has cool findings just waiting to be paid out.

### The real win

This journey has been a rollercoaster of massive highs and crushing lows. But looking at everything I’ve achieved, the biggest win wasn't the 4-digit bounties or the ATO bugs. It was the collaboration with **Lolamero**.

We found a chemistry that you can’t just manufacture. We share the same values, the same hunger, and the same ambitions. Having someone who is just as driven as you are makes the dry spells easier to handle and the big wins even better.

I started this journey as a lost graduate on a stage in June 2024, paralyzed by the fear of the unknown. I went from hoarding knowledge in a vacuum to building a "Second Brain," finding a pack, and eventually crafting a methodology that works in the real world.

The water didn't get warm because I waited; it got warm because I jumped. If you are standing where I was 15 months ago —stressed, lost, and wondering "now what?"— my only advice is to stop preparing and start doing.

![Story illustration](/images/image12.png) ![Story illustration](/images/image13.png)

Looking back, it is incredible how much life can change in just 15 months of hard work.