!SLIDE
# John Fink #
# Digital Scholarship Librarian #

.notes Relax and breathe.

!SLIDE bullets incremental
# Computing Infrastructure #
* Heavy reliance on VMs
* Keep administration agile

.notes Could not do this with standard admin. Note that some work scenarios
demand that outside parties have access (even root!) with inside machines:
using VM insures that we can provide that if needed. Also, ~10-15 minutes to
spin up a completely new machine ready to go, can't beat that.

!SLIDE bullets incremental
# Right now this means #
* KVM for VMs
* .deb based Linux distributions
* sysadmin through cherry-pick or clusterssh

.notes KVM is a particular kind of Linux virtualization technology that requireshypervisor support in hardware. .deb is because I am a Debian fascist. Explain clusterssh. Designed for my comfort.

!SLIDE bullets incremental
# This is not terribly scalable #
* Puppet/Chef for VM admin
* Maybe other OSs

.notes I am one guy and am not undergoing cellular mitosis. So at this point we are sort of OK, but scaling beyond is going to get hard. What's stopping me? laziness. Puppet/Chef are new. Laziness will always be a driver, so at the point where it's more lazy to use Puppet or Chef than do things clusterssh, I will switch.

!SLIDE bullets incremental
# grad and faculty relationship #
* (initially) Concentrate on underserved populations
* At Mac this means humanities grad students, humanities in general

.notes At McMaster sadly enough historically most of the attention has been on STEM. However this is also AWESOME really because underserver population = a market that will think you are wonderful for helping them out. Grad students especially.

!SLIDE bullets incremental
# sla writing #
* Necessary for a framework

.notes This is hard. It's part of that plumbing thing that needs being done but is distinctly unsexy and a bit of a slog. But without it, people (can/(will?)) just roll right over you. Have a structure document is *important*. Deciding on that structure doco has to (like a lot of stuff) be a collaborative endeavour.

!SLIDE bullets incremental
# services #
* Physical services
* Virtual services

.notes Hey, man, this is a service profession innit? Still here, even with this.So we're planning on having in-person consults, some species of regular office hours, as well as being available online. 

!SLIDE bullets incremental
# where do we stop or start with a project? #
* ...

.notes We're still really figuring this out. It's both a good and a bad thing. Early on, it's really great to cast your net as wide as possible, get some projects under your belt so you have something to point to, but later on if (when!) you get super popular, this becomes less scalable and that's where the SLA comes in.

!SLIDE bullets incremental
# github #
* Already a site for a lot of DH development
* Scholarslab, CHNM
* Visibility!

.notes Source code as the new peer review. This is an easy way we can demonstrate our utility as well as give back and make a name for ourselves generally. Viz CHNM, with Zotero, etc. *VERY* important that we have license flexibility (DFSG compliant) as we'd like to default to an open source license (as part of SLA? maybe). github is pre-eminent source code hosting service. http://github.com/scds/ We did our slide deck there, f'rinstance.

!SLIDE bullets incremental
# version control evangelism #
* *Anything* iterative and text based...
* ... and everything *should* be iterative and text based
* provides portability, flexibility, history tracking
* Surprisingly, this is a new concept to many academic tech types

.notes We will try to be flexible on many fronts -- languages, operating systems, service hours and service levels, but I would like to stick with one standard for documenting and sharing code. We've been using git for a while. Having documented changes and distributed backups of stuff is a Good Idea.


!SLIDE
# project management and culture #

!SLIDE center
# Contact info #
* email: john.fink@gmail.com
* twitter: adr
* github: http://github.com/adr

