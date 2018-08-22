### 2018/08/22

[https://www.androidcentral.com/protect-wi-fi-network-hackers](https://www.androidcentral.com/protect-wi-fi-network-hackers)

It's your house and your network, filled with your stuff. Nobody wants some random intruder snooping around in it.

[JERRY HILDENBRAND](https://www.androidcentral.com/author/Jerry Hildenbrand)

![](https://www.androidcentral.com/sites/androidcentral.com/files/styles/xlarge_wm_brw/public/article_images/2017/08/mi-router-3c-4.jpg?itok=eaVHNo-Q)

The digital information age is pretty awesome. I can find the answer to almost anything in just a few seconds, I can look at a screen small enough to carry in my pocket to know where to go**and**why I need to go there, and I can even make the lamp brighter by telling[Alexa](https://www.androidcentral.com/amazon-echo)or[Google](https://www.androidcentral.com/google-assistant)to do it instead of reaching over to the fixture and swiping its tiny touch panel. A big part of the reason why, as well as why it's only going to get even more awesome, is because everything is connected.

> If you're a network engineer you've got all this covered. The rest of us have to actually try.

For us, there is usually only one small part of that connection we need to worry about — the last 20 meters or so. Once all those digital signals make their way into our home they spread out over a Wi-Fi network that**we**control. The other gazillion meters of any connection have trained folks who are very good at keeping it all private and secure working to do just that, but that last 20 depends on us making the right decisions. If we don't, the consequences can range from the embarrassing to the criminal — if it happens on our network, we're the ones with our feet at the fire when judges and lawyers and Sony get worked up about the things that have passed through it.

That means it's important to keep hackers out of your Wi-Fi network. It's incredibly simple to get into about half of the Wi-Fi networks in any given town. Drive around and wait for a $12 gadget to blink green, pull over somewhere safe and start scanning and typing the right things in the right places and you are in. Any of us are fully capable of using the simple tools and a few online resources to break into a poorly secured Wi-Fi network. Here are a few easy things you can \(and should\) do to make sure yours isn't.

![](https://www.androidcentral.com/sites/androidcentral.com/files/styles/xlarge_wm_brw/public/article_images/2016/11/amplifi-hd-mesh-network-kit-2.jpg?itok=loxa3Sy-)

## The username and password

If I wanted to get inside a secured Wi-Fi network the first thing I would do is try to determine what hardware is there and acting as a router. With WPA2 being compromised, it's fairly easy to crunch enough numbers to crack a Wi-Fi password \([WPA3](https://www.androidcentral.com/what-wpa3)mostly fixes that\) and once I'm connected there's a 50-50 chance that the router still uses the default username and password for its admin utility. The number of Linksys routers in use that the word admin can grant you access to their setup is staggering. Seriously.

> Don't make things easier than they already are.

Once I have control over the things like open ports and it's set up for me to get in anytime I like without being in Wi-Fi range, I'd turn off any automatic update feature and change the login details so another jerk can't screw around in there. If a user didn't bother to change the default login, they'll never know that they can reset the router to undo everything I did or that I even did anything.

I'm not some sort of hacker-dood. You don't need to be a hacker to do exactly what I described to a router that still has the default admin credentials. Your smartphone, a laptop, and a couple of free utilities make it easy as pie.

If you haven't already done so, grab the manual that came with your router or Google its model to read it online and see how to reset the router, reconnect it to your modem, and then change the admin password. While you're at it, change the Wi-Fi password, too. then put everything into your favorite password manager because you'll never remember all those random passwords.

## Change the default SSID

SSID stands for Service Set Identifier but we know it better as the Wi-Fi network name. When you set up your Wi-Fi router it prompted you to create a network name and a password, but the network name was probably already filled in with the default. Like the admin credentials, a whole lot of people just left it that way.

> Even an SSID named "Mom click this for internet" is better than XFINITYWIFI.

Changing the default name from something like Linksys doesn't make your network more secure or do anything to thwart bandwidth piggybackers \(unless you name your SSID something like "c:\Win\System32\cmd-virus.bat" which will scare a lot of people away\) but it does stop advertising what hardware you're using. That's easy to figure out another way but it means that utilities that search for specific brands using the SSID aren't going to work. Doing anything to make a hacker single you out instead of advertising to him or her is a good thing.

## Use a good password for_everything_

![](https://www.androidcentral.com/sites/androidcentral.com/files/styles/xlarge_wm_brw/public/article_images/2016/10/best-android-password-managers.jpg?itok=hVIuN1e6)

Just a few years ago something like SeaToShiningSea22$ would have been a great password. It's easy to remember but complex enough that it's not going to be in any password cracking dictionary and using any brute force methods to crack it would have taken months or years of computing time. Those days are gone.

You need a password of\_reasonable\_length that includes upper and lower case letters, numbers, and symbols. They all need to be in some random order that doesn't mean anything to even you, and if you can you'll even want to use spaces. Computer processors have come a long way and billions of clock cycles no longer take months or years, they take hours and days. Don't be that unlucky person who gets their network password cracked in just an hour and make it hard as hell by adding complexity.

Reasonable means different things to different encryption schemes. Generally, 8 to 10 characters are pretty good and 15 is even better because we are only interested in making the password more complex so a tool that tries to crack it needs more time. You don't need to write some sort of random character novella, just use a password generator that comes with your password manager. It's better at this stuff than we are.

## \_Beware\_of MAC filtering and firewall settings

Using these tools to keep access to your Wi-Fi a bit more controlled can be tempting, but if you're not sure what you're doing you probably shouldn't. Take some time to read and understand what things are, what they can do, and how it all works together, first. A fun way to play around is to set up a second Wi-Fi router on your Wi-Fi to play around with — just be sure to unplug it when you're not playing until you're sure you can keep it from being exposed to traffic outside your own network.

> Sometimes fixing things makes them more broken — be sure you know what you're doing in these settings.

MAC \(**M**edia**A**ccess**C**ontrol\) address filtering uses a device's "unique" network signature to build a list of which devices are allowed to access any router. It's not a failsafe way to keep anyone out because a MAC address can be faked but it's another way to make sure it's not easier to break in than it needs to be. You can find a devices MAC address through its own network interface \(Google instructions for the device\) or through a router's control panel, and you whitelist the devices you want to let in and blacklist everything else. Know that MAC addresses aren't necessarily unique or permanent — they can be changed. And anytime you connect something new you'll need to add it to the whitelist.

Firewall settings on most consumer routers aren't very comprehensive, but you will usually find settings for port forwarding and domain blocking. Both can be great tools as long as you know how to allow the right ports to connect to the outside world and how \(and why\) to block a domain.

I monkey around with these settings because I almost remember everything I learned about them during some software administration certification classes \(if you're the head of a Fortune 500 company who wants to spend a lot of money and you still use RHEL 9 on your servers, call me\). They're worth learning more about if you're curious or if you live next door to a house filled with CS students who**will**try to monkey inside your Wi-Fi just to see if they can. They will, and someone in the comments will verify that \(don't make me look bad my computing scientist friends\).

If you just have no desire to learn about this sort of thing — and none of us here will blame you — it's better not to touch any of these settings.

## Make sure you have a good router

![](https://www.androidcentral.com/sites/androidcentral.com/files/styles/xlarge_wm_brw/public/article_images/2016/12/google-wifi-3.jpg?itok=5HJvxQT2)

This is the easiest and most important item on our list. You want a router that can put good Wi-Fi everywhere you need it, is dependable, and updates regularly and automatically. Full stop — if your router doesn't do all three of these things you should look into replacing it.

> Google Wifi is easy. I like easy and recommend easy whenever i can.

Nobody likes to spend money if they don't need to do it, but having dependable and secure equipment powering your Wi-Fi network really is more important than any of the things we can do to help keep it safe. Every piece of hardware connected to the internet is exploitable. Every Wi-Fi network is hackable. It's crazy to not do everything you can to patch exploits and make it more difficult for hackers. Timely and automatic updates are a lifesaver here — a system that emails you and lets you know there is an update that needs to be applied to your router's firmware is also acceptable if you're the kind of person who hates automatic anything — because you don't have to worry about looking for an update and applying it yourself.

A reliable and strong network is also important because it takes away the temptation to do something like adding more equipment that you need to secure — repeaters and APs can be exploited, too. Thankfully, there are plenty of routers to are strong, reliable and automatically updated on time whenever it's needed. They're all pretty good, too, and your favorite brand \(do people have a favorite brand of router?\) likely makes one. As most of us here are Android users and have already sold our life's information to Google in exchange for its great services, I'd recommend[Google Wifi](https://smile.amazon.com/Google-WiFi-system-3-Pack-replacement/dp/B01MAW2294)as a great option for most folks. But Netgear, Linksys, ASUS and names you might not know like Eero and Amplifi make great stuff, too.

[More: Google Wifi vs. Orbi vs. Eero vs. AmpliFi: Wireless Mesh Network Face-off](https://www.androidcentral.com/google-wifi-vs-orbi-vs-eero-vs-amplifi-which-mesh-system-should-you-buy)

An unsecured network is better than a poorly secured network. You won't have a false sense of security that way, and you can tell a judge that lots of people use your Wi-Fi and it wasn't you who downloaded that pirated music, and he or she might buy it. But the best thing to do is try and make things as secure as you can.

