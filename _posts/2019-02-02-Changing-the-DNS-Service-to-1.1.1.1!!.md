---
published: true
---


The DNS resolvers play a major role in the whole internet lookup process. The better ones are the ones which does this in a shorter period of time. The [1.1.1.1](http://1.1.1.1) claims to be the best. But thats not the only thing which got my my eyes. They claim that they provide 100% privacy which may raise some eyebrows.

## Privacy? What?

Yeah, the official [cloudflare blog](https://blog.cloudflare.com/announcing-1111/) claims to be privacy first DNS resolver. The privacy can be a huge issue as it can be used for a tool for censorship and even some of the ISPs are said to be selling the data of their users which is kind of creepy. So these DNS resolvers can be used to certain limit to avoid these issues.

## Speed?

According to the [official website](http://1.1.1.1) they are said to be leading than many of the other prominent players. Many people had various opinions about this. This [blog post](https://medium.com/@nykolas.z/dns-resolvers-performance-compared-cloudflare-x-google-x-quad9-x-opendns-149e803734e5) explains the speed differences and other important things like DNSCrypt, DNSeverHTTPS etc.


## Setting it Up

Its very easy to setup in your device. For most of the computers, you just need to change the DNS from the advanced menu settings.

	1.1.1.1	
Add the below to avoid any redundancy

	1.0.0.1
We have to add this one

    2606:4700:4700::1111  
and this one too for avoiding the conflicts.

	2606:4700:4700::1001 	

You can configure your Mac like the screenshot below

![Setting Up in Mac](https://raw.githubusercontent.com/beingfranklin/blog/gh-pages/_posts/Screenshot%202019-02-01%20at%208.41.13%20AM.png)


For Mobile devices they have an app which has the VPN features and uses their DNS instead. So it is helpful in places like India where the majority of the people rely upon the mobile data over WIFI for the internet.


## My Thoughts

I had configured tmy Wifi settings accordingly and I have noticed slight increase in loading time after I type some web address and hit enter. These are not so noticeable like they claim for me as such, but there is some improvement, thats for sure!
