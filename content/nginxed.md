+++
title = "Nginxed"
date = 2022-04-10

[taxonomies]
tags = ["webdev"]
+++

Every six months or so, I decide to give Nginx another try on my Macbook. After another OS update and several more updates of the software itself, I tell myself, surely this time I'll manage to figure it out and finally try out that php-based microblog framework that I've been trying to get to work for literally several years now. 

Over the past few years I've learned to be more patient when wrestling with software; that bottlenecks are part of the process, and you just have to keep working at it until you figure it out. Sometimes I've even experienced the dopamine rush when you finally actually manage to get something to work the way it's supposed to. So at first I remain patient and positive: what does the problem seem to be? Did I configure the server correctly? Am I using port 80 instead of port 8080? Did I set permissions correctly? Is my index.php file in the right directory? But as  minutes turn into hours, like playing a better opponent at Go and feeling that creeping, inexorable sense of doom, I feel the morale slowly draining out of me.  And after another evening of scrutinizing online tutorials, scouring discussion threads on StackEdit, editing localhost paths and servers in nginx.config, reloading nginx over and over again in the terminal, refreshing browser pages, uninstalling and reinstalling nginx, redownloading the repo, and above all, staring over and over again at Forbidden and Page Not Found messsages, with my head aching and my eyes prickling with sleep, I give up in despair and stumble off to bed, cursing myself for making the same mistake again and swearing that *this time* I will never, ever again try to get this stupid program working. 

If the coding gods are favorable, I might manage to get my info.php page to show its largely incomprehensible status message, or my index.html page to display its "Hello world" or even more mockingly, "It works!" message. (If only it did.) But after countless hours of trying over almost two years now, I still have no clue how php-based websites work and have been unable to get the elusive php microblog to display anything, let alone figuring out how the api page for updating it works.

It doesn't have to be this way, I tell myself every time: there are endless blogging and microblogging frameworks out there that I have managed to learn my way around over the past two years: Jekyll, Hugo, and my current favorite, Zola. As any network engineer is likely to ask, why do I even need Nginx at all, when on Mac Apache seems a lot easier to configure. But perhaps because of their stubborn resistance to all my efforts to master them, Nginx and the php microblog remain my obsessive El Dorado of web development.

Of course, early on, I tried emailing the developer, sending detailed reports on my trial and error. And he was initially responsive, replying with helpful suggestions that I couldn't make head or tail of. But eventually even he stopped replying to my messages. I checked recently and he hasn't posted anything on the microblog since last year. But there it sits, defiantly online, its ultra-stripped down, minimalist design apparently unattainable to all but coding initiates. After yet another evening of frustration, casting around for explanations, I find myself thinking that maybe it isn't me - maybe the code is buggy, or the documentation isn't clear enough, or something... But other than the existence of the original blog itself, there's no way of knowing for sure whether the code actually *does* work. So I end up as people who don't understand technology have always done, falling back on magical thinking: maybe, I think as I drift off to sleep, I'm just Nginxed.

If any php experts with more experience of configuring network servers than me feel like giving it a go, the repo is over [here](https://git.sr.ht/~hxii/saisho), so let me know how you get on. All I can say is, good luck.

