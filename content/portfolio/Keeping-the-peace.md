+++
image = ""
showonlyimage = false
date = ""
title = "Keeping the peace between IT and Development teams"
draft = false
weight = 12
+++
A list of Do's and Don'ts of creating a good relationship between your Developers and IT

Originally written in 2011 and most of it still valid.

<!--more-->
_In 2006, R&D Developers at a Fortune 100 company were building code for a new variant of a programme. They found the native virus checking to be an annoying obstacle to their work, and were allowed to become Local Administrators on their machines to disable it. A virus entered through a malware web address visited during testing and spread through the LAN into all unprotected machines. The clean-up took thousands of man-hours. In reaction to the security breech, the IT department released an improved virus checker that could not be disabled by Local Administrators, and it was rolled out to the R&D Developers. The new virus checker increased build times 400%, resulting in thousands of hours of lost productivity in the two weeks it took to uninstall. The new virus checker could only be uninstalled with intervention from IT, and a year later the company was still running two virus checkers with a large population of unprotected machines on their network._

This sobering story is just one example of many where your Development Teams and the IT department clash while both are trying to do their jobs to the best of their abilities. It demonstrates just how tricky managing the relationship between your IT department and your product development teams actually is.  Get it right and you can sit back and contemplate your coffee.  Get it wrong and you’re at risk of losing countless hours of productivity. What can be done to ensure that it doesn’t go wrong? 

From my experience there are seven keys to making the relationship work for both sides. As with the best business advice, the keys are in and of themselves very simple. It will be in practice that the “how” of these keys become evident. And like any tool, they will be more effective the more they are used.    

1.    Accept that it will always be a fraught relationship

These two factions are the competing übergeeks within your organisation - they both love their computers, codes and networks with a passion.  Set clear ground rules in the relationship.

* Be Open: both sides need to clearly state their needs and priorities
* Be  Clear: While both developers and IT speak geek and computer fluently, this can get in the way of real communication. Try to have conversations without acronyms.
* Be Reasonable: If something breaks your work, it’s important. If something means a small change to your ways, it is less important. 
* Be Respectful: Both developers and IT play vital roles for the company. Get them to be respectful towards each other, this may eventually build to respect. 

2.    Understand what your development teams need

To write the software that is often the backbone of your company, developers will have some very specific needs and wants. 

* Installations: Developers will need to be able to install their software, script languages, scripting tools, and a multitude of programmes. Different development teams will have different installation requirements; the testing and infrastructure team members might differ markedly from the coders on the team.
* Updating system files: Developers will want to change all sorts of system files. Registry and hosts file changes are often needed to test software.
* Creating multiple versions of key files: Developers often need to have several versions of Java installed. They may also need different versions of .Net.
* The Code developers require these to fulfil their roles as a developers - they don’t want to spend time managing their machines and doing “IT work”.
* Network rules might differ - the team will want to open ports, connect to machines and run virtual machines or connect to cloud-based machines. 

3.    Understand what IT needs

To maintain a good corporate IT environment, the IT department will have some very specific needs and wants.

* Standardised Environments: IT needs to have a known, small set of machines and Operating System variants to maintain.
* Managing the environment: IT wants to prevent users changing their machines in ways that will introduce new variants for testing. 
* Knowing the consequences: IT wants to be able to roll out changes to the computing environment fully cognizant of the implications
* IT wants the above in order to fulfil their role as an IT department - they don’t want to spent time managing problems and resolving complaints.

4.    You have to treat the Development environment as a special case

IT must know and understand what Coders are doing and are planning to do. 

Work with the Coders: Help deploy Code development software. That means IT is aware of updates and changes and can plan around them. Note: this suggestion will upset both Coders and IT, because Coders considers IT to be inflexible and IT will worry about the amount of updates. Resolving this requires a light touch, both in terms of process and technology. If it takes 12 to 16 weeks to package and test a release, Code teams will look elsewhere, as this timing is too slow for them. 

