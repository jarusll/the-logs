---
title: Diary
layout: layouts/home.html
date: 2022-03-24T00:00:00+05:30
---

# 2022-06-04

I need a refresher on redux. While I am at it, I'll write about rapid redux prototyping.
Org mode turned out not to be so good with live programming.
I installed & hosted jupyter notebook with javascript kernel. So far really good. I want live programming. Lets see how this goes.

# 2022-06-03

Recently during our conversations, we came across [Zettelkasten](https://eugeneyan.com/writing/note-taking-zettelkasten/#what-is-a-zettelkasten) system.

![Jun Zettelkasten setup](/images/jun_zel_setup.jpg)
*[Jun](https://arjunchoudhary.com/)'s Z setup* 

Now that I've been pretty acquainted with org-mode, I can start making notes. I realize I do tinker around alot of things but I don't write it down. So when I do go back, I have to backtrack from the beginning. I will be trying out org-roam for the coming days.

![Image](/images/1d911ae08bbc71bc60f71c388733d028.jpg) 
*Stray release date announced*

One of the games I am really excited for. I know I'll like it when it's produced by Annapurna Interactive

For the past few days my prototyping langauge has been Ruby. Even with 0 knowledge I am able to prototype rapidly. Its about time I did Ruby koans.

I'll get comfortable with org roam

Tomorrow's plan is to tinker around org roam and zoom through Ruby koans

![Image](/images/fa5711aacc7e9f5bb22a8f4c45d2f5fd.jpg) 

# 2022-06-02

0 config sftp is up. Although I don't have a use for now.

Plan for today
- [ ] Optimize site for mobile
- [x] Lookup basic seo files
- [x] Read mongodb manual

RTFM has proved to be the best guide

I skimmed through the mongodb manual. I learnt about the voting process if the primary node fails and I think its cool. 
I like distributed systems. I believe distributed programming & distributed storage comes under distributed systems. I might be wrong but I like them all.

I think one of the reasons I do like distributed systems is the horizontal scaling part. The fact that you can scale a system with relatively low powered hardware is cool.

Writing about a solution helps me gain more clarity. Its me directing the reader with the right questions at the right time to understand the solution.

I need more clarity on Manacher's algorithm

# 2022-06-01

Todays plan is to push the two post in pipeline and read about concurrency.

Cronified builds.

![Image](/images/f79daed00e572ea3ea066092cd5f878d.jpg) 
*Low effort CyberDeck*

Kadane's algorithm is out.

Running full fat Emacs on termux was slow, so I am using it on the vps. How cool is that, my own lil codespace.
I'll push Manacher's algorithm tomorrow.

Read about the actor model in concurrency and it's my favourite concurrency model. I won't code anything concurrent until I have very good knowledge about it.

# 2022-05-31

Just lost my changes by fucking around a detached head branch. 

Your home made cicd, CRON.
I could utilize github actions to build & push to vps but I won't because I will do things without automation for a week and automate incrementally.

Fixed nav background on mobile. The color glitch out on firefox because of vendor css props. I'll just use postcss to even everything out.

Wrote about Kadane's algorithm for linear time subarray sum. Looked at 
Manacher's algorithm for longest palindrome.

1 medium problem a day and a solution post is good enough. Tomorrow's plan is to integrate the artworks on site and cronify builds.

I looked at prolog today along with 99 problems in prolog. Logic programming has very elegant solutions and I like it. 

# 2022-05-30

Dark mode with invert hack integrated.
Did some clean up as well. I need to do some more for mobile.
Todays plan is to host the site on vps. The biggest letdown will be cicd. I have automated build triggers on submodule push. I don't know how I'll achieve that on vps.

I have `next lexicographic permutation` in pipeline today.

Brainfucked myself with firewall rules with `firewalld`. For some reason 443 wasn't going through it. I switched to `ufw` and allowed all necessary ports and it worked. I can start migrating my site to vps.

I won't automate anything for now. Will run this scavenged setup for a while so I can appreciate abstractions.

I learnt a lot today. Hosted my first site from scratch. Although `caddy` made alot of things easy, I will read about hosting for the coming days.

This will be my playground. I'll go from this scavenged setup to production docker-compose with caddy or nginx.

# 2022-05-29

I wrote a piece today. One is half done.
I feel like the code is redundant. Once idea has been passed, people can do it themselves. I'll soon move to psudocode

I got the Oracle free forever VPS. I'll setup hosting my website on it. If everything goes well, I'll setup a git instance as well. All of this using tailscale.

I don't see any point in having `fragments`. I'll merge it asap.

I tried some Ruby today. Its the closest thing to smalltalk. It has definitely peaked my curiosity and I know I'll be solving Ruby koans soon.

Recently Gopher came up in a conversation so I looked up other web protocols. I browsed gemini and gopher and I like the simplicity. I've always tried to go the other way. I don't need performance or fancy graphics. Thats why I use i3 and live in emacs. I'll look into porting my site to gemini and gopher. I'll be reading about them as well. 

# 2022-05-28

I am totally skipping over shared memory model in concurrency. Its too tedious and I'll never use it IRL.

I did it. My magnum opus till now. [Generating Permutations](https://surajyadav.xyz/fragments/generate-permutations/).
Written & evaluated in `org-mode`. Socratic dialogue + first principles. I am very proud of myself.
I will continue writing.

I haven't been able to write because of less desk time. I ordered a wireless keyboard. Its about time I go mobile.
Its termux time.

Good day, night.

# 2022-05-27

So much to work on today

Todo
- [X] Remove word count and read time
- [X] Change footer
- [X] Increase font size
- [X] Copy assets to static script
- [X] Copy relevant files from theme and remove theme

Read about concurrency patterns. Concurrency is my new obsession. I'll mess around with go subroutines.

Setup tailscale today. I'll look into it more tomorrow.

Tomorrows plan is to write some literate programs in org mode & read about concurrency.

Good day, night.

# 2022-05-26

Spent the day migrating to hugo. Need to setup cicd. 
Used [hugo-theme-mini](https://github.com/nodejh/hugo-theme-mini) 
![Preview](https://raw.githubusercontent.com/nodejh/hugo-theme-mini/master/images/screenshot.png)

Once this is up, I can start writing with org-mode.

Good day, night.

Testing new site trigger from submodule update. 
The new site didn't had the submodule push triggers. Added. Testing again.

IT WORKS!!!!!!!! AHAHAHAHAHAHAHAHAHAHAHAHAHAHAHAHAHA

Tomorrow, I'll fix the assets and it should be good to go.

# 2022-05-25

My leetcode practice & horizontal scaling obsession paid off. Fingers crossed.
I came across Bionic reading today. Its my new obsession. I installed a chrome extension so its on every page. I converted all my ebooks to bionic & sent to kindle. Been a while since I was this excited about reading.

I increased my font size on every system and my readability increased alot.

I have been thinking about hugo because of its native support for org files. Let me think about this.

# 2022-05-24

I have been looking up to something.
I read abit about Hadoop today. I am very interested in horizontal scaling these days.

Good day

# 2022-05-23

Personal day. 

# 2022-05-22

I binged Love, Death & Robots last night.

I played Transistor today. Its aesthetic. The art style and the little touches like the humming and the songs, this definitely makes in my top 10 list.

Today's plan is to solve some leetcode problems. 

`It should be noted that no ethically-trained software engineer would ever consent to write a DestroyBaghdad procedure. Basic professional ethics would instead require him to write a DestroyCity procedure, to which Baghdad could be given as a parameter.` 
- *Nathaniel Borenstein, 1992*

# 2022-05-21

Migrated to use-package in emacs & started using mnemonics for keybinds like spacemacs.

Base system for org site is up. I'll port my site over the coming days.

Good day, night

# 2022-05-20

Personal day today.

Took a online assessment test. Pretty good in frontend.  Average in backend. The backend assessment had alot of cryptographic security questions. 

Tomorrow, I'll start publishing org-mode. The plan is to get the system up ASAP and then I can port my site slowly.

# 2022-05-19

I'll be reading about horizontal scaling today. System design is my new obsession.

# 2022-05-18

The sample fullstack app is ready.

I had the whole thing up & running on localhost & I thought about trying it on my phone and oops, it doesn't run since localhost no longer points to my pc running the backend. Hopefully, the people from docker discord server helped me out and I learnt that its out of scope of my task.

Random people from discord are way helpful than any person I've met. You post one issue and two of them spam you with solutions and encourage you to ask more questions. Nice people.
Here's the server [Docker Discord server](https://discord.gg/XwvrsZ6r)

# 2022-05-17

Finally was able to get Prisma working in docker.

And after that I wasn't able to access the db instance from internal network. Turns out I was trying to access on external port. This was the first time I am trying to setup a full stack app. 

Tomorrow I should be able to be done with bulk of the problem. And then only finishing touches.

Good day, night

# 2022-05-16

I'll be messing around with Databases & its design for a while.

I am a beginner with database modelling. I could really improve there. I have decided to master psql and redis for now.

# 2022-05-15

Plan is to dockerize a fullstack sample app.
This evil & emacs combo is working very good. I don't want to switch my workflow to evil fully. I just want vim's powerful motions.
For the rest, emacs will do.

Integrating the backend is remaining in frontend.
Barebones backend is up.
DB needs to be implemented.
The whole thing is dockerized.

I tweaked which-key for faster response time. I still need a way to make which-key overlay on all the time. I'll be looking into it soon.

Good day, Night.

# 2022-05-14

I switched to `evil-mode`. The plan is to use evil-mode for editable buffers & emacs for read-only buffers.

I had my personal day. 

# 2022-05-13

I wasn't able to complete the challenge but on the upside I can write programs literate style now.

![Image](/images/d312a0c721255e43827d273349806bcf.jpg) 

![Image](/images/42a5a9804d0033e4ef3586135fd2d355.jpg) 

# 2022-05-12

I made a small mistake of using JSON as storage, should've gone with sqlite. I can't serialize python datetime into jsonvalue.
I have to look into it. 

Second, this is the first time I am using org-mode & literate programming for my development. I am still figuring out optimal ways to use it. I run snippets as well so the dev is iterative. I write a main program with the logical chunks-tags and then write those chunk tags in another block. But I want to test the chunk as well, so I write another block to test that code. If there are dependencies for a chunk, the get expanded as well so code is duplicated in the source file. I need to come up with a better solution for this so I can write my program as chunks, test them and the resulting source has no duplication.

All of this because I want to organize my program like a blog and instant feedback.

# 2022-05-11

Couldn't use my pc or wifi for 24 hours because the socket broke down.

Worked on the devops problem. Should be done by tomorrow.

# 2022-05-10

Started with a devops challenge, I am using literate programming for it and I am absolutely loving it. I am going in blind. Lets see if I can do this.

# 2022-05-09

Looked into noweb.

Occupied with personal stuff.

# 2022-05-08
I came across noweb for org-mode and I have fallen in love with it. It allows me to write seperate chunks of code and include in other chunks. I can start writing literate programs now. 

The other problem, more of an inconvenience is lack of support for org-mode for 11ty framework. I am looking into exporting my site to org-mode.

When I seperate the code in chunks and prepend the required code for evaluation, the prepended code also shows up in export. The prepended code is duplicated so it shows up twice. Using the `:noweb strip-export` flag fixes it. This is turning out to be real good.

Nixos would be an overkill for me. Another alternative for me would be managing dotfiles using GNU Stow and flatpak everything (I don't know if it's possible).

I am diving deeper in literate programming. I came across Leo editor today and I'll check it out tomorrow

Good day, night

# 2022-05-07
Org-mode is very good. Good as in it can take over my life for documentation, programming and note taking.

I'll be moving towards org mode slowly.

Maybe in an year I can get really efficient with org-mode and migrate my site to it.

I wrote a literal program in org-mode today. I still need to figure out how to integrate it on my site because it uses markdown. There are some issues which need to be fixed for markdown export from org-mode.

Good day, night.

# 2022-05-06

I am just spamming recursion with memoization and I am loving it.

I got TLE(Time Limit Extended) on 2 medium Dynamic programming problems today. Need to think about optimization.

# 2022-05-05

Dynamic programming & org-mode it is today.

I haven't setup emacs as proper ide so I've been using vscode for leetcode.

It happened again, Leetcode passed Wrong answer verdict for a working solution. This has happened multiple time and its frustrating.

I'll be moving towards cpp for problem solving

I have familiarized myself with debugging and now I can't live without it. Right now, the only dynamic language with good debugging support is Python.

![Image](/images/85f74287984d72c156b421909461417b.jpg) 

I need to figure out the layout I'll be using for literate programming.

Good day, Night

# 2022-05-04
Feel pretty comfortable with Linked lists & Doubly linked lists.
Recursion still seems to have downside with function call overhead. But I still prefer it over iterative solutions.

I have decided to publish the solutions as literate programming, using emacs `org-mode`

I'll be getting better at `org-mode` for the coming week.

Solved some more linked list & doubly linked list problems. Came across counting sort.

Tomorrow's plan is to solve some easy->medium dynamic programming problems.

# 2022-05-03
Solved a sliding hash problem.
Solved 2 more medium recursion problems.

I have decided to publish my leetcode solutions in fragments. I'll do that from tomorrow.

# 2022-05-02

Solved a linked list problem with 2 pointers. I am better off solving medium problems now.

![Image](/images/567adb1b5ddccd84b7228fa87394cd61.jpg)  
I should've bought her home but her siblings were around.

One of the downsides of recursion is the hard limit langauges have for recursive calls. Even if it's tail recursion.

Good day, Night

# 2022-05-01

Plan is to solve BST & Linked Lists today and look into bit masking.

![Image](/images/0a9b90f2a33b3be82eb38a49e7a356f8.jpg) 
I'll be bald this whole summer, probably.

I conducted a survey with a sample size of 2, including me if the 1/6th sliced sandwich is too big and the results are
- Yes - 100
- No - 0
We really need to rethink about sandwich slicing.

Dint really solve any today.

Night

# 2022-04-30

Solved some Binary search & Linked List problems. The 14 day plan of Leetcode is locked, I can't access all of them at once.
I am very comfortable with Binary search now. 
I will be doing BSTs and Linked lists tomorrow.
I am going to treat myself with icecream.

Leetcode still did that thing of passing Wrong Answer verdict for a working solution. I do not know what the issue is and I cannot do anything about it.

Solved some more of linked list. I missed recursion. Its back.

I feel I am ramping up with my problem solving skills. I don't wanna lose this momentum. Its been a while since I had this rush of problem solving. I want to continue doing this consistently.

Good day, Night

# 2022-04-29

Solved 2 problems in morning. 
Something's wrong with leetcode. The submit test cases flag Wrong Answer(WA) but when I check on local, it gives me correct answer.
To verify it I ran the failing test case in leetcode's test cases and it gave correct answer but submission is flagging wrong answer.

I like memoization.

I saw The Mitchell's vs. The Machines, like the artstyle.

Solved some problems with Jun. Tried out other domains as well.

Good day

# 2022-04-28

Solved 3 problems so far. Good start for the day.

Been a while since I played dota. Imma play some today.

I am going to deep dry clean my keyboard today.

Solved 5 problems in total today. I am picking up basics of algo analysis.

Good day, Night

# 2022-04-27

If it compiles, it works. Am I right? - *Some rust programmer*

![Image](/images/2f34c02994684b2cc351b079904cf163.jpg) 

Leetcode is tough. I might have to take it at this pace, slow.

Solved 2 problems today. Good day.

Night

# 2022-04-26

I have to fight the compiler alot with Rust.

Nope, rust is definitely not suitable for competitive programming for me.

Elegant code > everything.

I could only solve 1 problem today. While taking things slow is good but the languages feel inadequate. They don't support the verbs I want to work it. Something as simple as position-if function. I want these high order functions at my disposal.
I might have to build my own library. 

Night

# 2022-04-25

I solved one more problem today. I'll ramp up as I go.
I am solving rustlings, will make rust my competetive programming language.

I have integrated asserts in my programming, poor mans tdd. I like it.

Speed is not my priority when it comes to problem solving, readability is.

# 2022-04-24

Tried out some easy leetcode problems and I really need to catchup. 
I solved with python because it was the quickest to setup with tdd. I'll move on to cpp.

Spent some time looking into autotools. 
I wrote an emacs babel function for evaluating python functions in org-mode.

I don't like language quirks. I want determinism. I don't want to spend an hour on abs function which gives segmentation fault.
I might have to try out rust or typescript.

Good day, Grind starts tomorrow.

# 2022-04-23

The amount of boilerplate in java is bonkers. I am ditching it. I'll use smalltalk.

Helped Xeon with his project, and the issue was Java's build system. I don't know why it has to be so complex.

I slept today. Tomorrow's my day off as well. Only reading.

[Your love is my drug](https://youtu.be/nWKPYs54INA)

Night

# 2022-04-22
I started with the TDD practice. I will finish the first exercise.

Coming monday Leetcode grind starts. I will fuck around my personal things until this weekend, from monday strict DSA.

I realised the testing things pretty easy if you are good at design, which smalltalk taught me. 

Also [Dr. Ziltch](https://open.spotify.com/track/04RO1gAZbF34O2gv0Oak5U?si=lfdELlM0SgCfXZbESUv8Aw) slaps

I have been trying out the tdd in Javascript which doesn't really have good OOP support, It lacks some fundamentals. I am looking into Java, Java By Comparision - Pragmatic Bookshelf

Everything is just smalltalk & lisp. I don't need to learn the langauge, I just need to know its workflow, eg compilation, namespaces.

I'll look into Competetive programming books now. I'll setup the tdd setup with java tomorrow.

Came across yasnippets, I'll use and abuse it.

I'll get comfortable with Java tomorrow and start with some leetcode easy problems

Good day, night

# 2022-04-21

My cousin's here, we played Minecraft. I recommended him Portal, my first pc game.

I am not getting any pc time today, he's been playing Portal. I'll read.

![Image](/images/406a765d5812d69a243823ee1933f172.jpg) 
*Test subject recruited*

I finished the Unit testing section. I can start tdd.

I started reading TDD by Example by Kent Beck. I am going to setup my TDD repo and fuck around some test cases.

From what I've read about Gnomes, it suits my character. But I'll look for other races as well, I don't care how niche it gets. I am pretty sure about class, Druid.

Good day, night.

# 2022-04-20

Whenever a merge error happens, my GitJournal breaks. It happened today and I couldn't write from phone.

I read today, alot. I am halfway through the testing book. I also looked that `Players Handbook` for DND.
I like where I am headed as a dev. Docker then testing. 

My cat is pregnant. Lets hope they make it this time.

My DND character is Aarakocra Druid, once he levels up he'll be able to fly. And he already has a power of transforming into any other form. I feel like this would be too much power. I'll rethink my character's race.

Here are some of the attributes I want my character to have
- lives in nature, around trees
- hungry for knowledge
- lone wolf
- 4-5ft tall, nimble
- lives over 500+ years
- can transform to any other form
- does whatever the fuck he likes, without worrying about consequences

I'll dedicate a piece to my character

Good day, I am having absolute blast playing Invoker.
Night

### Plan for today

# 2022-04-19

I know when I miss programming.

### Plan for today
- [ ] try some testing katas

I recently found out about Socratic Dialogue. And the reason its big for me is because the two books which had a big impact on me as a developer were written that way. 
The Little Schemer & The Seasoned Schemer are written as Socratic dialogue.

I am going to read the 3rd book in the series The Reasoned Schemer, which is based on relational programming soon. I plan to read more of this style. Good stuff.

I will be reading alot for a while.

I have been itching alot to mess around with testing. Especially TDD. I am looking into it.

I started reading `Unit Testing: Principles, Practices & Patterns`. I really want to tinker with a good oop system but the only one which I like is smalltalk, nothing comes closer to the interactability of its IDE. I'll try it after testing for TDD.

Good day, I am getting good with Invoker.

Night

# 2022-04-18

I had the day for myself. I am going to write about my DND character and play some Divinity with Wolfie.

I also setup the vm I'll be testing on. Testing things on a VPS isn't the most ideal. Its just easy if its local.

# 2022-04-17

### Plan for today
  * [x] play lol/dota/rocket league
  * [ ] go through ahk docs

I pushed the Mobile phones post.

I have been playing as Oracle for a while, time to try out another hero. I want complexity, maybe Invoker.

I had a dream Last night, I was back in school and it was a drawing competition and I was drawing Paani puris.

I played Invoker. The number of playstyles this hero can pull off is insane. Plus the number of combos. I'll only play Invoker now.

I rewatched Blade Runner 2049. I am going to read about Brutalist architecture.

I am integrating this [fortune api](https://github.com/sarah256/fortune-api) on my site in diary section. Maybe not.

Invoker is fun.

I made my DND character today, It's an Aarakocra Druid. Me and Wolfie are going to play dnd soon.

Good day, Night

# 2022-04-16

### Plan for today
- [ ] dockerize repo mirror(postponed)
- [ ] push "My mobile phones till now"

I'll look into Autohotkey today.

Looks like I'll have to make my own image for hosting the mirror thing.

I'll have to move to trello or org-mode for managing things. This is getting out of hand. Plus I have been helping at home.

Every blocker comes back to linux administration. Like for today It was setting up ssh in docker. I know, a bit meta maybe. I need to take a step back & rethink.

I am taking a break tomorrow. Its editing & drawing maybe. And I'll play League with Wolfie.

The Mobile phones piece is half done. I'll finish it tomorrow.

Night

# 2022-04-15

### Plan for today
  * [x] mirror a repo with ansible & cron it
  
Played dota after a long time. I need a singleplayer now.

I noticed the two task I plan for the day need to be related. I'll keep that mind. I suppose I could edit & draw on Sundays.

I successfully mirrored my repos to bitbucket with ansible. Now to cronify it.
Added the mirroring playbook to cron. I'll check it at night if its working.

I might have overengineered the mirroring thing. Eh, if it works it'll payoff.

For some reason I can't set the python version for ansible. Tomorrow I'll dockerize & see if it works. The mirroring works fine on local with python3.8 But I am not able to set the specific version for ansible on vps.
Dockerizing should solve it.

Tomorrow I'll push a fragment about the phones I used. Its going to be good 😁.

Night

# 2022-04-14

### Plan for today
- [x] setup and tinker vps
- [ ] make Emacs artwork

There's no link styling on my site. I'll fix it today.

I liked playing as Brim in Valorant. I'll draw his Stim Beacon soon.

I'll soon setup a cyberdeck with termux. 
Something like this
![Image](/images/03725bccf6bc61b9eccdac7b6a7522f9.jpg) 
*Credit - https://sixohthree.com/termux-for-android*

I haven't been able to get alot of time on my desk. I really need a portable solution. Once I setup the vps I should be good to go with a ssh client.

I am looking into how to read man pages efficiently. I can write "Your best friends on the CLI".

I like determinism. I will be tinkering with ansible for the coming week. The first problem that I want to solve is mirroring my github repos on bitbucket with ansible. This will be a good exercize to learn ansible & to solve my problem.

Testing pushing from vps, success.

I setup ansible successfully. Now onto playbooks.
I did it. I cloned a repo using ansible. Small victory.

Tomorrow if I am able to mirror 1 repo, I'll call that a win.

Good day, I like the fact that I am moving towards devops. I'll be one man army.

Night

# 2022-04-13

### Plan for today
- [x] make 2 docker containers communicate(calling it done)
- [x] watch/read Linux administration

How do you even steer a train? I'll get to the bottom of this today.

https://youtu.be/XzgryPhtc1Y
https://youtu.be/_M6vhDvmtrI

Good train channel, Lesics

I set up the networking & assigned static ips to docker containers but to use those ips I need to set environment variables. I am not able to setup environment variables in create-react-app and digging into it is just not worth it.
I call this mission accomplished.

Time to focus on linux administration.

Just learnt I can use service name instead of assigning static ips to containers. 

Linux administration is very vast so I have decided to constrain myself to practices.
  * user management
  * service management
  * process management
  * authentication

My progress as a dev
  * [x] \*nix
  * [x] smalltalk
  * [x] lisp
  * [x] containerization(docker)
  * [ ] distributed computing(elixir/erlang)
  
Finally added checkboxes to my site, looks good.

This style of keeping track is not efficient. I need to start using kanban. I have noticed there 1 big task & a small one which I do get done, I need to start planning considering that.

I'll soon tinker around with elixir.
One of the aspects where I can improve alot is testing. This is very overlooked and it really pays off in the long run. I am going to setup a tdd lab and fuck around until I get comfortable.

Nasty thing happened, ref lock thing on my git repo. I am making backup repos now.

Got a GCP vps, lets try some shit.

Night

# 2022-04-12

### Plan for today
- [x] read docker cookbook
- [ ] look into Linux administration
- [ ] edit video

I'll read about terraform today.

I tried using emacs as my window manager, din't work out because
  * had to manually send keys
  * would freeze up sometimes and had to reboot
I realised I am better off with i3wm. I'll soon go through all the docs of i3 and rice it up, not that I haven't. But I'll be more comfortable tweaking it if I know everything.

![Image](/images/be0164af19d609f5bf0c7549588cebc2.jpg) 
*My new wallpaper*
Credit - https://www.reddit.com/r/cycling/comments/tz4d80/the_perfect_cycling_wallpaper_doesnt_exi

Just noticed text isn't wrapping on my site, will fix it asap

I need to test out multiple docker containers & docker compose. I'll just grab template repos & test.

My reading list at night
  * https://plato.stanford.edu/entries/concept-evil/
  * https://iep.utm.edu/moral-re/#:~:text=Moral%20relativism%20is%20the%20view,uniquely%20privileged%20over%20all%20others

I am not sleeping without docker composing the template fullstack app.

docker-compose is wayyy too powerful, I like it.

I composed them together. Now I need to make them talk to each other.

![Image](/images/a1e1f6660ddceb55e12338623f7acea1.jpg) 

I am going to finish watching Puss in Boots and then solve the docker thing

I'll look into it tomorrow

Night friend

# 2022-04-11

My legs sore and painful from all the cycling.

Busy with home stuff today. I'll dockerize my portfolio jut for fun today.

![Image](/images/1fe105dcb9d332cd75e1765e6d7b7f76.jpg) 

### Plan for today
- [x] dockerize portfolio

Dockerized.
I feel like I can augment `make` but this'll work for now.

What else can I do?
  * one click deployment
  * one click dev spin up

I mean theres not much to it, but I can use my portfolio to test it.

Came across my first hurdle, hot reloading. Lets figure that out.
Will be solved with volume mapping.

One of the reasons I am really good at my art is automation. If I ever notice repeating myself, I automate it.

Mapping the volume enables hot reloading, yayyyyy, EZ.

I am using make file for now, It should do the job. I'll use docker-compose.yml when the need arises. Plus I wanna use makefiles, I want to integrate them in my workflow.

I really need to edit my videos. I will edit them for the coming days along with tinkering with docker.

Actually good day considering I worked relatively less than usual but got more done. Working while cycling is cool. 

Night friend

# 2022-04-10

### Plan for today
- [ ] dockerize something, anything

Have been browsing alot of r/fuckcars. I have a craving for reading about city design.

I'll be making my own home gym.

My wifi has been down since afternoon. I'll just read Docker cookbook today.

I am really excited about Mumbai Metro. Soon I will take my bike along in Metro to meet with the Bois.

Couldn't really dockerize, I'll do it tomorrow.

Very tired due to workout.

Night friend

# 2022-04-09

### Plan for today
- [x] chill and fuck around docker

`The more we pursue the idea
of programs as literature, the better our programs become.` - *Some wise literate programmer*

Omg, r/instant_regret

I take it back, it was a blast. One of the best time with the Bois.
I am tired, I'll look into docker when I wake up. 

Somehow chrome seems to freeze exwm. I am switching to firefox permanently.

Me and Akshit played some Rocket League. Rumble & Hockey modes are cool.

I remapped application launcher on Super+Space and this is wayyyyyyyyy better.
I read some of `Docker cookbook` today. I'll be tinkering with docker playground tomorrow.

Good day, Night friend

# 2022-04-08

### Plan for today
- [ ] Setup desktop-environment, polybar & dunst(postponed)
- [ ] Make emacs artworks

I'll edit the video once I have my desktop setup.
I'll soon switch to nix or guix so this week will be spent experimenting.

Emacs artworks it is today.

I figured executing ssh-add persists until reboot. So I execute it once after every startup now.

Been having eyestrain past these days, gonna go get my eyes checked.

Got myself some glasses with the shades thingy, EZ.

Docker starts tomorrow, no matter what.

The current exwm setup feels sufficient. I don't have a system tray but I don't miss it.
I have decided to continue using it for now and rice it when I feel the need for.

I'll try to setup docker playground now.
Tried docker, it feels pretty easy. Its just linux with some automation.
I'll deep dive now.

I got my glasses and OMG it feels so trippy. Everythings so clear.
Idk how I managed until now. I wanna go to places just to see things this clear.

I can see things on my pc from bed. This power... its too much. I have a fucking scope.

I looked more into docker, it feels just linux. Thats it. 
Shouldn't be hard to master it.

Just enabled `ivy-rich` and it made my life even better. Gives the docstring of entities.

Good day, i ll try to get comfortable with docker asap.

My eyes feel ticklish and watery, it ll be fine after they get used to glasses.

Couldn't draw Emacs because spent the whole day in Linux.

Tomorrow I'll push the `My favourite Emacs packages` article. 

I am going to attend the convocation of the Bois. Its party time. EZ.

Night friend.

# 2022-04-07

### Plan for today
- [ ] Edit 2nd chunk with Davinci
- [x] Rice up my exwm

Honestly I feel like I've gotten myself comfortable with Davinci's workflow.
Thats why I've been putting off editing the other chunks with something else.
I'll edit the 2nd part today.
Any other video I make, I'll edit it with something else.

I am missing essentials from exwm like bar and applets. I'll add them today.

I came across `golden ratio` emacs package. This is gold. Automatically resizes the focused window.
Fragments worthy.

I recently switched to firefox and it feels snappy. Snappier than Chrome.

For essentials, system tray is left in exwm. For some reason exwm-systray isn't available. I'll have to use something else

System tray not available. I ll setup polybar tomorrow.

Easy day. Night friend

# 2022-04-06

### Plan for today
- [x] Configure exwm
- [ ] Edit with Kdenlive

I noticed I haven't been using emacs alot for the past few days.
And that changes today, I am installing exwm and making it my default window manager.
Its everything emacs baby.

Installed evil-mode. Best of both worlds. Since I am comfortable with emacs and I like vim's keybinds, this setup is comfortable
than grabbing a distribution.

I'll spend the day today configuring exwm and evil keybinds.

Exwm with evil mode turned out to be a bit of hassle, my browser windows turn read only. This is something I'll look into later on.
Vanilla emacs exwm it is for me for now.

I looked up about `ssh-add` persistence and I came across `ssh-add -K /path/to/key`. Lets see if this works. 
It did prompt me once. Let me try again. Nope, no luck.

Figured out how to show the command keybind in minibuffer completion. One of the best things.
Added it in fragments. ezpz.

Need to setup gif recordings & add assets from fragments.

One of these days I'll make an emacs artwork.

# 2022-04-05

### Plan for today
- [ ] Edit with Kdenlive
- [x] Add `fragments`

I'll take a look at Davinci Resolve fusion nodes today. 
I might try NixOS in a VM. The documentation is very good.

I tried out clojure today. It feels like it has more support due to being on JVM, but thats just how I feel.
One of the biggest reason I haven't gotten really good at lisp is lack of documentation & discoverability.
I want an emacs package which'll list out all the packages, functions, classes and let me browse through just like any smalltalk implementation.

I skimmed through fusion nodes. It seems like I can use frequently used effects as nodes. I'll look into it soon.

Added base `fragments`. This will work for now. Since I have fragments up and running now would be a good time
to look for a good git android app. Fragments can be anything which doesn't belong in diary or worth calling a good piece, its like youtube shorts or a 1 man twitter.

Tomorrow, I edit my 2nd video with Kdenlive. I'll lookup some basic seo as well.

Calling it a day, Night friend

# 2022-04-04

Davinci Resolve is taking too much time. Jun recommended to chunk it so I can experiment with
- other editing programs
- editing styles

### Plan for today
- [x] Release first chunk of `Solving Clojure Koans`

First video is out, yayyyyy.

I have a purpose now. Puzzle life and the biggest puzzle is my life.

I'll make the portal companion cube artwork and make it as my channel logo.

Since I have one content for `shorts`, I can start working on it today.

I am not calling it `shorts`, its `fragments`.

I want an electric bicycle. I'll buy it next year. 

I finally made the companion cube. This will be my official logo everywhere now. 
![Companion Cube](https://raw.githubusercontent.com/jarusll/artworks/main/companion_cube/cube.svg)

I finished watching `The way of the househusband`, pretty wholesome. I'll read the manga now

20 mins, not enough.

Instead of figuring things out how to filter, I'll just push `fragments` for now. I'll manage filtering later on. So I can finish base implementation tomorrow. 

I'll push the videos every alternate days so I can get comfortable with an editor in a day and push the video next day.

From what I've read Latin feels like the lisp of languages. I might give it a try.

Night friend.

# 2022-04-03

finished clojurescript koans first thing in the morning.

### Plan for today
- [ ] come up with a design for shorts
- [x] edit clojurescript koans videos

I need to start making realistic plans. Looking back I am not able to finish everything I plan for. I'll be easing it now.
In a day, I am only able to do one big task. So I'll just plan a semi big task for a day.

I have been using mechvibes since yesterday. Its cool. https://mechvibes.com. I like the sound of Blacks. Blues have this springy tone at the end
and its annoying.

I forgot to delete my lightsail instances and I've been charged for 3 months now. I did disable the instance.

Things I need to do for the edit
- Line up the videos
- Transitions(maybe)
- Background music(lofi chill)
- Color grading(warm and low contrast)

There is just too much to learn about video editing. I will give this a day more. 
I am blurring things out right now. I am yet to add text banners. Commentary is out of the question.

Editing is a bitch. I did an amateur of not doing things in incognito and I now have to blur things out. AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA

I have the videos lined up & blurred out whatever needed to be.
I am going to take a break. I'll add the text banners now and it should be good to go.

I am calling it a day. I'll finish editing it tomorrow.

Night friend.

# 2022-04-02

### Plan for today
- [ ] setup `shorts` on portfolio
- [ ] record screencast of solving clojure koans at http://clojurescriptkoans.com
- [ ] watch some linear video editing
- [x] play dota with the bois, been a while since I played(played lol)

I'll read some short stories today. 
One of these days need to think about seamless images integration on portfolio. I can add image in diary but they get added in diary repo, that directory hasn't been configured for images. There will be more resources directories in future. Need a futureproof(enough) solution.

Next week I'll setup RSS for my portfolio.

![My Setup](/images/45c1d0ac5c158dbe491e518249607dc5.jpg) 
*My Setup*

Testing image. 
Needs to be prefixed by `/images/`. Testing again.
Works.

Images can be easily added by passthrough copy in 11ty. The raw images uploaded from phone would be unoptimized but this will suffice for now.

I am still yet to design the setup for shorts. Since there will be lots of posts, I will need filtering. 

Halfway through clojure koans.
Once I have a stable recording setup I can start recording other things.

# 2022-04-01

### Plan for today
- [x] look into org mode
- [x] fuck around github copilot

I'll start applying for jobs soon.

I love github copilot. No, it won't make people lose their jobs, it'll help them grow as a dev.
One of the things will be sensible names when they try to use copilot suggestions. For me it'll be generating boilerplate, discoverability(with caution) 
and automating trivial things. I will decompose my problem more and thus improve my code quality.

I have made a Point class library for fun. That library can have some more functions if I had Angle class. I will be making the Angle class
 with the help of github copilot. Lets see how this goes.
 
Looks like there's no pornhub comments api, just scraping solutions.

https://game.postdoesnotexist.com/ - Good game

`faces` are typefaces in emacs. Can customize to my liking.

I was thinking about making a `shorts` section on my site. There are things which shouldn't go in my diary but shorts.

Tomorrow I will be working on shorts section. I was also planning on doing screencasts. Maybe I can combine both of these in one section. They will be fragments of cool things which don't belong in my diary.

Night friend.

# 2022-03-31

### Plan for today
- [x] finish elisp koans
- [ ] draw portal companion cube

Have been looking into guix, this is definitely something I'll look into someday.

I feel like I have familiarized myself with emacs well to move around quick enough. Next plan would be to setting custom keybinds.

Emacs has a diary. I looked into it. My current setup works for now given that I push from my phone as well.

All this time I have been on a scavenged linux setup. I picked the first obvious solution & stuck to it. I really want to craft a system and stick to it. 
The setup will be
- minimal
- stable
- deterministic

I haven't looked at guix yet but scheme as config language does seem appealing to me plus its something new so fun.

I read some of "One more thing: stories & other stories". Good short stories.

I looked at nixos, I like the idea. Now I need to find out & justify if it works for me.

I finished the koans, there are 2 koans but they are exercise. I might do them if I feel like it. Right now, I have to digest some elisp. I'll come back to these after a day or two.

Haven't been able to do alot these days because I have been helping at home. If it becomes extreme I might look for a laptop or travel keyboard so I can work from phone.

Good day, night friend.

# 2022-03-30

### Plan for today
- [ ] finish elisp koans
- [x] setup krita/libresprite for drawing

Easy day, woke up late. Need to fix my sleep schedule. I wish I can get back my lost sleep but that's not possible.

I'll draw the portal companion cube today.

One of these days need to think about seo. It feels spammy and unethical. I'll keep it clean.

Found out a really sweet [Clojure Koans website](http://clojurescriptkoans.com/). Will give it a try soon.

Helped out Xeon with his assignment today. Java isn't that bad. I'll give it a try someday. 

`"CL (and elisp!) provides the programmer with more than enough rope to hang themself."` - *elisp-koans*

I like introspection. Thats one of the big reasons I like emacs & smalltalk.

# 2022-03-29

### Plan for today
- [x] figure out data sources for d2newspaper
- [ ] do elisp koans
- [x] watch system crafters

Came across `elcord-mode`, discord rich presense for emacs. Looks cool.
`recentf-mode`, remembers all the recent files. I am using it now.

Just found out about `describe-symbol` in emacs. It gives documentation about elisp symbols.

One thing that I really want to master in emacs is motions, moving around in buffer fast, really fast. Thats the thing I liked about Vim alot. If I can make it happen here, I won't need any vi emulation modes.

One of these days I'll draw the portal companion cube artwork. I got one online but it seems unethical. I'll make my own.

Seems like `ssh-add` doesn't persist. I don't know how long but it doesn't. I am trying out `git config credential.helper store`. Lets see if this works.

I know just enough about elisp so that I can read the manual & get stuff done.
Also the credential helper thing doesn't store any ssh keys. I'll have to look into it soon.

Found out `which-key`, It lists all the commands available in current mode. 
Here's a preview from ![justbur/emacs-which-key](https://github.com/justbur/emacs-which-key/raw/master/img/which-key-bottom.png)
This is very helpful. I can just scroll through the commands to see what action I want, It shows the keybind as well. After a while it'll become second nature.

Me and Wolfie figured out how to get all the data for d2newspaper. We'll be using jq to filter out. Should be easy. ezpz.

Holy shit `which-key` is fucking awesome. If I enable `which-key-mode`, I can type out Key combinations and wait for the suggestions. This is exactly what I was looking for.

Actually good day, learnt alot about Emacs. Day rating - 6/10. Tomorrow I'll try to finish elisp-koans.
Ez, night friend

# 2022-03-28

### Plan for today
- [x] setup `D2Newspaper`
- [x] fix posts github script
- [ ] setup git on android

The mount is here. Power tools are scary.
I have enough desk space now, I can use my drawing tablet. 
I set it up everything. I ll play Far Changing Tides, I've earned it.

I'll be messing around with emacs lisp for a while. My goal is to start talking in terms of emacs objects like buffers, windows & frames and then write some trivial macros.

Man I love magit, I am quickly able to do git actions which is letting me make rapid small changes. Good stuff.

I'll be trying out [elisp koans](https://github.com/jtmoulia/elisp-koans)
I did some elisp koans. I expected emacs types but this is standard lisp stuff. 
Anyways the youtube series by System Crafters should get me upto speed with emacs types.

I wanted to open my diary file quickly, I came across emacs registers. You can store any thing, good stuff. I stored my diary file at d. So I can access it by `C-x r j d` from anywhere in emacs. ezpz.

Easy day, pushed "What motivates me", started with elisp. System crafters should get me upto speed with Emacs.

Planned about d2newspaper. Lets make this happen.

Night friend

# 2022-03-27

### Plan for today
- [ ] setup `D2Newspaper`

There's alot of dust buildup in my pc, need to clean it. I ll do it when the mount arrives.

Wolfie talked about how he's missing reading books and now I want to read🥺. I will gain momentum first with short reads.

Pushed draft of "What motivates me"

Now that everything has been automated and decoupled, I can write articles on my phone. Need to find a good git app for Android.

Wolfie busy, we ll setup tomorrow.

Just realised I have misconfigured GitHub actions for posts and no listener for posts_push on portfolio. Will fix it tomorrow.

Day rating - 5/10. My eyes were strained and I lost all dota matches

# 2022-03-26

### Plan for today
- [x] add site build trigger on `posts` push
- [x] integrate artworks
- [ ] push `why i like smalltalk - message protocols`
- [ ] add `` markdown highlights

Holy shit webp is good.
Just found out I can add ssh keys and I won't have to input password. VERY BIG, love it, my life is easy.

Its been a while since I had any day off, tomorrow is my day. No work tomorrow. I ll play dota and draw.

`The Green Knight` was the last decent movie I saw. I might watch some `Monty Python`. 

Me and Wolfie discussed about the Destiny thing(`D2Newspaper` for now). I'll be working on it with him.

# 2022-03-25
Like LoL characters, but the game feels like a mobile game. Might give it one more try.

### Plan for today
- [x] integrate diary
- [ ] push `why i like smalltalk - message protocols`
- [x] think about artworks integration 
- [ ] plan for destiny thing with Wolfie

Man i love playing Oracle

I have my `posts` repo as gitsubmodule in `portfolio` repo and whenever I make a change in posts, I have to commit it twice, once in `post` & once in `portfolio`.
I just want to commit once and be done

Integrated Dark mode, ezpz

One of these days, need to plan about decoupling the submodules and building the site on push of any dependency repos

Oh hello git submodules

I did it, ahahah. I am a fucking god. I successfully tested GitHub actions trigger on push in submodule repo.

Lets see if this works.

Yes it does, ahahahahahahaah.

Automated site build on submodule push. I did it for diary so I can write from phone, push and everything will just work. Tomorrow I'll do the same for posts

Good day, night friend

# 2022-03-24

Hello friend

24th November

`Just let it crash and drop in debugger, we'll define things on the fly` - *Some wise smalltalk programmer*

Easy day, dint really get much done. Pushed "Why I made a public diary" and made the diary. 

Need to clone the diary repo in GitHub workflow.
