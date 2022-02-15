# Full Stack FrontEnd
Full stack is someone who can build an application from start to finish.
## Internet
So how does the Internet work? A bunch of computers talking to each other. I think a lot of what we think of the Internet is we think of web browsers, and we think of, I don't know, maybe streaming movies or something like that. Mostly what people interact with the Internet is the World Wide Web, that's the www dot something. It's just that when you type in, but that's the World Wide Web, that's just a part of the Internet. There's still FTP, there's things that run over the Internet, so there's things like a BitTorrent or movie streaming. There's lots of other examples, but most people.
I just said it's a series of globally interconnected devices. And I'll say it's a series of publicly interconnected devices. That's the Internet, that's the thing we all know, it's the thing we're using right now. Thing that is running through and streaming to you at home, you in the classroom.
### IP Addresses & Protocols
The Internet runs on this trust system, and it's a series of protocols that everybody sat down to agree to like 30 years ago or something. They said, hey, this is how my computer can talk to you. And that protocol is called IP, and that just stands for Internet Protocol. I know how to write it, read it, and I know how to send it back to you to let you know that I got it, that's the Internet Protocol.
IP addresses that are used by the Internet Protocol to kind of talk to each other, just let you know, hey, here I am. Here's how to get to me. Like I said, this all runs on a different protocol called TCP. And most of you heard TCP over IP, or IP over TCP, it's just a protocol and a standardization of how computers can talk to each other.
### Domain Name System
Domain name system is just a way of making the Internet accessible for more people. And you probably all see or not you probably, I guarantee you've seen domains and domain is something like frontendmasters.com, jemyoung.com, that's called your domain.
### Trace Routes
Traceroute gives you a map of every single hop along that point. It's mapping the path of every single server that we hit along the way. So every time you see another hop, and a hop is just from one to two, two to three, three to four stuff like that.
### Packets
Well, technically a bit is the smallest information you can transfer it. Inside that packet has the information. And that's what a packet is. It's just this base unit of information of how everything's transmitting. Fact, the way I'm talking to you on the internet is just billions, and trillions, and trillions of packets are moving right now. But a packet mainly contains metadata.
## Servers
### VIM 
VIM stands for Vi Improved, it's one of those meta-definitions kind of like PHP. The great thing about VI is you can't use a mouse. It forces you to not use a mouse. I mean, I'm sure there's plugins that let you use a mouse. But, if you're really good at VI, you're gonna be much faster than someone with a mouse and keyboard.
### Servers
I'd say it responds to requests. Yes, that's also what a server does. Though you can argue the definition of responses is a form of content. But yours is probably a bit more encompassing, which is good, but it serves files. Like that's usually what you want a server to do.They're like, for all intents and purposes, it doesn't exist to my needs. But a server is also just a really, really powerful computer, or any computer at all can be a server. Servers, essentially, are custom built machines specifically for disturbing files and not necessarily interacting with as much.
### Data Centers and the Cloud
 Servers generally live in a place called data centers. Data centers are these racks and racks and racks and racks and racks and racks machines usually run really, really cold environments, just because computers run hot, servers like to run cold.
### Virtual Private Server
When we size a server it's called a VPS, that's a Virtual Private Server. Again because when you're manipulating it, it looks like you have an entire server to yourself but in reality you just have a chunk of a box, of a piece of a server. And I can pay five bucks a month and you get a chunk of a server rather than having to run an entire server.
### SSH
SSH stands for Secure Socket Shell, it is a, well, I'll get to it in a minute. But it's a very large key that is as of now unbreakable. And so it's a much secure way of logging into your server. The switch is made up of two parts, that's why it's usually, for all us, a key pair but I'll just call it key. There's a public key There's a private key. And the way that works is the private key stays on your computer on your phone wherever you wanna keep it. The public key goes on a server. And what happens is everything is encrypted with the private key. So when it's encrypted, it goes in transit, and no one can intercept what's happening.
## BASH Basic
### Standard Streams & Redirections
Yeah, you've probably used it. If you've written any sort of Unix or even a note application you use these things too. There's things called standard streams, they're standard output which is stdout that you'll see it written as that. Standard input stdin, and there's standard error, stderr. It's great because this is the standard for almost all Unix applications. There's something called the POSIX standards, which, I don't remember what POSIX means, but it's in the notes. Portable Operating System Interface. So it's a group of people that decided, hey, if you're writing any sort of Unix application, there should be some sort of standard way that inputs come out or inputs go in, outputs go out and errors are handled.
## Nginx
About Nginx as being a web server, a reverse proxy, kinda a jack of all trades, and it's just really, really, really fast.
## Security
Security is honestly one of the most important things you'll do, which kind of run contrary to what we do as engineers. We think, no, my job is to build things and connect things and make sure the pipes are running smoothly and everything like that. But the thing about security is none of, none of your cleverness, none of your code, none of your fast application matters if you have no security. 
So security is one of the more important things we're doing. That's why there's an entire section on this. Even though it's full stack engineers, you probably won't do as much security as you think. There's dedicated people that dedicate their entire lives just doing security and operations, security, things like that.