At the same time, IT will chafe at the idea of installing non-standardised software, which may be open source, have a small support group, or be outside corporate guidelines. IT will also resent the workload on the packaging team, and may seek to deprioritise any Coder packaging work. 

Testing on Development Machines: Ask Coders to create automated testing of the most common steps in development (get SDK, get binaries, build, run). Have IT learn to use this and run updates through these tests. Note: this is again a big ask but a huge win. If IT can spot issues that could impact Coders in the early testing phase, a solution can be found prior to any roll out to the production environment. Catching potential problems early keeps them from becoming actual problems. 

Deliver updates on a schedule: Coding teams agree to take tested IT updates on a standard schedule (same day each month). This means any overnight work (builds and automated testing) can be planned around potential reboots. Note: both Coders and IT will always want to cancel or change this because of an “urgent need”.  To help manage this, ensure that only staff reporting to the CEO can stop this agreement. If it is important enough to get the issue discussed at this level, it is important. 

5.    Development teams will hate talking to IT (and vice versa)

If you spend your day writing code, being walked through your settings when you know the command line shortcut to the same place is very frustrating.

If you spend your day walking people through the trouble shooting process, having someone argue with you about your methods at each step is equally frustrating.

It’s all about respect. Build on this quickly:

Ensure Coders problem’s are handled by your most knowledgeable IT staff at that level
Ensure IT staff handling Coder calls have an understanding of what the Code Development teams do everyday.
This comes down to documenting, training, and up-skilling your frontline IT staff. 

6.    Coders will hate talking to Code tool Developers

When you create and maintain tools within your Product department, you must maintain a small, focused support desk. This will take over the triage, training and some testing functions for the Coding Tools Development team. 

Depending on the number of Product/Development teams to support and the number and complexity of the tools, this can be handled by a small team (less than 10 people). Don’t try to put in full IT processes - a light touch process and issue tracking tool will be sufficient. 

This support team provides a catch-all point for the developers and the issues are then passed on to the correct development Tool Development team or off to IT.

The IT department won’t be able to up-skill all of their staff to understand the developmebt tools and processes. Note: they will try, but you need a team focused on supporting Coding tools, and this team need to be able to go through the processes for development of your code. If the support team can’t go through the code development processes, how can they confirm issues and test patches?

The Coding Tools Developers won’t have the time. If you are trying to create patches and updates, the last thing you want to respond to is “How do I…?” questions and “It broke when I did this…” emails. Note: they will try, but will get frustrated at the interruptions in their workflow and provide less than ideal support - often referring to ‘functions as specified’ as a solution.

You will need a strong manager with both a developer and a support background for the team. You need someone who understands both sides of this schism. They do exist, generally in telecoms network third level support teams.  For the other members of the team, this can be an ideal starting role for junior developers as they get exposure across the organisation. 

7.    Manage the relationship

Even if you follow the above six keys to the letter, success is still not guaranteed. This is a relationship that must be continually managed and guided. Someone has to keep checking and smoothing the friction points.

Create a team of people equally respected (or equally hated - both work) by Developers and IT departments. This team must have liaisons in both departments from the mid-grade to the CEO level, and must be able to escalate issues through management levels.

The team must be close enough to the Developers to be able to understand how code is developed, built and tested. 

It must be close enough to the IT department to understand ITIL, especially change management and problem management.

Get the team right and the rest will follow. 

These seven keys will lead to a functional relationship between your IT and your Coding departments. 

Our Fortune 100 company eventually repaired their Development/IT schism. A test plan was agreed between the camps and the virus checker settings were updated with input from the manufacturer until there was no more interference in the automatically tested Development machines. A roll-out plan was created to incrementally roll out to developers and any issues arising were picked up immediately (there were two, both due to hardware issues). In 6 weeks, a standardised virus checker was working on all machines in the company.