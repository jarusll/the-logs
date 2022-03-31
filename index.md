---
title: Diary
layout: layouts/home.html
---

# 2022-03-31

### Plan for today
- [x] finish elisp koans
- [ ] draw portal companion cube

Have been looking into guix, this is definitely something I'll look into someday.

I want someone cute, I want to read, write and fuck around computers.

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

Absolutely not having chicken again.

Day rating - 5/10. My eyes were strained and I lost all dota matches but Charu cheered me up

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

Played roblox with Joles, it went... okay.
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

Good day, Charu cute, night friend

# 2022-03-24

Hello friend

Charu... Cute... 24th November

> Just let it crash and drop in debugger, we'll define things on the fly - *Some wise smalltalk programmer*

Easy day, dint really get much done. Pushed "Why I made a public diary" and made the diary. 

Need to clone the diary repo in GitHub workflow.
