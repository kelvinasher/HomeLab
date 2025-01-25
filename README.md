# HomeLab

I began working on this project 1/1/2025, at that point in time I only began researching and learning about various technologies and not yet implementing. 

The overarching point of this project is to learn more about the technologies that I've identified as "up and coming" that will further dominate the technology space in terms of administration, networking, data processing, hosting, ect. I want to learn more specifically about technologies like k8s, Linux, FluxCD, containerization, and some others. 

At the time of writing, my setup consists only of a laptop I got from my grandfather that has "OK" specs. On this laptop I have installed Ubuntu Server and k3s to start with.

At current, my goal is to establish an outward-facing web server that I can connect to anywhere, with some service running there. I am thinking perhaps a portfolio, or maybe a constructed demo-platform showing my homelab set up off in some way. I want to have a 'dashboard' that has all of my services, links, applications, ect on it that I can access from anywhere, ideally with some sort of file storage solution that I can access with a username and password from my phone (I do all work from my desktop and iPad, so if I am ever doing anything from my phone and I need those files I would not be able to access them without a cloud solution. Of course the solutions exist, but this sounds more fun.)

I have intermediate experience with networking, I am in school for network engineering and security and hope to take the skills I have and will further learn somewhere I can fully utilize them to solve challenging problems.

I have some Linux experience from my professional past, but not extensive enough to claim profiency.

I have very minor exposure to k8s, containerization.


01/24/25

I decided to use Talos Linux as my Kubernetes cluster utility instead of booting a typical distro and installing k3s or similar. This decision came from the fact that Talos is extremely lightweight, immutable, and I found the challenge that naturally comes from Kubernetes-centric, CLI-only distro worth the challenge and learning experience. 

I have been struggling over the last few weeks in my free time to get a healthy Talos Linux cluster up and running, but today I found the point of all of my frustrations thus-far. 

Ultimately, my issues arose from poor documentation/log readability because the issues I faced were misexplained, or not explained at all so I had to punch sand until I found the variable that was not working for me. 
    To put it shortly, it was merely a misconfiguration that was persistent across multiple installs that prevented various things such as networking, the actual installation process, commuinication betweern the Talos API server and the node, and some other critical processes. It was a big game of finding out where to look for what, I was being pulled in every direction and none of the support options were particularly helpful. I can at least sayt, I feel like I leartned a lot just from me attempting to initialize a cluster to start with. 

Future notes will be inside of a continued notes directory, although at the time of writing I am unsure of the structure I want to use. I am thinking I will be putting notes inside of each directory I create, the changes I am making and the idealogy behind them as well as troubleshooting info/important info while also maintaining a general project notes file that will have new notes appended, possibly with the notes also being in their own files? 
        1: Notes in/with relevant arms of the project. `main/stuff/thing/notes`?
        2: General notes (such as this one) in a longer, continually updated file. `main/notes/NOTEPAD`?
        3: General notes (such as this one, starting with the date) in individual files. `main/notes/Jan25`? `main/notes/012425`?

I am still pondering how I want all of this to be set up, since I am not a Git professional by any means this will mostly be my own flow that feels comfortable to me, so I will eventually get it under my belt and make this look better.

ReadMe.md update coming soon, hopefully. Looking to make it an introduction to the project instead of a diary entry, lol.
